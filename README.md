# Hi, I'm Kavya Gautam

I'm a **senior Computer Science student at Mississippi State University** interested in distributed systems, backend infrastructure, data-intensive applications, and AI systems.

My work spans research data platforms, real-time EV and power-grid simulation, and AI applications with source-backed answers. I expect to graduate in **May 2027** and currently hold a **4.0 GPA**.

I'm seeking **2027 new-grad software engineering roles**, particularly in backend engineering, distributed systems, infrastructure, data engineering, and AI.

[Website](https://www.kavyagautam.com) · [Resume](https://www.kavyagautam.com/Kavya_Gautam_Resume.pdf) · [LinkedIn](https://linkedin.com/in/kavya-gautam)

## Experience

### NSF SECURE research intelligence platform

Undergraduate Researcher, Software & Data Engineering · MSU Office of Research and Economic Development · June 2025 to August 2026

- Led development of a platform combining **8+ public research-funding and publication datasets across 187 R1 universities**, plus nonprofits, small businesses, and federal labs.
- Engineered Python and PostgreSQL ETL pipelines for **400K+ publication and funding records**, with automated institution matching, validation, and source tracking for reproducible results.
- Developed a TypeScript and React web app for funding analytics, peer-institution benchmarking, and research-security scoring.

### EV grid simulation platform

Undergraduate Researcher · MSU Artificial Intelligence Research Lab · February to August 2026

- Replaced HTTP polling with WebSocket push updates, eliminating **5–7 requests per second per client** and **2–5 seconds of stale data**.
- Built an LLM interface with **26 function-calling tools** for simulation control and scaled the platform from approximately **100 to 700+ vehicles at 60 FPS**.
- Co-authored an **IJCAI-ECAI 2026 Demo Track paper** on transparent LLM control of a real-time EV and power-grid simulation.

### Legal compliance AI assistant

AI Fellow · Mississippi AI Innovation Hub · December 2025 to May 2026

- Expanded a retrieval-augmented generation assistant to **7 states and 5,000+ legal documents**, with Playwright and Scrapy crawlers for 4 state websites.
- Built the retrieval and answer pipeline on **AWS Bedrock, OpenSearch, and S3**, restricting answers to cited sources.
- Added an in-app PDF viewer so users could inspect the documents behind each answer.

## Featured projects

### [Distributed remote code execution engine](https://github.com/spicyneutrino/distributed-rce-engine)

An asynchronous Python execution service built with **FastAPI, RabbitMQ, PostgreSQL, MinIO, and Podman**.

- Queues jobs through FastAPI gateways to RabbitMQ workers, with PostgreSQL for persistent job state and MinIO for source storage.
- Runs code in short-lived Podman sandboxes with AST code scanning, network isolation, resource limits, and Linux syscall filtering through seccomp.
- Uses asynchronous I/O and connection pooling, with Locust workloads for load testing and Prometheus and Grafana for observability.

The project demonstrates sandbox controls for code execution. It is a development system, not a hardened boundary for a production service with multiple tenants.

### [Vision Transformer for audio classification](https://github.com/spicyneutrino/audio-classification-using-ViT)

An audio classification project that adapts an image-based Vision Transformer to recognize urban sounds from spectrograms.

- Reached **71.2% accuracy on UrbanSound8K** without audio-specific pretraining.
- Fine-tuned the model with PyTorch, mixed-precision training, and learning-rate scheduling on an **NVIDIA A100 GPU through Slurm**.

## Research

### [LLM-to-Map: Transparent Conversational Tool Orchestration for Real-Time Multi-Domain Simulation](https://www.ijcai.org/proceedings/2026/958)

Co-authored paper in the **IJCAI 2026 Demo Track**.

LLM-to-Map connects natural-language requests to structured tool calls for traffic and power-grid simulation. The interface exposes tool calls, parameters, and execution logs so users can inspect how the system interprets and executes their requests.

## Teaching and leadership

### Teaching assistant and mentor

NSF AI/ML Education Programs · Mississippi State University · September 2026 to present

- Design rubrics, grade assignments, and answer questions for **8 students** in NSF ExLENT, a program for experiential learning in AI and machine learning.
- Mentor **3 high school students** in NSF iTEST/SmartCT as they build camera-based AI systems, including a smart door and an object sorter, with Python, OpenCV, and TensorFlow Lite.

### ACM SIGHPC chapter president

Mississippi State University · September 2024 to May 2026

- Led MSU's ACM SIGHPC student chapter as president after serving as vice president, organizing biweekly workshops.

## Technical interests

Distributed systems, databases and storage engines, event streaming, fault tolerance, replication, observability, and AI systems.

I'm interested in contributing to open-source projects in these areas, especially backend infrastructure and data-intensive systems.

## Technologies

**Languages**

Python · C++ · SQL · TypeScript · JavaScript · Bash

**Backend and data**

FastAPI · REST APIs · WebSockets · Socket.IO · RabbitMQ · PostgreSQL · MinIO · OpenSearch · ETL pipelines

**Web**

React · Streamlit · Playwright · Scrapy

**Infrastructure and cloud**

AWS Bedrock and S3 · Linux · Docker · Podman · Slurm · GitHub Actions · Prometheus · Grafana

**AI and machine learning**

PyTorch · scikit-learn · NumPy · Pandas · OpenCV · TensorFlow Lite · RAG · LLM tool calling · OpenAI API
