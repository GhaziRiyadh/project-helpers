# 🚀 Dev Helper Stack

This repository provides a **universal Docker development stack** with commonly used databases and caching tools.  
It’s designed as a **developer helper toolbox** — not tied to a single project, but available system-wide.  

## 🛠 Services

| Service      | Port | UI / Tool |
|--------------|------|------------|
| MariaDB      | 3306 | phpMyAdmin → http://localhost:8080 |
| PostgreSQL   | 5432 | Adminer → http://localhost:8081 |
| Redis        | 6379 | CLI / clients |
| Memcached    | 11211| CLI / clients |

---

## 📦 Setup

1. Install **Docker** and **Docker Compose**.
2. Clone this repo (or copy `docker-compose.yml` & `README.md`).
3. Start the stack:

   ```bash
   docker compose up -d
