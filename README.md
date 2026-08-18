# Hostel and PG Management System 🏨

![DevOps](https://img.shields.io/badge/DevOps-Jenkins-blue)
![Docker](https://img.shields.io/badge/Containerized-Docker-blue)
![React](https://img.shields.io/badge/Frontend-React-61DAFB)
![Node](https://img.shields.io/badge/Backend-Node.js-339933)

## 📖 Overview
The Hostel and PG Management System is a full-stack web application designed to digitize and streamline the administrative tasks of managing student accommodations. It provides a centralized, real-time dashboard for administrators to allocate rooms, track student records, and manage fee statuses seamlessly. 

A primary focus of this project is the implementation of modern DevOps practices. The application is fully containerized and utilizes an automated Continuous Integration and Continuous Deployment (CI/CD) pipeline orchestrated by Jenkins.

## ✨ Key Features
* **Role-Based Access Control:** Secure authentication for administrators and students.
* **Dashboard Analytics:** High-level overview of total students, room vacancies, and pending fees.
* **Student Management:** Register, update, and manage resident profiles easily.
* **Room Management:** Monitor room inventory, capacity, and real-time occupancy status.
* **Fee Tracking:** Track paid and pending dues for individual residents.
* **Automated CI/CD:** Zero-touch deployment using Jenkins, Docker Hub, and Docker Compose.

## 🛠️ Tech Stack
**Application Layer:**
* **Frontend:** React.js, Vite
* **Backend:** Node.js, Express.js
* **Database:** SQLite (Persistent storage via Docker Volumes)

**DevOps & Infrastructure:**
* **Version Control:** Git & GitHub
* **Containerization:** Docker & Docker Compose
* **CI/CD Automation:** Jenkins

## 🚀 Local Setup & Installation

### Prerequisites
* [Docker Desktop](https://www.docker.com/products/docker-desktop) installed and running.
* Git installed on your local machine.

### Steps to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/your-repo-name.git](https://github.com/yourusername/your-repo-name.git)
   cd your-repo-name
