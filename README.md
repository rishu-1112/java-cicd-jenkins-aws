# 🚀 Java CI/CD Pipeline using Jenkins, Maven & AWS EC2

## 📌 Project Overview

This project demonstrates a complete CI/CD (Continuous Integration & Continuous Deployment) pipeline for a Java web application using Jenkins, Maven, and AWS EC2.

The pipeline automates the process of building, testing, and deploying the application to a remote Apache Tomcat server.

---

## 🏗️ Architecture

GitHub → Jenkins → Maven Build → Deploy → Tomcat (EC2)

---

## ⚙️ Tech Stack

* **Programming Language:** Java
* **Build Tool:** Maven
* **CI/CD Tool:** Jenkins
* **Cloud Platform:** AWS EC2
* **Web Server:** Apache Tomcat
* **Version Control:** Git & GitHub

---

## 🔥 Features

* Automated build using Jenkins Freestyle Job
* Continuous integration with GitHub
* Deployment to remote Tomcat server (EC2)
* Secure SSH communication between servers
* Maven-based project build

---

## 📁 Project Structure

```
project-root/
│── src/
│── pom.xml
│── screenshots/
│── README.md
```

---

## 🚀 Setup & Execution Steps

### 1️⃣ Launch EC2 Instances

* Instance 1: Jenkins Server
* Instance 2: Tomcat Server

---

### 2️⃣ Install Required Tools

#### On Jenkins Server:

* Java
* Jenkins
* Git
* Maven

#### On Tomcat Server:

* Java
* Apache Tomcat

---

### 3️⃣ Configure Jenkins

* Install required plugins (Git, Maven, SSH Agent)
* Create Freestyle Job
* Configure GitHub repository
* Add build step: `clean install`
* Configure post-build deployment to Tomcat server

---

### 4️⃣ Setup SSH Connection

* Generate SSH keys on Jenkins server
* Copy public key to Tomcat server
* Enable password-less authentication

---

### 5️⃣ Deployment

* Jenkins pulls code from GitHub
* Builds using Maven
* Deploys WAR file to Tomcat

---

## 📸 Screenshots

(Add your screenshots inside `/screenshots` folder)

Examples:

* Jenkins Job Configuration
* Build Success Console Output
* EC2 Instances Running
* Tomcat Deployment Result

---

## 🔐 Security Note

Sensitive files like `.pem`, credentials, and private keys are not included in this repository.

---

## 💼 Resume Value

This project demonstrates:

* Real-world CI/CD pipeline implementation
* Cloud deployment using AWS
* Automation using Jenkins
* Backend deployment skills

---

## 📈 Future Enhancements

* Convert Freestyle job to Jenkins Pipeline (Jenkinsfile)
* Add Docker containerization
* Implement GitHub Webhooks
* Add monitoring (Prometheus/Grafana)

---

## 🙌 Author

**Risu Kumari**
B.Tech CSE | DevOps Enthusiast

GitHub: https://github.com/rishu-1112

---
