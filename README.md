This repository contains my hands-on DevOps implementation using:

- VMware Workstation
- Ubuntu Server
- Docker
- Git & GitHub
- Jenkins CI/CD Pipeline
---

## 📂 Project Structure

jenkins/
│
├── Dockerfile
├── index.html
├── Jenkinsfile
└── README.md


---

## 🖥️ Environment Setup

### 🔹 VMware
- Installed VMware Workstation
- Created Ubuntu Server VM
- Configured NAT networking

### 🔹 Ubuntu Configuration
- System update & upgrade
- Installed OpenSSH
- Configured firewall

---

## 🐳 Docker Implementation

✔ Installed Docker  
✔ Built Docker image  
✔ Created Nginx container  
✔ Port mapping (5000/5001 → 80)  
✔ Container lifecycle management  

---

## 🔀 Git & GitHub

✔ SSH authentication setup  
✔ Branch management  
✔ Repository structuring  
✔ Code version control  

---

## ⚙️ Jenkins CI/CD (Day 4)

✔ Installed OpenJDK 21  
✔ Installed Jenkins  
✔ Configured Pipeline  
✔ Integrated GitHub repository  
✔ Automated Docker build & deployment  

---

## 🧪 CI/CD Pipeline Flow

1️⃣ Jenkins pulls code from GitHub  
2️⃣ Docker image is built  
3️⃣ Old container is stopped & removed  
4️⃣ New container is deployed  
5️⃣ Website runs automatically  

---

## 🌐 Application Access

After successful pipeline build:

http://<your-server-ip>:5000


Example:
http://192.168.117.128:5000


---

## 🎯 Learning Outcomes

- Linux command proficiency  
- Docker image & container lifecycle  
- Git branching strategy  
- Jenkins pipeline automation  
- CI/CD workflow understanding  

---


## 📌 Status

This project is actively maintained as part of my DevOps learning journey.
