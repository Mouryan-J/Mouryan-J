# 👋 Hi, I'm Mouryan Jayasankar

🎓 MS in Data Science @ Indiana University Bloomington (2024–2026)
🔬 Research Assistant @ Luddy School (FADS) | Ex-MLE Intern @ MyEdMaster | Ex-GET @ HCLTech
📫 mouryanj2001@gmail.com | 🔗 [LinkedIn](https://linkedin.com/in/mouryanj)

---

## 🚀 About Me

I'm a Data Scientist / ML Engineer focused on building production-grade LLM systems, RAG pipelines, and multi-agent architectures. My work spans from optimizing inference at the kernel level to architecting knowledge-graph-augmented retrieval systems that actually move accuracy numbers, not just look good in a notebook.

---

## 🧠 What I Do

### 🔹 LLM Systems & RAG

- Built RAG pipelines with semantic chunking, FAISS vector search, and cross-encoder reranking for field-level PDF extraction
- Benchmarked AWQ, GPTQ, and GGUF quantization, selecting Marlin kernel to hit 50ms TTFT at 6.97 perplexity
- Served LLM inference through vLLM with batching for real-time extraction throughput
- Designed GraphRAG systems on Neo4j (50K+ entities) for multi-hop reasoning and semantic search

### 🔹 Multi-Agent & Orchestration

- Architected multi-agent LLM orchestration pipelines (LangGraph) combining hybrid retrieval (BM25 + Qdrant + Cohere reranking) with knowledge-graph dependency reasoning, 96% Recall@1 using Claude Haiku
- Built an LLM-as-judge evaluation framework for RCA accuracy, debugging a token-truncation bug that raised accuracy from 60% → 100%
- Built enterprise conversational AI agents with intent classification and a secure Text-to-SQL engine routing across multiple MCP servers

### 🔹 Machine Learning & Deep Learning

- Architected diabetic retinopathy detection using Vision Transformers (ViT) on retinal fundus images, QWK score of 0.887 across 5-stage classification
- Designed hybrid CNN-ANN models for breast cancer stage classification (99.6% train / 77.7% val accuracy), published in a Scopus-indexed journal
- Built automated LLM benchmarking pipelines comparing GPT-4, Claude, and Gemini across cost-latency-quality tradeoffs

---

## 🛠️ Skills & Tools

**Languages:** Python, R, SQL, TypeScript
**ML/AI:** PyTorch, TensorFlow, Scikit-learn, MLflow, Transformers, RAG, LangGraph, Causal Inference
**Data Engineering:** PySpark, dbt, Airflow, Databricks, Snowflake
**Cloud:** AWS (S3, Lambda, Redshift), Azure (Synapse, ADF)
**Infra/MLOps:** Docker, Kubernetes, CI/CD, FastAPI, Neo4j, Qdrant
**Visualization:** Tableau, Power BI, Matplotlib, ggplot2

---

## 📂 Featured Projects

### 🔍 RootCause: Multi-Agent Incident RCA System
`LLM` `LangGraph` `Neo4j` `FastAPI`
- Multi-agent orchestration pipeline with hybrid retrieval (BM25 + Qdrant + Cohere reranking) and Neo4j-based dependency reasoning, 96% Recall@1
- LLM-as-judge eval framework; fixed token-truncation bug raising accuracy from 60% to 100%

### 🏢 IntelliFlow: Enterprise AI Orchestration System
`LLM` `Neo4j` `FastAPI` `MCP`
- Enterprise conversational AI agent with secure Text-to-SQL routing across 3 MCP servers
- GraphRAG research system on Neo4j with 50K+ entities for multi-hop reasoning

### ✈️ No Detours: Interactive Travel Agent Planner
`GPT-4` `Claude` `FastAPI`
- AI travel planning assistant generating itineraries, budgets, and weather-aware schedules
- Automated LLM benchmarking pipeline across 5 performance metrics for model selection

### 🩺 Diabetic Retinopathy Detection
`ViT` `TensorFlow/Keras`
- Vision Transformer model for 5-stage severity classification, QWK score of 0.887
- REST API integration into a production retinal screening pipeline

---

## 📫 Let's Connect

Always up for a conversation about LLM systems, RAG, or data engineering, reach out via [LinkedIn](https://linkedin.com/in/mouryanj) or email at **mouryanj2001@gmail.com**.
