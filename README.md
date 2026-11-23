### Shruti Prabhu — Analytics Manager → AI Data Scientist

I build **explainable machine learning and LLM systems for lending decisions**: models that rank the right customers, say *why* in plain English, and hand frontline teams something they can act on.

Today I lead analytics for home buying at an Australian bank. On GitHub I publish end-to-end projects that I build myself, using **synthetic data only**.

---

**What I focus on**

- **Propensity and decision modelling.** Gradient boosting, calibration, lift, and choosing a model by business impact, not AUC alone.
- **Explainability and responsible AI.** SHAP reason codes, fairness monitoring, and keeping protected attributes out of the model.
- **LLM applications that stay grounded.** Claude-based agents and briefs that only reason over computed facts, with guardrails and fallbacks.
- **Causal thinking.** Moving from "who will act" to "whose action changes if we reach out" (uplift modelling).

---

**Featured projects**

| Project | What it does | Outcome |
|---|---|---|
| [**First Home Buyer Lead Intelligence**](https://github.com/Shru2006/first-home-buyer-lead-intelligence) | LightGBM propensity model + SHAP reason codes + fairness checks + Claude-written lender briefs, in a Streamlit app | Top 10% of ranked customers captures **49% of future applicants** (**4.9x lift**, ROC-AUC 0.85) on a 12,500-customer test set |
| [**Outreach Uplift Modelling**](https://github.com/Shru2006/outreach-uplift-modelling) | Causal targeting: S-, T- and X-learners vs propensity ranking on a randomised outreach experiment, scored with Qini curves and known true uplift | Same call budget, **60% more incremental applications** than propensity targeting (108 vs 68 per 1,000 calls), reaching 94% of the best possible |
| [**LLM Brief Evals**](https://github.com/Shru2006/llm-brief-evals) | Eval harness for the Claude-written lender briefs: golden set with prompt-injection cases, deterministic checks, LLM-as-judge, and a CI release gate. It also measures what the checks themselves catch | Checks catch 98% of plainly worded faults with zero false alarms, and 0% of paraphrased ones (the judge's job). The gate blocks a prompt edit with 28% compliance failures |

*Earlier work:* [customer churn modelling](https://github.com/Shru2006/Modelling-Customer-Churn) on a public bank churn dataset.

*Coming next:* model monitoring with drift alerts.

---

**Tools**

Python · SQL · pandas · scikit-learn · LightGBM · SHAP · Claude API · Streamlit · FastAPI · React · Git

---

**Contact:** [LinkedIn](https://www.linkedin.com/in/shruti-prabhu-32b77477) · Open to conversations about AI and data science in financial services.

<sub>Personal projects on synthetic or public data. Views are my own and not those of my employer. Nothing here is financial advice.</sub>
