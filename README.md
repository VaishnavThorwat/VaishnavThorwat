# Hi, I'm Vaishnav Thorwat

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaishnav-thorwat)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/VaishnavThorwat)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vaishnavthorwat.github.io/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:thorwatvaishnav@gmail.com)

</div>

---

## About Me

I'm an **AI Engineer** with a B.E. in Artificial Intelligence & Data Science (Mumbai University, 2025), focused on building production-ready **Generative AI** and **Agentic AI** systems.

I work across the full AI stack — designing **RAG pipelines** and **multi-agent workflows** with LangChain, LlamaIndex & CrewAI, to building **AI automation** with n8n and OpenAI/Gemini APIs. I take ideas from rapid POC to modular, deployment-ready backends.

```python
class VaishnavThorwat:
    def __init__(self):
        self.role      = "AI Engineer | GenAI & Agentic AI"
        self.education = "B.E. in AI & Data Science '25 — Mumbai University"
        self.location  = "Navi Mumbai, Maharashtra, India"
        self.focus     = ["LLM Orchestration", "RAG Pipelines", "Agentic Workflows",
                          "NLP", "Machine Learning"]

    def current_stack(self):
        return {
            "GenAI":    ["LangChain", "LlamaIndex", "CrewAI", "OpenAI API", "Gemini 2.0"],
            "ML/DL":    ["TensorFlow", "Keras", "Scikit-learn", "CNN Bi-LSTM"],
            "Tools":    ["Streamlit", "Python", "SQL", "Git"],
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
![Google Gemini](https://img.shields.io/badge/Gemini_2.0-4285F4?style=for-the-badge&logo=google&logoColor=white)

### Machine Learning & Deep Learning
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Languages & Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## Featured Projects

### [Multi-Index Knowledge Orchestrator — RAG Research Agent](https://github.com/VaishnavThorwat/Multi-Index-Knowledge-Orchestrator)
**Stack:** LlamaIndex · LangChain · Google Gemini 2.0 Flash · Vector Embeddings

A dual-index RAG pipeline that intelligently routes queries between semantic search and tree summarization based on question intent — with persistent on-disk vector indexing and shared StorageContext.

- **Architecture:** Dual-index design (VectorStoreIndex + SummaryIndex) from enriched nodes via IngestionPipeline
- **Impact:** Reduced redundant LLM API calls by ~40% via shared StorageContext
- **Key techniques:** QuestionsAnsweredExtractor metadata enrichment, SentenceSplitter, batch processing for free-tier rate limits

---

### [Autonomous Code Review Agent — Multi-Agent CrewAI Pipeline](https://github.com/VaishnavThorwat/Autonomous-Code-Review-Agent)
**Stack:** CrewAI · Gemini 2.0 Flash · Streamlit · OWASP

A 3-agent agentic workflow that autonomously reviews pull requests for code quality and security vulnerabilities across 4 severity levels.

- **Agents:** Senior Developer (quality analysis) → Security Engineer (OWASP scanning) → Tech Lead (final decision)
- **Output:** Structured JSON per agent + Markdown report with required changes and blocking logic
- **Deployment:** Ships as both a CLI tool and interactive Streamlit web app with one-click report download

---

### [SafeSpace — Real-Time Cyberbullying Detection](https://github.com/VaishnavThorwat/SafeSpace__Digital_Behaviour_Monitor)
**Stack:** CNN-Bi-LSTM · TensorFlow · Keras · NLP Pipeline

A hybrid deep learning model for real-time cyberbullying detection on Hinglish text.

- **Dataset:** 21K+ Hinglish conversational entries with full NLP preprocessing pipeline
- **Results:** 91% validation accuracy · 91.45% precision · 90.65% recall
- **Architecture:** CNN for local feature extraction + Bi-LSTM for sequential context, with client-server inference framework

---

## Hackathon Projects

| Project | Event | Stack | What It Does |
|---|---|---|---|
| Real Estate AI Sales Qualification Bot | Product Space Hackathon | n8n · OpenAI API · WhatsApp API | Lead scoring engine — classifies buyer intent (Hot/Warm/Cold) from multi-channel inquiries and auto-routes leads in seconds |
| Onboarding Drop-off Analyzer | Swafinix Technology Hackathon | n8n · Gemini AI · PostHog · Slack | Weekly AI pipeline clustering drop-off causes and auto-delivering prioritised UX fix recommendations to Slack |

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=VaishnavThorwat&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" height="180" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=VaishnavThorwat&theme=radical&hide_border=true" alt="GitHub Streak" height="180" />

</div>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VaishnavThorwat&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="48%" />

</div>

---

## What I'm Building Next

- Deploying a publicly accessible RAG application with a live URL
- Deepening expertise in **agentic AI** — tool use, memory, and multi-agent orchestration patterns
- Exploring **LLM evaluation frameworks** (RAGAS, LLM-as-judge) for production reliability
- Building with **FastAPI** for production-grade AI backends

---

## Education

**B.E. — Artificial Intelligence & Data Science Engineering**  
*Terna Engineering College, Navi Mumbai | Mumbai University | 2021 – 2025*

Relevant Coursework: Machine Learning, Deep Learning, Natural Language Processing, Data Mining, Data Structures & Algorithms, Probability & Statistics

---

## Let's Connect

I'm actively seeking **AI Engineer / LLM Engineer / Applied ML Engineer** roles where I can build real, production-grade intelligent systems.

- **Portfolio:** [vaishnavthorwat.github.io](https://vaishnavthorwat.github.io/)
- **LinkedIn:** [linkedin.com/in/vaishnav-thorwat](https://www.linkedin.com/in/vaishnav-thorwat)
- **Email:** thorwatvaishnav@gmail.com

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=VaishnavThorwat&color=blue&style=flat-square)

</div>
