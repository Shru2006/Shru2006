### Shruti Prabhu — Analytics Manager → AI Data Scientist

I build **explainable machine learning and LLM systems for lending decisions**: models that rank the right customers, say *why* in plain English, and keep working after launch.

Today I lead analytics for home buying at an Australian bank. On GitHub I publish end-to-end projects that I build myself, using **synthetic data only**.

---

**A lending AI series: one problem, end to end**

Each part takes the same question further: *which home loan customers should a lender talk to, and how do you trust the answer?*

| | Project | The question | Result |
|---|---|---|---|
| **1** | [**First Home Buyer Lead Intelligence**](https://github.com/Shru2006/first-home-buyer-lead-intelligence) | Who is about to apply, and why? | Top 10% of ranked customers captures **49% of future applicants** (4.9x lift). SHAP reason codes and Claude-written lender briefs, with age and gender kept out of the model |
| **2** | [**Outreach Uplift Modelling**](https://github.com/Shru2006/outreach-uplift-modelling) | Who applies *because* we called? | Same call budget, **60% more incremental applications** than propensity targeting (108 vs 68 per 1,000 calls) |
| **3** | [**LLM Brief Evals**](https://github.com/Shru2006/llm-brief-evals) | Can we trust the LLM's briefs? | Checks catch 98% of plain faults with zero false alarms. A CI gate blocks risky prompt edits, and it found and verified a prompt-injection fix in part 1 |
| **4** | [**Model Monitoring Pipeline**](https://github.com/Shru2006/model-monitoring-pipeline) | How soon do we know it's going stale? | Drift alert **9 months before** outcome labels confirmed the decay. Retraining on drift kept **36% vs 30%** of applicants in the top 10% |

Every project in the series has the same shape: a one-line question, results first, a model card or responsible-AI section, honest limitations, tests, CI, and one command to reproduce it.

*Earlier work:* [customer churn modelling](https://github.com/Shru2006/Modelling-Customer-Churn) on a public bank dataset, with notes on what I'd do differently now.

---

**What I focus on**

- **Decision modelling.** Gradient boosting, lift and calibration, and choosing a model by business impact, not AUC alone.
- **Causal thinking.** Moving from "who will act" to "whose action changes if we reach out".
- **Explainability and responsible AI.** SHAP reason codes, fairness monitoring, protected attributes kept out of models.
- **LLM applications that stay grounded.** Claude briefs that only reason over computed facts, tested with evals and release gates.
- **Models that hold up after launch.** Drift monitoring and retraining that respect how late outcome labels arrive.

**Tools:** Python · SQL · pandas · scikit-learn · LightGBM · SHAP · causal ML · Claude API · LLM evaluation · Streamlit · FastAPI · React · GitHub Actions · Git

---

**Contact:** [LinkedIn](https://www.linkedin.com/in/shruti-prabhu-32b77477) · Open to conversations about AI and data science in financial services.

<sub>Personal projects on synthetic or public data. Views are my own and not those of my employer. Nothing here is financial advice.</sub>
