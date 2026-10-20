<h1 align="center">Ignacio Mendoza Rojas</h1>

<p align="center">
  <b>Corporate Finance · Financial Risk Management · Quantitative Modelling</b><br/>
  Barcelona, Spain
</p>

<p align="center">
  <a href="https://ignaciomendozarojas.github.io"><img src="https://img.shields.io/badge/Findings-ignaciomendozarojas.github.io-1f63b8" alt="Findings page"/></a>
  <a href="https://www.linkedin.com/in/ignaciomendozarojas"><img src="https://img.shields.io/badge/LinkedIn-ignaciomendozarojas-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

---

I'm a finance professional with **5 years of experience in banking and corporate finance**,
working on investment evaluation, financial planning, derivatives and credit risk.

As **Financial Risk & Modelling Analyst at Banco Ripley** (Chile), I build the models behind
counterparty and liquidity risk: stochastic **Potential Future Exposure** for derivatives,
**deposit balance decay**, **CVA/DVA** sensitivities, automated **ILAAP** projections under
Basel III, and the Python pipelines and Power BI dashboards that feed and monitor them.
In 2023 I spent a period at **Red Interclínica**, where I consolidated and automated financial
planning for four clinics, monitored €11M of capex and assessed projects on the investment committee.

This GitHub is where I rebuild that kind of work **from public theory and real data**
(public filings, regulator files, or my own anonymised records), as clean, tested,
documented code. No employer code, data or parameters.

## 🔭 What I work on

| Area | Topics |
|---|---|
| **Counterparty credit risk** | Monte Carlo exposure (EE, PFE), netting and collateral, derivatives valuation, CVA / DVA |
| **Liquidity risk** | Deposit decay, LCR / NSFR projections, cash-flow stress testing, haircuts under stress |
| **Forecasting** | ARIMA and time-series models for credit line usage and intraday liquidity |
| **Corporate finance** | Equity valuation, financial planning, P&L and cash-flow models, CAPEX evaluation (NPV, IRR, payback), unit economics |
| **Data & automation** | Python ETL pipelines, web scraping without APIs, SQL, Power BI |

## 📂 Projects

| Project | What it does | Stack |
|---|---|---|
| [**equity-research-engine**](https://github.com/IgnacioMendozaRojas/equity-research-engine) | Reusable valuation engine that turns public filings into a CFA-style research report: segment volume × price model, royalties and state take, DCF + residual income, Monte Carlo and a backtest. First case is SQM, revisiting my CFA Research Challenge company: an October 2026 report plus the October 2020 valuation held against what happened. | Python · NumPy · pandas · SEC XBRL · pytest · CI |
| [**counterparty-credit-risk**](https://github.com/IgnacioMendozaRojas/counterparty-credit-risk) | Monte Carlo engine for derivatives exposure: Hull-White rates and FX simulation, netting and collateral (CSA), EE / PFE / Basel EEPE, and CVA / DVA. Validated against closed-form results. | Python · NumPy · pytest · CI |
| [**restaurant-analytics**](https://github.com/IgnacioMendozaRojas/restaurant-analytics) | Menu engineering, yield-adjusted ingredient usage and break-even on real operating data from a restaurant I ran in 2023. Found a 17% vs 36% gap between recipe and actual food cost. | Python · pandas · matplotlib |
| [**chile-mutual-funds-analytics**](https://github.com/IgnacioMendozaRojas/chile-mutual-funds-analytics) | What Chilean mutual funds hold, monthly 2019-2026, from 3.3 million CMF portfolio records: the 2021-22 shift from bank deposits to Central Bank paper, funds as a concentrated source of bank funding, duration through the rate cycle, and how little FX exposure is hedged. | Python · pandas · CMF data · pytest · CI |
| [**cmf-ffmm-etl**](https://github.com/IgnacioMendozaRojas/cmf-ffmm-etl) | Monthly pipeline that scrapes the holdings of every Chilean mutual fund from the regulator's portal (no API), runs 7 quality gates and loads them idempotently. History since 2008. | Python · pandas · SQLAlchemy · pytest · CI |
| [**db-migration-validator**](https://github.com/IgnacioMendozaRojas/db-migration-validator) | Proves a database migration lost nothing: compares structure, row counts, order-independent content fingerprints and grants between source and target, across Oracle, SQL Server, PostgreSQL and MySQL. Fails the pipeline on any critical finding. | Python · SQLAlchemy · PostgreSQL · pytest · CI |

**Currently building:** a second company in the equity research engine, valued from CMF filings only.

## 🛠️ Toolkit

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel%20·%20VBA%20·%20Power%20Query-217346?logo=microsoftexcel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## 💼 Experience

| Period | Role |
|---|---|
| 2023 – present | **Financial Risk & Modelling Analyst**, Banco Ripley (Chile) |
| 2023 | **Strategy & Investment Analyst**, Red Interclínica (Chile) |
| 2021 – 2023 | **Financial Risk Analyst**, Banco Ripley (Chile) |

## 🎓 Education

- **MSc in Business Research**, Universitat de Barcelona (2025 – 2027). Thesis: *Artificial
  Intelligence Use and Labour Cost Stickiness: Evidence from Spanish Firms* (8.5/10).
- **MSc in Finance**, Universidad Adolfo Ibáñez (2020 – 2021), CFA Institute affiliated.
- **BSc in Business Administration and Economics**, Universidad Adolfo Ibáñez (2016 – 2019).
- 🏆 **Winner, CFA Institute Research Challenge, South America Regional Final** (2020 – 2021).
- **Languages:** Spanish (native), English (TOEFL iBT, B2).

## 📫 Get in touch

Happy to talk about risk models, data pipelines or any of these projects.
The best way to reach me is [LinkedIn](https://www.linkedin.com/in/ignaciomendozarojas).
