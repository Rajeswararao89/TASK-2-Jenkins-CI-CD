🛠️ Task 2 - Jenkins CI/CD Pipeline for Flask App Deployment
📋 Project Overview
This project demonstrates a CI/CD pipeline using Jenkins to automate the build and deployment of a simple Flask-based REST API inside a Docker container on AWS EC2.

The pipeline pulls source code from GitHub, builds a Docker image, and deploys the app automatically.

🚀 Tech Stack & Tools
Tool	               Purpose
Jenkins	             CI/CD automation
Docker	             Containerization of the app
Flask	               Python web framework (REST API)
SQLAlchemy	         ORM for database operations
GitHub	             Source code repository
AWS EC2	             Server to host Jenkins & Docker

🛠️ Project Structure

TASK-2-Jenkins-CI-CD/
├── app/
│   ├── app.py
│   └── models.py
├── Dockerfile
├── Jenkinsfile
├── requirements.txt
├── README.md
└── screenshots/
    ├── pipeline-success.png
    ├── console-output.png
    ├── app-running.png
    └── docker-ps.png
🧱 Pipeline Flow (Jenkinsfile)
Checkout Code from GitHub

Build Docker Image for Flask App

Deploy Docker Container

Access app via EC2 Public IP at /tasks

✅ Application Endpoint
Method	             Endpoint	              Description
GET	                 /tasks	                Get all tasks (JSON)
POST	               /tasks	                Add new task (JSON)


📦 Final Output
✅ Flask API containerized & deployed

✅ CI/CD pipeline automated with Jenkins

✅ Accessible on public IP:5000/tasks

✍️ Author
Rajeswara Rao
