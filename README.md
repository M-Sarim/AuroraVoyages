<h1 align="center">🌌 Aurora Voyages</h1>
<p align="center"><b>Microservices-Based Travel Booking Platform</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/build-passing-brightgreen" alt="Build Passing">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License: MIT">
  <img src="https://img.shields.io/badge/dockerized-yes-2496ED" alt="Dockerized">
</p>

---

## 🌍 Overview

**Aurora Voyages** is a cloud-native travel booking application developed as a course project to explore **microservices architecture**, **Docker containerization**, and **inter-service communication**. The platform simulates a complete travel ecosystem — from user registration to payment processing and real-time notifications.

---

## 📚 Table of Contents

- [🌍 Overview](#-overview)
- [📦 Features](#-features)
- [🔧 Architecture](#-architecture)
- [⚙️ Installation](#️-installation)
- [🚀 Usage](#-usage)
- [🧪 API Testing](#-api-testing)
- [📁 Project Structure](#-project-structure)
- [🔧 Configuration](#-configuration)
- [📚 Documentation](#-documentation)
- [🐞 Troubleshooting](#-troubleshooting)
- [🤝 Contributors](#-contributors)
- [📄 License](#-license)

---

## 📦 Features

✅ Modular microservices  
✅ Containerized with Docker & Docker Compose  
✅ RESTful APIs for all services  
✅ SMTP-based email notifications  
✅ Health check & testing scripts  
✅ Scalable architecture ready for orchestration  

---

## 🔧 Architecture

```

\[ User Service ] ---> \[ Auth Service ]
\|                     |
v                     v
\[ Trip Service ] <--> \[ Payment Service ] <--> \[ Notification Service ]
|
v
\[ MongoDB | Redis | RabbitMQ ]

````

> Each box represents an isolated microservice with its own responsibilities, data storage, and API.

---

## ⚙️ Installation

> Make sure you have **Docker** and **Docker Compose** installed.

```bash
# Clone the repository
git clone <repo-url>
cd AuroraVoyages-courseProject

# Build and start all services
docker-compose up --build
````

🔍 Check services:

```bash
# For Linux/Mac
./test-services.sh

# For Windows
check-services.bat
```

---

## 🚀 Usage

* **Frontend**: `http://localhost:3000`
* **Example API Endpoint**: `http://localhost:8001/api/users`

Use `test-api.js` to perform sample API requests:

```bash
node test-api.js
```

---

## 🧪 API Testing

Sample request:

```http
POST /api/users/register
Content-Type: application/json

{
  "name": "Alice",
  "email": "alice@example.com",
  "password": "securepass"
}
```

---

## 📁 Project Structure

```
AuroraVoyages-courseProject/
├── user-service/
├── payment-service/
├── trip-service/
├── notification-service/
├── docker-compose.yml
├── test-api.js
├── check-services.bat
├── start-services.ps1
└── docs/
    ├── MICROSERVICES-README.md
    ├── implementation-steps.md
    └── microservices-implementation-plan.md
```

---

## 🔧 Configuration

Each service uses environment variables or `.env` files.

**Common Configurations**:

* `API_PORT`: Port number
* `DB_URI`: Database connection string
* `MAIL_CONFIG`: SMTP settings for email service
* `SERVICE_ENDPOINTS`: Internal service URLs

🛠 Modify `docker-compose.override.yml` for local overrides.

---

## 📚 Documentation

* [`MICROSERVICES-README.md`](./docs/MICROSERVICES-README.md) – Service breakdown and responsibilities
* [`implementation-steps.md`](./docs/implementation-steps.md) – Setup steps and explanations
* [`microservices-implementation-plan.md`](./docs/microservices-implementation-plan.md) – Planning and architecture

---

## 🐞 Troubleshooting

| Issue                   | Solution                                                 |
| ----------------------- | -------------------------------------------------------- |
| Port conflicts          | Modify ports in `docker-compose.override.yml`            |
| Services not starting   | Run `docker-compose up --build` to rebuild containers    |
| Database not connecting | Check `DB_URI` values in env files                       |
| Logs not showing        | Use `docker-compose logs <service-name>` for diagnostics |

---

## 🤝 Contributors

👤 **\[Muhammad Sarim]** – Project Lead
🎓 Developed as part of \[Fast National University CFD Campus]

---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](./LICENSE) file for details.

---
