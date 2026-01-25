---
title: "Tutorial: Automating PPC Client Reports Using Zapier and OpenAI"
date: 2023-02-10T21:44:56.000Z
author: "Daniel Barrett"
url: https://www.betterquestions.co/how-to-automating-ppc-client-reports-using-zapier-and-openai/
slug: how-to-automating-ppc-client-reports-using-zapier-and-openai
description: "Last week we talked about Freud.\n\nThis week? We&#x27;re talking Droid.\n\nI&#x27;ve been doing quite a bit of work lately on automating client reports.\n\nSee, most of our clients are NOT technical. We send them a dashboard of all their campaign stats, but it looks like this:\n\n...and, well. Yeah. Not exactly the easiest thing in the world to read!\n\nThe end result of all that is generally that client&#x27;s don&#x27;t read their dashboards. This leads them to feeling out-of-the-loop, creates anxiety, and generally creat"
image: https://www.betterquestions.co/content/images/2023/02/enemieslist_a_cute_flat_cartoon_of_a_frazzled_android_producing_e36adf59-47cb-4b12-a2b4-cf56cc176c7d.png
tags: []
content_type: essay
word_count: 695
scraped_at: 2026-01-25T16:24:33.629505Z
---

Last week we [talked about Freud](https://www.betterquestions.co/the-secret-at-the-heart-of-analysis/).

This week? We're talking ***Droid*.**

I've been doing quite a bit of work lately on automating client reports.

See, most of our clients are NOT technical. We send them a dashboard of all their campaign stats, but it looks like this:

![](https://www.betterquestions.co/content/images/2023/02/Screen-Shot-2023-02-10-at-4.26.19-PM.png)

An example client dashboard.

...and, well. Yeah. Not exactly the easiest thing in the world to read!

The end result of all that is generally that client's **don't read their dashboards.** This leads them to feeling out-of-the-loop, creates anxiety, and generally creates a bad experience.

To help with this, we produce written-reports summarizing their account data in a friendly way. The reports look something like this:

![](https://www.betterquestions.co/content/images/2023/02/Screen-Shot-2023-02-10-at-4.28.13-PM.png)

An example client report.

Better! But still not great, because now the account manager is spending a significant amount of time each week summarizing a bunch of numbers when they could be...you know. Making those numbers go UP!

One fun potential solution I've been playing with: Using Zapier's OpenAI API connection to automatically create reports based on data in a Google Sheet.

I walk through the process here:

Here's an example report, produced by GPT after inputting the last 14 days worth of account data, the data from the *previous* 14 day period, and a quick description of the tasks completed by the team:

*"**ACCOUNT UPDATE:**The past 14 days have seen an increase in account performance across all metrics. There has been an increase in impressions of 27%, reaching a total of 54,521 impressions. This is an absolute change of 11,719 impressions. CTR has seen a slight increase of 4%, bringing it up to 0.12%. This is an absolute change of 0.005%. CPM has seen a decrease of 9%, bringing it down to $1.70. This is an absolute change of $0.17.Overall, the account has seen a significant increase in impressions. This could be due to changes in the targeting, or changes in the ad copy. In addition, an increase in CTR is good news, as it indicates that more people are engaging with the ad. The decrease in CPM suggests that the account is running more efficiently, as it is costing the client less to get the same or better results.The account is performing well, and I will continue to monitor the metrics to ensure that the client is getting the best results possible.*

***MANAGEMENT NOTES:** Over the past 14 days, I have made several changes to the online marketing account to ensure that we are targeting motivated sellers with intent-based searches. To start, I added 23 negative terms to limit traffic that is looking for general information. This ensures that we are only targeting relevant searches that are likely to convert. I also paused two non-performing keywords to reduce our overall cost.Looking ahead, I plan to continue monitoring the performance of our account for the next 14 days. This is necessary as it takes time for Google to collect more data after our ads stopped running and became recently active. I will also add more negative keywords to make sure that we are only showing for high-intent searches. This will help us to better target motivated sellers who are more likely to convert. Finally, I will review the performance of our keywords and will adjust bids accordingly to ensure that we are maximizing our reach and optimizing our budget."*

Neat! Instant productivity gain for our team (less time writing, more time managing), and clarity gain for our clients (numbers explained in plain English).

There are a few small caveats I would encourage you to keep in mind, however:

**1.) All forms of summarization necessarily leave things out, which can be dangerous:**

![](https://www.betterquestions.co/content/images/2023/02/Screen-Shot-2023-02-10-at-4.32.53-PM.png)

**2.) AI can sometimes "hallucinate" (a.k.a., make things up).**

In order to avoid GPT "improvising" data that isn't actually there, I have since added the following text to the prompt I show in the video:

*"In the event that all of the data is not provided, please state that the data is missing and do not include any estimates or assumptions in the report."*

Of course, no post on GPT would be complete without the pre-requisite screenshot of me asking GPT about itself, so here you go:

![](https://www.betterquestions.co/content/images/2023/02/Screen-Shot-2023-02-10-at-4.36.45-PM.png)

**By the way, I'm looking to get started doing automation/Zapier consulting, so if you're interested, [feel free to hit me up.](https://www.betterquestions.co/consulting/)**

**Dan | [@danbarrett316](https://twitter.com/danbarrett316?ref=betterquestions.co)**