# Yogesh Kuchimanchi

**Python | SQL | Data pipelines | ML evaluation**

I'm an M.S. Data Science candidate at Rochester Institute of Technology, with expected graduation in December 2026. I'm looking for entry-level data science and ML engineering roles. My projects focus on making data pipelines and model results easy to run, inspect, and explain.

[Portfolio](https://yogeshkuchimanchi.com/) | [LinkedIn](https://www.linkedin.com/in/yogeshkuchimanchi/) | [Email](mailto:kuchimanchiyogesh@gmail.com)

## Start with these three

### [NYC 311 Service Monitor](https://github.com/Zinga18018/nyc-311-service-monitor)
**Python | SQL/SQLite | Streamlit | Data engineering**

A resumable pipeline that retains source versions and separates request demand, observed open status, and recorded closure time. Start with the [workflow](https://github.com/Zinga18018/nyc-311-service-monitor/blob/main/WORKFLOW.md) and [metric definitions](https://github.com/Zinga18018/nyc-311-service-monitor/blob/main/docs/METRICS.md). The recovery demonstration uses synthetic fixtures, not citywide service-performance results.

### [Product Analytics Experimentation Lab](https://github.com/Zinga18018/product-analytics-experimentation-lab)
**Python | SQL/SQLite | Statistical testing | Streamlit**

A reproducible A/B-test readout with complete follow-up windows, confidence intervals, and conversion, retention, revenue, and assignment-balance checks. The [example report](https://github.com/Zinga18018/product-analytics-experimentation-lab/blob/main/outputs/analysis_report.md) shows why a conversion gain can still lead to a hold decision. All data and results are synthetic, not measured business lift.

### [DriftLab: Model Monitoring Simulator](https://github.com/Zinga18018/driftlab-model-monitoring-simulator)
**NumPy | Model evaluation | Distribution diagnostics | Streamlit**

Compare independent training, reference, and current windows to distinguish distribution change from predictive degradation. Inspect the [repeated-trial benchmark](https://github.com/Zinga18018/driftlab-model-monitoring-simulator/blob/main/outputs/MONITORING_BENCHMARK.md) and [10,000-seed no-drift follow-up](https://github.com/Zinga18018/driftlab-model-monitoring-simulator/blob/main/outputs/no_drift_10000/REPORT.md). These are seeded synthetic experiments, not a production-monitoring guarantee.

## Search, APIs, and research

- **[Product Catalog Search](https://github.com/Zinga18018/product-catalog-search):** compare TF-IDF and BM25 with term-level score explanations, filters, and [reproducible query-level evaluation](https://github.com/Zinga18018/product-catalog-search/blob/main/results/evaluation.json). Runs locally with Python and no third-party runtime dependencies. The 54-product catalog and relevance judgments are synthetic; no embeddings are implemented.
- **[Retrieval Evaluation API](https://github.com/Zinga18018/rag-evaluation-deployment-api):** a FastAPI lexical retrieval and extractive-answer baseline with explicit abstention and traceable citations. The [evaluation report](https://github.com/Zinga18018/rag-evaluation-deployment-api/blob/main/outputs/EVALUATION_REPORT.md) separates retrieval success from answer correctness and includes false answers. Development labels await human review; this is not an LLM service.
- **[Women's Safety Discourse Dashboard](https://github.com/Zinga18018/womens-safety-discourse-dashboard):** explore aggregate platform and case coverage from academic research, without publishing raw posts in the dashboard. [Research context](https://yogeshkuchimanchi.com/research/women-safety/). Corpus coverage is separate from model-label accuracy or representative public opinion.

## More projects

[GWAS Evidence Explorer](https://github.com/Zinga18018/cardiometabolic-gwas-evidence-explorer) integrates public genetics evidence without claiming causal-gene discovery. [CoreGene Bayes Benchmark](https://github.com/Zinga18018/coregene-bayes-benchmark) studies uncertainty in a synthetic four-gene model. [Prompt Rewriter](https://github.com/Zinga18018/prompt-rewriter) is an alpha Windows text-rewriting tool. [Backstory](https://github.com/Zinga18018/backstory) is a local-first Chrome extension for recording project evidence and practicing interview explanations.

## Research and work

- Graduate research project at RIT: Python/Pandas analysis of 351,501 Reddit and YouTube comments across 16 women-safety cases. The project includes statistical comparisons and a fixed 3,000-row validation sample for the stance model. A co-authored paper was accepted at ASONAM 2026; the site separates the submitted-paper results from later audits.
- GCCIS Technical Assistant at RIT: support 200+ Windows and Linux lab systems and maintain Excel/VBA reports.
- Research Assistant at RIT, December 2024–April 2025: refactored Pandas/NumPy scripts and validated PostgreSQL and Excel data for weekly reporting.

## Tools I use

Python and SQL for data work; PyTorch, scikit-learn, and Hugging Face Transformers for modeling; NumPy, Pandas, and SciPy for analysis; FastAPI and Streamlit for sharing results. Tests, data provenance, calibration, and clear metric definitions are part of the work.

I approach an ML project the way I build a PC: understand what each component does, check how the parts fit, and test the whole system.
