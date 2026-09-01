### Hi, I'm Arti 👋

Software Engineer — React, Next.js, Node.js, TypeScript, Python, Java
Building **StudySprout**, a Notion-style collaborative learning workspace with real-time editing, AI-generated flashcards, and automatic concept mapping — built solo, end to end.

🔭 Currently building: [StudySprout](https://studysprouts.in)
🌱 Open to: Software Engineer roles at product companies
📫 Reach me: artigaund2210@gmail.com
🔗 Portfolio: [artigaund-portfolio.vercel.app](https://artigaund-portfolio.vercel.app/)

---

### 🛠️ Tech Stack

`TypeScript` `JavaScript` `React` `Next.js` `Node.js` `Java` `Python` `MongoDB` `Redis` `Socket.io` `BullMQ` `Yjs` `Django` `React Native` `Kotlin`

---

### 💡 Featured Project — StudySprout

A collaborative workspace for learning: write notes directly or drop in a PDF, and either way get AI-generated flashcards, spaced repetition, and automatic concept mapping. Built solo across four services in three repos.

- **Real-time collaboration** — multiple users editing the same file at once, conflict-free, via Yjs CRDTs synced over Socket.io
- **Custom PDF pipeline** (Python: pdfplumber, pikepdf, PyMuPDF) that parses structure — headings, tables, math zones — and splits one PDF into multiple topic-scoped files, instead of just dumping raw text
- **Concept graphs & prerequisite detection** — zero-LLM, term-index-based, visualized with D3
- **AI flashcards** (Gemini) with SM-2 spaced repetition, six question formats (Q&A, Cloze, MCQ, Concept Diagram, Chart-based, Image Labeling)
- **Browser Clipper extension** — capture content from any webpage into a private inbox, then merge it into any file through the same live Yjs pipeline as collaborative edits
- **Standalone Java rate-limiter** (token bucket, Redis/Lua) guarding Gemini API calls from abuse

| Repo | What it is |
|---|---|
| [`studysprout`](https://github.com/ArtiGaund/studysprout) | Main app — Next.js frontend, API routes, background workers, PDF pipeline |
| [`studysprout-realtime-server`](https://github.com/ArtiGaund/studysprout-realtime-server) | Socket.io + Yjs collaboration server, presence, generation/title locks |
| [`rate-limiter`](https://github.com/ArtiGaund/rate-limiter) | Standalone Java token-bucket rate limiter for the Gemini API |
| [`studysprout-clipper`](https://github.com/ArtiGaund/studysprout-clipper) | Chrome extension (Manifest V3) for capturing web content into the Inbox |

**[Live](https://studysprouts.in)** · **[Full README with architecture diagrams](https://github.com/ArtiGaund/studysprout)**

---

### 🌍 Open Source — GirlScript Summer of Code 2024

- **[Item detail screen feature](https://github.com/sourabhkumar47/ResQFood/pull/89)** — ResQFood — built and shipped a new screen end to end, merged
- **[Cross-page build error fix](https://github.com/Trisha-tech/OnlineBookSales/pull/106)** — resolved a navbar/footer rendering bug across all pages, merged
- **[Page navigation routing](https://github.com/Trisha-tech/OnlineBookSales/pull/63)** — merged
- **[Navigation bar component](https://github.com/Trisha-tech/OnlineBookSales/pull/24)** — merged

---

### 📦 Other Projects

- **[PersonaBlog](https://github.com/ArtiGaund/PersonaBlog)** — blogging platform, React + Redux Toolkit + Appwrite
- **Video Hosting Platform (backend)** — Node/Express, MongoDB, JWT auth, Cloudinary
- **TUBER** — Django-based marketplace
- **TSHIRT EXPRESS** — React/Django e-commerce
- **TRANSLATOR** — Android app, Firebase + Google ML Kit

---

### 📊 GitHub Stats

[![](https://github-readme-stats.vercel.app/api?username=ArtiGaund&theme=dark&hide_border=false&include_all_commits=true&count_private=true)](https://github.com/ArtiGaund)
[![](https://github-readme-stats.vercel.app/api/top-langs/?username=ArtiGaund&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)](https://github.com/ArtiGaund)
