# QA API Testing Project

## 📌 Project Overview
This project demonstrates API testing of a user management system using Postman. The goal was to validate API functionality, response structure, and error handling.

---

## 🧪 APIs Tested
- GET /users
- GET /users/{id}
- POST /users

---

## ✅ Test Coverage
- Functional Testing (valid requests)
- Negative Testing (invalid inputs, missing fields)
- Response Validation (status codes, data structure)
- Edge Case Testing (invalid endpoints, empty responses)
- Basic Performance Testing (response time)

---

## 🧾 Test Cases
- Total Test Cases: 10
- Passed: 8
- Failed: 2

---

## 🐞 Defects Identified
1. API returns **500 Internal Server Error** for invalid input instead of proper validation error (400)
2. API allows creation of user with empty body (missing validation)

---

## 🛠 Tools Used
- Postman
- JSONPlaceholder API

---

## 📊 Key Validations Performed
- Status code verification (200, 201, 404, 500)
- Response body validation
- Field validation (id, email, etc.)
- Error handling validation

---

## 📁 Project Files
- Test-Cases.xlsx → API test cases
- Postman-Collection.json → API requests & validations
- Test-Report.md → Summary of execution

---

## 🚀 What I Learned
- API request and response validation
- Writing structured test cases
- Performing negative and edge case testing
- Identifying real-world API issues

---
