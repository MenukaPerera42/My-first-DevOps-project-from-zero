
# 🚀 CI/CD Pipeline with Docker & GitHub Actions


## 📌 Project Overview

This project demonstrates a **complete DevOps CI/CD pipeline** built **from zero** using real-world tools and best practices.

The pipeline automatically:
- 🔧 Builds a Docker image from a Node.js application  
- 📦 Pushes the image to Docker Hub  
- ⚙️ Runs automatically on every push to the `main` branch using GitHub Actions  

This project focuses on **automation, containerization, and CI/CD fundamentals**.

---

## 🛠️ Tech Stack

| Category | Tools | 
|--------|------|
| Programming | Node.js |
| Containerization | Docker |
| CI/CD | GitHub Actions |
| Version Control | Git, GitHub |
| Image Registry | Docker Hub |
| OS | macOS |

---

## 📂 Project Structure

My-first-DevOps-project-from-zero/                                
│
├── app/                                 
│ ├── server.js # Node.js application                                 
│ ├── Dockerfile # Docker image configuration                                 
│ └── app.txt # Sample project file                                 
│                                                                 
├── .github/                                 
│ └── workflows/                                 
│ └── ci.yml # GitHub Actions CI/CD pipeline                                 
│
└── README.md # Project documentation                                 

---

## 🔄 CI/CD Workflow Explanation

1️⃣ Developer pushes code to the `main` branch  
2️⃣ GitHub Actions workflow is triggered  
3️⃣ Docker image is built automatically  
4️⃣ Image is pushed to Docker Hub  
5️⃣ Application is ready to run anywhere  

---

## ▶️ Run the Application Locally

Pull and run the Docker image from Docker Hub:

```bash
docker run -p 3000:3000 menukaperera2001/hello-devops:latest
```                   
Then open your browser:                    
http://localhost:3000

Expected output:                                      
Hello DevOps 🚀 App is running!

---

## 🔐 Security & Secrets Management

* Docker Hub credentials are stored securely using **GitHub Secrets**
* Authentication uses **Docker Hub access tokens**
* No secrets are hardcoded in the repository

---

## 🧪 What I Learned

* ✔️ Docker image creation and optimization
* ✔️ CI/CD pipeline creation using GitHub Actions
* ✔️ Docker Hub authentication and image publishing
* ✔️ Secure secrets management
* ✔️ Debugging real CI/CD permission issues

---

## 🎯 Why This Project Matters

This project reflects **real DevOps work**, not tutorials:

* Automated pipelines
* Secure credentials
* Production-style workflows
* Debugging real failures

It is suitable for:

* Junior DevOps Engineer roles
* Cloud Engineer roles
* Internship & entry-level DevOps positions

---

## 🚀 Future Improvements

* ☸️ Kubernetes deployment (Minikube / EKS)
* ☁️ Cloud deployment (AWS / Azure)
* 📊 Monitoring & logging
* 🔒 DevSecOps security scanning
* 🔄 Multi-environment pipelines (dev / prod)

---

## 👨‍💻 Author

**Menuka Perera**
GitHub: [https://github.com/MenukaPerera42](https://github.com/MenukaPerera42)        
Docker Hub: [https://hub.docker.com/u/menukaperera2001](https://hub.docker.com/u/menukaperera2001)

---
