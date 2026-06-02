# Hi, I'm Phani


I build ML systems that go beyond notebooks into production with tests, monitoring, and CI/CD.

## What I work with

**ML/DL:** Python, TensorFlow, PyTorch, Scikit-learn, XGBoost, PySpark

**NLP/GenAI:** Sentence Transformers, FAISS, ChromaDB, SpaCy, LangChain, Llama 3.1

**Deployment:** FastAPI, Docker, MLflow, Evidently AI, GitHub Actions

**Data:** Pandas, NumPy, SQL, Apache Spark, Power BI, Tableau

## Projects

### [Slonik-7B](https://github.com/phanipal/slonik-7b) — PostgreSQL Text-to-SQL Specialist
QLoRA SFT + 2000-step GRPO with execution-based rewards on Qwen2.5-Coder-7B. Achieves **38.20% on BIRD Mini-Dev PostgreSQL — beating GPT-4o (34.44%)** and 15+ points above Qwen2.5-Coder-32B, plus 45.20% on BIRD Mini-Dev SQLite. Trained on a single RTX 5080 Laptop GPU (16 GB VRAM) in ~24h, ~$3 in API costs. Three reward signals (execution match, sqlglot syntax, format) against live Postgres+pgvector. Models published as safetensors and GGUF (Q4_K_M/Q5_K_M/Q8_0) for Ollama/llama.cpp.

`Python` `PyTorch` `Unsloth` `TRL` `QLoRA` `GRPO` `Qwen` `PostgreSQL` `pgvector` `sqlglot` `llama.cpp` `GGUF`

### [IntelliDesk](https://github.com/phanipal/Intellidesk) — AI-Powered IT Service Desk
ML ticket-triage system with dual XGBoost classifiers for category and priority. Solved a 12:1 class imbalance using sqrt-scaled weights after standard balanced weighting hurt F1. Sentence-transformer + FAISS retriever for knowledge base search. MLflow tracking, Evidently drift monitoring, 39-check validation suite, full CI/CD.

`Python` `FastAPI` `XGBoost` `FAISS` `MLflow` `Evidently` `Docker` `GitHub Actions`

### [DocBrain](https://github.com/phanipal/docbrain) — Document Intelligence Engine
Grounded RAG pipeline for messy PDFs using ChromaDB, Sentence-Transformers, and Llama 3.1 8B. Evaluated on 30 hand-written queries: 0.90 Recall@5, 0.78 MRR, 1.00 Recall@1 on contracts. Second-layer LLM-judge faithfulness scoring that caught answer-quality issues on correctly-retrieved queries. Quality-based OCR routing, SpaCy NER, 162 pytest tests.

`Python` `PyTorch` `ChromaDB` `Llama 3.1` `FAISS` `SpaCy` `FastAPI` `Docker`

## Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/phanendra-p/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:phanendraus111@gmail.com)
