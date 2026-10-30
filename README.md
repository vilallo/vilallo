## Hi, I'm Vinícius 👋

**MSc in Data Science and Advanced Analytics @ NOVA IMS, Lisboa.**

I build data science and AI solutions for real business problems, from classic ML (segmentation, forecasting) to LLM applications and RAG. I'm currently working on my master's thesis, **Agent as a Service**, a multi-tenant platform that lets small businesses deploy their own AI customer-service agents.

### 🎓 Master's Project: Agent as a Service

An open-source, multi-tenant AI platform for small business automation. Non-technical SME owners can deploy a personalised customer-service agent grounded in their own data (website, PDFs, FAQs). It runs entirely on open-source models:
- **RAG pipeline:** heading-aware chunking, per-tenant ChromaDB collections and a BGE cross-encoder reranker.
- **Local LLM via Ollama** with a swappable model registry. Qwen3 8B, Llama 3.1, Gemma 3 and Mistral 7B were compared under the same retrieval setup.
- **Evaluation:** an LLM-as-a-Judge pipeline over 227 questions from 5 real businesses. The chosen model (Qwen3 8B) reached **77.5% strict / 93.4% lenient accuracy**, up from a 43.6% strict baseline.
- **Product:** FastAPI backend, React dashboard with per-message model selection, and Streamlit evaluation dashboards.
- **Methodology:** Design Science Research.

`Python` `FastAPI` `Ollama` `Qwen3` `LangChain` `ChromaDB` `RAG` `LLM-as-a-Judge` `React` `Docker`

### 🚀 Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**Fidelidade MySavings Chatbot**](https://github.com/vilallo/Insurance-Savings-Assistance) | RAG chatbot that answers customer questions about Fidelidade's savings and retirement products (e.g. PPR), grounded in official product documentation and current Euribor rates. Supports multiple conversations. | `Azure OpenAI` `Assistants API` `RAG` `Gradio` |
| [**Siemens Sales Forecast**](https://github.com/vilallo/b2b-Sales-Forecasting) | 10-month sales forecasts for 14 Siemens business units using macroeconomic indicators, with one tuned model per unit. Best model: XGBoost, with a mean validation RMSE of ~€690K vs ~€970K for SVR. Follows CRISP-DM. | `XGBoost` `LightGBM` `SVR` `Optuna` `scikit-learn` |
| [**Hotel Guest Segmentation**](https://github.com/vilallo/Hotel-Guest-Segmentation) | Behaviour-based segmentation of ~111K hotel customer records into 4 actionable segments, each with its own marketing plan. Uses K-Means, with the number of clusters validated by hierarchical clustering. Follows CRISP-DM. | `scikit-learn` `K-Means` `Hierarchical Clustering` `pandas` `SciPy` |
| [**Food Delivery Customer Segmentation**](https://github.com/vilallo/food-delivery-customer-segmentation) | Segmentation of ~31.7K food delivery customers into 4 behavioural segments, combining a preferences perspective and a value perspective. One-time buyers (22%) are analysed separately. Best model: Ward hierarchical clustering, chosen over K-Means and Mean-Shift. Follows CRISP-DM. | `scikit-learn` `Hierarchical Clustering` `K-Means` `Mean-Shift` `t-SNE` |

### 🛠️ Tech Stack

**Languages:** Python · SQL · JavaScript

**ML / AI:** scikit-learn · XGBoost · LightGBM · Optuna

**LLMs & GenAI:** Ollama · LangChain · ChromaDB · Azure OpenAI · RAG · LLM-as-a-Judge

**Data:** pandas · NumPy · Matplotlib · Seaborn

**Tools:** Jupyter · FastAPI · Gradio · Streamlit · React · Docker · Git

### 🎓 Education

**MSc Data Science and Advanced Analytics** — NOVA IMS (2024–2026)
Thesis: *Agent as a Service — Intelligent Multi-Tenant AI Platform for Small Business Automation*

**BSc Information Systems and Technologies** — NOVA IMS (2021–2024)

### 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vilallo/vilallo/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vilallo/vilallo/output/github-snake.svg" />
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/vilallo/vilallo/output/github-snake.svg" />
</picture>

### 📫 Let's connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vin%C3%ADcius-lallo-costa-pinto-961388202)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vinicius.lallo@gmail.com)
