# Docker Node Demo

This is a simple Node.js application using Express. It's a minimal app created manually to learn Docker and containerization.

---

## 🛠️ Prerequisites

- Docker (no need for Node.js locally if using Docker)

---

## 📁 Project Structure

docker-node-demo/
├── Dockerfile
├── index.js
├── package.json
└── README.md

---

## 📦 How to Run Locally (Optional)

If you want to run without Docker:

$ npm install
$ npm start

Then visit: http://localhost:8080

---

## 🐳 Running with Docker

# 1. Build the Docker image
$ docker build -t docker-node-demo .

# 2. Run the container
$ docker run -p 8080:8080 docker-node-demo

Then visit: http://localhost:8080

---

## ✅ Expected Output

When you visit the app in the browser, it will display:

Hi there

---

## 📄 License

MIT — free to use for learning or creating your own projects.
