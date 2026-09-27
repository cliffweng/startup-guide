---
title: "09. Incorporation high-level"
layout: default
nav_order: 10
---

# Incorporation, high level
{: .no_toc }

*~8 min read*

## Why it matters

A company is a separate legal person that can own the product, sign contracts, open a bank account, and issue equity. Until that exists, *you* own the risk and the IP in a messy way, and an investor usually will not wire money. You do not need to become a lawyer. You do need to know the one US pattern venture-backed software startups actually use, when it starts to matter, and what to hand a lawyer instead of inventing.

This page is not legal advice, not a filing guide, and not a comparison of entities outside the United States. If you are not building toward a US venture-style company, stop here and talk to counsel in the place you actually operate. Country-specific incorporation is an explicit non-goal of this playbook.

## Core concepts

- **The common US venture pattern is a Delaware C-corporation.** Investors, option plans, and startup law firms are set up for it. That is a coordination fact, not a moral claim that Delaware is "best" for every student project, consultancy, or non-US team. An LLC can be the right box for a small cash business you do not plan to raise venture for. If you might raise from angels or funds, don't improvise a structure — ask a startup lawyer early, because converting later is a project.
- **Separate means separate.** The company should own the IP, the domain, the bank account, and the contracts. Founders assign IP in. Mixing personal Venmo, personal laptops full of unassigned code, and a "we'll paper it later" handshake is how a small fight becomes a company that can't be financed.
- **Timing is "before other people's money and before serious IP," not "the morning of demo day."** You can talk to users as a person. Once someone is paying real money, a cofounder is writing code you intend to own together, or an investor is interested, the entity and the assignments need to exist. Earlier is paperwork. Later is a mess.
- **Use a standard path.** Clerky-style startup formation services, or a lawyer who does this every week, exist so you get boring, investor-familiar documents. Novelty in your charter is not a feature. You are not trying to be clever about corporate form.
- **Paper you should expect to exist, without memorizing it:** certificate of incorporation, bylaws, founder stock purchase agreements, IP assignment, and a cap table that matches those papers. A lawyer or a standard service produces these. You read them. You do not copy a random gist.
- **Equity paperwork has deadlines that are not optional.** Vesting and any tax election a lawyer tells you about (people will mention an 83(b) in the US) are time-sensitive. The action is: ask counsel the week the stock is granted, not after you Google it at month three. This playbook will not walk you through a filing.
- **Bank account, bookkeeping, and "don't commingle" are the operating minimum.** Open a company account once the entity exists. Pay company costs from it. Keep every receipt. That is the whole accounting system you need until [runway](../08-runway-unit-economics/) gets more complicated — not an ERP.
- **If you are joining rather than founding,** you are not incorporating. You are checking that *they* did: the offer comes from a company, IP you write will be assigned to it, and someone can tell you the state of the equity paperwork. Vague answers are a reason to slow down.

## What to do next

- [ ] Decide which sentence is true: "we may raise venture or issue options in the US" or "this is a small project / non-US and we need local advice." Do not straddle.
- [ ] If it's the US venture path, book a startup lawyer or a standard formation service this month. Bring: founder names, roughly equal or not (see [Equity](../10-equity-cofounder/)), who will be an officer, and that you want a boring Delaware C-corp. Ask them what you should *not* do before papers are signed.
- [ ] List every asset that must move into the company: repos, domains, designs, name, any code written before the company. Nothing stays "on my personal GitHub, trust me."
- [ ] After the entity exists, open the bank account and point [runway tracking](../08-runway-unit-economics/) at it.
- [ ] Write down questions for counsel instead of resolving them in a group chat: founder stock, vesting, IP, and whether anyone is being paid yet.
- [ ] Do not file random forms from a blog post, and do not take entity advice from an investor's tweet. The cost of a lawyer hour is smaller than an unfinanceable cap table.

## Mental model

```
  you, as people                 the company (a separate box)
  ---------------                ----------------------------
  ideas, labor, reputations      owns IP, contracts, cash
                                 issues stock to founders
                                 can hire and raise

  US venture default for this box: Delaware C-corp
  (a convention investors expect — not a global answer)

  your job:  choose the path, use standard docs,
             move IP in, keep cash separate,
             ask a lawyer about deadlines
  not your job:  invent a structure, or become the lawyer
```

Boring corporate form is a feature. The novel thing should be the product.

## Common failure modes

- **A semester of code with no assignment.** The person who leaves still owns what they wrote. Fixing that under time pressure, or after a fight, is miserable.
- **"We'll stay an LLC and convert if we raise."** Sometimes right, often a surprise tax and legal project. Decide with a lawyer *before* the cap table has friends on it.
- **Commingled money.** Personal expenses out of the company, or company revenue into a personal account, blows up both the books and the "separate entity" story.
- **Optimizing tax trivia instead of talking to users.** Entity choice does not find a customer. Spend an afternoon on formation, then go back to the wedge.

## Watch

- [Legal and Accounting Basics for Startups with Kirsty Nathoo and Carolynn Levy (HtSaS 2014: 18)](https://www.youtube.com/watch?v=sd9yLmJ1Jfk) — Y Combinator. Formation, why teams use a Delaware corporation, founder paperwork, vesting, and the basics of not creating a mess. Watch it as a map of topics to ask a lawyer, not as instructions to file alone.

A second video is omitted on purpose: most "how to incorporate" material online is either a product ad or jurisdiction-specific tax advice, and this playbook will not guess URLs.

## Further reading

- The same lecture's slides and transcript are linked from the Y Combinator description of the video above. Use them to build your question list.
- Your lawyer's engagement email. That is the reading that applies to you. This page is not a substitute.
