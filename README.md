# Employee Management System (EMS) - AKS Full-Stack Deployment

## 📌 Project Overview
The **Employee Management System (EMS)** is a **full-stack application** deployed on **Azure Kubernetes Service (AKS)**.  
It demonstrates a **3-tier architecture** with:

- **Frontend:** React.js
- **Backend:** Spring Boot
- **Database:** MySQL
- **Deployment:** Kubernetes on AKS with LoadBalancer services

This project highlights **cloud-native deployment, containerization, and orchestration**, which are highly relevant for enterprise applications.

---

## 🏗️ Architecture
User
│
▼
Frontend (React.js) [LoadBalancer Service: 5173]
│
▼
Backend (Spring Boot) [LoadBalancer Service: 8081]
│
▼
Database (MySQL)
