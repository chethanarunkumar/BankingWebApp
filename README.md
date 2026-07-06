# 🏦 Banking Web Application

A full-stack **Banking Web Application** built using **Spring Boot, Java 17, and Maven**. This project demonstrates CRUD operations for bank accounts and showcases a complete **DevOps CI/CD pipeline** using **Docker, Jenkins, and Kubernetes** for automated deployment.

---

## 📌 Project Overview

The Banking Web Application enables users to perform essential banking operations through REST APIs and a user-friendly web interface. The application is containerized using Docker and deployed to Kubernetes via an automated Jenkins CI/CD pipeline.

### Key Learning Areas

- Spring Boot REST API Development
- Java 17 & Maven
- Docker Containerization
- Jenkins CI/CD Pipeline
- Kubernetes Deployment
- Git & GitHub Version Control

---

## 🚀 Features

- ✅ Create Bank Account
- ✅ View All Accounts
- ✅ View Account by ID
- ✅ Update Account Details
- ✅ Delete Account
- ✅ RESTful APIs
- ✅ Responsive Web Interface
- ✅ Dockerized Application
- ✅ Automated Jenkins CI/CD Pipeline
- ✅ Kubernetes Deployment

---

## 🛠️ Tech Stack

### Backend
- Java 17
- Spring Boot 2.7.4
- Spring Data JPA
- Spring Web
- Maven

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap

### DevOps
- Git
- GitHub
- Docker
- Jenkins
- Kubernetes

---

## 📂 Project Structure

```
BankingWebApp/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/project/banking/
│   │   │       ├── Account.java
│   │   │       ├── AccountController.java
│   │   │       ├── AccountRepository.java
│   │   │       ├── AccountService.java
│   │   │       └── BankingApplication.java
│   │   │
│   │   └── resources/
│   │       ├── application.properties
│   │       └── static/
│   │           ├── index.html
│   │           ├── style.css
│   │           └── script.js
│
├── Dockerfile
├── Jenkinsfile
├── bankingdeploy.yaml
├── pom.xml
└── README.md
```

---

## ⚙️ Prerequisites

Before running this project, ensure you have installed:

- Java 17
- Maven
- Git
- Docker
- Jenkins
- Kubernetes 

---

## 📥 Clone the Repository

```bash
git clone https://github.com/chethanarunkumar/BankingWebApp.git

cd BankingWebApp
```

---

## 🔨 Build the Project

```bash
mvn clean install
```

or

```bash
mvn clean package
```

---

## ▶️ Run the Application

### Using Maven

```bash
mvn spring-boot:run
```

### Using JAR File

```bash
java -jar target/*.jar
```

Open your browser:

```
http://localhost:8082
```

---

# 🐳 Docker

### Build Docker Image

```bash
docker build -t bankingwebapp .
```

### Verify Image

```bash
docker images
```

### Run Container

```bash
docker run -d -p 8082:8082 bankingwebapp
```

### Verify Running Containers

```bash
docker ps
```

Application URL:

```
http://localhost:8082
```

---

# ☸️ Kubernetes Deployment

### Deploy Application

```bash
kubectl apply -f bankingdeploy.yaml
```

### Check Pods

```bash
kubectl get pods
```

### Check Deployments

```bash
kubectl get deployments
```

### Check Services

```bash
kubectl get svc
```

### Describe Deployment

```bash
kubectl describe deployment bankingapp-deploy
```

### Delete Deployment

```bash
kubectl delete -f bankingdeploy.yaml
```

---

# 🔄 Jenkins CI/CD Pipeline

The application follows an automated CI/CD workflow using Jenkins.

### Pipeline Stages

- Source Code Checkout from GitHub
- Maven Build
- Unit Testing
- Docker Image Build
- Push Docker Image to Docker Hub
- Kubernetes Deployment

---

# 📡 REST API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/` | Home Page |
| GET | `/accounts` | Retrieve All Accounts |
| GET | `/accounts/{id}` | Retrieve Account by ID |
| POST | `/accounts` | Create New Account |
| PUT | `/accounts/{id}` | Update Existing Account |
| DELETE | `/accounts/{id}` | Delete Account |

---

# 💻 DevOps Workflow

```
Developer
     │
     ▼
GitHub Repository
     │
     ▼
Jenkins Pipeline
     │
     ▼
Maven Build
     │
     ▼
Docker Image Build
     │
     ▼
Docker Hub
     │
     ▼
Kubernetes Deployment
     │
     ▼
Banking Web Application
```

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Spring Boot Development
- RESTful API Design
- CRUD Operations
- Maven Build Automation
- Docker Containerization
- Jenkins CI/CD Automation
- Kubernetes Deployment
- Git & GitHub Version Control


---
# 👨‍💻 Author

**Chethan B A**
---

# 📄 License

This project is intended for educational and learning purposes.

Feel free to fork, modify, and enhance the project.
