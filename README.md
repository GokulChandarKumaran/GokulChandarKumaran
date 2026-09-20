# Gokul Chandar Kumaran

MS Data Analytics Engineering at Northeastern University, Boston — December 2026.
Nine months of healthcare analytics through a co-op, and prior data engineering
in logistics.

I build the data layer and then hold it to account. The habit that shows up in
most of these repos: reconcile against the publisher's own figures before making
a claim of my own, then say where the finding stops holding.

## Selected work

| Project | What it establishes |
|---|---|
| [staffing-shortfall-warehouse](https://github.com/GokulChandarKumaran/staffing-shortfall-warehouse) | Star-schema warehouse over 2,625,134 daily CMS nurse-staffing records. Rebuilt the quarterly average CMS publishes from the daily payroll source and reconciled to it at r = 0.999996 first. 36.5% of facility-days fall below the federal minimum; weekends fail at 61.4% against 26.6% on weekdays. |
| [claim-check](https://github.com/GokulChandarKumaran/claim-check) | An agent that fact-checks claims against a 485M-record warehouse without writing SQL — the model picks from a closed catalog, so every identifier reaching the query is a validated key. Ablation over a 20-claim gold set: zero confidently-wrong answers at 1.00 abstention recall. |
| [clinical-trial-rag](https://github.com/GokulChandarKumaran/clinical-trial-rag) | Retrieval-augmented service over 114,900 oncology trials. 13.2 ms retrieval, 0.867 Precision@5, SSE streaming, and a deterministic guardrail that produced zero fabricated citations across the evaluation set. |
| [claims-denial-recovery](https://github.com/GokulChandarKumaran/claims-denial-recovery) | 485,167,265 commercial claims. 47.0% of denials are process failures against 4.6% for medical necessity — which moves the business case from appeals to prevention. Eight BA documents and a runnable ROI model. |
| [trial-site-selection](https://github.com/GokulChandarKumaran/trial-site-selection) | Competitive density raises accrual-failure risk 31% for single-site trials (z = 4.49) and not at all at three or more sites — visible only after narrowing the outcome to accrual-specific failure. |
| [supply-chain-risk](https://github.com/GokulChandarKumaran/supply-chain-risk) | Recursive-CTE traversal of an npm dependency graph: 52.8% of 1,985 reachable packages have a single maintainer. |

Each repo has a runnable script that reproduces its numbers; most carry a test
suite, and several ship a FastAPI service and a React front end.

## Tools

`SQL` `Python` `DuckDB` `Apache Spark` `Airflow` `AWS` `FastAPI` `React` `Docker` `Tableau` `Power BI`

## Elsewhere

- LinkedIn — https://www.linkedin.com/in/gokul-chandar-kumaran-b171211a1
- gokulchandarkumaran@gmail.com

Open to Data Analyst, Business Analyst and AI Engineer roles in Boston or
remote, from December 2026.
