## Adrian Hartanto

Senior Data Scientist / Machine Learning Engineer with a background in mining engineering. I build production ML systems where optimization, causality, and careful evaluation matter more than leaderboard scores.

Currently focused on: causal inference, constrained optimization (OR-Tools), agentic AI (Google ADK), and retrieval systems.

---

### Showcase repos

| Repo | What it does | Key technique |
|------|-------------|---------------|
| [uplift-promo-optimizer](https://github.com/adrianhtt/uplift-promo-optimizer) | Causal meta-learners (S/T/X/DR) + MILP budget allocation; MILP captures 91% of oracle profit vs treat-all being profit-negative | X-learner, DR-learner, OR-Tools MILP |
| [cp-sat-hvac-optimizer](https://github.com/adrianhtt/cp-sat-hvac-optimizer) | XGBoost tree ensemble encoded as 0-1 ILP inside OR-Tools CP-SAT; solver finds globally-optimal HVAC setpoints in <1 s | CP-SAT, integer programming |
| [transaction-categorizer](https://github.com/adrianhtt/transaction-categorizer) | TabTransformer for financial transaction categorisation; 95% accuracy, 76% on ambiguous merchants where categories share vocabulary | Attention over feature tokens |
| [multimodal-doc-rag](https://github.com/adrianhtt/multimodal-doc-rag) | Dual-encoder RAG (text + image); 84% precision under 50% modality failure vs 64% text-only | MobileNetV2, FAISS, fusion |
| [adk-analyst-crew](https://github.com/adrianhtt/adk-analyst-crew) | Multi-agent sales analysis: data-analyst + critic + report-writer agents with tool use | Google ADK, Gemini 2.5 Flash |
| [kg-fraud-detection](https://github.com/adrianhtt/kg-fraud-detection) | Graph features (PageRank, community, merchant co-occurrence) lift fraud AUPRC from 0.47 to 1.00 | NetworkX, LightGBM |
| [rul-uncertainty](https://github.com/adrianhtt/rul-uncertainty) | Calibrated quantile regression for HVAC unit remaining-useful-life with grouped cross-validation | LightGBM, grouped CV |

### Templates

| Repo | Purpose |
|------|---------|
| [cookiecutter-fastapi-ml](https://github.com/adrianhtt/cookiecutter-fastapi-ml) | Production FastAPI + ML service: async endpoints, Docker/Compose, Prometheus, Sentry |
| [cookiecutter-go-ml](https://github.com/adrianhtt/cookiecutter-go-ml) | Go REST API + gRPC template with PostgreSQL, Redis, Docker, ML inference endpoint |

---

All repos: clean-room implementations on synthetic data, MIT licensed, tested end-to-end.
