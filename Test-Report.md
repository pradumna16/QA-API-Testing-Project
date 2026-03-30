# API Testing Report

## 📌 Project Name
User Management API Testing

---

## 🧪 Objective
To validate the functionality, reliability, and error handling of user-related APIs using Postman.

---

## 📊 Test Summary

| Metric              | Count |
|--------------------|------|
| Total Test Cases   | 10   |
| Passed             | 8    |
| Failed             | 2    |

---

## 🧾 Scope of Testing
- GET /users
- GET /users/{id}
- POST /users

---

## 🔍 Testing Types Performed
- Functional Testing
- Negative Testing
- Response Validation
- Edge Case Testing
- Basic Performance Testing

---

## 🐞 Defects Identified

### 1. Improper Error Handling
- **Description:** API returns 500 Internal Server Error for invalid input instead of proper validation error (400)
- **Severity:** High
- **Priority:** High

---

### 2. Missing Validation for Empty Request
- **Description:** API allows creation of user with empty request body
- **Severity:** Medium
- **Priority:** Medium

---

## ⚠️ Observations
- Some APIs do not perform proper input validation
- Error handling can be improved for better reliability

---

## ✅ Conclusion
The APIs are functionally working for valid requests, but improvements are required in validation and error handling to ensure robustness and reliability.

---
