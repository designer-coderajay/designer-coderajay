<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=200&section=header&text=Ajay%20Mahale&fontSize=52&fontColor=fff&animation=fadeIn&fontAlignY=36&desc=AI%20Researcher%20·%20Mechanistic%20Interpretability%20·%20Responsible%20AI&descAlignY=56&descSize=16"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=15&duration=3500&pause=1200&color=888888&center=true&vCenter=true&width=600&lines=Causally+grounded+mechanistic+interpretability.;Post-hoc+causal+attribution+over+agent+trajectories.;Advancing+AI+traceability+and+compliance.;arXiv+published+%C2%B7+2026+submissions+%C2%B7+PyPI+maintainer.)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-ajaymahale.online-059669?style=flat-square)](https://ajaymahale.online)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ajay--mh-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ajay-mh)
[![PyPI](https://img.shields.io/badge/PyPI-glassbox--mech--interp-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/glassbox-mech-interp/)
[![Email](https://img.shields.io/badge/Email-mahale.ajay01-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mahale.ajay01@gmail.com)
[![X](https://img.shields.io/badge/X-AjayPMahale-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/AjayPMahale)

<br/>

📍 Trier, Germany &nbsp;|&nbsp; 🎓 MSc AI @ Hochschule Trier (June 2026)[cite: 3] &nbsp;|&nbsp; 🏢 Machine Learning Researcher[cite: 3]

</div>

---

## Research Focus

I am a Machine Learning Researcher focused on mechanistic interpretability and responsible AI[cite: 3]. My primary research investigates a foundational question: when a language model explains itself, is that explanation causally true[cite: 1]? Through causal intervention methods like activation patching, my work aims to expose the gap between what evaluation metrics measure and what they claim to measure[cite: 1, 3].

Recently, my research has expanded into the rigorous evaluation of multi-agent systems[cite: 3]. I develop formal estimators for causal attribution in agentic decisions, directly addressing the traceability and record-keeping requirements specified by the EU AI Act[cite: 2, 3].

---

## Selected Publications & Preprints

**Causal Attribution for Agentic Decisions: Estimators, Coupling, and a Traceability Specification** (Sep 2026)[cite: 3]
*Preprint under review*[cite: 3]. 
*   **Contribution:** Established that marginal total effect estimators fail to separate causally inert steps from decisive ones in agent trajectories[cite: 2].
*   **Methodology:** Separated the marginal total effect from a common-random-numbers total effect that isolates a step’s own contribution[cite: 2].
*   **Impact:** Derived a 12-requirement traceability specification for high-risk agentic AI systems to bridge the gap in Article 86 explanations under the EU AI Act[cite: 2].

**Explanation Multiplicity: Circuit-Level Interpretability Evidence Does Not Survive Defensible Analytic Variation** (Aug 2026)[cite: 3]
[![arXiv](https://img.shields.io/badge/arXiv-2608.13754-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2608.13754)
*   **Contribution:** Demonstrated that circuit-level interpretability evidence fails to survive defensible analytic variation[cite: 3].
*   **Methodology:** Conducted a pre-registered multiverse analysis over 15,840 specifications on GPT-2 small[cite: 1, 3].
*   **Findings:** The derived EU AI Act Annex IV statement flipped across 73.2% of specification pairs[cite: 1].

**Explainable AI for LLMs: Causally Grounded Mechanistic Interpretability for LLMs with Faithful Natural-Language Explanations** (Feb 2026)[cite: 3]
[![arXiv](https://img.shields.io/badge/arXiv-2603.09988-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.09988)
*   **Contribution:** Proved that model confidence is not a usable proxy for explanation faithfulness[cite: 1]. 
*   **Findings:** Measured a near-zero correlation (r = 0.009) between model confidence and internal reasoning faithfulness across 50 prompts[cite: 1, 3]. Scored an identified circuit 100% sufficient but only 22% comprehensive[cite: 1, 3].

---

## Open-Source Research Infrastructure

### 🔎 [Glassbox AI — Mechanistic Interpretability Toolkit](https://github.com/designer-coderajay/Glassbox-AI-2.0-Mechanistic-Interpretability-tool)
`Python` `PyTorch` `TransformerLens` `arXiv` `PyPI` `Hugging Face`

Published an open-source mechanistic interpretability toolkit to PyPI (v4.5.0), implementing 21 mathematical frameworks[cite: 1, 3].
*   Accelerated causal circuit discovery 15 to 37 times against ACDC baselines on GPT-2 Small[cite: 3].
*   Extended exact edge-level discovery to grouped-query-attention and RMSNorm architectures (Llama-3, Mistral, Phi-3, Gemma)[cite: 3].
*   Automated generation of structured JSON for EU AI Act Annex IV documentation[cite: 1, 3].

### 🧠 [Enterprise Agentic AI Platform](https://github.com/designer-coderajay/enterprise-agentic-ai-platform)
`LangGraph` `Model Context Protocol (MCP)` `Qdrant` `LlamaIndex`

Multi-agent orchestration system developed to evaluate complex automated reasoning architectures[cite: 3].
*   Orchestrates 3 MCP servers (Postgres, document, notification) via LangGraph (0.3)[cite: 3].
*   Integrates hybrid RAG over Qdrant using LlamaIndex[cite: 3].

### 📚 [Thesis-RAG Literature Retrieval](https://github.com/designer-coderajay/thesis-rag)
`Llama 3.2` `FAISS` `RAG`

Privacy-preserving embedding and retrieval system for rigorous, source-grounded academic literature reviews[cite: 3].
*   Indexes approximately 6,000 chunks across 50+ mechanistic interpretability papers[cite: 3].

---

## Technical Expertise

*   **Quantitative Methods:** Pre-registered experimental design, multiverse/specification-curve analysis, nonparametric bootstrap, causal intervention methods, variance decomposition[cite: 3].
*   **Machine Learning Core:** PyTorch, TransformerLens, Hugging Face, scikit-learn, XGBoost, LightGBM, SHAP[cite: 3].
*   **Agentic Frameworks:** LangGraph, Model Context Protocol (MCP), Qdrant, LlamaIndex, FAISS[cite: 3].
*   **Systems & MLOps:** MLflow, Optuna, FastAPI, Docker, GitHub Actions, CI/CD pipelines[cite: 3].

---

## Current Status

*   🎓 **Academic:** Master's thesis completed and graded 1.0 (highest on the German scale)[cite: 3].
*   🎯 **Availability:** Open to PhD positions in Responsible AI / Interpretability, or Applied Scientist / Research Engineer roles in the EU[cite: 1, 3]. Available full-time immediately, no sponsorship required[cite: 3].

---

<div align="center">

*Advancing the transparency, traceability, and alignment of artificial intelligence.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer"/>

</div>
