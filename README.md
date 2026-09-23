# Hi, I'm Nick (Zixi Lian)

I build small, complete systems end to end — data pipelines, automation, and single-file web apps
that run for months with nothing to maintain. Most of what's here started as a tool I needed
myself; the public repos are the ones that turned out to be worth showing.

**Portfolio:** [Nick-Lian-Portfolio.pdf](./Nick-Lian-Portfolio.pdf) · **Email:** [nicklian0315@gmail.com](mailto:nicklian0315@gmail.com)

A few things that show up in everything I ship:

- **Zero-cost, zero-ops by default** — public data, static hosting, standard libraries, and a
  scheduled script instead of a server.
- **Guards for the failures that actually happened** — every pipeline here carries a fix with the
  incident that caused it written next to it.
- **Measured, not assumed** — thresholds come from data, hypotheses get tested against the full
  sample, and a negative result is recorded rather than deleted.

## Projects

| | What it is | Built with |
|---|---|---|
| [**Scholar Outflow Lab**](https://github.com/NickkkLian/Scholar-Outflow-Lab) · [live](https://nickkklian.github.io/Scholar-Outflow-Lab/) | Where researchers from 13 countries ended up — every rate shown with its sample size. | Python stdlib, OpenAlex (CC0), one static HTML file, launchd |
| [**Bill Bench**](https://github.com/NickkkLian/bill-categoriser) · [demo](https://nickkklian.github.io/bill-categoriser/?demo=1) | Clean, categorise and reconcile a year of bills in the browser — every row stays traceable. | Python stdlib, seeded synthetic data, GitHub Actions on Windows/macOS/Linux |
| [**Callback Desk**](https://github.com/NickkkLian/missed-call-booking) · [simulator](https://nickkklian.github.io/missed-call-booking/) | Turn missed calls into bookings — staff approve every message and every calendar write. | n8n JSON, Node stdlib simulator, no external services |
| [**CallDelta**](https://github.com/NickkkLian/Earnings-Call-Sentiment-Analyser) · [dashboard](https://nickkklian.github.io/Earnings-Call-Sentiment-Analyser/) | Call tone vs. analyst pushback — not a trading signal. | Python, LLM-scored transcripts, residual-return target |
| [**ApplyLedger**](https://github.com/NickkkLian/Job-Tracker) · [demo](https://nickkklian.github.io/Job-Tracker/?demo=1&tab=tracker) | A job-application tracker for people applying in several countries at once. | React 18 in one HTML file, GitHub Contents API as the backend |
| [**Clipbind**](https://github.com/NickkkLian/content-organizer) · [demo](https://nickkklian.github.io/content-organizer/?demo=1) | What you saved on Xiaohongshu and Bilibili, bound into one piece you can read. | Vanilla JS, IndexedDB, private-repo sync with tombstone merge, Claude structured outputs |
| [**Vacancy Signal**](https://github.com/NickkkLian/Ghost-Job-Detection-And-Trading-Signal) · [results](https://nickkklian.github.io/Ghost-Job-Detection-And-Trading-Signal/) | Ghost job postings as an equity signal — the course report's figures, not recomputed here: the data is licensed. (UBC Sauder, team project) | Python, scikit-learn, XGBoost |
| [**Letterkeep**](https://github.com/NickkkLian/Prof-Reference-System) · [tour](https://nickkklian.github.io/Prof-Reference-System/) | Students check whether they qualify for a reference letter before they ask — the roster, the grades and the files never leave the professor's own machine. | Flask, SQLite |
| [**Query Mirror**](https://github.com/NickkkLian/SQL-Viz-for-Edu) · [demo](https://nickkklian.github.io/SQL-Viz-for-Edu/) | Every click becomes the SQL behind it — practice is graded on results, not wording. | Vanilla JS, sql.js (SQLite in WebAssembly) vendored in the repo, no build step or server |
| [**Headersort**](https://github.com/NickkkLian/Mail-Sorter) · [demo](https://nickkklian.github.io/Mail-Sorter/?demo=1) | Gmail triage that reads only sender and subject — and only adds labels. | GitHub Actions cron, IMAP + app password, Claude Haiku, two JSON files as the database |

## How I work

- Python and JavaScript, mostly without frameworks; SQL; the GitHub API as a free database more
  often than I'd admit.
- Comfortable driving Claude end to end — prompts with structured outputs, vision, and agents that
  do real work under documented, human-approved rules.
- English and Chinese, both native-level working languages; everything I publish is bilingual or
  English-first.

Based in Canada, working with North American hours.
