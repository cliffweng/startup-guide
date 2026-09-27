---
title: "08. Runway & simple unit economics"
layout: default
nav_order: 9
---

# Runway and simple unit economics
{: .no_toc }

*~9 min read*

## Why it matters

Startups usually die because the bank account hits zero, not because the idea was "bad" in the abstract. Runway is how many months you have at the current rate of cash leaving. Unit economics is the smaller question underneath: when one customer pays, do you keep anything after the direct cost of serving them, and how long until a dollar you spent to get them comes back. You do not need a finance hire to know these. You need the bank balance and a spreadsheet.

This is not full accounting. It will not close your books or file your taxes. It will stop you from being surprised.

## Core concepts

- **Cash is the only number that keeps you alive.** Revenue you have not collected does not pay rent. Net burn is cash out minus cash in over a month, from the bank account, not from a hopeful P&L. If a customer "agreed" but pays next semester, they are not in this month's burn.
- **Runway is cash divided by net burn.** $30,000 in the bank and $5,000 net burn is 6 months. Say the months out loud. If burn is lumpy (a one-time legal bill), use a 3-month average and still note the lump so you don't scare yourself — or comfort yourself — with one weird month.
- **Default alive vs default dead.** If you change nothing else (no new fundraise) and revenue keeps growing the way it actually has, do you reach cash-flow break-even before the account hits zero? If yes, you are default alive. If no, you are default dead, and the work is to cut burn, grow revenue, or both — not to "wait and see." Hope is not a third category.
- **A unit is one customer (or one account), not the company.** Price minus the direct cost to serve that one customer (payment fees, the model API calls you can attribute, the contractor hour you spend only because they exist) is a rough contribution. If contribution is negative, growth makes you poorer. Fix price or cost before you "scale."
- **Do not invent a precise LTV.** Lifetime value needs a retention curve you do not have at ten users. Use a simple payback instead: if you spent money or hours to acquire them, how many payments until contribution covers that spend? "Payback under a few months" is a useful early bar. A 5-year LTV spreadsheet is fiction.
- **Your own unpaid time is not free, but don't launder it into fake precision.** For a student team, the dangerous costs are cash costs and opportunity (a semester). Track cash honestly. Separately, notice if the only way the unit "works" is you doing unpaid concierge forever — that's a signal to automate or to charge more, which you already allowed as a manual step in [MVP scope](../03-mvp-scope/).
- **Fundraising is not runway you have.** It is runway you might buy, at the cost of time and dilution. See [Fundraising map](../12-fundraising-map/). Decide as if the round slips two months, because it often does.

## What to do next

- [ ] Open the bank account (or the shared ledger if you are not incorporated yet — still list real cash). Write down the balance today.
- [ ] For last month, list cash in and cash out. Net burn = out − in. Do it from transactions, not memory.
- [ ] Compute runway in months. Put the date you hit zero on the calendar. That date drives hiring and scope, not the other way around.
- [ ] Answer default alive or default dead in one sentence, using the revenue trend you actually have (see [Metrics](../07-metrics-that-matter/)). If dead, name the cut or the price change you will make this week.
- [ ] For one paying (or pilot) customer, sketch price − direct cost. If you have no payers, write "unknown" — do not backfill with a fantasy ARPU.
- [ ] Repeat the cash check every week inside the [operating cadence](../14-weekly-operating-cadence/). Five minutes. Same spreadsheet.

## Mental model

```
  bank balance
  -------------   =   runway in months
  net burn / month

  net burn = cash out − cash in     (not "expenses on a slide")

  one customer:
     price
     − payment fees
     − direct cost to serve them
     = contribution     (if this is negative, stop scaling)

  default alive:  current growth reaches break-even before cash = 0
  default dead:   it doesn't — cut, charge, or both, now
```

Two clocks: the bank account, and whether a single customer is worth serving.

## Common failure modes

- **Counting the SAFE you haven't closed.** Pipeline is not cash. Runway uses cleared money.
- **Mixing accrual feelings with cash.** "We made $2k this month" because someone said yes, while the account went down, is how teams miss the date.
- **LTV theater.** A beautiful LTV/CAC ratio with invented retention will convince you to spend. You will not get the LTV. You will lose the cash.
- **Cutting too late.** Default dead with four months left feels fine until hiring and rent are committed. The time to change burn is while you still have a choice.

## Watch

- [Tim Brady - How do you calculate burn rate, runway and growth rate?](https://www.youtube.com/watch?v=aDM8CNnCOwk) — Y Combinator. The three numbers, computed from cash, in a few minutes.
- [Kirsty Nathoo - Managing Startup Finances](https://www.youtube.com/watch?v=LBC16jhiwak) — Y Combinator. Bank balance, money in, money out, burn, runway, and default alive — the version a founder can do without a finance team.
- [Save Your Startup During an Economic Downturn](https://www.youtube.com/watch?v=0OVSTWozvfY) — Dalton Caldwell and Michael Seibel, Y Combinator. What to do once you admit you are default dead. Pairs with Paul Graham's essay below.

## Further reading

- [Default Alive or Default Dead](http://paulgraham.com/aord.html) — Paul Graham. The binary, and why founders hide from it.
- [Advice for companies with less than 1 year of runway](https://www.ycombinator.com/library/3Z-advice-for-companies-with-less-than-1-year-of-runway) — Dalton Caldwell, Y Combinator. What to do when the number of months gets small.
- [Trevor Blackwell's growth calculator](http://growth.tlb.org/) — the small tool YC points at for the default-alive sketch. It is a sketch, not a forecast.
