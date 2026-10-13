# Lidia Montero García

I’m pursuing a double degree in Computer Science and Business Administration at the University of Alicante. I build machine learning systems and the software around them, with recent work in deep reinforcement learning, LLM-based applications, and AI evaluation.

**[Resume](assets/Lidia_Montero_Resume.pdf) · [LinkedIn](https://linkedin.com/in/lidia-montero-garcia) · [Email](mailto:lidia.montero.garcia02@gmail.com)**

---

### Selected projects

#### [FinSight](https://github.com/lmg136-ua/finsight) — Enterprise Financial Research Agent
`Python` · `LangGraph` · `Hybrid RAG` · `ReAct` · `Streamlit`
* Built a self-correcting agentic RAG system with LangGraph to automate cross-company financial analysis over SEC Form 10-K filings (Alphabet & Microsoft).
* Engineered a cyclic architecture pairing a ReAct analyst agent with deterministic arithmetic tools (CAGR, margins, ratios) and an evidence-verification loop to eliminate LLM hallucinations.
* Implemented hybrid retrieval (Dense Vector HuggingFace BGE + Sparse BM25 with Reciprocal Rank Fusion) and page-level chunking to preserve complex tabular data without context loss.

#### [Dynamic Portfolio Optimization](https://github.com/lmg136-ua/gated-ppo-portfolio-optimization) — Macro-Aware Deep RL with Convex Safety Shields
`Python` · `PyTorch` · `Stable-Baselines3` · `CVXPY / OSQP` · `PPO`
* Engineered a gated PPO agent managing 100 S&P 500 assets across 13 walk-forward folds (2010–2024), conditioning allocation policies on macroeconomic regime shifts (FRED + HMM).
* Integrated an Adaptive Convex Safety Shield (CVXPY/OSQP) to enforce institutional turnover and risk bounds under realistic market frictions.
* Outperformed the S&P 500 Buy & Hold benchmark by +22.6% with a Calmar Ratio of 2.324, leading all evaluated strategies. *Final degree project, graded 10/10.*

#### [Ralue](https://resumin-rose.vercel.app) — AI-Powered Career Intelligence Platform *(in development)*
`TypeScript` · `Node.js` · `Supabase` · `WOPI` · `LLMs`
* Architected a centralized document model (`cv_json`) using RFC-6902 JSON Patches, synchronizing real-time browser document editing (WOPI) with debounced headless Chromium PDF exports.
* Built fault-tolerant LLM pipelines with schema-validated structured outputs and automated repair loops for ATS semantic matching, skill-gap detection, and role-tailored resume generation.

---

### Education

* **University of Alicante** — Double Degree in Computer Science and Business Administration *(expected 2028)*
* **University of North Florida** — Incoming exchange, Business Administration *(Spring 2027)*
* **Tecnológico de Monterrey** — Exchange, Computer Science and Business Administration *(2025)*
* **Lublin University of Technology** — Exchange, Computer Science *(2024)*

---

### Experience

#### Gil y Pineda — Data Science & Business Consultant
*September 2025 – June 2026*
* Built Python and SQL workflows for business data processing and automated recurring tasks, reducing administrative processing time by 40%.
* Developed predictive models and exploratory data analysis (EDA) pipelines in Python (pandas, scikit-learn) for customer segmentation and demand forecasting, translating quantitative findings into strategic recommendations for stakeholders.
