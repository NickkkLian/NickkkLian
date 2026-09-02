# Hi, I'm Nick (Zixi Lian)

I build small, complete systems end to end — data pipelines, automation, and single-file web apps
that run for months with nothing to maintain. Most of what's here started as a tool I needed
myself; the public repos are the ones that turned out to be worth showing.

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
| [**Scholar Outflow Lab**](https://github.com/NickkkLian/Scholar-Outflow-Lab) · [live](https://nickkklian.github.io/Scholar-Outflow-Lab/) | Where researchers who start in one country end up — 13 origin countries, 1.4 M sampled authors, stratified by length of stay, with a cross-origin comparison that differs 3–4× for the same destination | Python stdlib, OpenAlex (CC0), one static HTML file, launchd |
| [**Earnings Call Sentiment Analyser**](https://github.com/NickkkLian/Earnings-Call-Sentiment-Analyser) | Separates management framing from analyst pushback in earnings calls and tests whether the gap predicts post-call returns *after* controlling for the EPS surprise | Python, LLM-scored transcripts, residual-return target |
| [**Job Application Command Center**](https://github.com/NickkkLian/Job-Tracker) · [demo](https://nickkklian.github.io/Job-Tracker/?demo=1&tab=tracker) | A multi-region job-search tracker with prompt generators, batch resume tailoring, and a CEC hours ledger that applies IRCC's 30 h/week cap across all jobs combined | React 18 in one HTML file, GitHub Contents API as the backend |
| [**Content Organizer**](https://github.com/NickkkLian/content-organizer) · [demo](https://nickkklian.github.io/content-organizer/?demo=1) | One library for Xiaohongshu and Bilibili saves, with AI consolidation into sectioned write-ups, expiring-image archiving, and a local video-transcription service | Vanilla JS, IndexedDB, private-repo sync with tombstone merge, Claude structured outputs |
| [**Ghost Job Detection**](https://github.com/NickkkLian/Ghost-Job-Detection-And-Trading-Signal) | A labour-market mispricing signal from job postings kept open with no intent to hire — XGBoost + SHAP, GMM regimes, walk-forward backtest (UBC Sauder, team project) | Python, scikit-learn, XGBoost |
| [**Prof Reference System**](https://github.com/NickkkLian/Prof-Reference-System) | Automates eligibility screening for professor reference letters: student portal, roster import, transcript parsing, email notification | Flask, SQLite |
| [**SQL-Viz-for-Edu**](https://github.com/NickkkLian/SQL-Viz-for-Edu) · [demo](https://nickkklian.github.io/SQL-Viz-for-Edu/) | Explore real datasets with plain-English controls while the exact Oracle SQL updates live — built for students who learn SQL better by seeing it | One HTML file, no dependencies |
| [**Mail Sorter**](https://github.com/NickkkLian/Mail-Sorter) · [demo](https://nickkklian.github.io/Mail-Sorter/?demo=1) | A Gmail triage board with no server: a scheduled Action labels new mail from sender and subject only — never the body — and only ever adds a label, never deletes, archives or marks as read | GitHub Actions cron, IMAP + app password, Claude Haiku, two JSON files as the database |

## How I work

- Python and JavaScript, mostly without frameworks; SQL; the GitHub API as a free database more
  often than I'd admit.
- Comfortable driving Claude end to end — prompts with structured outputs, vision, and agents that
  do real work under documented, human-approved rules.
- English and Chinese, both native-level working languages; everything I publish is bilingual or
  English-first.

Based in Canada, working with North American hours.
