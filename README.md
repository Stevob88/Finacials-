# Development Appraisal Tool

A single-file residential development appraisal tool for UK schemes (GBP). Open `index.html` in any browser: no install, no backend, works offline.

- Profit mode and residual land value mode (binary-search solve)
- Monthly cash-flow finance: equity in first, then debt; simple interest; loan repaid from sales as units sell
- SDLT at non-residential rates (0% / 2% / 5%), with manual override
- 5×5 sensitivity table (sale price vs build cost)
- Info explanations on every field and a step-by-step "How this was calculated" section
- Save/load named appraisals (localStorage), JSON export/import, printable one-page summary

**Learning and screening tool only.** It is not a substitute for a professional appraisal or financial advice.
