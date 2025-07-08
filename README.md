My Auto-Deployed WebApp
This project contains a simple static site served by Nginx in Docker.

Features
✅ Static HTML/CSS/JS site
✅ Dockerized with Nginx
✅ CI/CD pipeline with Jenkins
✅ Deployed to AWS ECS Fargate

Build & Run Locally
docker build -t my-webapp .
docker run -p 8080:80 my-webapp
