# Hardeep Singh

AI Builder from IIT Delhi. I ship things.

---

## what I'm building

**[coffeecoach.app](https://coffeecoach.app)** — [coffee-coach](https://github.com/rav4nn/coffee-coach)  
A specialty coffee brewing companion. Log brews, get coaching from Kapi (an AI coach), dial in your technique. 3,000+ bean catalog with freshness tracking, a two-layer coaching system (recipe-diff for beginners → sensory coaching from cup ratings and flavor notes), and a full brew journal. 150+ commits in. Live.  
`Next.js 15` `React 19` `FastAPI` `PostgreSQL` `Vercel + Hetzner` `Docker`

**[FluxRAG](https://github.com/rav4nn/flux-rag)** — universal ingestion-to-evaluation RAG pipeline  
Built as the RAG backend for Coffee Coach — but designed to be domain-agnostic. Drop in any file type (PDF, YouTube URL, audio, images, HTML) and get a benchmarked knowledge base with documented quality scores. The key idea: build the evaluation harness first, then optimise against it. Every chunking strategy, embedding model, reranker, and LLM is benchmarked on the same QA test set before anything ships.  
`Python` `RAGAS` `ChromaDB` `Qdrant` `FastAPI` `Docker` `spaCy` `sentence-transformers`

**[youtube-rag-scraper](https://github.com/rav4nn/youtube-rag-scraper)** ⭐ 44  
Production-grade CLI: YouTube channel → transcripts → FAISS vector index → semantic search. Parallel downloads, resume support, multi-format export (JSON/JSONL/CSV/Parquet). Built to index specialty coffee content; now used by others building domain-specific knowledge bases.  
`Python` `FAISS` `sentence-transformers` `yt-dlp` `YouTube Data API`

**[grandma-proof](https://github.com/rav4nn/grandma-proof)**  
An AI agent that browses your site as a confused first-time user, then produces a structured UX report: confusion points, drop-off risk scores, actionable recommendations. Multi-provider LLM support (OpenAI, Gemini, DeepSeek) via a FastAPI + Playwright backend.  
`Python` `FastAPI` `Playwright` `OpenAI / Gemini / DeepSeek`

---

## what I care about

RAG pipelines that actually get evaluated before shipping. AI products built around real domain data, not demos. Full-stack ownership — frontend, backend, infra, and the AI layer.

---

## stack

`Python` `FastAPI` `Next.js` `TypeScript` `PostgreSQL` `Docker`  
`RAG / FAISS / ChromaDB / Qdrant` `sentence-transformers` `RAGAS`  
`LLM APIs` `Nginx` `Hetzner` `Vercel` `Cloudflare`

---

## open to

AI/ML engineering roles at early-stage startups in India. Small, fast-moving teams building real products.
