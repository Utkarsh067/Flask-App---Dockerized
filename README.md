# 🐳 Flask App - Dockerized

This project is a simple Flask web application that displays a welcome message. The app is containerised using Docker and runs on `localhost`.

## 📌 Project Overview

- Built with Python and Flask
- Dockerized for easy deployment and portability
- Runs on `localhost:5000` by default
- Great starting point for learning Docker + Flask

---

## 🗂️ Project Structure
```
flask-docker-app/
│
├── README.md 
├── app.py
├── dockerfile
└── requirements.txt
```

--- 

## ⚙️ Prerequisites

Make sure you have Docker installed on your system.

👉 [Download Docker Desktop](https://www.docker.com/products/docker-desktop)

To verify installation:

```
docker --version
```

## 🚀 Getting Started

### 1️⃣ Login to Docker using CLI

```
docker login
```

### 2️⃣ Clone the Repository

```
git clone https://github.com/your-username/flask-docker-app.git
cd flask-docker-app
```

### 3️⃣ Build the Docker Image

```
docker build -t flask-docker-app .
```

### 4️⃣ Run the Container

```
docker run -p 8080:5000 flask-docker-app
```
**🔧 Note:** Replace 8080 with your desired port if needed.
The format is ``` -p <host_port>:<container_port>. ```

### Open your browser and go to ```http://localhost:<Host_port>``` to see the app running!
