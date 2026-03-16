# capstone
Making an AI IDS website for cyber attack 
🚀 AI-Powered Intrusion Detection System for SDN
Full Stack + DevOps Capstone Project










This project implements an AI-powered Intrusion Detection System (IDS) for Software Defined Networks (SDN) with a modern DevOps workflow.

The system provides real-time monitoring, machine learning based attack detection, and administrative control through a dashboard interface.

It is built using a full stack architecture and deployed using Docker containers with CI/CD automation through Jenkins pipelines.

📌 Project Objective

Traditional networks struggle to detect sophisticated cyber attacks in real time.

This project aims to:

Monitor network traffic in an SDN environment

Detect malicious activity using AI/ML models

Provide real-time monitoring dashboards

Automate deployment with DevOps practices

🧠 AI-Based IDS in SDN

The system integrates Machine Learning based IDS with Software Defined Networking (SDN).

Key Capabilities

• Real-time network traffic monitoring
• AI-based attack detection
• Flow statistics analysis
• Traffic classification (Normal / Malicious)
• Admin monitoring dashboard
• Alert and log management

The system can identify:

DDoS attacks

abnormal traffic patterns

suspicious network flows

malicious packet behavior

🏗 System Architecture
                +--------------------+
                |      User/Admin    |
                +----------+---------+
                           |
                           v
                +--------------------+
                |   React Dashboard  |
                | (Traffic Monitoring|
                | Intrusion Detection|
                | Alerts & Logs)     |
                +----------+---------+
                           |
                           v
                +--------------------+
                | Node.js Backend API|
                |  Authentication    |
                |  IDS Integration   |
                +----------+---------+
                           |
                           v
                +--------------------+
                |  Machine Learning  |
                | IDS Detection Model|
                +----------+---------+
                           |
                           v
                +--------------------+
                | Database           |
                | MongoDB/PostgreSQL |
                +----------+---------+
                           |
                           v
                +--------------------+
                | Docker Containers  |
                +----------+---------+
                           |
                           v
                +--------------------+
                | Jenkins CI/CD      |
                +--------------------+
⚙️ Technology Stack
Frontend

React.js

Tailwind CSS

JavaScript

HTML5

Backend

Node.js

Express.js

REST APIs

Database

MongoDB / PostgreSQL

DevOps

Docker

Docker Compose

Jenkins

Security

JWT Authentication

AI / IDS

Machine Learning model for traffic classification

🔐 Key Features
JWT Authentication

Secure login system using JSON Web Tokens

Protected API routes

Role-based admin access

Database Integration

The system stores:

user credentials

network traffic logs

IDS detection results

system alerts

Supported databases:

MongoDB

PostgreSQL

📊 AI-Powered IDS Dashboard

The dashboard allows administrators to:

• Monitor real-time network traffic
• View IDS detection results
• Analyze flow statistics
• Track suspicious activity
• Manage alerts and logs

📸 Project Screenshots
Jenkins CI/CD Pipeline (Working)

This screenshot shows the automated Jenkins pipeline executing build and verification stages.

Pipeline stages include:

Checkout source code

Verify project files

Build application

Post build actions

AI-Powered IDS Dashboard
Dashboard Overview

Displays real-time monitoring metrics such as:

Active connections

Attack detections

network activity statistics

Traffic Monitoring

Provides detailed flow statistics for network traffic analysis.

Intrusion Detection

Controls the IDS model execution and displays classification results.

Alerts & Logs

Displays security alerts and system events.

📂 Project Structure
CAPSTONE
│
├── backend
│   ├── config
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── Dockerfile
│   ├── server.js
│   └── package.json
│
├── frontend
│   ├── public
│   ├── src
│   ├── Dockerfile
│   ├── tailwind.config.js
│   └── package.json
│
├── docker-compose.yml
├── Jenkinsfile
├── jenkins-docker
└── README.md
🐳 Running the Project
Clone the Repository
git clone https://github.com/yourusername/ai-ids-sdn.git
cd ai-ids-sdn
Run using Docker
docker-compose up --build

This will start:

frontend container

backend container

database container

🔄 CI/CD Pipeline

The Jenkins pipeline automates:

1️⃣ Code checkout from repository
2️⃣ Build verification
3️⃣ Docker image build
4️⃣ Container deployment

Pipeline configuration is defined in:

Jenkinsfile
🚧 Future Improvements

Planned improvements:

advanced ML model training

cloud deployment (AWS / GCP)

network visualization graphs

IDS performance metrics

security hardening

automated threat mitigation

👨‍💻 Author

Satya Anand

B.Tech Computer Science
NIIT University

Interests:

Cybersecurity

DevOps

AI Security

Data Analytics

⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
📩 Provide suggestions

📜 License

This project is for academic and research purposes.