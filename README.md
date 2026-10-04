# About Me

I'm an Associate Business Analyst at [Koïos Intelligence](https://koiosintelligence.ca/), where I work on conversational AI chatbots for insurance clients across the Python backend and TypeScript frontend.

I hold a BAA from HEC Montreal with a specialization in information technology, and I focus on machine learning engineering and backend development. I work primarily in Python and C++, and have built production ML systems covering recommendation engines, agentic AI, and computer vision inference pipelines.

**Portfolio:** [simon-bouchard.com](https://simon-bouchard.com)

---

## Tech Stack

**Languages:** Python, C++, TypeScript

**Frameworks and Libraries:** FastAPI, PyTorch, scikit-learn, LangChain, LangGraph, pandas, NumPy

**Machine Learning:** Collaborative filtering (ALS), attention-pooled embeddings, RAG systems, FAISS/HNSW indexing, semantic search, model serving

**Data Engineering:** Kafka, Spark, Airflow, SQL, Redis, ETL/ELT pipelines

**Cloud and Infrastructure:** AWS (SageMaker, S3, EC2), Docker, Nginx, CI/CD (GitHub Actions), Linux/Bash

**Observability:** Prometheus, Grafana, OpenTelemetry, Jaeger

**Tools:** Git, Visual Studio Code, WSL (Ubuntu), tmux, neovim, Jupyter

---

## Projects

**Book Recommendation System** | [Live demo](https://recsys.simon-bouchard.com) | [GitHub](https://github.com/simon-bouchard/book-recommendation-platform)

Production ML platform built on approximately 250,000 books. Features a dual-factor recommendation engine combining ALS collaborative filtering with custom attention-pooled subject embeddings trained with a dual regression and contrastive loss. Includes a multi-agent LangGraph chatbot with semantic search (FAISS HNSW), RAG, user personalization, and web search. Automated daily retraining pipeline with a quality gate, zero-downtime hot-reload across 5 model microservices, and full observability with Prometheus, Grafana, and Jaeger distributed tracing.

**CV Inference with NVIDIA Triton** | [GitHub](https://github.com/simon-bouchard/cv-inference-triton)

Deploying computer vision models with NVIDIA Triton Inference Server. Covers model optimization (ONNX to TensorRT FP16), ensemble pipelines, and a custom C++ preprocessing backend. Each experiment identifies a bottleneck, addresses it, and documents the result with real benchmark numbers. Achieved 34% throughput improvement and 30% latency reduction over the baseline ONNX pipeline by eliminating Python GIL overhead and maximizing GPU utilization.

**AI Framework Tracker** | [GitHub](https://github.com/simon-bouchard/ai-researcher)

An agentic pipeline built with the Claude Agent SDK and Airflow that continuously scrapes emerging AI agent frameworks and compiles them into a queryable, interlinked knowledge base, so coding agents past their training cutoff can stay aware of what exists. The LLM only makes semantic scope judgments while Python handles search and filtering, and change detection plus a rejection cache ensure no repo is fetched or judged twice.

**Quebec Region Classifier** | [GitHub](https://github.com/simon-bouchard/geo-classifier-quebec)

A fine-tuned EfficientNet-V2-M that classifies street-level photos into one of Quebec's 17 administrative regions, reaching 89.8% test accuracy (0.898 macro F1). Trained on a self-built dataset from an async Mapillary grid scan with spatially stratified sampling, then exported to ONNX FP16 for lightweight inference.

**C++ Thread Pool** | [GitHub](https://github.com/simon-bouchard/cpp-threadpool)

A C++23 thread pool with work-stealing deques and dependency-graph task scheduling, including failure propagation across transitive and diamond-shaped dependency chains. Uses `std::jthread` with `std::stop_token` for cooperative shutdown and is tested under ASan, UBSan, and TSan in CI.

More projects at [simon-bouchard.com/projects](https://simon-bouchard.com/projects/).

---

## Certifications

**AWS Certified Generative AI Developer Professional (AIP-C01)** | Early Adopter (First 5,000 globally) | Jan 2026

**AWS Certified Machine Learning Specialty (MLS-C01)** | Score: 890/1000 | Jan 2026

**Advanced Machine Learning:** MIT Introduction to Deep Learning, fast.ai Practical Deep Learning for Coders (Parts 1 and 2)

**AI and Generative AI:** DeepLearning.AI: AI for Everyone, Generative AI for Everyone, Agentic AI

**Software Engineering:** MIT The Missing Semester of Your CS Education

**Backend Development:** FreeCodeCamp (Backend APIs, Quality Assurance, Information Security, Scientific Computing, Data Analysis, Machine Learning with Python)
