<div align="center">

# Землянко Кирилл

### ML Engineer / AI Engineer

Студент НГУ, направление — машинное обучение и искусственный интеллект  
Институт интеллектуальной робототехники

[English](README.md) | [Русский](README.ru.md)

</div>

---

## Обо мне

Я занимаюсь машинным обучением. Мне интересно создавать практические AI-сервисы: RAG-системы, LLM-агентов, классификаторы, семантический поиск и backend API для ML-моделей.

Сейчас я больше всего развиваюсь в NLP, retrieval-системах, детекции галлюцинаций и разработке ML-сервисов на Python. В проектах стараюсь уделять внимание не только модели, но и качеству решения: метрикам, структуре кода, API, хранению данных и удобству использования. Также мне интересно разбираться в том, как улучшать качество моделей и делать решения более надежными на реальных данных.

В моем опыте есть достойные хакатоны, командные проекты и личные ML-системы. Я стараюсь проектировать решения не только как модельные эксперименты, но и как полноценные engineering-проекты с понятной структурой, воспроизводимым запуском, измеримыми результатами и удобным интерфейсом.

---

## Стек технологий

### Языки программирования

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

### Machine learning и NLP

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=for-the-badge)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-111111?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-2D6CDF?style=for-the-badge)
![Classification](https://img.shields.io/badge/Classification-4B8BBE?style=for-the-badge)
![Feature Engineering](https://img.shields.io/badge/Feature%20Engineering-333333?style=for-the-badge)
![TF--IDF](https://img.shields.io/badge/TF--IDF-005571?style=for-the-badge)
![Embeddings](https://img.shields.io/badge/Embeddings-6E40C9?style=for-the-badge)

### LLM, агенты и retrieval

![RAG](https://img.shields.io/badge/RAG-4B8BBE?style=for-the-badge)
![LLM Agents](https://img.shields.io/badge/LLM%20Agents-111111?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-6E40C9?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![OpenAI API](https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=for-the-badge)
![Vector Search](https://img.shields.io/badge/Vector%20Search-008080?style=for-the-badge)
![Hybrid Search](https://img.shields.io/badge/Hybrid%20Search-5C2D91?style=for-the-badge)

### Backend, API и хранение данных

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-02569B?style=for-the-badge)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![CRUD](https://img.shields.io/badge/CRUD-555555?style=for-the-badge)

### Infrastructure, testing и systems

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Testing](https://img.shields.io/badge/Testing-6DB33F?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Embedded Linux](https://img.shields.io/badge/Embedded%20Linux-222222?style=for-the-badge)
![ARM64](https://img.shields.io/badge/ARM64-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![NPU](https://img.shields.io/badge/NPU-5C2D91?style=for-the-badge)
![ONNX Runtime](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)

---

## Достижения

- 2 место, трек Avito — IT Purple Hack 2026
- 3 место, трек Sber — IT Purple Hack 2026
- 3 место — Cloud.ru Hackathon

---

## Избранные проекты

| Проект | Описание | Стек / результат |
|---|---|---|
| [Guardian of Truth](https://github.com/Ultramind-67/purple_hack_sber) | Система детекции галлюцинаций в ответах LLM. Проект сфокусирован на анализе внутренних представлений модели и построении классификатора, который оценивает, является ли ответ надежным или содержит галлюцинации. | Python, ML-классификация, hidden states, feature engineering, оценка через PR-AUC. Результат: final/private PR-AUC ~0.8541, 3 место в треке Sber на IT Purple Hack 2026. |
| [Avito Split Detector](https://github.com/Ultramind-67/avito_hack_solution) | ML-сервис для определения split listings в данных маркетплейса. Система объединяет табличные признаки и текстовые сигналы, чтобы находить ситуации, когда один реальный объект представлен несколькими дублирующимися или фрагментированными объявлениями. | Python, CatBoost, TF-IDF, текстовые признаки, tabular ML, FastAPI. Результат: 2 место в треке Avito на IT Purple Hack 2026. |
| [AI Procurement Agent](https://github.com/Ultramind-67/hack_mcp_cloud_ru) | AI-агент для procurement-сценариев на базе Model Context Protocol. Проект сочетает tool-calling, retrieval по документам и интерактивный интерфейс для анализа закупочных данных. | Python, MCP, RAG, ChromaDB, Streamlit, LLM agents, tool-calling, retrieval pipelines. Результат: 3 место на Cloud.ru Hackathon. |
| [Semantic Search](https://github.com/kzemlyanko-wq/semantic-search) | Система семантического и гибридного поиска с API, локальным хранилищем, тестами и контейнеризацией. Проект поддерживает индексацию документов, хранение чанков, embedding-based retrieval и гибридное ранжирование для более релевантной выдачи. | Python, sentence-transformers, FastAPI, SQLite, SQL, Docker, tests, embeddings, hybrid search. Результат: MRR = 0.925. |
| [CdekStart RAG Bot](https://github.com/kzemlyanko-wq/Cdek_RAG-Bot) | RAG-бот с FastAPI backend и graph-based orchestration для ответов с учетом контекста. Система построена вокруг детерминированных retrieval-шагов и поддерживает разные LLM-провайдеры для гибкого локального или API-based запуска. | Python, FastAPI, LangGraph, RAG, OpenAI API, Ollama, retrieval orchestration, backend API. |
| [Neural Network in C](https://github.com/kzemlyanko-wq/neural-network-c) | Нейронная сеть, реализованная с нуля на C для классификации MNIST. Проект сфокусирован на понимании базовых механизмов deep learning без использования высокоуровневых ML-фреймворков. | C, MNIST, backpropagation, stochastic gradient descent, ReLU, softmax, ручной training loop. Результат: accuracy 86.15%. |
| [Orange Pi NPU on Alt Linux](https://github.com/Ultramind-67/orange-pi-6-plus-alt-linux-npu) | Embedded ML-проект по запуску нейросетевого инференса на Orange Pi 6 Plus под Alt Linux с ускорением на NPU. Проект связывает ML deployment, Linux и ARM-based hardware. | ARM64, Alt Linux, Embedded Linux, NPU, ONNX Runtime, ResNet50 inference, hardware-oriented deployment. |

---

## Контакты

- Telegram: [@k6r1ll](https://t.me/k6r1ll)
- Email: [k.zemlyanko@g.nsu.ru](mailto:k.zemlyanko@g.nsu.ru)
- GitHub: [kzemlyanko-wq](https://github.com/kzemlyanko-wq)
