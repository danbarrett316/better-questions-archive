# Statistical Process Control and Variation

The measurement and analytical backbone of Barrett's entire framework. Drawn from W. Edwards Deming and the quality management tradition that powered both the U.S. WWII manufacturing effort and the Japanese manufacturing miracle of the 1980s. The core insight: **all numbers vary, and the question is whether the variation you're observing has a specific identifiable cause or is simply the natural wiggling of the universe.**

---

## Core Concepts

### Two Types of Variation
- **Routine variation** (common cause): Natural, random fluctuation present in any metric over time. No single cause. Cost per lead going up one week and down the next is usually this.
- **Exceptional variation** (special/single cause): A change attributable to a specific, identifiable cause. Pausing the account drops impressions to zero. A Houston flood dries up leads. A broken form cuts conversions in half.

### Deming's Critical Insight
**You cannot improve a system that is not in routine variation.** If a system is experiencing exceptional variation — unexplained swings from unknown causes — then any experiment you run is confounded. You can't tell if a change happened because of what you did or because of the unknown exceptional cause. You must first eliminate exceptional variation and establish routine variation before attempting improvement.

### XMR Charts / Process Behavior Charts (PBC)
- The primary analytical tool for distinguishing routine from exceptional variation.
- Individual values plotted over time with calculated upper and lower natural process limits.
- Requires 12-14 data points before limits become stable.
- Data point granularity depends on the metric: impressions/clicks can be daily; cost per lead may need weekly; rare events may need quarterly.
- **No conclusions before the baseline is established. Period.**
- Used extensively by Barrett for both PPC management and personal health tracking (HRV, sleep, A-fib, weight). ("2024 Year in Review")

### The Voice of the Process (Deming)
- Understanding how a system actually works before trying to change it.
- "The question is not 'where do I want to be?' but rather, 'where am I right now, and how can I improve?'" ("More Better Different," 2024)
- Continuous improvement over baseline rather than arbitrary targets.
- Goals imply lack and create resistance; working with the Voice of the Process means working with what is.

### The Knowledge Problem
- Knowledge is that which allows you to accurately predict.
- We create knowledge by making predictions (hypotheses about cause and effect) and checking them against reality.
- But variation confounds this process. Random wiggling can look like a meaningful signal.
- XMR charts are how we distinguish between the two.

### The Measurement Paradox
- "When a measure becomes a target, it ceases to be a good measure." (Goodhart's Law)
- We prioritize the numbers that seek to measure the goal outcome over the goal outcome itself.
- Yet measurement itself can cause improvement: "The simple act of continuously bringing your attention to something causes you to change your behavior regarding that thing." ("On Composure," 2024)
- The resolution: measure to understand the system, not to set arbitrary targets.

---

## The Practical Discipline (5-Step Method)

### Step 1: Establish a Statistical Baseline
- Collect 12-14 data points on a time series for each management metric.
- This is the point at which XMR chart limits become stable.
- No conclusions before the baseline is established.

### Step 2: Establish Routine Variation
- Use XMR charts to identify whether each metric is in routine or exceptional variation.
- If exceptional variation exists, identify and eliminate its causes before attempting improvement.
- Causes can come from anywhere — inside the account or outside it. The account is a proxy for the world.

### Step 3: Identify the Constraint
- Determine which funnel stage most limits throughput (cash in bank, not leads).
- Common constraint locations: impression volume, click volume, conversion volume, lead contact rate, close rate, deal-to-cash conversion.

### Step 4: Design and Run an Experiment
- Every experiment serves two purposes: (1) alleviate the current constraint, and (2) test a hypothesis about how the system works.
- Experiments must have clear predictions and measurement criteria.
- After a successful experiment produces exceptional variation (the desired improvement), reestablish routine variation at the new performance level.

### Step 5: Loop
- Reidentify the constraint (it has likely moved).
- Design the next experiment.
- Continue the OODA loop indefinitely.

---

## Key Thinkers

| Thinker | Framework | Key Contribution |
|---|---|---|
| **W. Edwards Deming** | Statistical Process Control | Variation theory; routine vs. exceptional; you cannot improve what you cannot predict; "Drive Out Fear"; "A bad system will beat a good person every time" |
| **Donald Wheeler** | Understanding Variation | XMR charts; Process Behavior Charts; practical SPC application |
| **Taiichi Ohno** | Toyota Production System / Lean | Practical application of Deming's ideas; proof that these principles transform industries |
| **Walter Shewhart** | Control Charts (implicit) | The original inventor of statistical process control |

---

## Signature Concepts and Quotes

- "All numbers vary."
- "You cannot improve a system that is not in routine variation."
- "A bad system will beat a good person every time." (Deming)
- "No conclusions before the baseline is established."
- "The question is not 'where do I want to be?' but rather, 'where am I right now, and how can I improve?'"
- "When a measure becomes a target, it ceases to be a good measure." (Goodhart's Law)
- "Drive Out Fear." (Deming)
- "PPC management is one of the most superstitious industries on the planet."

---

## Key Blog Posts

- PPC Philosophy Guide — Core articulation of the 5-step discipline
- Agency Steering Document — Detailed application to PPC management
- "Winning the Wars" (2023) — PBC/XMR charts introduced for PPC
- "More Better Different" (2024) — Voice of the Process; continuous improvement vs. goals
- "Abstraction Diseases" (2024) — Goodhart's Law; measurement as target
- "The Horror of Wanting" (2024) — The causal chain from measurement to anxiety
- "On Composure" (2024) — Measurement as improvement mechanism
- "2024 Year in Review" (2025) — Extensive PBC analysis of personal health data
- "Define Your Terms" (2023) — The importance of precise definitions before measurement

---

## Application to PPC Management

### The OODA Loop as Operating Method
Every action is an experiment attached to a hypothesis:
- **Observe:** Collect the data (XMR charts, funnel metrics).
- **Orient:** What type of system are we in (Cynefin)? Is variation routine or exceptional? Where is the constraint?
- **Decide:** What experiment will I run? What hypothesis am I testing? How will I measure it?
- **Act:** Execute the experiment. Loop back to Observe.

"There is no 'just making changes.' There is no 'optimizing.' There is only: hypothesize, test, learn, repeat." (PPC Philosophy)

### Alpha Generation
- **Alpha** (from finance): returns above the market benchmark.
- Generated by identifying and exploiting gaps between what the market prices and what the system actually delivers.
- Three primary alpha strategies: conversion event shifting, mid-funnel proxy development, and deliberate algorithmic arbitrage.
- Alpha erodes over time as competitors adapt — ongoing knowledge creation is required.

---

## Connections to Other Themes

- **Systems Thinking:** SPC is the measurement layer that makes systems visible and manageable
- **Epistemology:** XMR charts are the practical tool for creating reliable knowledge from noisy data
- **Risk/Uncertainty:** Routine variation defines the boundary between calculable risk and true uncertainty
- **Theory of Constraints:** You must first establish routine variation before you can identify and alleviate constraints
- **Behavioral Systems:** The 5-step discipline requires the same commitment as Barrett's Rule — it's a system, not willpower
