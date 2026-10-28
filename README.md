# Hi, I'm Kavya Gautam

I build distributed systems, data pipelines, and AI research tools. I'm a senior studying Computer Science at Mississippi State University with a **4.0 GPA**. I expect to graduate in **May 2027**.

I'm seeking **2027 new-grad software engineering roles** in backend engineering, distributed systems, and AI.

[Website](https://www.kavyagautam.com) · [Resume](https://www.kavyagautam.com/Kavya_Gautam_Resume.pdf) · [LinkedIn](https://linkedin.com/in/kavya-gautam)

## Projects and research

### [Distributed remote code execution engine](https://github.com/spicyneutrino/distributed-rce-engine)

I built an asynchronous Python execution service with FastAPI and RabbitMQ workers. PostgreSQL stores job state, and MinIO stores source files. Jobs run in short-lived Podman containers with code scanning, network isolation, resource limits, and seccomp. Prometheus collects metrics, Grafana displays them, and Locust generates test workloads.

### NSF SECURE research intelligence platform

As an undergraduate researcher at MSU, I led development of a platform that combines **8+ public datasets**. The platform covers **187 R1 universities**, plus nonprofits, small businesses, and federal labs.

I built Python and PostgreSQL pipelines to extract, transform, and load **400K+ publication and funding records**. The pipelines match institutions, validate records, and track sources. I also developed a TypeScript and React app for funding analytics and comparisons between institutions.

### EV grid simulation and LLM-to-Map

At MSU's Artificial Intelligence Research Lab, I replaced HTTP polling with WebSocket updates. I also built an interface that lets a large language model control the simulator through structured tool calls.

I co-authored [LLM-to-Map: Transparent Conversational Tool Orchestration for Real-Time Multi-Domain Simulation](https://www.ijcai.org/proceedings/2026/958), a paper in the **IJCAI 2026 Demo Track**. The system converts natural-language requests into tool calls that control traffic and power-grid simulations. Users can inspect the tool calls and execution logs.

### Legal compliance AI assistant

As an AI Fellow at the Mississippi AI Innovation Hub, I expanded an assistant to cover **7 states and 5,000+ legal documents**. I built crawlers with Playwright and Scrapy, and a retrieval pipeline with AWS Bedrock, OpenSearch, and S3. The assistant retrieves documents to generate answers with source citations. Users can inspect those sources in the app's PDF viewer.

### [Vision Transformer for audio classification](https://github.com/spicyneutrino/audio-classification-using-ViT)

I adapted an image-based Vision Transformer to classify UrbanSound8K audio spectrograms. The model reached **71.2% accuracy** without audio-specific pretraining. I fine-tuned the model with PyTorch, mixed-precision training, and learning-rate scheduling on an NVIDIA A100 through Slurm.

## Teaching and community

I'm a teaching assistant and mentor for NSF programs in AI and machine learning at MSU. I support 8 students in ExLENT and mentor 3 high school students in iTEST/SmartCT. The high school students build camera-based AI systems with Python, OpenCV, and TensorFlow Lite.

Previously, I led MSU's ACM SIGHPC student chapter as president and organized biweekly workshops.

## Tools I use

- **Languages:** Python, C++, SQL, TypeScript, JavaScript, Bash
- **Backend and data:** FastAPI, PostgreSQL, RabbitMQ, MinIO, WebSockets, Socket.IO, OpenSearch
- **Web:** React, Streamlit, Playwright, Scrapy
- **Infrastructure:** Linux, AWS, Docker, Podman, Slurm, GitHub Actions, Prometheus, Grafana
- **AI/ML:** PyTorch, scikit-learn, OpenCV, TensorFlow Lite, RAG, LLM tool calling

I'm interested in open-source work on distributed systems, databases, storage, observability, and backend infrastructure.
