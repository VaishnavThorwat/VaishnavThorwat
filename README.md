# Hi, I'm Vaishnav Thorwat

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaishnav-thorwat)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VaishnavThorwat)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vaishnavthorwat.github.io/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thorwatvaishnav25@gmail.com)

</div>

---

## About Me

I'm an **AI Engineer** with a B.E. in Artificial Intelligence & Data Science (Mumbai University, 2025), focused on building production-ready **Generative AI** and **Agentic AI** systems.

I work across the full AI stack — designing **RAG pipelines** and **multi-agent workflows** with LangChain, LlamaIndex & CrewAI, writing **LLM evaluation suites** with pytest + DeepEval, and building **AI automation** with n8n and the Gemini/OpenAI APIs. I take ideas from rapid POC to modular, deployment-ready backends.

```python
class VaishnavThorwat:
    def __init__(self):
        self.role      = "AI Engineer | GenAI & Agentic AI"
        self.education = "B.E. in AI & Data Science '25 — Mumbai University"
        self.location  = "Navi Mumbai, Maharashtra, India"
        self.focus     = ["LLM Orchestration", "RAG Pipelines", "Agentic Workflows",
                          "LLM Evaluation", "NLP", "Machine Learning"]

    def current_stack(self):
        return {
            "GenAI":       ["LangChain", "LlamaIndex", "CrewAI", "OpenAI API",
                             "Gemini API", "Groq (LLaMA 3.3 70B)", "LiteLLM", "Ollama"],
            "ML/DL":       ["TensorFlow", "Keras", "scikit-learn",
                             "Hugging Face Transformers", "CNN-BiLSTM"],
            "Eval/Test":   ["pytest", "DeepEval (GEval, LLMTestCase)"],
            "Dev/Deploy":  ["FastAPI", "Docker", "Streamlit", "Python", "SQL", "Git"],
        }

    def say_hi(self):
        print("Let's build AI that actually does something useful!")
```

---

## Tech Stack

### Generative AI & LLM Orchestration
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6B48FF?style=for-the-badge&logo=python&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF6B6B?style=for-the-badge&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logo=lightning&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-000000?style=for-the-badge&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

### LLM Evaluation & Testing
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![DeepEval](https://img.shields.io/badge/DeepEval-6B48FF?style=for-the-badge&logo=python&logoColor=white)

### Machine Learning & Deep Learning
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Languages & Deployment
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

> A few of these (FastAPI, Docker, Ollama, Hugging Face Transformers) are skills I'm actively building with and about to showcase in upcoming repos — badges above reflect current capability, and linked project write-ups below will expand as those ship.

---

## Featured Projects

### [Autonomous PR Review Agent — Multi-Agent CrewAI Pipeline](https://github.com/VaishnavThorwat/Autonomous-Code-Review-Agent)
**Stack:** CrewAI · Gemini 2.0 Flash · Streamlit · OWASP

A 3-agent agentic workflow that autonomously reviews pull requests for code quality and security vulnerabilities.

- **Agents:** Senior Developer (quality analysis) → Security Engineer (OWASP-grounded vulnerability lookups via SerperDevTool + ScrapeWebsiteTool) → Tech Lead (final decision)
- **Output:** Structured JSON per agent + a Markdown report with required changes and blocking logic
- **Deployment:** Ships as both a CLI tool and an interactive Streamlit web app with a severity dashboard and one-click report export

---

### [Multi-Index RAG Research Agent](https://github.com/VaishnavThorwat/Multi-Index-Knowledge-Orchestrator)
**Stack:** LlamaIndex · LangChain · Google Gemini 2.0 Flash

A dual-index RAG pipeline that routes queries between semantic search and tree summarization based on question intent.

- **Architecture:** Dual-index design (VectorStoreIndex + SummaryIndex) built from a shared, enriched node set via an IngestionPipeline
- **Persistence:** Both indexes share a single StorageContext, so on-disk indexes reload without re-ingesting or re-embedding source documents
- **Key techniques:** QuestionsAnsweredExtractor metadata enrichment, SentenceSplitter chunking, batched processing with rate-limit handling for the Gemini free tier

---

### [AI Mock Interview Coach + LLM Evaluation Suite](https://github.com/VaishnavThorwat/ai-mock-interview-coach)
**Stack:** CrewAI · LiteLLM · Groq · pytest · DeepEval

A multi-agent CLI that runs realistic mock interviews and grades the transcript against a five-dimension rubric — plus the test suite that verifies the grader itself.

- **Agents:** Research Agent (role-specific interview brief) → live LiteLLM Interviewer loop (full conversation history as memory) → Evaluator Agent (scores Clarity, Depth, Relevance, Evidence, Role Fit)
- **Evaluation:** DeepEval (GEval) suite testing feedback specificity, model-answer quality, and score-justification consistency, using Gemini as the judge via LiteLLM
- **Testing:** Deterministic pytest edge-case coverage (blank / skipped answers) with report-structure validation across multiple fixtures

---

### [SafeSpace — Cyberbullying Detection](https://github.com/VaishnavThorwat/SafeSpace__Digital_Behaviour_Monitor)
**Stack:** CNN-BiLSTM · TensorFlow · Keras · NLP Pipeline · Python Sockets

A hybrid deep learning model for cyberbullying classification on Hinglish text.

- **Dataset:** 21K+ Hinglish conversational entries with a full NLP preprocessing pipeline (tokenization, stopword removal, sequence padding)
- **Results:** ~91% validation accuracy on binary bullying classification
- **Architecture:** CNN for local feature extraction + Bi-LSTM for sequential context, paired with a TF-IDF inference pathway and a Python socket-based chat server supporting concurrent multi-room sessions

---

## Hackathon Projects

| Project | Event | Stack | What It Does |
|---|---|---|---|
| Real Estate AI Sales Qualification Bot | Product Space Hackathon | n8n · OpenAI API · WhatsApp API | Lead scoring engine — classifies buyer intent (Hot/Warm/Cold) from multi-channel inquiries and auto-routes leads in seconds |
| Onboarding Drop-off Analyzer | Swafinix Technology Hackathon | n8n · Gemini AI · PostHog · Slack | Weekly AI pipeline clustering drop-off causes and auto-delivering prioritised UX fix recommendations to Slack |

---
## What I'm Building Next

- Deploying a publicly accessible RAG application with a live URL
- Shipping the FastAPI + Docker versions of my existing agent projects as proper backends
- Deepening expertise in **agentic AI** — tool use, memory, and multi-agent orchestration patterns
- Expanding **LLM evaluation** coverage (DeepEval, pytest) across all agent projects, not just the interview coach

---

## Education & Certifications

**B.E. — Artificial Intelligence & Data Science Engineering**
*Terna Engineering College, Navi Mumbai | Mumbai University | 2021 – 2025*

Relevant Coursework: Machine Learning, Deep Learning, Natural Language Processing, Data Mining, Data Structures & Algorithms, Probability & Statistics

- **Prompt Engineering for ChatGPT** — Coursera — *Feb 2026*

---

## Let's Connect

I'm actively seeking **AI Engineer / LLM Engineer / Applied ML Engineer** roles where I can build real, production-grade intelligent systems.

- **Portfolio:** [vaishnavthorwat.github.io](https://vaishnavthorwat.github.io/)
- **LinkedIn:** [linkedin.com/in/vaishnav-thorwat](https://www.linkedin.com/in/vaishnav-thorwat)
- **Email:** thorwatvaishnav25@gmail.com

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=VaishnavThorwat&color=blue&style=flat-square)

</div>
