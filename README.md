# 📝 Flask To-Do List App

A simple Flask-based To-Do list web application with Docker support.

## 🚀 Features

- Add, toggle, and delete tasks
- Runs in a container using Docker
- Lightweight and easy to deploy

## 🛠️ Setup

### Run Locally

```bash
pip install -r requirements.txt
python app.py
```
Open your browser at http://localhost:5000

🐳 Run with Docker(optional)
```bash
docker build -t todo-app .
```
```bash
docker run -p 5000:5000 todo-app
```
Run with docker-compose.yaml
```bash
docker compose up --build
```
