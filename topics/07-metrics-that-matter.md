---
title: "07. Metrics that matter"
layout: default
nav_order: 8
---

# Metrics that matter
{: .no_toc }

*~9 min read*

## Why it matters

Early metrics are not a dashboard. They are three questions: did a new user reach the value, did they come back, and did anyone pay. Everything else (visits, signups, GitHub stars, waitlist count) can go up while the company is not working. Pick a handful of numbers you will look at every week in the [operating cadence](../14-weekly-operating-cadence/), and ignore the rest until those move.

You need users for any of this to mean something. If you have fewer than five people who tried the product, go back to [Distribution](../05-distribution-gtm/) before you build analytics.

## Core concepts

- **Activation: they reached the aha, not the signup.** Define activation as the first moment the wedge job is done. For a reconciliation tool, that is "a real ledger came out," not "they created an account." Write the event down. If you cannot name it, you do not know what the product is for.
- **Retention: they came back without you nagging.** Plot it by cohort (people who started the same week) not by a blended "active users" line that mixes newcomers with everyone else. A flat or rising cohort curve means the product is fitting into the job. A curve that falls off a cliff means the workaround won.
- **Revenue: someone paid, and whether it repeats.** Cash collected beats bookings you hope to invoice. If the model is recurring, track who renewed or who was still paying in week four. A one-time pilot fee is still useful — label it as a pilot so you don't pretend it is a run-rate. Pricing lives in [Pricing & packaging](../06-pricing-packaging/).
- **One primary metric.** At this stage it is usually revenue, or a tight proxy that leads revenue (activated teams per week) if you are deliberately pre-charge for a defined reason. Secondary metrics (activation rate, week-4 retention) explain the primary one. Vanity metrics explain nothing.
- **Rates need a denominator you trust.** "20% retention" with five users is a story, not a law. Still compute it — and write the numerator beside it ("1 of 5 came back"). False precision is worse than a fraction.
- **Qualitative sits next to the number.** When retention drops, the metric does not say why. The call does. Every ugly number should schedule a conversation, not a redesign in isolation.
- **B2B and consumer count differently, the questions don't.** Consumer: did they complete the core action, did they return next day or next week, will they pay or refer. B2B: did the account reach value in the pilot, did they expand usage, did they pay. Don't import a social-app dashboard into a tool a treasurer opens twice a month. Match the window to the job.

## What to do next

- [ ] Write the activation event in one line: "Activated when the user ____." Instrument that single event. Skip the rest of the taxonomy.
- [ ] Make a cohort scratchpad (a spreadsheet is fine): each row is a user or account, columns are week 0, week 1, week 4 — did they do the job again, and did they pay.
- [ ] Pick the primary metric for the next four weeks. Tell your cofounder. Put it at the top of the weekly review.
- [ ] Define a vanity list you will not celebrate: raw signups, page views, followers. You can glance at them. They do not get to be the goal.
- [ ] When a cohort looks bad, book two calls with people who left or stalled before you change the product. Bring their words to the review.
- [ ] Once money is real, hand the same numbers to [Runway](../08-runway-unit-economics/) so growth and cash are the same conversation.

## Mental model

```
  new user
     |
     v
  activation ---- no ---> the first session failed
     |                     (watch one, fix the path)
    yes
     |
     v
  return on the job's natural cycle ---- no ---> workaround won
     |
    yes
     |
     v
  paid (or a dated commitment to pay)
     |
     v
  that is the company, in miniature

  weekly view:  cohort table + cash collected
  not:          a wall of charts
```

If you only have time for one artifact, make it the cohort spreadsheet with a "paid?" column.

## Common failure modes

- **Celebrating signups.** Signups measure your launch tweet, not the product. Activation measures the product.
- **A blended retention number.** New users hide the fact that last month's users left. Cohorts are the whole point.
- **Dashboard theater.** A tool with 40 charts before you have 40 users is procrastination. The spreadsheet is enough.
- **Optimizing a proxy that isn't the job.** Time-on-site, messages sent, or "AI queries" can rise while the treasurer still reconciles in Excel. Tie the metric to the outcome they wanted.

## Watch

- [B2B Startup Metrics | Startup School](https://www.youtube.com/watch?v=_mKeVGSqQac) — Y Combinator. Which numbers matter when the buyer is an account, and how not to drown in them.
- [Consumer Startup Metrics | Startup School](https://www.youtube.com/watch?v=fdD4y4Civp4) — Y Combinator. The consumer counterpart: activation and retention without pretending you are already a growth team.
- [How To Keep Your Users | Startup School](https://www.youtube.com/watch?v=VNxBZ7ka5J0) — Y Combinator. Retention as something you act on — cohorts, why people leave, what to change — not a chart to admire.

## Further reading

- [Startup Growth](http://www.paulgraham.com/growth.html) — Paul Graham. A push to care about the rate, after you have a real numerator.
