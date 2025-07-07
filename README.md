# 💰 Expense Manager – Spring Boot REST API

A backend-only application developed with **Java**, **Spring Boot**, and **MySQL** to manage and track personal expenses. It provides RESTful endpoints for CRUD operations and generates summaries to help users manage daily spending.

---

## 🚀 Features

- ➕ Add new expense entries
- 🧾 Update or delete existing expenses
- 📆 Filter expenses by date, category, or amount
- 📊 View summaries of total spending
- 🔐 Secure backend with clean API structure

---

## 🧰 Tech Stack

| Layer     | Tech Stack                              |
|-----------|------------------------------------------|
| Language  | Java                                     |
| Backend   | Spring Boot, Spring MVC, Spring Data JPA |
| Database  | MySQL                                    |
| Tools     | Maven, Postman, Git, GitHub              |

---

## 📂 Folder Structure

expense-manager/
├── src/
│ ├── main/
│ │ ├── java/com/expensemanager/... (controllers, services, models)
│ │ └── resources/application.properties
└── pom.xml


---

## 📑 API Endpoints Overview

| Method | Endpoint              | Description                    |
|--------|-----------------------|--------------------------------|
| POST   | `/api/expenses`       | Add a new expense              |
| GET    | `/api/expenses`       | Get all expenses               |
| GET    | `/api/expenses/{id}`  | Get expense by ID              |
| PUT    | `/api/expenses/{id}`  | Update an expense              |
| DELETE | `/api/expenses/{id}`  | Delete an expense              |
| GET    | `/api/summary`        | Get total and categorized summary |

---

## 🧠 Learning Highlights

- Implemented REST API using Spring Boot and JPA
- Practiced layered architecture (Controller → Service → Repository)
- Performed CRUD operations using MySQL
- Strengthened understanding of API design and data modeling

---

## 🧪 How to Run Locally

1. **Clone the repo**

```bash
git clone https://github.com/KSaurabh2001/Expense-Manager.git
cd Expense-Manager
