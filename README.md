# Day1-Docker-Python# Day 1 — Dockerized Python Hello World

A simple Python application created as part of my **AI/ML Engineering Day 1 Environment & Tooling practice**.

The project demonstrates how to run a Python application locally and inside a Docker container.

## 🚀 Technologies

* Python 3.11
* Docker
* Git
* GitHub

## 📁 Project Structure

```text
Day1-Docker-Python/
│
├── .gitignore
├── Dockerfile
├── main.py
├── README.md
└── requirements.txt
```

## 🐍 Run Locally

Run the Python application:

```bash
python main.py
```

Expected output:

```text
Hello from Python!
This application is running successfully.
```

## 🐳 Build Docker Image

Build the Docker image:

```bash
docker build -t day1-python .
```

## ▶️ Run Docker Container

Run the application inside Docker:

```bash
docker run --rm day1-python
```

Expected output:

```text
Hello from Python!
This application is running successfully.
```

## 🧩 Dockerfile

The Dockerfile:

1. Uses the official Python 3.11 slim image.
2. Creates `/app` as the working directory.
3. Copies the Python application into the container.
4. Runs the Python application.

## 📚 What I Learned

* Python project structure
* Python virtual environments
* Git repository initialization
* Git add, commit, branch, and remote
* GitHub repository management
* Docker images and containers
* Writing a Dockerfile
* Building Docker images
* Running containers

## 🔗 GitHub

This project is available on my GitHub profile.
https://github.com/Muhammad-Khizer-Hayat/Day1-Docker-Python
 Muhammad Khizer Hayat
