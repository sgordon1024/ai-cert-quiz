# AI Course Matchmaker

A 10-question quiz that recommends AI courses and certifications based on your role, experience level, budget, time, credential preferences, and goals.

**Live quiz:** https://sgordon1024.github.io/ai-cert-quiz/

**Browse all courses:** https://sgordon1024.github.io/ai-cert-quiz/courses.html — a spreadsheet-style table with sortable columns, search, discipline/credential/format filters, a free-only toggle, and column show/hide (persisted per browser).

## How it works

- One `index.html`, zero dependencies — vanilla HTML/CSS/JS.
- 33 courses and certifications (Anthropic, Google, Microsoft/GitHub, AWS, NN/g, IxDF, Designlab, Stanford, and more) each tagged with discipline, difficulty (1–3), estimated cost, estimated effort hours, format, credential type, vendor, and topics.
- Your 10 answers score every course; over-budget options are filtered out, and the top 3 matches are shown with "why this matched" chips, plus a few runners-up.

## Editing the course list

All data lives in the `COURSES` array in `courses-data.js`, shared by the quiz and the table. Add or edit entries there — no build step needed.

## Caveats

- Prices are USD list prices as of **August 2026** — confirm before enrolling.
- Anthropic's proctored certifications currently require Claude Partner Network access; the free Anthropic Academy courses are open to everyone.
- Cost and effort numbers are rough single-value estimates used for matching; follow the course links for current details.
