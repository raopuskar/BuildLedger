# BuildLedger 🏗️

A full-stack MERN application designed to streamline construction project management by enabling efficient tracking of projects, expenses, budgets, contractors, and financial records through a centralized dashboard.

## 📌 Overview

BuildLedger is a construction management and expense tracking platform that helps builders, contractors, and project managers monitor project finances in real time. The system provides a structured way to manage project budgets, track expenditures, maintain records, and generate financial insights.

## 🚀 Features

### User Authentication

* Secure JWT-based authentication
* User registration and login
* Protected routes
* Password encryption using bcrypt

### Project Management

* Create construction projects
* Update project details
* Delete projects
* View project status and progress

### Expense Tracking

* Add project expenses
* Categorize expenses
* Track spending history
* Monitor project budgets

### Dashboard Analytics

* Total project overview
* Expense summaries
* Budget utilization tracking
* Financial statistics visualization

### Record Management

* Maintain construction records
* Organize project data
* Easy access to financial information

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript (ES6+)
* CSS3
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication & Security

* JWT Authentication
* bcrypt.js
* Protected API Routes

### Development Tools

* Git
* GitHub
* VS Code
* Postman

## 📂 Project Structure

```bash
BuildLedger/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── package.json
│
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/raopuskar/BuildLedger.git
cd BuildLedger
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Install Backend Dependencies

```bash
cd ../server
npm install
```

### Configure Environment Variables

Create a `.env` file inside the server directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### Run Backend

```bash
npm start
```

### Run Frontend

```bash
npm start
```

## 📸 Screenshots

### Login Page

(Add Screenshot Here)

### Dashboard

(Add Screenshot Here)

### Project Management

(Add Screenshot Here)

### Expense Tracking

(Add Screenshot Here)

## 🔗 API Endpoints

### Authentication

```http
POST /api/auth/register
POST /api/auth/login
```

### Projects

```http
GET    /api/projects
POST   /api/projects
PUT    /api/projects/:id
DELETE /api/projects/:id
```

### Expenses

```http
GET    /api/expenses
POST   /api/expenses
PUT    /api/expenses/:id
DELETE /api/expenses/:id
```

## 🎯 Future Enhancements

* PDF report generation
* Expense analytics charts
* Multi-user collaboration
* Role-based access control
* Email notifications
* Cloud deployment (AWS)

## 💡 Learning Outcomes

Through this project, I gained practical experience in:

* MERN Stack Development
* REST API Design
* MongoDB Data Modeling
* JWT Authentication
* State Management
* Frontend-Backend Integration
* Secure Web Application Development

## 👨‍💻 Author

**Puskar Rao**

* GitHub: https://github.com/raopuskar
* LinkedIn: Add Your LinkedIn Profile

## 📄 License

This project is developed for educational and portfolio purposes.
