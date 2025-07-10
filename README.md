# 📝 Full-Stack To-Do List App with FastAPI 🚀 Streamlit 🎨 Docker 🐳

[![Dockerized](https://img.shields.io/badge/Dockerized-Yes-blue?logo=docker)](https://hub.docker.com/)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?logo=fastapi)](https://fastapi.tiangolo.com/)
[![Streamlit](https://img.shields.io/badge/Frontend-Streamlit-ff4b4b?logo=streamlit)](https://streamlit.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)](https://python.org/)

> 🚀 Build and deploy a complete **To-Do List Web App** with **FastAPI (backend)**, **Streamlit (frontend)**, and **Docker** — all backed by a simple and secure `JSON` file as a local database.  
> ✅ SEO keywords: `fastapi todo app`, `streamlit todo list`, `fastapi json database`, `docker fastapi project`, `todo list python`, `fastapi streamlit example`.

---

## 🖼️ Live Demo

> Coming Soon! *(You can deploy to [Render](https://render.com/), [Railway](https://railway.app/), or [Fly.io](https://fly.io/))*  
📸 Screenshots and demo video will be added.

---

## 📦 Features

- 🔄 Full **CRUD operations**
- 💾 Uses `todo.json` file as a **JSON-based lightweight database**
- 🎨 Beautiful, interactive frontend built with **Streamlit**
- ⚡ Ultra-fast and modern API with **FastAPI**
- 🔐 Secure schema validation via **Pydantic v2**
- 🐳 Fully **Dockerized** for easy cross-platform deployment

---

## ⚙️ Project Stack

| Layer      | Technology |
|------------|------------|
| Backend    | [FastAPI](https://fastapi.tiangolo.com/) |
| Frontend   | [Streamlit](https://streamlit.io/) |
| Database   | JSON File (no SQL needed) |
| DevOps     | [Docker](https://www.docker.com/) |
| Validation | [Pydantic v2](https://docs.pydantic.dev/) |

---

## 🧠 How It Works

```mermaid
graph LR
  A[Docker Image] --> B[Docker Container]
  B --> C[FastAPI Server]
  C -->|HTTP| D[Streamlit UI]
  C --> E[todo.json]


