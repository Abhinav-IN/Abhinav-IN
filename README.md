# Abhinav Kumar

Passionate about how systems work underneath the hood. Design decisions made early define everything downstream — and that is the part of engineering I find most important to get right.

Final year CS student at GTBIT, Delhi · Open to SDE roles

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhinav-kumar-001774298/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/abhinav__kumar10/)
[![Gmail](https://img.shields.io/badge/abhinavcode1015@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:abhinavcode1015@gmail.com)

---

## Projects

### [SoulSync](https://github.com/Abhinav-IN/soul-sync) — Dating Application
Polyrepo microservice architecture across 8 repositories. Users match based on music taste compatibility — match scores computed via Jaccard similarity on Spotify top artists and tracks. Services communicate asynchronously through Kafka so no service is tightly coupled to another.

- 7 independent NestJS backend services · React frontend
- API Gateway handles JWT validation, WebSocket upgrades, and cross-service aggregation
- Kafka topics: `profile.data.update` · `spotify.data.updated` · `user.matched`
- Spotify OAuth 2.0 with token rotation · Pre-computed recommendations via MongoDB
- Deployed on self-hosted VPS via Coolify

**NestJS · Kafka · MySQL (TiDB) · MongoDB Atlas · Cloudinary · Spotify API · React**

[![Architecture & README](https://img.shields.io/badge/Architecture%20%26%20README-6C63FF?style=flat-square&logo=github&logoColor=white)](https://github.com/Abhinav-IN/soul-sync)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-6C63FF?style=flat-square)](https://soulsync.manavkashyap.com/demo)

---

### [Fi-Track](https://github.com/Abhinav-IN/finance_tracker) — Personal Finance Tracker
Headless monolith with a FastAPI backend and Vanilla JS frontend. Tracks income, expenses, subscriptions, budgets, and investments — with a graphical dashboard and JWT authentication. Background email delivery via Celery workers keeps the API non-blocking.

- Auto-billing on subscriptions rolls charges into expenses automatically
- Async email jobs: account verification · password reset · subscription reminders
- Celery implemented in `main` branch · disabled in `deploy` branch to optimise VPS resource usage

**FastAPI · MySQL (TiDB) · Celery · Redis · Vanilla JS**

[![README](https://img.shields.io/badge/README-16A34A?style=flat-square&logo=github&logoColor=white)](https://github.com/Abhinav-IN/finance_tracker)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-16A34A?style=flat-square)](http://fi-track.manavkashyap.com)

---

## Skills

**Languages** — TypeScript · Python · JavaScript · Java

**Backend** — NestJS · FastAPI · REST APIs · JWT · WebSocket · Kafka · Celery

**Databases** — MySQL · MongoDB · Redis

**Infrastructure** — Docker · Linux · VPS · Coolify · Cloudinary
