# Jenkins-Task
# Jenkins Deployment on AWS EC2

## 📌 Project Overview

This project demonstrates the installation and configuration of Jenkins on an AWS EC2 instance.

The objective was to launch Jenkins, access the Jenkins dashboard, create a Jenkins project, execute a build, and explore Jenkins user management.

---

## 🛠️ Technologies Used

- AWS EC2
- Ubuntu Server 24.04 LTS
- Jenkins
- Java OpenJDK 21
- PuTTY
- GitHub

---

## ☁️ AWS EC2 Configuration

An Ubuntu EC2 instance was launched on AWS with the following configuration:

- Instance Name: `jenkins-server`
- Operating System: Ubuntu Server 24.04 LTS
- Instance Type: `t2.micro`
- SSH Port: `22`
- Jenkins Port: `8080`

Jenkins was accessed using the EC2 public IP and port 8080.

Example:

```text
http://<EC2-PUBLIC-IP>:8080
