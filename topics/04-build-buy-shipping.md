---
title: "04. Build vs buy & shipping cadence"
layout: default
nav_order: 5
---

# Build vs buy and shipping cadence
{: .no_toc }

*~8 min read*

## Why it matters

Your scarce resource is not cloud credits. It is the number of focused days before you run out of motivation, semester, or money. Every week spent on auth, payments plumbing, or a custom design system is a week not spent on the wedge. The other half of this page is cadence: a team that "builds" but does not put software in front of a user on a regular rhythm is not a startup yet. It is a repo.

This pairs with [MVP scope](../03-mvp-scope/). Scope says what. This page says what you refuse to build yourself, and how often something real ships.

## Core concepts

- **Build the wedge. Buy the rest.** Buy (or take the boring hosted version of) authentication, email delivery, payments, error tracking, hosting, file storage, and analytics. Build the workflow the user is paying you for — the part where your [why this](../02-idea-wedge/) lives.
- **"Buy" includes doing it by hand.** A Stripe Payment Link, a Typeform, a spreadsheet, and your own inbox are legitimate v1 infrastructure. Replace them when the manual step is the bottleneck, not when it feels unprofessional.
- **Pick the stack you can already ship in.** The best stack is the one both founders can debug at midnight. A résumé-driven rewrite is a hidden delay. You can migrate later if the product works; you cannot migrate a product nobody uses.
- **Technical debt is a choice with a date.** Shipping a shortcut is fine if you name it ("we will rewrite billing when we have 10 paying teams, not before"). Unnamed debt is how the codebase becomes the excuse for not talking to users.
- **Cadence beats heroics.** A weekly ship — something a user can touch — keeps scope honest. A six-week "we'll show you when it's ready" almost always means the spec grew.
- **The founder still does support.** Early on, the person who wrote the code should watch it break. Hiring support, or hiding behind a bot, throws away the information the MVP exists to collect.
- **If you are the first engineer joining,** ask what shipped in the last two weeks and who the last user was. A beautiful roadmap with no cadence is the thing you are signing up to fix. See [Hiring](../11-hiring-first/).

## What to do next

- [ ] List everything you think you need to build. Split it into two columns: "the job" and "plumbing." Plumbing gets a vendor, a manual step, or a no.
- [ ] Choose the stack in one sitting and write it at the top of the README. Ban rewrites until the first users have done the job.
- [ ] Set a weekly shipping ritual: same day, one user-visible change, demoed to each other (or to a user) even if it is small. Put it on the calendar before you pick a project-management tool.
- [ ] Instrument the one action that matters so you know it happened without reading logs for fun. A single event ("reconcile_completed") is enough. More metrics come in [Metrics that matter](../07-metrics-that-matter/).
- [ ] Keep a "not building" list next to the spec. Review it in the weekly ritual so bought-or-skipped things don't creep back in.

## Mental model

```
  your week
  -------------------------------------------------
  most days:  the wedge workflow  (you build this)
  a few hours: glue              (you buy or do by hand)
  one block:  ship + watch a user hit the change

  build if:  it is the reason they switch
  buy if:    users do not care how it works
  manual if: you have done it fewer than ~10 times

  cadence:   one user-visible change per week
             no change = the week did not happen
```

Speed is a consequence of a short list, not of working more nights.

## Common failure modes

- **Custom auth, custom billing, custom design system before ten users.** None of those is the product. They feel like engineering because they are.
- **Replatforming as procrastination.** "We should move to microservices / a monorepo / Rust" in month two is almost never about users.
- **Shipping to production and not to a person.** The deploy is not the cadence. The cadence is a user encountering the change.
- **Buying a tool to avoid a decision.** A heavy project-management suite with an empty backlog is still an empty backlog. The calendar ritual matters more than the tool.

## Watch

- [Tips For Technical Startup Founders \| Startup School](https://www.youtube.com/watch?v=rP7bpYsfa6Q) — Diana Hu, Y Combinator. How a technical founder should spend time, pick a stack, live with debt, and only then hire.
- [How to Build An MVP \| Startup School](https://www.youtube.com/watch?v=QRZ_l7cVzzU) — Michael Seibel, Y Combinator. The shipping half: get a thin product out, then iterate. Use it as the cadence reminder if the stack talk tempts you to tinker.
- [The Best Way To Launch Your Startup \| Startup School](https://www.youtube.com/watch?v=u36A-YTxiOw) — Y Combinator. Launch is a repeated motion, not a single Product Hunt day. Good bridge into [Distribution](../05-distribution-gtm/).

## Further reading

- [How to Plan an MVP](https://www.ycombinator.com/library/6f-how-to-plan-an-mvp) — Y Combinator. The "hacks for building quickly" section is a build-vs-buy list in disguise.
