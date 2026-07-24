# Sai Swayam Pradhan

Backend/distributed systems engineer (B.Tech CSE, VIT Chennai) building AI/ML-powered systems end-to-end.
Skilled in Java, Python, and C.

## About Me

I'm a Computer Science undergrad at VIT Chennai who builds software end-to-end — from distributed backend infrastructure to the ML systems that run on top of it. My core interest is backend/distributed systems (queues, concurrency, crash recovery — see Task Orchestration System below), and I apply the same rigor to ML: retrieval pipelines, fine-tuned transformers, semantic search. Currently sharpening DSA and systems fundamentals. Outside of code, I sing and do photography.

---

## Projects

### [Distributed Task Orchestration System](https://github.com/saiswayam2027/Distributed-Task-Orchestration-System) *(Java, Spring Boot, Redis, PostgreSQL, Docker)*
A from-scratch reimplementation of the core of AWS SQS / Celery: an at-least-once distributed task queue with atomic Lua-scripted dequeue, visibility timeouts with crash recovery, exponential backoff with full jitter, and a durable PostgreSQL audit trail alongside Redis-backed queue state.

### [Adaptive RAG System](https://github.com/saiswayam2027/Adaptive-RAG-System) *(Python, BM25, Sentence-Transformers, Streamlit)*
Adaptive RAG pipeline with hybrid BM25 + dense retrieval (RRF fusion), a query router that refuses out-of-scope questions and decomposes multi-hop ones, re-ranking, and post-generation hallucination checking. Verified on a 16-document adversarial eval corpus across two embedding backends: 100% hybrid retrieval hit@5, 96% routing accuracy.

### [GitHub Profile Analyzer](https://github.com/saiswayam2027/Github-Profile-Analyzer) *(Python, Requests, Matplotlib, Jupyter Notebook)*
Fetches and analyzes GitHub user activity via the GitHub API, surfacing repository stats, most-used languages, and activity trends through clean visualizations.

### [Semantic Search System](https://github.com/saiswayam2027/semantic-search-system) *(Python, FastAPI, SentenceTransformers, Scikit-learn, Docker)*
A semantic search API that embeds queries with SentenceTransformers, clusters them into topics via TF-IDF + NMF, and uses a cosine-similarity cache to return results for semantically similar queries — served through FastAPI and containerized with Docker.

### [Virtual Mouse & Keyboard](https://github.com/saiswayam2027/Vertual-mouse-and-keyboard) *(Python, OpenCV, MediaPipe Hands)*
Gesture-controlled system with three modes — mouse control, an on-screen virtual keyboard, and a drawing canvas — driven entirely by webcam hand tracking, with gesture shortcuts for mode switching, screenshots, and scrolling.

### [Emotion Detection ML](https://github.com/saiswayam2027/Emotion-detection-ML) *(Python, PyTorch, Transformers, BERT, Scikit-learn)*
Detects emotions in short, informal text such as tweets and comments using a fine-tuned BERT-based transformer, with a dedicated cleaning pipeline to handle emojis and noisy text before training.

---

## Contact

Email: saiswayam1919@gmail.com
LinkedIn: https://www.linkedin.com/in/sai-swayam-pradhan/
Portfolio: https://saiswayam2027.github.io/
