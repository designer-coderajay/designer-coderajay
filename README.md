<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=200&section=header&text=Ajay%20Mahale&fontSize=52&fontColor=fff&animation=fadeIn&fontAlignY=36&desc=ML%20Engineer%20·%20Mechanistic%20Interpretability%20·%20LLM%20Evaluation&descAlignY=56&descSize=16"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=15&duration=3500&pause=1200&color=888888&center=true&vCenter=true&width=600&lines=Building+tools+that+reveal+what+actually+happens+inside+LLMs.;37%C3%97+faster+circuit+discovery.+r%3D0.009+confidence-faithfulness+finding.;arXiv+published+%C2%B7+ICML+2026+submission+%C2%B7+PyPI+package.)](https://git.io/typing-svg)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-ajaymahale.online-059669?style=flat-square)](https://ajaymahale.online)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ajay--mh-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ajay-mh)
[![arXiv](https://img.shields.io/badge/arXiv-2603.09988-b31b1b?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2603.09988)
[![PyPI](https://img.shields.io/badge/PyPI-glassbox--mech--interp-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/glassbox-mech-interp/)
[![Email](https://img.shields.io/badge/Email-mahale.ajay01-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mahale.ajay01@gmail.com)
[![X](https://img.shields.io/badge/X-AjayPMahale-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/AjayPMahale)

<br/>

📍 Trier, Germany &nbsp;|&nbsp; 🎓 MSc AI @ Hochschule Trier (May 2026) &nbsp;|&nbsp; 🏢 ML Engineer @ One75 Labs, Berlin

</div>

---

## Who I Am

I build evaluation infrastructure for language models, not dashboards that look good in demos, but pipelines that surface what metrics actually measure versus what they claim to measure.

My core thesis: **confidence scores are lying to you**. I proved it with a near-zero correlation (r = 0.009) between model confidence and internal reasoning faithfulness. That finding came from combining activation patching, causal circuit analysis, and a reproducible benchmarking framework I built from scratch.

Currently writing my MSc thesis on explainable AI for LLMs with causally grounded natural language explanations, while working as an ML Engineer at One75 Labs in Berlin on production LLM evaluation systems.

---

## Highlights That Matter

| What | Result |
|------|--------|
| 🔬 Causal circuit discovery speed | **1.2s on CPU** vs 43.2s baseline, **37× faster** than ACDC (Conmy et al. 2023) |
| 📊 Confidence vs. faithfulness correlation | **r = 0.009**, near-zero. Confidence-based eval signals are unreliable. |
| ✅ LLM explanation quality | **99% quality** via ERASER metrics vs. 60% template baseline |
| 🧪 CI reliability | **12/12 passing** tests. Reproducible, auditable evaluation framework |
| 📦 Open-source reach | Published on **arXiv**, deployed on **Hugging Face**, packaged on **PyPI** with 76 automated tests |
| 📝 Research output | Submitted to **ICML 2026 Workshop** on Mechanistic Interpretability |

---

## Featured Projects

### 🔎 [Glassbox AI — Mechanistic Interpretability Tool](https://github.com/designer-coderajay/Glassbox-AI-2.0-Mechanistic-Interpretability-tool)
`Python` `PyTorch` `TransformerLens` `arXiv` `PyPI` `Hugging Face`

The project that came out of a direct question: *can we tell, causally, which parts of GPT-2 drove a specific prediction?*

- Built a causal circuit discovery engine that answers that question in **1.2s on CPU using 3 forward passes**, 37× faster than the ACDC baseline
- Quantified **r = 0.009** correlation between model confidence and internal reasoning faithfulness, a result with direct implications for EU AI Act compliance
- Automated generation of all **9 required EU AI Act Annex IV sections** from a single function call. Structured JSON output ready for GRC system import
- Published on **[arXiv (2603.09988)](https://arxiv.org/abs/2603.09988)**, deployed a live **Hugging Face demo**, and shipped to **PyPI** with a CLI + 76 automated tests

> Compliance teams can audit any model in under a minute with zero infrastructure setup.

---

### ☁️ [Azure Cloud AI RAG System](https://github.com/designer-coderajay/azure-ai-rag-system)
`Azure OpenAI` `Azure AI Search` `FastAPI` `Streamlit` `GPT-4o-mini`

Document Q&A system with source citations built on Azure's full AI stack.

- Hybrid search combining **vector embeddings + keyword matching** for semantically-aware retrieval
- Document ingestion pipeline with **512-token chunking** and `text-embedding-3-small` embeddings
- **FastAPI** backend + **Streamlit** frontend with streaming responses for real-time answer generation

---

### 🤖 [End-to-End Azure ML Pipeline](https://github.com/designer-coderajay/azure-ml-pipeline)
`Azure Machine Learning` `MLflow` `scikit-learn` `Azure ML SDK v2`

Automated 4-step ML pipeline: data prep → training → evaluation → model registration.

- **74% test accuracy, 80% F1, 87% AUC-ROC** on heart disease prediction (200-record held-out test set)
- Auto-scaling compute with **minimum zero nodes**. Clusters shut down automatically when idle
- **MLflow tracking + Azure ML Model Registry** for full experiment reproducibility and version rollback

---

## Research

**Explainable AI for LLMs: A Causally Grounded Pipeline**
*Submitted to ICML 2026 Workshop on Mechanistic Interpretability*

[![arXiv](https://img.shields.io/badge/arXiv-2603.09988-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.09988)

The core finding: traditional attention-based metrics miss **39% of prediction behavior**. Ground truth established via 100% sufficiency scoring using activation patching and causal circuit analysis. The pipeline converts technical circuit data into structured natural language explanations validated against ERASER metrics.

---

## Stack

**Languages:** Python, SQL

**ML / Research:** PyTorch, TransformerLens, HuggingFace, scikit-learn, NumPy, Pandas

**Cloud / Infra:** Azure Machine Learning, MLflow, Docker, REST APIs, FastAPI, GitHub Actions, CI/CD

**Core Expertise:** Mechanistic Interpretability · Activation Patching · Transformer Architecture · LLM Evaluation Methodology · Causal Analysis · Python Package Development (PyPI) · Prompt Engineering

---

## Certifications

![Azure AI Engineer](https://img.shields.io/badge/Azure_AI_Engineer-AI--102-0078D4?style=flat-square&logo=microsoft-azure)
![Azure AI Fundamentals](https://img.shields.io/badge/Azure_AI_Fundamentals-AI--900-0078D4?style=flat-square&logo=microsoft-azure)
![BlueDot](https://img.shields.io/badge/Technical_AI_Safety-BlueDot_Impact-2D9D4E?style=flat-square)
![Google](https://img.shields.io/badge/AI_Essentials-Google-4285F4?style=flat-square&logo=google)
![UX Research](https://img.shields.io/badge/UX_Research-Google_Professional-4285F4?style=flat-square&logo=google)

---

## Currently

- 📝 **MSc Thesis**. Mechanistic interpretability of LLMs with causally grounded explanations
- 🏢 **ML Engineer @ One75 Labs**. Production LLM evaluation infrastructure, Berlin
- 🎯 **Open to**. ML Engineer / AI Researcher roles in the EU (post-graduation, May 2026)

---

<div align="center">

*I don't just run models. I open them up and see what's actually going on inside.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer"/>

</div>
