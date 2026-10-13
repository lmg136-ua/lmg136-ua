# Lidia Montero García

**Computer Science × AI Engineering × Software Systems**  
*Double Degree in Computer Science and Business Administration @ University of Alicante*

**[Resume](assets/Lidia_Montero_Resume.pdf) · [LinkedIn](https://linkedin.com/in/lidia-montero-garcia) · [Email](mailto:lidia.montero.garcia02@gmail.com)**

Building machine learning systems and production software, with recent work in deep reinforcement learning, agentic AI workflows, and full-stack platforms.

---

## Featured Projects

### [FinSight](https://github.com/lmg136-ua/finsight) — Enterprise Financial Research Agent
`Python` · `LangGraph` · `Hybrid RAG` · `ReAct` · `ChromaDB` · `Streamlit`

*Autonomous research agent that investigates and compares SEC 10-K filings across public companies, grounding comparative financial queries in verified citations.*

* **Cyclic Agentic Workflow:** Orchestrated a multi-agent graph with LangGraph (Query Planner, ReAct Analyst, Evidence Verifier) that iteratively refines queries and audits draft answers against raw filing text.
* **Deterministic Math Engine:** Decoupled financial calculations (CAGR, margin variance, financial ratios) into deterministic Python tools, reducing unsupported claims through strict evidence verification.
* **Hybrid Page-Level Retrieval:** Combined dense vector embeddings (`all-MiniLM-L6-v2`) with sparse keyword search (`rank_bm25`) and balanced multi-entity reranking, using page-level chunking to preserve complex financial tables intact.

---

### [Dynamic Portfolio Optimization](https://github.com/lmg136-ua/gated-ppo-portfolio-optimization) — Macro-Aware Deep RL with Convex Safety Shields
`Python` · `PyTorch` · `Stable-Baselines3` · `CVXPY / OSQP` · `Time Series`

*Institutional-grade reinforcement learning framework for large-scale portfolio management ($N = 100$ assets) under realistic market frictions.*

* **Macro Regime Conditioning:** Trained a gated PPO agent across 13 walk-forward folds (2010–2024), adapting asset allocation decisions to macroeconomic shifts identified via FRED indicators and Hidden Markov Models.
* **Adaptive Convex Safety Shield:** Enforced turnover caps and quadratic risk constraints at inference using CVXPY and OSQP solvers, ensuring strict compliance with institutional execution bounds.
* **Quantitative Performance:** Achieved a 2.324 Calmar Ratio across 13 walk-forward evaluation periods, a 22.6% relative improvement over the S&P 500 benchmark, while enforcing portfolio risk and turnover constraints. *(Final Degree Project, Graded 10/10)*

---

### [Ralue](https://resumin-rose.vercel.app) — AI-Powered Career Intelligence Platform *(in development)*
`TypeScript` · `Node.js` · `Supabase` · `WOPI` · `Playwright` · `LLMs`

*Full-stack career intelligence platform unifying master profiles and role-tailored resumes with collaborative browser document editing and schema-validated AI workflows.*

* **State Architecture & PDF Pipeline:** Designed a single-source-of-truth document model (`cv_json`) using RFC-6902 JSON Patches, synchronizing browser-based document editing (WOPI) with debounced headless Chromium (Playwright) A4 PDF exports.
* **Fault-Tolerant Agent Pipelines:** Implemented schema-validated LLM operations with automated repair loops for ATS semantic matching, skill-gap detection, and contextual resume generation.
* **Concurrency & Persistence:** Built robust versioned document persistence and concurrency-safe save workflows on Supabase and PostgreSQL.

---

## Professional Experience

### Gil y Pineda — Data Science & Business Consultant
*September 2025 – June 2026 · Alicante, Spain*
* Built Python and SQL workflows for automated business data collection, cleaning, and structuring, reducing administrative processing time by 40%.
* Developed predictive models and exploratory data analysis (EDA) pipelines in Python (pandas, scikit-learn) for customer segmentation and demand forecasting, translating quantitative findings into strategic recommendations for stakeholders.
* Communicated technical insights and data-driven recommendations clearly to cross-functional teams and business users.

---

## Education

* **University of Alicante** — Double Degree in Computer Science and Business Administration *(Expected 2028)*
* **University of North Florida** — Incoming Exchange, Business Administration *(Jacksonville, FL, USA · Spring 2027)*
* **Tecnológico de Monterrey** — International Exchange, Computer Science & Business Administration *(Monterrey, Mexico · 2025)*
* **Lublin University of Technology** — International Exchange, Computer Science *(Lublin, Poland · 2024)*
