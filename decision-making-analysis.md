# Decision Making, Probability & Rational Thinking: Analysis of Better Questions Archive

> Analysis of 262 blog posts from betterquestions.co by Daniel Barrett.
> 24 posts identified as substantively relevant to decision making, probability, rational thinking, and related concepts.

---

## Table of Contents

1. [Overview](#overview)
2. [Post Summaries & Key Concepts](#post-summaries--key-concepts)
   - [Tier 1: Core Decision Making Posts](#tier-1-core-decision-making-posts)
   - [Tier 2: Applied Decision Making](#tier-2-applied-decision-making)
   - [Tier 3: Supporting & Adjacent Posts](#tier-3-supporting--adjacent-posts)
3. [Cross-Cutting Themes](#cross-cutting-themes)
4. [Key Thinkers & Influences](#key-thinkers--influences)
5. [Master Concept Index](#master-concept-index)

---

## Overview

Decision making is arguably the deepest intellectual thread in Better Questions. Barrett's most ambitious series, "All Woods Must Fail" (2020), was a multi-month exploration of risk, uncertainty, probability, and game theory, written in real-time during the early months of the COVID-19 pandemic. This series alone introduced more than a dozen distinct mental models and forms the backbone of this category.

Out of 262 total posts, **24 posts** are substantively about decision making, probability, and rational thinking. They cluster into three intellectual threads:

1. **The "All Woods Must Fail" Series (2020):** A cohesive 10-part series on risk, uncertainty, Bayesian priors, base rates, derivatives, game theory, common knowledge, and the epistemology of scientific knowledge — all applied to the COVID-19 pandemic.

2. **Decision Frameworks & Heuristics (2020-2024):** Posts on decision journals, explore vs. exploit strategies, bimodal strategies, the accuracy-effort tradeoff, micromorts, MinMax Regret, and the Trolley Problem.

3. **Cognitive Biases & Epistemology (2021-2024):** Posts on ironic processes, belief-action-result loops, updating priors, defining terms, question framing, and the relationship between expectations and perception.

---

## Post Summaries & Key Concepts

### Tier 1: Core Decision Making Posts

These posts are primarily and substantively about decision making, probability, or rational thinking.

---

#### 1. "Bad Priors" (2020-06-17)
**File:** `2020-06-17-bad-priors.md`

**Summary:** The opening essay of the "All Woods Must Fail" series. Introduces priors — the pre-existing beliefs we bring to every decision, built from personal experience. Uses the "how many people named Tom do you know?" exercise to show how personal experience shapes probabilistic reasoning. Priors influence both our predictions AND how we interpret evidence afterward.

**Key Concepts:**
- **Priors:** information about the world we bring to any decision-making process, based on lived experience
- Priors influence predictions AND post-hoc interpretation of evidence
- Our experiences are limited and therefore our priors are often unrepresentative
- "All decisions are just predictions about how things will turn out"
- The difficulty of updating priors when new information contradicts lived experience

---

#### 2. "Map Meets Territory" (2020-06-22)
**File:** `2020-06-22-map-meets-territory.md`

**Summary:** Introduces the distinction between priors (personal experience) and base rates (average outcomes from large datasets). Argues base rates often provide a more accurate picture than priors because they aggregate over more data. However, base rates can also mislead through narrative bias — the tendency to construct compelling stories from statistical data.

**Key Concepts:**
- **Base rates:** average statistical outcomes from large datasets
- Base rates vs. priors — aggregate data vs. personal experience
- **Narrative bias:** we construct compelling stories from statistics, which distorts their meaning
- Base rates are more reliable than priors for most predictions
- But both can be misleading — the map is never fully the territory (Korzybski)

---

#### 3. "8 Months To Live" (2020-07-06)
**File:** `2020-07-06-8-months-to-live.md`

**Summary:** Tells the story of Stephen Jay Gould, diagnosed with mesothelioma and given 8 months to live. Gould survived 20 years by recognizing that the median survival time was misleading for his individual case. Introduces the critical distinction between group-indexed and individually-indexed statistics.

**Key Concepts:**
- **Group-indexed vs. individually-indexed statistics:** averages describe groups, not individuals
- The median is the point where half the people are above and half below — it says nothing about the shape of the distribution
- **Right-skewed distributions:** a long tail of people who survive far longer than the median
- Individuating data (age, health, access to treatment) can radically change your personal odds
- "The man who opens a parachute store on the ground floor of the Empire State Building might cite excellent base rates, but his individual experience will be very different"

---

#### 4. "No Basis" (2020-07-06)
**File:** `2020-07-06-no-basis.md`

**Summary:** Introduces the critical distinction between risk and uncertainty, and the concepts of derivatives, underlyings, and basis. Uses the personal example of body fat and attractiveness to show how algorithmic thinking (if X then Y) can fail when the basis between derivative and underlying changes over time.

**Key Concepts:**
- **Risk vs. Uncertainty:** risk has known odds; uncertainty has unknown odds
- **Derivative:** a proxy measure correlated with what you actually care about (the underlying)
- **Underlying:** the thing you truly care about
- **Basis:** the relationship between derivative and underlying
- **Basis risk:** the damage that occurs when the basis isn't what you thought, or changes over time
- Humans are "incredible at creating algorithms and terrible at updating them"
- Statistical analysis works for risk; game theory works for uncertainty

---

#### 5. "False Positive" (2020-07-06)
**File:** `2020-07-06-false-positive.md`

**Summary:** Explores two dangerous illusions in decision making. The zero-risk illusion is overconfidence in certainty (believing a positive medical test means you definitely have a disease). The calculable-risk illusion is assuming you can calculate odds in situations of genuine uncertainty — the "Turkey Problem."

**Key Concepts:**
- **Zero-risk illusion:** a sense of certainty leads us to overlook probabilities
- **Calculable-risk illusion:** we think we know the odds when we actually don't
- **The Turkey Problem** (Nassim Taleb): every data point tells the turkey the farmer is kind — until Thanksgiving
- False positive rates mean a positive medical test is far less certain than it appears
- The most dangerous illusion is mistaking uncertainty for risk

---

#### 6. "The Beauty Contest" (2020-06-22)
**File:** `2020-06-22-the-beauty-contest.md`

**Summary:** Introduces game theory through Keynes's beauty contest analogy. In a Common Knowledge Game, you don't act based on your own preferences (first-order) or what you think others prefer (second-order), but on what you think others think others prefer (third-order). This applies to markets, politics, and social behavior.

**Key Concepts:**
- **Common Knowledge Game:** acting based on what you believe other people believe
- **First-order decision making:** choosing what YOU think is best
- **Second-order decision making:** choosing what you think OTHERS think is best
- **Third-order decision making:** choosing what you think others think others think is best
- Keynes's beauty contest analogy: judges vote for who they think other judges will pick
- Markets, elections, and social movements are all common knowledge games

---

#### 7. "Missionaries" (2020-07-06)
**File:** `2020-07-06-missionaries.md`

**Summary:** Explores how Common Knowledge is created through public statements, using the famous blue-eyed islander riddle. Information already known privately becomes transformative when made publicly known — because now everyone knows that everyone else knows. "Missionaries" are the public authorities whose statements create common knowledge.

**Key Concepts:**
- **Common Knowledge:** not just what everyone knows, but what everyone knows everyone else knows
- The blue-eyed islander riddle: N blue-eyed islanders leave on day N after a public statement
- **Missionaries:** public authorities whose statements create common knowledge
- It isn't new information that changes behavior — it's the fact that the information becomes public
- Once a missionary speaks, there's a time delay proportional to the ambiguity of the message
- Modern missionaries: media, the Fed, social media influencers

---

#### 8. "Monty Hall" (2020-08-10)
**File:** `2020-08-10-monty-hall.md`

**Summary:** Brings all the series concepts together through the Monty Hall Problem. Demonstrates how the problem appears to be one of risk (calculable odds) but is actually one of uncertainty (Monty Hall controls the game). The lesson: know when you're "playing the game" vs. "playing the player."

**Key Concepts:**
- **The Monty Hall Problem:** always switch doors (in the pure version, switching wins 2/3 of the time)
- Imagining a large group going through the same scenario clarifies probability problems
- But the real Monty Hall manipulated contestants, making it a game of uncertainty, not risk
- **Playing the game vs. playing the player:** statistical analysis vs. game theory
- The shift from game to player requires considering the other party's personality, incentives, and knowledge
- **Calculable-risk illusion in action:** contestants thought they were calculating odds when they should have been reading Monty

---

#### 9. "All In Our Heads" (2020-08-10)
**File:** `2020-08-10-all-in-our-heads.md`

**Summary:** Barrett's most philosophical essay, arguing that the difficulty of understanding COVID-19 isn't logistical but epistemological. Introduces Karl Popper (theories can only be falsified, never proven) and Thomas Kuhn (paradigm shifts through accumulation of anomalies). Argues that the public visibility of scientific self-correction during COVID made people lose faith in science.

**Key Concepts:**
- **Karl Popper:** theories can never be empirically proven, only falsified
- **Thomas Kuhn:** scientific paradigms are overturned when anomalies accumulate (paradigm shifts)
- Knowledge is an act of creative destruction — science advances by undermining itself
- COVID-19 made the self-destructive process of science publicly visible for the first time
- Information overload + public scientific debate = loss of faith in expertise
- When everyone becomes a "missionary," no one can determine what constitutes common knowledge
- **Epistemological crisis:** the problem isn't what we know but how we know what we know

---

#### 10. "One In a Million" (2020-08-10)
**File:** `2020-08-10-one-in-a-million.md`

**Summary:** The culminating essay of the COVID series. Introduces micromorts (one-in-a-million chance of death as a unit of risk), heuristics (rules of thumb that perform as well as complex models), and MinMax Regret (minimize the maximum regret you'd feel). Also contains a powerful moral argument against schadenfreude and for empathy as the foundation of collective action.

**Key Concepts:**
- **Micromorts:** a unit of risk equal to a one-in-a-million chance of death
- Micromorts enable comparing dissimilar risks on a common scale
- **Heuristics:** simple rules of thumb that often match or beat complex mathematical models
- **Accuracy-effort tradeoff:** more accuracy requires more effort; heuristics are efficient
- **The Gaze Heuristic:** fix your gaze on the ball, start running, adjust speed to keep the angle constant — requires zero knowledge of variables
- **Maximax:** maximize maximum possible payoff (high risk, high reward)
- **Maximin:** maximize minimum possible payoff (cap your downside)
- **MinMax Regret:** minimize the maximum regret you'd feel — incorporates emotions and opportunity cost
- Empathy as the only tool for bridging divides in the face of irreducible uncertainty

---

### Tier 2: Applied Decision Making

These posts apply decision-making frameworks to specific contexts or extend core concepts.

---

#### 11. "Corona Virus: The Decision Journal Challenge" (2020-03-13)
**File:** `2020-03-13-corona-virus-the-decision-journal-challenge.md`

**Summary:** Introduces the Decision Journal as a tool for improving reasoning and predictions. Write down your beliefs, your reasons, and specific predictions with deadlines. Then check back and honestly assess what you got right and wrong.

**Key Concepts:**
- **Decision Journal:** a structured tool for tracking predictions and updating beliefs
- Record: what you believe, why, and how you'll know if you were right
- Revisit predictions after a set period and honestly evaluate
- Most people avoid this because "we don't like to be wrong"
- Improves reasoning, prediction accuracy, and decision quality over time

---

#### 12. "Bad Priors: COVID-19 Edition" (2021-05-26)
**File:** `2021-05-26-bad-priors-covid-19-edition.md`

**Summary:** Barrett publicly updates his own priors about COVID-19, modeling the practice of honest self-correction. Admits to being wrong about surface transmission, outdoor masking risks, vaccine transmission prevention, and the lab-leak hypothesis. Shows how political identity distorted his reasoning.

**Key Concepts:**
- **Updating priors in practice:** public, specific, honest admission of what changed and why
- Political identity as a source of bad priors: "Because Donald Trump said it, so it must be bullshit"
- Lived experience feels more real than abstract data, making prior-updating emotionally difficult
- Masking took on social meaning beyond its epidemiological function
- "None of us are perfect, but we can all be better"

---

#### 13. "Sending Pens To Space" (2020-05-14)
**File:** `2020-05-14-sending-pens-to-space.md`

**Summary:** Uses the (apocryphal) NASA pen story to illustrate two decision-making traps: our love of complex solutions to simple problems, and how the questions we ask shape the answers we get. "How do we make pens work in space?" vs. "How do I most conveniently write in space?" yield very different solutions.

**Key Concepts:**
- **Question framing:** the questions we ask embed assumptions that constrain the answers
- "Every question has, within it, the seed of its own answer" (Taleb/Fat Tony)
- We prefer complex solutions because simplicity is frightening — it forces us to confront basic competence
- **The fear of simplicity:** retreating to complexity is often fear-based, not sophistication-based
- The Trolley Problem meme subverts the question rather than answering it — a valid strategy

---

#### 14. "Ironic Processes" (2021-04-21)
**File:** `2021-04-21-ironic-processes.md`

**Summary:** Introduces Daniel Wegner's Ironic Process Theory: attempting to suppress a thought makes it stronger, because the mind must imagine the thought in order to monitor for it. This applies to habits, affirmations, and any attempt at thought control. The implication: you cannot avoid, you can only redirect.

**Key Concepts:**
- **Ironic Process Theory** (Daniel Wegner): thought suppression strengthens the suppressed thought
- The mind must represent a thought in order to check if you're thinking about it
- Affirmations that negate (e.g., "I don't enjoy smoking") activate the very thing they deny
- "The mind cannot consciously avoid, it can only intentionally focus and attend" (Clifton Mitchell)
- "We are entwined with what we struggle against"
- Stress and fatigue amplify ironic processes

---

#### 15. "This, Or That" (2021-06-23)
**File:** `2021-06-23-this-or-that.md`

**Summary:** Argues that the inability to "have it all" isn't a defect but the source of meaning. Uses Viktor Frankl's insight that mortality creates responsibility — without death, there's no reason to act now. Parkinson's Law (work expands to fill time available) shows that unlimited time leads to paralysis, not productivity.

**Key Concepts:**
- **Opportunity cost:** choosing one thing means giving up others
- **Parkinson's Law:** work expands to fill the time available for its completion
- **Viktor Frankl:** "Death forms the background against which our act of being becomes a responsibility"
- Limitation and constraint create meaning, not deprivation
- Fear of "choosing wrong" leads to paralysis; acceptance of loss enables action

---

#### 16. "The Outside View" (2022-03-30)
**File:** `2022-03-30-the-outside-view.md`

**Summary:** Explains why the best performers all have coaches — not for knowledge, but for an accurate outside perspective. Cognitive biases are strongest regarding self-perception, and since all change requires self-knowledge, an outside view is essential.

**Key Concepts:**
- **The Outside View:** what a coach provides — an accurate external perception of yourself
- Coaches don't need to be better than you; they need to see what you can't
- "You can't read the label from inside the bottle"
- All change requires personal change; personal change requires accurate self-knowledge
- Cognitive biases are strongest when directed at ourselves
- Goldratt: "We are in a better position than the other party to recognize how to fulfill his major needs"

---

#### 17. "Be Careful What You Expect" (2023-03-29)
**File:** `2023-03-29-be-careful-what-you-expect.md`

**Summary:** Describes the feedback loop between beliefs, actions, results, and back to beliefs. What you expect changes what you see. Trying to change at the level of action ("just do it!") fails because underlying beliefs remain unchanged. Lasting change requires changing beliefs, not just behaviors.

**Key Concepts:**
- **Belief-Action-Result Loop:** Belief → Action → Result → Belief (self-reinforcing cycle)
- Expectations change perception — you see what you expect to see
- Intervening at the level of action fails if underlying beliefs are unchanged
- Iain McGilchrist: "Our minds are so constructed that we don't even see the discrepancies"
- Attempts at change that operate purely at the conscious/rational level rarely work

---

#### 18. "Getting Lucky" (2024-12-04)
**File:** `2024-12-04-gett.md`

**Summary:** Introduces the explore/exploit framework from computer science (via *Algorithms to Live By*). When you have time, explore; when you need results, exploit your best option. The key is being "on either end of the explore-exploit spectrum, never in the middle." Also covers optimal stopping problems and bimodal strategies.

**Key Concepts:**
- **Explore vs. Exploit:** explore when you have time to use new knowledge; exploit when you need results
- **Optimal stopping problem:** how long to search before choosing
- **Bimodal (barbell) strategy:** go all-in on exploring OR all-in on exploiting — never half of each
- **Multiple safe-to-fail probes** (Dave Snowden): test things without over-committing
- Indeterminacy is where luck comes from — being in the right place at the right time requires openness
- The value of exploration can only decrease over time (shrinking remaining opportunities)

---

#### 19. "Shoot An Arrow, See Where It Lands" (2024-09-20)
**File:** `2024-09-20-shoot-an-arrow-see-where-it-lands.md`

**Summary:** Barrett's personal reflection on the explore/exploit framework in practice. After a decade of running his agency, he's in full explore mode — testing coaching, hypnotherapy, blogging, podcasting, and more. The essay also introduces Peter Palchinsky's maxim: try new things, make them small, learn from the experience.

**Key Concepts:**
- **Bimodal strategy in practice:** Barrett's own transition from exploit to explore
- **Peter Palchinsky's principles:** try new things, make them small (safe-to-fail), and learn
- Decisions carry costs — opportunity cost is real
- Fear of commitment leads to underperformance; but so does premature commitment
- Feedback from exploration = "the universe whispering that there is something here"

---

### Tier 3: Supporting & Adjacent Posts

These posts touch on decision making through adjacent concerns (productivity framing, personal philosophy, belief systems).

---

#### 20. "Order of Operations" (2022-02-23)
**File:** `2022-02-23-order-of-operations.md`

**Summary:** Barrett's personal heuristic for getting back on track: Sleep → Food → Attention → Focus. Each step builds on the one before; you can't skip ahead. A practical application of decision-making through ordered priorities rather than ambition.

**Key Concepts:**
- **Order of Operations:** Sleep → Food → Attention → Focus (a sequential heuristic)
- Each step is prerequisite to the next — you cannot skip the sequence
- Practical, detailed guidance for each phase (light exposure, calorie tracking, media filtering)
- "Knowing everything and actually acting on that information are two very different things"
- Attention is capacity to focus; focus is what you're focused on

---

#### 21. "Direction, Path and Outcome" (2021-10-06)
**File:** `2021-10-06-direction-path-and-outcome.md`

**Summary:** Introduces Work Cycles — 90-minute focused blocks with a clear direction, path, and outcome. A practical decision-making structure for creative work where "how to spend your time" is the primary challenge.

**Key Concepts:**
- **Work Cycles:** time-boxed blocks with Direction (what), Path (how), and Outcome (result)
- Creative work lacks clear next actions, making time management a decision-making problem
- If what you do can be reduced to a checklist, it can be automated
- Adapted from Ultraworking, simplified for reduced friction
- The Pomodoro Technique as the underlying time structure

---

#### 22. "All You Need Is One Idea" (2020-01-27)
**File:** `2020-01-27-all-you-need-is-one-idea.md`

**Summary:** Barrett's founding post. Argues that transformative ideas can produce instantaneous change — the idea that change must be "hard" is itself a mental model. The blog's mission: explore potentially life-changing ideas, filtering signal from noise.

**Key Concepts:**
- **Instantaneous change through ideas:** a single heuristic (e.g., shoulder seam rule) can immediately transform outcomes
- The mental model that "change must be hard" is itself a barrier
- The primary problem is noise — too many ideas to filter
- Heuristics and mental models as the practical tools for better decisions

---

#### 23. "Define Your Terms" (2024-04-04)
**File:** `2024-04-04-define-your-terms.md`

**Summary:** Argues that defining terms is the foundational act of rational thinking, yet one we actively resist. Explores both the intellectual difficulty (words are vaguer than we realize) and the emotional difficulty (defining what you want makes failure possible). Applied to Barrett's transition into hypnotherapy.

**Key Concepts:**
- **Define your terms:** the foundation of clear thinking, and the thing we most resist
- Intellectual difficulty: words carry more ambiguity than we realize
- Emotional difficulty: defining your desire makes failure possible
- "Easiest way to make people mad is to ask them to define the terms they've been using"
- Speaking your desire is an act of courage and commitment

---

#### 24. "The Reasonably Rational Thinking Process, Part 2: The Goal Tree" (2020-03-10)
**File:** `2020-03-10-the-reasonably-rational-thinking-process-part-2-the-goal-tree.md`

**Summary:** While primarily a systems thinking post, the Goal Tree is fundamentally a decision-making tool. Problems only exist in relation to goals, and most decision paralysis stems from unclear goals. The Goal Tree decomposes broad aspirations into Critical Success Factors and Necessary Conditions.

**Key Concepts:**
- **Problems only exist in relation to goals** — no situation is an issue unless you have a desired alternative
- Goal Tree forces clarity about what you actually want
- Unclear priorities cause subconscious avoidance of progress
- Start with Necessary Conditions at the bottom of the tree — the simplest, most immediate actions
- Speed of implementation + feedback > rigorous completeness for personal decisions

---

## Cross-Cutting Themes

### 1. Risk vs. Uncertainty: The Master Distinction
The single most important concept in Barrett's decision-making framework. Risk has known probabilities (use statistical analysis); uncertainty has unknown probabilities (use game theory). Most of our biggest mistakes come from confusing the two — either treating uncertainty as calculable risk or treating risk as pure uncertainty. This distinction appears in at least 8 posts.

### 2. Priors, Base Rates, and the Difficulty of Updating
We build mental models from experience (priors), and those models resist update even when contradicted by evidence. Base rates (aggregate statistics) are more reliable but can still mislead through narrative bias or group-indexing. The hardest and most important cognitive skill is updating priors honestly — as Barrett demonstrates by publicly correcting his own COVID beliefs.

### 3. The Map Is Not the Territory
A thread connecting probability theory, epistemology, and personal development. All our models — statistical, mental, social — are simplifications of reality. Derivatives approximate underlyings; base rates describe groups, not individuals; scientific theories are useful but never "true." The basis between map and territory can change over time, and failing to notice this is the source of catastrophic errors.

### 4. Heuristics Over Optimization
Complex mathematical models are not always better than simple rules of thumb. The Gaze Heuristic catches baseballs without any physics. MinMax Regret incorporates emotional reality that pure math ignores. Micromorts enable quick risk comparisons without epidemiological expertise. Barrett consistently argues that "close enough" is often the most rational strategy, especially under uncertainty.

### 5. Question Framing Shapes Answer Space
"How do we make pens work in space?" and "How do I conveniently write in space?" produce radically different solutions. The Trolley Problem constrains your options by its framing. Affirmations that negate ("I don't enjoy smoking") activate the thing they deny. Barrett repeatedly emphasizes that the question you ask determines the answers available to you.

### 6. The Epistemological Crisis of Modern Life
COVID-19 made visible what was always true: scientific knowledge advances through self-destruction, information overload makes it impossible to determine truth, and everyone's "missionary" contradicts every other missionary. This isn't a temporary crisis — it's the permanent condition of modern epistemology. The rational response is humility, heuristics, and empathy rather than false certainty.

### 7. Emotion as Data, Not Obstacle
MinMax Regret explicitly incorporates regret — an emotion — into rational decision-making. Frankl's insight that mortality creates meaning is an emotional truth with practical implications. Barrett's argument for empathy during COVID isn't sentimental — it's game-theoretic (without empathy, cooperation is impossible). Emotions are information about what matters, not noise to be eliminated.

---

## Key Thinkers & Influences

| Thinker | Contribution | Posts Referencing |
|---|---|---|
| **Nassim Nicholas Taleb** | Turkey Problem, antifragility, "every question contains the seed of its own answer" | False Positive, Sending Pens To Space |
| **Karl Popper** | Falsificationism — theories can only be falsified, never proven | All In Our Heads |
| **Thomas Kuhn** | Paradigm shifts, Structure of Scientific Revolutions | All In Our Heads |
| **Stephen Jay Gould** | Median survival statistics, right-skewed distributions, individuating data | 8 Months To Live |
| **John Maynard Keynes** | Beauty contest analogy for markets/common knowledge games | The Beauty Contest |
| **Viktor Frankl** | Mortality creates meaning; constraint enables responsibility | This, Or That |
| **Daniel Wegner** | Ironic Process Theory — thought suppression strengthens the thought | Ironic Processes |
| **Iain McGilchrist** | Expectations shape perception; hemispheric brain theory | Be Careful What You Expect |
| **Clifton Mitchell** | "The mind cannot consciously avoid, it can only intentionally focus" | Ironic Processes |
| **Dave Snowden** | Safe-to-fail probes, Cynefin framework | Getting Lucky, Shoot An Arrow |
| **Peter Palchinsky** | Try new things, make them small, learn from the experience | Shoot An Arrow |
| **Alfred Korzybski** | "The map is not the territory" | Map Meets Territory |
| **Eli Goldratt** | Outside View, Theory of Constraints, decision clarity | The Outside View, Goal Tree |
| **Terence Tao** | Blue-eyed islander riddle | Missionaries |
| **Ben Hunt (Epsilon Theory)** | Common Knowledge Games, missionaries, narrative | Beauty Contest, Missionaries |

---

## Master Concept Index

| Concept | Definition (Barrett's usage) | Key Post(s) |
|---|---|---|
| **Priors** | Pre-existing beliefs about the world, built from personal experience, used to make predictions | Bad Priors, Bad Priors COVID Edition |
| **Base Rate** | The average statistical outcome from a large dataset; a more objective alternative to priors | Map Meets Territory |
| **Group-Indexed vs. Individually-Indexed Statistics** | Group averages describe groups, not individuals; individuating data matters | 8 Months To Live |
| **Risk** | A situation where probabilities and potential payoffs are known — use statistical analysis | No Basis, False Positive |
| **Uncertainty** | A situation where probabilities and payoffs are unknown — use game theory | No Basis, False Positive |
| **Derivative** | A proxy metric correlated with the thing you actually care about (the underlying) | No Basis |
| **Underlying** | The thing you truly care about, which may be hard to measure or change directly | No Basis |
| **Basis** | The relationship between derivative and underlying | No Basis |
| **Basis Risk** | The damage that occurs when the basis isn't what you thought, or changes over time | No Basis |
| **Zero-Risk Illusion** | Overconfidence in certainty — overlooking probabilities | False Positive |
| **Calculable-Risk Illusion** | Treating uncertainty as calculable risk — "we think we know the odds" | False Positive, Monty Hall |
| **The Turkey Problem** | Every data point confirms the model — until the model catastrophically fails | False Positive |
| **Common Knowledge Game** | Acting based on what you believe other people believe | The Beauty Contest, Missionaries |
| **First/Second/Third-Order Decision Making** | Choosing based on your own preferences vs. others' preferences vs. others' beliefs about others' preferences | The Beauty Contest |
| **Missionaries** | Public authorities whose statements create common knowledge | Missionaries, All In Our Heads |
| **Micromorts** | A unit of risk equal to one-in-a-million chance of death | One In A Million |
| **Heuristics** | Simple rules of thumb that often perform as well as complex mathematical models | One In A Million, All You Need Is One Idea |
| **Accuracy-Effort Tradeoff** | More accuracy requires more effort; heuristics balance accuracy and efficiency | One In A Million |
| **Gaze Heuristic** | Fix your gaze on the ball, start running, adjust speed to keep the angle constant | One In A Million |
| **Maximax** | Maximize maximum possible payoff — high risk, high reward | One In A Million |
| **Maximin** | Maximize minimum possible payoff — cap your downside | One In A Million |
| **MinMax Regret** | Minimize the maximum regret you'd feel — incorporates emotional and opportunity costs | One In A Million |
| **Falsificationism (Popper)** | Theories can never be proven, only falsified — knowledge proceeds negatively | All In Our Heads |
| **Paradigm Shift (Kuhn)** | Scientific consensus is overturned when anomalies accumulate beyond tolerance | All In Our Heads |
| **Ironic Process Theory** | Attempting to suppress a thought makes it stronger | Ironic Processes |
| **Decision Journal** | A structured record of beliefs, reasons, and predictions, revisited to improve reasoning | Decision Journal Challenge |
| **Explore vs. Exploit** | Explore when you have time; exploit when you need results | Getting Lucky, Shoot An Arrow |
| **Bimodal (Barbell) Strategy** | Go all-in on exploring OR exploiting — never half of each | Getting Lucky |
| **Optimal Stopping Problem** | How long to search before choosing — depends on how much time you have to use the knowledge | Getting Lucky |
| **Question Framing** | The way a question is asked constrains the answers available | Sending Pens To Space |
| **Belief-Action-Result Loop** | A self-reinforcing cycle: beliefs shape actions, which produce results, which confirm beliefs | Be Careful What You Expect |
| **Order of Operations** | A sequential heuristic: Sleep → Food → Attention → Focus | Order of Operations |
| **Opportunity Cost** | Every choice means giving up alternatives; limitation creates meaning | This, Or That |
| **The Outside View** | External perspective on yourself, unclouded by self-serving biases | The Outside View |
| **Narrative Bias** | The tendency to construct compelling stories from statistical data, distorting their meaning | Map Meets Territory |
