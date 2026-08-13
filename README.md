👋 Hi, I'm Ayan Ahmad
💻 Backend-Focused Full-Stack Developer | Node.js · Distributed Systems · AI-Powered Tooling
---
🧭 About Me
I'm a Computer Science and Engineering graduate focused on backend development and scalable system design.
My core strength is building production-style backend systems — REST and async APIs, job queues, caching layers, and now AI-driven pipelines. Recently I've been going deeper into system design fundamentals: distributed rate limiting with Redis + Lua, background job processing with BullMQ, and integrating LLM/RAG pipelines (LangGraph, vector search) into real developer tooling.
Alongside backend work, I build React.js frontends to ship complete, end-to-end products rather than isolated APIs.
I prefer writing code that's modular, readable, and easy to maintain, and I learn best by building and shipping real projects — including deploying and testing them in production-like conditions (Docker, CI/CD, real cloud infra).
---
🛠️ Skills & Technologies
💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

🧠 Core Programming
C++: Data Structures & Algorithms
JavaScript (ES6+): Primary language across the stack

⚙️ Backend Development (Main Focus)
Node.js & Express.js: REST + async APIs, middleware, authentication, error handling
Distributed systems: Redis + Lua for atomic rate limiting, BullMQ for background job queues, Socket.io + Redis Pub/Sub for real-time updates across services
AI/LLM infra: RAG pipelines with vector search (Pinecone), multi-agent orchestration with LangGraph, LLM provider integration (Gemini, Groq)
Databases: MongoDB (schema design, aggregation), MySQL (relational design, query optimization)
Authentication: Passport.js (OAuth strategies), JWT with Redis-backed session revocation, API-key auth for public APIs
Architecture: MVC pattern, multi-tenant scoping, modular services, containerized (Docker) deployments

🎨 Frontend Development
React.js: Hooks, state management, API integration, real-time UI via Socket.io
Tailwind CSS / Bootstrap: Responsive, clean UI

🧰 Tools & Workflow
Docker & Docker Compose: Multi-service local dev and deployment
CI/CD: GitHub Actions integration for automated checks
AWS (EC2) / GCP: Cloud deployment
Git & GitHub, Postman: Version control and API testing
---
🚀 Featured Projects
🤖 CodeSense AI — AI Code Review Platform
An AI-powered GitHub PR review tool that combines RAG and multi-agent orchestration to give context-aware code reviews, plus a public CI/CD API for automated review gating.
Tech Stack: Node.js · Express · BullMQ · Redis · MongoDB · LangGraph · Pinecone (RAG) · React · Docker · GitHub Actions
Key Features:
Multi-agent review pipeline (LangGraph): diffs are classified, then routed in parallel to security/logic/style review agents, with deduplicated, severity-scored findings
RAG pipeline over the full repo (semantic chunking + Pinecone vector search) for context-aware reviews, not just diff-only analysis
Public CI/CD API (API-key auth, async job submission + polling) that integrates directly into GitHub Actions as a required status check
Real-time updates via Socket.io + Redis Pub/Sub across the web dashboard and background worker
Multi-tenant, GitHub OAuth-secured, deployed on Docker with AWS EC2

⚡ Distributed Rate Limiter as a Service — `rate-limiter-node`
A backend-systems-focused project implementing rate limiting as a standalone service, built to demonstrate distributed-systems depth.
Tech Stack: Node.js · Redis · Lua (atomic scripts) · Jest · React
Key Features:
Token Bucket, Sliding Window, and Fixed Window algorithms, all implemented with atomic Redis + Lua operations
Real-time React dashboard for visualizing limiter state
Full Jest test coverage

🏙️ UrbanNest – Online Property Listing Platform
A complete real-estate platform for listing, searching, and booking properties.
Tech Stack: MongoDB · Express.js · Node.js · EJS · Bootstrap
Key Features:
Multi-strategy authentication (Passport.js + Google OAuth), role-based access
Cloudinary for image handling, Mapbox for location features
RESTful CRUD APIs with centralized error handling and clean MVC structure
---
📈 Focus & Learning Path
Backend architecture depth: distributed systems, queues, caching, real-time infra
AI-era backend tooling: RAG pipelines, multi-agent LLM orchestration, provider-agnostic LLM integration
DevOps: Docker, CI/CD pipelines, cloud deployment (AWS/GCP)
Strengthening DSA and CS fundamentals (OS, DBMS, CN) for interviews
---
🔗 Connect With Me
GitHub: github.com/ayanah24
LinkedIn: linkedin.com/in/ayan-ahmad-464528214
Email: ayan27452@gmail.com
X (Twitter): x.com/ayan27452
---
📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=ayanah24&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=ayanah24&theme=tokyonight&hide_border=true)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=ayanah24&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&layout=compact)


