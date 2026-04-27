<div align="center">

# Kirill Zemlyanko

### ML Engineer / AI Engineer

ML & AI student at Novosibirsk State University  
Institute of Intelligent Robotics

[English](README.md) | [Русский](README.ru.md)

</div>

---

## About me

I work with machine learning and AI engineering. I enjoy building practical AI services such as RAG systems, LLM agents, classifiers, semantic search tools, and backend APIs for ML models.

My current focus is NLP, retrieval systems, hallucination detection, and Python-based ML services. In my projects, I try to pay attention not only to the model itself, but also to solution quality: metrics, code structure, APIs, data storage, and usability. I’m also interested in improving model quality and making ML solutions more reliable on real-world data.

My project experience includes hackathon solutions, [team projects](https://github.com/Ultramind-67) and personal ML systems. I try to design projects so they are not only model experiments, but complete engineering solutions with clear structure, reproducible setup, measurable results and understandable interfaces.

---

## Tech stack

### Programming languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

### Machine learning and NLP

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-111111?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-2D6CDF?style=for-the-badge)
![Classification](https://img.shields.io/badge/Classification-4B8BBE?style=for-the-badge)
![Feature Engineering](https://img.shields.io/badge/Feature%20Engineering-333333?style=for-the-badge)
![TF--IDF](https://img.shields.io/badge/TF--IDF-005571?style=for-the-badge)
![Embeddings](https://img.shields.io/badge/Embeddings-6E40C9?style=for-the-badge)

### LLM, agents and retrieval

![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge)
![LLM Agents](https://img.shields.io/badge/LLM%20Agents-111111?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-6E40C9?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge)
![Vector Search](https://img.shields.io/badge/Vector%20Search-008080?style=for-the-badge)
![Hybrid Search](https://img.shields.io/badge/Hybrid%20Search-5C2D91?style=for-the-badge)

### Backend, APIs and data storage

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-02569B?style=for-the-badge)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![CRUD](https://img.shields.io/badge/CRUD-555555?style=for-the-badge)

### Infrastructure, testing and systems

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Testing](https://img.shields.io/badge/Testing-6DB33F?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Embedded Linux](https://img.shields.io/badge/Embedded%20Linux-222222?style=for-the-badge)
![ARM64](https://img.shields.io/badge/ARM64-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![NPU](https://img.shields.io/badge/NPU-5C2D91?style=for-the-badge)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)

---

## Achievements

- 2nd place, Avito track — IT Purple Hack 2026
- 3rd place, Sber track — IT Purple Hack 2026
- 3rd place — Cloud.ru Hackathon

---

## Featured projects

| Project | Description | Stack / Result |
|---|---|---|
| [Guardian of Truth](https://github.com/Ultramind-67/purple_hack_sber) | Hallucination detection system for LLM-generated answers. The project focuses on analyzing internal model representations and building a classifier that estimates whether an answer is reliable or contains hallucinated content. | Python, ML classification, hidden states, feature engineering, evaluation with PR-AUC. Result: final/private PR-AUC ~0.8541, 3rd place in the Sber track at IT Purple Hack 2026. |
| [Avito Split Detector](https://github.com/Ultramind-67/avito_hack_solution) | Hybrid ML service for the Avito case at IT Purple Hack 2026. The system analyzes a home renovation listing and decides whether it should be split into separate service listings. It detects additional microcategories in the text, makes a local ML-based split decision, and can optionally generate draft listings. | Python, CatBoost, TF-IDF, rule-based detector, meta-features, FastAPI, optional OpenRouter LLM drafts, tests. Result: 2nd place in the Avito track at IT Purple Hack 2026. |
| [AI Procurement Agent](https://github.com/Ultramind-67/hack_mcp_cloud_ru) | AI agent for procurement scenarios based on the Model Context Protocol. The project combines tool-calling, retrieval over documents and an interactive interface to support analysis of procurement-related data. | Python, MCP, RAG, ChromaDB, Streamlit, LLM agents, tool-calling, retrieval pipelines. Result: 3rd place at Cloud.ru Hackathon. |
| [Semantic Search](https://github.com/kzemlyanko-wq/semantic-search) | Semantic and hybrid search system with API, local storage, tests and containerization. The project supports document indexing, chunk storage, embedding-based retrieval and hybrid ranking for more relevant search results. | Python, sentence-transformers, FastAPI, SQLite, SQL, Docker, tests, embeddings, hybrid search. Result: MRR = 0.925. |
| [CdekStart RAG Bot](https://github.com/kzemlyanko-wq/Cdek_RAG-Bot) | RAG bot with a FastAPI backend and graph-based orchestration for context-aware answers. The system is designed around deterministic retrieval steps and supports different LLM providers for flexible deployment. | Python, FastAPI, LangGraph, RAG, OpenAI API, Ollama, retrieval orchestration, backend API. |
| [Neural Network in C](https://github.com/kzemlyanko-wq/neural-network-c) | Neural network implemented from scratch in C for MNIST classification. The project focuses on understanding core deep learning mechanics without high-level ML frameworks. | C, MNIST, backpropagation, stochastic gradient descent, ReLU, softmax, manual training loop. Result: 86.15% accuracy. |
| [Orange Pi NPU on Alt Linux](https://github.com/Ultramind-67/orange-pi-6-plus-alt-linux-npu) | Embedded ML inference project focused on running neural network inference on Orange Pi 6 Plus under Alt Linux with NPU acceleration. The project connects ML deployment with Linux and ARM-based hardware. | ARM64, Alt Linux, Embedded Linux, NPU, ONNX Runtime, ResNet50 inference, hardware-oriented deployment. |

---

## Contacts

- Telegram: [@k6r1ll](https://t.me/k6r1ll)
- Email: [k.zemlyanko@g.nsu.ru](mailto:k.zemlyanko@g.nsu.ru)
- GitHub: [kzemlyanko-wq](https://github.com/kzemlyanko-wq)
