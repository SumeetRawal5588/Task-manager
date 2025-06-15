# 📝 Task Manager App with Full DevOps Lifecycle

This is a full-stack **Task Management App** built using **Node.js** and **Vanilla JS**, styled with custom CSS.  
It is containerized using **Docker**, automated via **Jenkins**, deployed on an **Azure VM**, and monitored using **Prometheus + Grafana**.

---

## 🧱 Tech Stack

| Layer         | Tools / Tech                      |
|--------------|-----------------------------------|
| Frontend     | HTML, CSS (Dark Theme), JS        |
| Backend      | Node.js, Express.js               |
| Database     | MongoDB                           |
| DevOps       | Docker, DockerHub, Jenkins        |
| Deployment   | Azure VM (Ubuntu)                 |
| IaC          | Shell Scripts / Terraform         |
| Monitoring   | Node Exporter, Prometheus, Grafana|

---

## 📂 Project Structure

task-manager-devops/
├── frontend/
│ └── index.html
├── server.js
├── package.json
├── Dockerfile
├── docker-compose.yml
├── jenkins/
│ └── Jenkinsfile
├── scripts/
│ └── deploy.sh
├── monitoring/
│ ├── prometheus.yml
│ └── grafana/
├── .gitignore
└── README.md

yaml
Copy
Edit

---

## 🚀 How to Run Locally

### 1. Clone the repo

```bash
git clone https://github.com/<your-username>/task-manager-devops.git
cd task-manager-devops

2. Install dependencies
bash
Copy
Edit
npm install


3. Start Backend
bash
Copy
Edit
node server.js


4. Open Frontend
Just open frontend/index.html in browser or use Live Server.

🐳 Run with Docker
bash
Copy
Edit
docker build -t task-manager-app .
docker run -p 3000:3000 task-manager-app


⚙️ CI/CD Pipeline
GitHub → Jenkins (pull latest code)

Build Docker image

Push to DockerHub

SSH into Azure VM

Pull & Restart container


📊 Monitoring Stack
Node Exporter for metrics

Prometheus to collect metrics

Grafana dashboards to visualize


📌 Features
Add, List, Delete Tasks

Fully responsive UI

REST API with error handling

Dockerized for portability

Auto-deployed via Jenkins

Infra-as-Code setup scripts


🙌 Author
Sumeet Rawal
DevOps Enthusiast | QA Engineer → DevOps Transition

