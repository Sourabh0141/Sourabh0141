# Sourabh Sharma

**Software Engineer — Backend Systems, Applied AI & Cloud Architecture**  
Jaipur, India · Associate Software Developer at Predusk Technology

[Live Portfolio](https://sourabh.pages.dev) · [LinkedIn](https://www.linkedin.com/in/sourabh-sharma-3221932b5/) · [Email](mailto:sourabh.sharma0141@gmail.com)

---

### Engineering Profile

I architect high-throughput asynchronous backends, event-driven streaming pipelines, and production machine learning workflows. My core engineering focus centers on eliminating synchronous bottlenecks with non-blocking I/O, replacing fragile polling mechanisms with broker-based push topologies, and deploying low-latency vision, speech, and retrieval models across Google Cloud, AWS, and Cloudflare.

---

### Key Architectures & Production Systems

#### Caliber — Cross-Cloud Video Platform & Data Engine
* Led offshore engineering spanning Google Cloud and AWS for US social video media brands (The News Movement, Recount).
* Architected keyless cross-cloud authentication using AWS-to-GCP Workload Identity Federation, allowing AWS Lambda services to securely query BigQuery catalogs without static service account keys.
* Decomposed monolithic classification pipelines into modular Cloud Functions with LLM inference and guarded SQL MERGE write-backs to preserve editorial annotations.
* Engineered an automated video transcription pool featuring time-budgeted execution, exponential jitter backoff, and idempotent BigQuery job management.

#### Labelfort — Multi-Tenant AI Data Annotation Platform
* Replaced polling and SSE with a RabbitMQ topic exchange and Web-MQTT gateway over WebSockets, delivering real-time progress for 5 event domains with role-based topic filtering.
* Integrated GPU-accelerated microservices: polygon instance segmentation via SAM 2.1 and multi-object tracking via YOLO11x with BoT-SORT.
* Built browser-direct presigned S3/MinIO multipart uploads with SHA-256 duplicate detection and resume checkpoints.

#### Digilekh — Document Intelligence & Audit Automation
* Engineered a 9-stage Celery ingestion pipeline incorporating Surya OCR, chunking algorithms, and hybrid dense/sparse vector indexing in Qdrant.
* Led a non-blocking asynchronous migration across 3 core microservices using SQLAlchemy 2.0 (asyncpg), aioboto3, and httpx.
* Integrated self-hosted Faster-Whisper (STT) and Kokoro-82M (TTS) microservices with TTL caching for low-latency speech pipelines.

#### ArchiveLens — Historical Document Layout Segmentation & Search
* Built an end-to-end processing pipeline cutting scanned Hindi newspaper pages into individual articles using polygon refinement and Surya OCR on vLLM.
* Implemented OCR hallucination defence using zlib compression ratio checks (<0.06) and temperature escalation.
* Configured an OpenSearch index featuring ICU transliteration and custom Hindi analyzers.

---

### Open Source & Public Repositories

| Repository | Focus Area | Technology Stack |
| :--- | :--- | :--- |
| [kokoro-tts](https://github.com/Sourabh0141/kokoro-tts) | Self-hosted, containerized Text-to-Speech API with interactive playground | Python, FastAPI, Kokoro TTS, Docker |
| [speech-to-text](https://github.com/Sourabh0141/speech-to-text) | Speech recognition service with WebSocket streaming and batch endpoints | Python, Faster-Whisper, WebSockets |
| [flare](https://github.com/Sourabh0141/flare) | Edge-native real-time conversational voice companion | TypeScript, Cloudflare Workers, WebRTC |
| [portfolio](https://github.com/Sourabh0141/portfolio) | Statically generated developer portfolio with strict CSP and zero runtime overhead | Astro, TypeScript, Vanilla CSS, Cloudflare Pages |

---

### Technical Proficiency Matrix

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Applied AI & ML** | vLLM, Surya OCR, SAM 2.1, YOLO11x, BoT-SORT, Faster-Whisper, Kokoro TTS, Qdrant, LangGraph, RAG |
| **Backend & APIs** | FastAPI, SQLAlchemy (Asyncpg), Celery, Pydantic v2, Hono, Uvicorn, REST, JWT, OAuth2 |
| **Messaging & Streaming** | RabbitMQ (Web-STOMP), MQTT (EMQX / Web-MQTT), WebSockets, Server-Sent Events, aio-pika |
| **Data & Storage** | PostgreSQL, Redis, BigQuery, OpenSearch, MinIO, AWS S3 (aioboto3), DynamoDB, Cloudflare D1 |
| **Cloud & DevOps** | Google Cloud (Functions, Workflows), AWS (CDK, Lambda, S3, Cognito), Cloudflare Pages/Workers, Docker, Linux, Terraform |
| **Testing & CI/CD** | Pytest, Vitest, Playwright, GitHub Actions, ESLint, Prettier |

---

### Education & Credentials

* **Bachelor of Computer Applications (BCA)**  
  SSG Pareek College, University of Rajasthan (2022 – 2025) · Jaipur, India

---

### Contact & Collaboration

* **Email**: sourabh.sharma0141@gmail.com
* **Portfolio**: [https://sourabh.pages.dev](https://sourabh.pages.dev)
* **LinkedIn**: [linkedin.com/in/sourabh-sharma-3221932b5](https://www.linkedin.com/in/sourabh-sharma-3221932b5/)
* **Location**: Jaipur, Rajasthan, India (UTC +05:30)
