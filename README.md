# Hi, I'm Nick (Zixi Lian)

I build small, complete systems end to end — data pipelines, automation, and small web apps that run for months with
nothing to maintain. Most of what's here started as a tool I needed myself, and eleven of the projects below have a live
page you can open now. Start with [**Query Mirror**](https://nickkklian.github.io/SQL-Viz-for-Edu/?db=movies&tables=film%2Cdirector&q=eyJjIjpbImZpX3RpdGxlIiwiZmlfeWVhciIsImZpX3JhdGluZyIsImRpX25hbWUiLCJjbF9jb250cmliIl0sImYiOltbImZpX3JhdGluZyIsImlzIGF0IGxlYXN0IiwiOCJdXSwicyI6WyJmaV9yYXRpbmciLCJERVNDIl19) (every click becomes the SQL behind it),
[**Scholar Outflow Lab**](https://nickkklian.github.io/Scholar-Outflow-Lab/) (where researchers from 13 countries ended up) or
[**Bill Bench**](https://nickkklian.github.io/bill-categoriser/?demo=1) (clean, categorise and reconcile a year of bills in the browser).

**Portfolio:** [Nick-Lian-Portfolio.pdf](./Nick-Lian-Portfolio.pdf) · **Email:** [nicklian0315@gmail.com](mailto:nicklian0315@gmail.com) · **Website:** [nickkk.com](https://nickkk.com)

## Projects

| | What it is | Built with |
|---|---|---|
| [**Query Mirror**](https://github.com/NickkkLian/SQL-Viz-for-Edu) · [demo](https://nickkklian.github.io/SQL-Viz-for-Edu/?db=movies&tables=film%2Cdirector&q=eyJjIjpbImZpX3RpdGxlIiwiZmlfeWVhciIsImZpX3JhdGluZyIsImRpX25hbWUiLCJjbF9jb250cmliIl0sImYiOltbImZpX3JhdGluZyIsImlzIGF0IGxlYXN0IiwiOCJdXSwicyI6WyJmaV9yYXRpbmciLCJERVNDIl19) | Every click becomes the SQL behind it — practice is graded on results, not wording. | Vanilla JS, sql.js (SQLite in WebAssembly) vendored in the repo, no build step or server |
| [**Scholar Outflow Lab**](https://github.com/NickkkLian/Scholar-Outflow-Lab) · [live](https://nickkklian.github.io/Scholar-Outflow-Lab/) | Where researchers from 13 countries ended up, and how much that depends on the country they came from. | Python stdlib, OpenAlex (CC0), a static page, launchd |
| [**Bill Bench**](https://github.com/NickkkLian/bill-categoriser) · [demo](https://nickkklian.github.io/bill-categoriser/?demo=1) | Clean, categorise and reconcile a year of bills in the browser — every row stays traceable. | Python stdlib for the CLI, a static browser workbench, no account or key |
| [**CallDelta**](https://github.com/NickkkLian/Earnings-Call-Sentiment-Analyser) · [dashboard](https://nickkklian.github.io/Earnings-Call-Sentiment-Analyser/) | How rosy management sounds vs. how sceptical analysts are, scored for each earnings call. | Python, LLM-scored transcripts, residual-return target |
| [**ApplyLedger**](https://github.com/NickkkLian/Job-Tracker) · [demo](https://nickkklian.github.io/Job-Tracker/?demo=1&tab=tracker) | A job-application tracker for people applying in several countries at once. | React 18 compiled ahead of time with esbuild, GitHub Contents API as the backend |
| [**Clipbind**](https://github.com/NickkkLian/content-organizer) · [demo](https://nickkklian.github.io/content-organizer/?demo=1) | What you saved on Xiaohongshu and Bilibili, bound into one piece you can read. | Vanilla JS, IndexedDB, private-repo sync with tombstone merge, Claude structured outputs |
| [**Letterkeep**](https://github.com/NickkkLian/Prof-Reference-System) · [tour](https://nickkklian.github.io/Prof-Reference-System/) | Students check whether they qualify for a reference letter before they ask — the roster, the grades and the files never leave the professor's own machine. | Flask, SQLite |
| [**Headersort**](https://github.com/NickkkLian/Mail-Sorter) · [demo](https://nickkklian.github.io/Mail-Sorter/?demo=1) | Sort mail worth keeping, review outdated mail before cleanup, archive with undo. | GitHub Actions cron, IMAP + app password, Claude Sonnet 5.5 by default, JSON files in a private repo as the database |
| [**Build Check-in**](https://github.com/NickkkLian/build-check-in) · [guide](https://nickkklian.github.io/build-check-in/) | Turn a coding project's history into questions, a cited instructor key and note drafts. | A Claude skill, Python standard library |

## Team projects

| | What it is | Built with |
|---|---|---|
| [**Loopool**](https://github.com/NickkkLian/loopool) · [demo](https://nickkklian.github.io/loopool/) | A fair queue and an AI referee for pool tables, run by one n8n workflow. **Overall Second Place** at the UBC eProjects × n8n LOOP Hackathon 2026 (team of four). | n8n, Claude Haiku 5.5 vision (chosen by testing 6 models on 184 labelled shots), JavaScript |
| [**Vacancy Signal**](https://github.com/NickkkLian/Ghost-Job-Detection-And-Trading-Signal) · [results](https://nickkklian.github.io/Ghost-Job-Detection-And-Trading-Signal/) | Ghost job postings as an equity signal: a score for 2,919 US public firms from 310,821 postings. (UBC Sauder COMM 486I, team of three) | Python, scikit-learn, XGBoost |

**Agent skills:** [nickkk-skills](https://github.com/NickkkLian/nickkk-skills) — 14 skills for Claude Code and OpenAI Codex that turn a spreadsheet, a formula or one sentence into a page you can open, plus checks for an agent's work and guards for a repository.

## How I work

- Python and JavaScript, mostly without frameworks; SQL; the GitHub API as a free database.
- Zero-cost, zero-ops by default: public data, static hosting, standard libraries, and a
  scheduled script instead of a server.
- Building with Claude: structured outputs, vision and agent workflows.
- Chinese (native) and English (fluent).

Based in Canada, working with North American hours.
