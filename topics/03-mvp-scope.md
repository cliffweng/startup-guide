---
title: "03. MVP scope"
layout: default
nav_order: 4
---

# MVP scope
{: .no_toc }

*~8 min read*

## Why it matters

An MVP is not a small version of your vision. It is the fastest thing you can put in front of the wedge user that does the job well enough for them to switch from the workaround. Technical founders expand scope because building feels like progress and cutting feels like failure. The opposite is true: every feature you refuse to build is a week you get back for [distribution](../05-distribution-gtm/).

## Core concepts

- **Launch is a learning tool, not a verdict.** The first version is how the conversation with users gets specific. It will be missing things. That is the point, as long as the missing things are not the job itself.
- **Time-box the spec, then cut it again.** "What can two people ship in two weeks?" is a better filter than "what does v1 need?" If the honest answer is three months, the wedge is still too wide. Go back to [Idea → wedge](../02-idea-wedge/).
- **Write the spec down.** A spec that lives in Slack changes every time someone smart objects. A written list lets you see that you are changing it.
- **One path, happy-path only.** Sign-up, the core action, and a way for you to know it happened. No admin panel, no settings page, no teams, no roles, no notifications framework — unless that *is* the job.
- **Manual behind the scenes is allowed.** Concierge the step you haven't automated. If the treasurer emails you a CSV and you send back a reconciled sheet the same day, you are testing the job. Automate the step only after it repeats.
- **"Embarrassing" is a feature if a real user gets value.** Embarrassing to other engineers is not the same as broken for the user. Broken for the user (loses their data, can't finish the job) is not an MVP. It is a bug.
- **Define done as "a user did the job," not "we deployed."** A deploy nobody uses taught you about your CI pipeline.

## What to do next

- [ ] Write the spec as a numbered list of user-visible behaviors. Cap it at what you can build before a date on the calendar (two weeks is a good default).
- [ ] Mark each line: must-have for the job, or "they might ask." Delete the second category from this sprint. Park it in a "not now" doc so you stop re-arguing it.
- [ ] Circle the one step you will do by hand. Name who does it (you) and how the user reaches you (a shared inbox, a text, a calendar link).
- [ ] Pick the first user from the list in [Problem & customer](../01-problem-customer/) and tell them the date you will hand it over. A date with a person's name on it beats an internal milestone.
- [ ] Ship to that person even if the second user would want more. Then watch them use it. Do not narrate. Note where they stall.
- [ ] After the session, cut or fix one thing before you add anything. Scope only grows by default.

## Mental model

```
  vision (do not build)          this sprint (build)
  -------------------------      -------------------------
  accounts, teams, billing,      one user
  mobile, admin, analytics,      one job
  "and also AI"                  one path through it
                                 you in the loop where
                                 the software is thin

  spec written down
        |
        v
  delete anything not required
  for the first person to finish
        |
        v
  date + named user
        |
        v
  watch them, then cut again
```

The MVP is finished when that person gets the outcome, not when you are proud of the repo.

## Common failure modes

- **Building the platform because "we'll need it."** You will need a different thing once five users have touched the product. Premature structure is how two-week plans become semesters.
- **No named user at the end of the sprint.** "Launch" to an empty production URL is a deploy. Schedule the person first.
- **Falling in love with the demo.** The demo optimized for other students is usually not the path the treasurer takes. Watch the treasurer.
- **Quality in the wrong place.** Pixel-perfect empty states, zero tests on the one action that loses data. Polish the step they must trust. Leave the rest ugly.

## Watch

- [How to Build An MVP \| Startup School](https://www.youtube.com/watch?v=QRZ_l7cVzzU) — Michael Seibel, Y Combinator. What an early product actually was at Airbnb, Twitch, and Stripe, and why speed matters more than completeness.
- [Michael Seibel - How to Plan an MVP](https://www.youtube.com/watch?v=1hHMwLxN6EM) — Y Combinator. Time-box the spec, write it down, cut it, and don't fall in love with it. The practical companion to the talk above.

## Further reading

- [How to Plan an MVP](https://www.ycombinator.com/library/6f-how-to-plan-an-mvp) — the YC library write-up that matches the Seibel lecture.
- [Do Things that Don't Scale](http://www.paulgraham.com/ds.html) — Paul Graham. Manual work is part of the scope, not a failure of the scope.
