# 🏗️ BuildLedger

> **A Microservices-Based Construction Contract & Vendor Management Platform**

BuildLedger is a modern full-stack enterprise application designed to simplify construction project management by digitizing contract lifecycle management, vendor operations, invoice processing, delivery tracking, and payment workflows.

The application follows a **Microservices Architecture** built with **Spring Boot**, allowing independent deployment, scalability, and maintainability for enterprise-grade systems.

---

## ✨ Features

### 🔐 Authentication & Authorization

* Secure user authentication
* Role-Based Access Control (RBAC)
* Protected REST APIs
* Session management

### 📑 Contract Management

* Create and manage construction contracts
* Contract lifecycle tracking
* Contract status management

### 🏢 Vendor Management

* Vendor registration
* Vendor profile management
* Vendor performance tracking
* Contract assignment

### 📦 Delivery Tracking

* Monitor material deliveries
* Delivery status updates
* Shipment history

### 💳 Invoice & Payment Management

* Generate invoices
* Track payment status
* Payment history
* Financial record management

### ⚡ Microservices

* Independent business services
* Service discovery using Eureka
* Inter-service communication using OpenFeign
* Modular architecture

---

# 🏛️ System Architecture

```text
                        Client (React.js)
                               │
                               ▼
                     Spring Boot REST APIs
                               │
      ┌───────────────┬───────────────┬───────────────┐
      ▼               ▼               ▼               ▼
 Contract Service  Vendor Service  Payment Service  Delivery Service
      │               │               │               │
      └───────────────┴───────────────┴───────────────┘
                      Eureka Discovery Server
                               │
                            MySQL Database
```

---

# 🚀 Tech Stack

## Frontend

* React.js
* JavaScript
* HTML5
* CSS3

## Backend

* Java
* Spring Boot
* Spring MVC
* Spring Security
* REST APIs

## Microservices

* Eureka Discovery Server
* OpenFeign

## Database

* MySQL

## Tools

* Git
* GitHub
* Postman
* Swagger (OpenAPI)
* Maven

---

# 📂 Project Structure

```text
BuildLedger/

├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── backend/
│   ├── api-gateway/
│   ├── contract-service/
│   ├── vendor-service/
│   ├── payment-service/
│   ├── delivery-service/
│   ├── eureka-server/
│   └── pom.xml
│
└── README.md
```

---

# 📸 Screenshots

## Dashboard

<img width="100%" src="images/dashboard.png">

---

## Vendor Management

<img width="100%" src="images/vendors.png">

---

## Contract Management

<img width="100%" src="images/contracts.png">

---

## Payment Dashboard

<img width="100%" src="images/payments.png">

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/raopuskar/BuildLedger.git

cd BuildLedger
```

---

## Backend

```bash
cd backend

mvn clean install

mvn spring-boot:run
```

---

## Frontend

```bash
cd frontend

npm install

npm start
```

---

# 🛠 Environment Variables

```env
MYSQL_URL=

MYSQL_USERNAME=

MYSQL_PASSWORD=

JWT_SECRET=
```

---

# 📡 API Modules

### Authentication

```
POST /api/auth/login

POST /api/auth/register
```

### Contracts

```
GET /contracts

POST /contracts

PUT /contracts/{id}

DELETE /contracts/{id}
```

### Vendors

```
GET /vendors

POST /vendors

PUT /vendors/{id}

DELETE /vendors/{id}
```

### Payments

```
GET /payments

POST /payments
```

### Deliveries

```
GET /deliveries

POST /deliveries
```

---

# 🎯 Key Highlights

* Enterprise-grade Microservices Architecture
* Spring Boot + React Full Stack
* Eureka Service Discovery
* OpenFeign Communication
* Secure RBAC Implementation
* RESTful API Design
* Optimized MySQL Database
* Modular & Scalable Design

---

# 📈 Future Improvements

* Docker Support
* Kubernetes Deployment
* API Gateway
* Redis Caching
* RabbitMQ Event Messaging
* CI/CD Pipeline
* AWS Deployment
* Email Notifications
* Dashboard Analytics
* PDF Report Generation

---

# 👨‍💻 Author

**Puskar Rao**

📧 [raopushkar4@gmail.com](mailto:raopushkar4@gmail.com)

🔗 LinkedIn
https://linkedin.com/in/puskar-rao

💻 GitHub
https://github.com/raopuskar

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further development.

---

## 📄 License

This project is developed for educational and portfolio purposes.
