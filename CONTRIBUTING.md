# Contributing

Thanks for helping improve the playbook. A few ground rules:

- **Scope**: one topic per file under `topics/`. Keep each topic readable in ~10 minutes.
- **Template**: follow the structure already used in existing topic files (Why it matters, Core concepts, What to do next, Mental model, Common failure modes, Watch, Further reading). No interview-question section. No frequency badges.
- **Links must be real**: only link to YouTube videos and articles you have personally verified exist (open the URL, confirm the title/content). Never guess a video ID or URL. Prefer Y Combinator Startup School, the Stanford/YC "How to Start a Startup" lectures, and other reputable educational sources — but any verified source is fine. If you are unsure of an exact URL, omit the video rather than invent one.
- **No invented product direction**: this is a practical playbook for first-time technical founders who are founding or joining early. It is not an interview guide (that sibling, the Founders Interview Guide, is a separate project). It is not deep legal advice, not a full accounting system, not country-specific incorporation instructions, and not a quiz, auth, or progress-tracking site. If you want to propose a new topic or reorganize the curriculum, open an issue first.
- **Keep topics tight**: prefer a checklist the reader can do this week over encyclopedic coverage. Don't invent extra scope (no legal templates, no cap-table software, no login).
- **Local preview**:
  ```bash
  bundle install
  bundle exec jekyll serve
  ```
  Then open `http://localhost:4000`.
- **Pull requests**: keep them focused (one topic or fix per PR) and describe what changed and why.
