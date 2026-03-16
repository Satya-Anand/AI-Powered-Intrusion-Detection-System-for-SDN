🧠 AI-Based IDS for SDN

The system integrates Machine Learning based intrusion detection with Software Defined Networking.

Key Capabilities

• Real-time traffic monitoring
• Machine learning attack detection
• Traffic classification (Normal / Attack)
• Network flow statistics analysis
• Alert and log management
• Administrative control dashboard

The system can detect:

DDoS attacks

abnormal traffic flows

malicious packets

suspicious network patterns

🏗 System Architecture
User / Administrator
        │
        ▼
React Dashboard (Monitoring Interface)
        │
        ▼
Node.js Backend API
        │
        ▼
AI/ML Intrusion Detection Model
        │
        ▼
Database (MongoDB / PostgreSQL)
        │
        ▼
Docker Containers
        │
        ▼
Jenkins CI/CD Pipeline
⚙️ Technology Stack
Frontend

React.js

Tailwind CSS

JavaScript

HTML5

Backend

Node.js

Express.js

REST API

Database

MongoDB

PostgreSQL

DevOps

Docker

Docker Compose

Jenkins CI/CD

Security

JWT Authentication

Machine Learning

AI-based traffic classification model

🔐 Key Features
JWT Authentication

Secure login system using JSON Web Tokens (JWT).

Features:

Protected API endpoints

Secure user sessions

Admin authentication

Database Integration

The system stores:

user authentication data

traffic logs

IDS detection results

security alerts

system events

Supported databases:

MongoDB

PostgreSQL

📊 AI-Powered IDS Dashboard

The dashboard enables administrators to:

• Monitor network traffic
• View intrusion detection results
• Analyze flow statistics
• Track security alerts
• Manage logs and events

📸 Project Screenshots
Jenkins CI/CD Pipeline

Shows automated pipeline execution including build and verification stages.

Dashboard Overview

Real-time monitoring metrics:

active connections

detected attacks

network traffic statistics

Traffic Monitoring

Displays network flow statistics and traffic details.

Intrusion Detection

Controls the machine learning IDS model and shows classification results.

Alerts and Logs

Displays security alerts and system activity logs.

📂 Project Structure
AI-Powered-Intrusion-Detection-System-for-SDN
│
├── backend
│   ├── config
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── server.js
│   ├── Dockerfile
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
⚙️ Backend Setup

Before running the backend server, install required dependencies.

Navigate to the backend directory:

cd backend

Install dependencies:

npm install

This command will create the node_modules folder automatically.

📦 Installing Express

If Express is not installed, install it using:

npm install express

Backend structure after installation:

backend
│
├── config
├── controllers
├── models
├── routes
├── node_modules
├── package.json
├── package-lock.json
└── server.js
▶ Running the Backend Server

Run the backend server:

node server.js

Or using nodemon:

npx nodemon server.js
🐳 Running the Project with Docker

Clone the repository:

git clone https://github.com/Satya-Anand/AI-Powered-Intrusion-Detection-System-for-SDN.git
cd AI-Powered-Intrusion-Detection-System-for-SDN

Run containers:

docker-compose up --build

This will start:

frontend container

backend container

database services

🔄 Jenkins CI/CD Pipeline

The Jenkins pipeline automates the following steps:

1️⃣ Source code checkout
2️⃣ Build verification
3️⃣ Docker image build
4️⃣ Container deployment

Pipeline configuration is defined in:

Jenkinsfile
🚧 Future Improvements

Planned improvements:

advanced ML model training

cloud deployment (AWS / GCP)

automated threat mitigation

network visualization graphs

IDS performance metrics

security hardening

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
🍴 Fork the repository
📩 Share suggestions

📜 License

This project is created for academic and research purposes.
