# Startup Guide

A practical playbook for first-time technical founders — founding a company, or joining one while it is still early. Written for Penn CS and engineering builders. Not an interview guide.

**Live site:** https://cliffweng.github.io/startup-guide/

Also published at https://cliffweng.com/startup-guide/

The sibling **Founders Interview Guide** is a separate project. This repo does not contain interview questions, frequency badges, or prep tracks. Don't merge the two.

## Roadmap

14 topics, one file each under [`topics/`](topics/), ordered from "who is this for" through "how do we run the week":

1. Problem & customer (talk to users)
2. Idea → wedge (why this, why now)
3. MVP scope (cut ruthlessly)
4. Build vs buy & shipping cadence
5. Distribution & early GTM
6. Pricing & packaging intro
7. Metrics that matter (activation, retention, revenue)
8. Runway & simple unit economics
9. Incorporation high-level (US Delaware C-corp note only)
10. Equity & cofounder agreements (concepts)
11. Hiring first eng / first non-eng
12. Fundraising map (friends/family → angels → seed)
13. Pitch narrative structure
14. Weekly operating cadence (goals, reviews)

## How to use this guide

Each topic page is designed to be read in **~10 minutes** and follows the same structure: why it matters, core concepts, a what-to-do-next checklist, a mental model, common failure modes, and a short list of verified YouTube videos. Read them in order, or jump straight to the decision in front of you. No backend, no auth, no sign-up — just read the pages and do the next thing.

## How to contribute

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: one topic per file, keep it under ~10 minutes to read, and only link to sources (especially YouTube videos) you've personally verified exist. Open an issue before proposing new topics or restructuring the curriculum.

## Decisions

These are the product locks this playbook was built against — echoed here so future contributors don't accidentally relitigate them:

- **Audience**: Penn CS/engineering builders (founding, or joining as an early teammate). Not a general entrepreneurship survey and not interview prep.
- **Time-boxed**: every topic is readable in 10 minutes or less. Depth is sacrificed for "what do I do next"; "further reading" links are where depth lives.
- **Practical, not prep**: checklists and failure modes. No interview questions. No "frequent / occasional / background" badges.
- **Real links only**: every YouTube link is verified to exist before being added. No invented URLs, ever.
- **Non-goals**: deep legal advice, full accounting, country-specific incorporation, quizzes, auth, progress tracking.
- **Static site, GitHub Pages, Just the Docs**: no backend, no auth, no quizzes. Cheap to host, cheap to maintain, easy to contribute to via plain Markdown + front matter.

## Enabling GitHub Pages

Just the Docs is configured via `_config.yml` (remote theme). After this lands on `main`:

1. Repo **Settings → Pages**.
2. **Build and deployment → Source**: **Deploy from a branch**.
3. Branch: `main` / folder: `/ (root)`.
4. Save. Site publishes to https://cliffweng.github.io/startup-guide/

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## License

[MIT](LICENSE)
