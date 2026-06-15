# NGINX + Docker Learning Project

This project is a hands-on learning setup to understand how modern web applications are deployed using **Node.js, Docker, and NGINX**.

---

## 📌 What I Learned

### 🟢 Node.js Basics
- Created a simple Express server
- Served static files (HTML, images)
- Understood routing and request handling

---

### 🐳 Docker Basics
- Created a Dockerfile for Node.js app
- Learned how to build Docker images
- Ran multiple containers with different ports
- Understood container isolation and port mapping

Commands used:
```bash
docker build -t myapp .
docker run -p 3000:3000 myapp
docker ps
