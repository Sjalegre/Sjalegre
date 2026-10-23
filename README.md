## Sergio Alegre

Economist (National University of Asunción, 2025) and data analyst in Paraguay.
I verify and approve 100+ taxpayer records a day at **DNIT**, the national tax
authority — high-volume data quality control in a regulated body. Before that:
Power BI dashboards for a consultancy, and financial analysis for SMEs.

I build things that check their own work. Each project below publishes a
measurement of how well it did, including when the answer is unflattering.

---

### Projects

**[paraguay-open-data-pipeline](https://github.com/Sjalegre/paraguay-open-data-pipeline)** — integration & data quality
&nbsp;&nbsp;↳ **[Live quality report](https://sjalegre.github.io/paraguay-open-data-pipeline/)**

DuckDB star schema over Paraguayan public data, with 30 quality checks stored
as facts rather than logged. Paraguay's two official district registers don't
join as published — one key is zero-padded, the other isn't, so a direct join
matches *nothing*. All 263 districts reconcile here with no hand-written
exceptions. `82 tests · Python · DuckDB · SQL`

**[costco-fpa-model](https://github.com/Sjalegre/costco-fpa-model)** — financial modelling
&nbsp;&nbsp;↳ **[Live model report](https://sjalegre.github.io/costco-fpa-model/)**

Driver-based three-statement model from SEC XBRL filings, walked forward over
13 years and scored against what actually happened. Beats a naive baseline on
all nine line-and-horizon combinations — and is biased low on profit by 9–14%,
which is published rather than tuned away. Nothing is plugged: the balance
sheet is a real test. `42 tests · Python · SEC EDGAR`

**[paraguay-informality](https://github.com/Sjalegre/paraguay-informality)** — applied statistics & ML
&nbsp;&nbsp;↳ **[Live report](https://sjalegre.github.io/paraguay-informality/)**

Six in ten private-sector employees in Paraguay work without a pension. Ignoring
the survey weights moves that by 4 points; a textbook confidence interval is 40%
too narrow. Firm size explains almost everything else. `16 tests · scikit-learn ·
complex survey design`

**[fx-backtest-spread](https://github.com/Sjalegre/fx-backtest-spread)** — quantitative analysis

Does a trading edge survive what trading costs? No. In-sample Sharpe averages
0.81 across four instruments; out of sample, 0.05. Neither strategy clears a
deflated Sharpe ratio. The negative result is the deliverable. `38 tests ·
walk-forward · multiple-testing correction`

---

### Tools

`SQL` `Python` (pandas, NumPy, scikit-learn) `Power BI` `DuckDB` `Excel` `EViews`

### Contact

[LinkedIn](https://www.linkedin.com/in/sealegref) · sjalegre39@gmail.com · Asunción, Paraguay
