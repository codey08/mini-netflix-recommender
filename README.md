# mini-netflix-recommender

# 🎬 Mini-Netflix Recommender

A **content-based movie recommendation system** built with **FastAPI (backend)** and **Next.js (frontend)**.  
This project demonstrates full-stack skills: **data ingestion → ML model → API → frontend → Docker + CI/CD → deployment**.

---

## 🚀 Problem Statement
Netflix and similar platforms rely on **recommendation systems** to keep users engaged.  
This project replicates a **simplified version** of that idea:

- Users can **search movies**
- View **details & genres**
- Get **content-based recommendations** using **TF-IDF + cosine similarity**
- Save movies to a **watchlist** (demo, no auth)

The goal is to demonstrate:
- **Data preprocessing**
- **ML model integration with APIs**
- **Modern full-stack deployment**
- **Clean engineering practices (CI, Docker, modular code)**

---

## 📂 Tech Stack
- **Backend**: FastAPI, scikit-learn, pandas, SQLite  
- **Frontend**: Next.js (React), Tailwind CSS (optional)  
- **Infrastructure**: Docker, GitHub Actions CI, Vercel (frontend), Render/Railway (backend)

---

## 📊 Roadmap Checklist

### ✅ Phase 1: Core MVP
- [x] Load **MovieLens dataset** (`movies.csv`)
- [x] Build **TF-IDF similarity recommender**
- [x] Expose API endpoints:
  - `/search?q=…`
  - `/movies/{id}`
  - `/recommend/{id}`
  - `/watchlist`
- [x] Minimal frontend (search + movie detail + recommendations)
- [x] Watchlist (local demo or SQLite)

### 🔜 Phase 2: Improvements
- [ ] Add posters via TMDb API
- [ ] Collaborative filtering model (user-user similarity)
- [ ] User authentication + persistent watchlist
- [ ] Add pagination + filters (genre/year)
- [ ] Better UI with Tailwind & shadcn/ui
- [ ] Add analytics dashboard (request latency, popular movies)

### 🎯 Phase 3: Production-ready
- [ ] CI/CD pipeline (lint, tests, build)
- [ ] Dockerize backend & frontend
- [ ] Deploy backend (Render/Railway) + frontend (Vercel)
- [ ] Add monitoring/logging
- [ ] Write blog post + demo video

---

## ⚡ Quickstart

### 1. Clone repo
```bash
git clone https://github.com/YOURNAME/mini-netflix-recommender.git
cd mini-netflix-recommender
