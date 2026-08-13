# About Me

I'm a recent business school graduate (BAA, HEC Montreal) with a specialization in information technology, focused on machine learning engineering and backend development. I work primarily in Python and have built production ML systems covering recommendation engines, agentic AI, and computer vision inference pipelines.

I'm currently deepening my experience in ML infrastructure, model serving, and production-grade API design.

---

## Tech Stack

**Languages:** Python, C++, Typescript

**Frameworks and Libraries:** FastAPI, PyTorch, scikit-learn, LangChain, LangGraph, pandas, NumPy

**Machine Learning:** Collaborative filtering (ALS), attention-pooled embeddings, RAG systems, FAISS/HNSW indexing, semantic search, model serving

**Data Engineering:** Kafka, Spark, SQL, Redis, ETL/ELT pipelines

**Cloud and Infrastructure:** AWS (SageMaker, S3, EC2), Docker, Nginx, CI/CD (GitHub Actions), Linux/Bash

**Observability:** Prometheus, Grafana, OpenTelemetry, Jaeger

**Tools:** Git, Visual Studio Code, WSL (Ubuntu), tmux, neovim, Jupyter

---

## Projects

**Book Recommendation System** | [recsys.simonbouchard.space](https://recsys.simonbouchard.space)

Production ML platform built on approximately 250,000 books. Features a dual-factor recommendation engine combining ALS collaborative filtering with custom attention-pooled subject embeddings trained with a dual regression and contrastive loss. Includes a multi-agent LangGraph chatbot with semantic search (FAISS HNSW), RAG, user personalization, and web search. Automated daily retraining pipeline with a quality gate, zero-downtime hot-reload across 5 model microservices, and full observability with Prometheus, Grafana, and Jaeger distributed tracing.

[GitHub](https://github.com/simon-bouchard/book-recommendation-platform)

**CV Inference with NVIDIA Triton**

Portfolio project focused on deploying computer vision models with NVIDIA Triton Inference Server. Covers model optimization (ONNX to TensorRT FP16), ensemble pipelines, and a custom C++ preprocessing backend. Each experiment identifies a bottleneck, addresses it, and documents the result with real benchmark numbers. Achieved 34% throughput improvement and 30% latency reduction over the baseline ONNX pipeline by eliminating Python GIL overhead and maximizing GPU utilization.

[GitHub](https://github.com/simon-bouchard/cv-inference-triton)

**Missing Semester Solutions Website**

PHP-based website hosted with Apache to share organized notes and solutions for The Missing Semester course. Deployed on Oracle Cloud with DNS and HTTPS configured.

[GitHub](https://github.com/simon-bouchard/Missing-Semester-Solutions)

---

## Certifications

**AWS Certified Generative AI Developer Professional (AIP-C01)** | Early Adopter (First 5,000 globally) | Jan 2026

**AWS Certified Machine Learning Specialty (MLS-C01)** | Score: 890/1000 | Jan 2026

**Advanced Machine Learning:** MIT Introduction to Deep Learning, fast.ai Practical Deep Learning for Coders (Parts 1 and 2)

**AI and Generative AI:** DeepLearning.AI -- AI for Everyone, Generative AI for Everyone, Agentic AI

**Software Engineering:** MIT The Missing Semester of Your CS Education

**Backend Development:** FreeCodeCamp (Backend APIs, Quality Assurance, Information Security, Scientific Computing, Data Analysis, Machine Learning with Python)
