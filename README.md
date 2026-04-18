# shop sales service with built docker,iroha,flask

# 🛒 Shop Sales Service

A lightweight **shop sales management service** built using **Flask**, **Hyperledger Iroha**, and **Docker**.  
This project demonstrates a simple backend system for managing sales records with blockchain-based ledger integration.

---

## 🚀 Features

- REST API built with Flask
- Sales record management
- Blockchain integration using Hyperledger Iroha
- Dockerized environment for easy setup
- Secure and immutable transaction logging

---

## 🏗️ Tech Stack

- **Backend:** Flask (Python)
- **Blockchain:** Hyperledger Iroha
- **Containerization:** Docker, Docker Compose
- **Database:** Iroha ledger storage
- **API Format:** REST / JSON

---

---

## ⚙️ Installation & Setup

1. Clone the repository
git clone https://github.com/Mbpartner128/3eets.git
cd 3eets

2. Build Docker containers
docker-compose build

3. Run the project
docker-compose up

4. API will be available at:
http://localhost:5000

📡 API Endpoints
➕ Add Sale
POST /sales

Request Body:

{
  "item": "Laptop",
  "price": 1200,
  "quantity": 1
}
📄 Get All Sales
GET /sales
🔗 Blockchain Record

Each sale is recorded in Hyperledger Iroha ledger for immutability.

🐳 Docker Setup

The system runs using Docker containers:

Flask API container
Iroha blockchain node
Network bridge between services
🧠 Future Improvements
User authentication (JWT)
Admin dashboard (React)
Analytics dashboard
Multi-store support
Cloud deployment (AWS / GCP)

Full Stack Developer
GitHub: https://github.com/Mbpartner128

---

If you want, I can also:
- :contentReference[oaicite:0]{index=0}  
- or :contentReference[oaicite:1]{index=1}  
- or :contentReference[oaicite:2]{index=2} 👍
