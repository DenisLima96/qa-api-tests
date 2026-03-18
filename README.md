# 🔗 API Testing (QA)

This repository contains basic concepts and examples of API testing as part of my QA learning journey.

---

## 🌍 Note

This content is written in English to follow industry standards.

---

## 📌 What is API Testing?

API testing is the process of validating the functionality, reliability, performance, and security of an API.

Instead of testing the user interface, we test the communication between systems.

---

## 📌 Example: User Login API

### 🔸 Endpoint

POST /api/login

---

### 🔸 Request (JSON)

```json
{
  "email": "user@email.com",
  "password": "123456"
}
```

---

### 🔸 Expected Response (Success)

```json
{
  "status": 200,
  "message": "Login successful",
  "token": "abc123xyz"
}
```

---

### 🔸 Expected Response (Error)

```json
{
  "status": 401,
  "message": "Invalid credentials"
}
```

---

## ✅ What to validate?

* Status code (200, 400, 401, 500)
* Response body
* Response time
* Data consistency

---

## 🧠 Real-world usage

In my QA experience, I validate data flows and system behavior through logs, ensuring that the backend processes information correctly.

---

## 🚀 Next Steps

* Learn Postman
* Practice real API requests
* Automate API tests

---

💬 API testing is essential to ensure system reliability beyond the UI.
