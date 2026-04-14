# FastAPI User Management API

A production-ready backend API built using FastAPI, designed to handle user management with secure authentication, database integration, and scalable deployment.

---

## 🚀 Features

* User CRUD operations (Create, Read, Update, Delete)
* Secure authentication using JWT
* MySQL database integration
* RESTful API architecture
* Dockerized for deployment

---

## 🛠️ Tech Stack

* Python
* FastAPI
* MySQL
* SQLAlchemy (ORM)
* JWT Authentication
* Docker

---

## 📂 Project Structure

```
app/
 ├── routers/        # API routes
 ├── models/         # Database models
 ├── schemas/        # Pydantic schemas
 ├── database/       # DB connection
 ├── auth/           # Authentication logic
 └── main.py         # Entry point
```

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/BytePassionDeepika/fastapi-user-management-api.git
cd fastapi-user-management-api
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the server

```bash
uvicorn app.main:app --reload
```

---

## 📌 API Documentation

FastAPI provides built-in interactive docs:

* Swagger UI → http://127.0.0.1:8000/docs
* ReDoc → http://127.0.0.1:8000/redoc

---

## 🔐 Authentication

* JWT-based authentication system
* Secure login & token validation
* Protected routes require token access

---

## 📈 Future Enhancements

* Role-based access control (RBAC)
* Pagination & filtering
* Logging & monitoring
* Deployment on cloud (AWS / Render)

---

## 👩‍💻 Author

**Deepika M**
