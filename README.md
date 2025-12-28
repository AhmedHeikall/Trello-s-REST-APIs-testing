# 📌 Trello REST API Automation Project

## 🎓 Graduation Project Information
This project was developed as a **Graduation Project** for the  
**Udacity Nanodegree Program**, delivered in collaboration with **Sprints.ai**,  
and **sponsored by MCIT (Ministry of Communications and Information Technology – Egypt)**.

The project focuses on **API testing and automation** using **Postman**, validating real-world REST APIs through structured test cases and automated collections.

---

## 📌 Project Overview
This project automates testing of **Trello REST APIs** using **Postman** to validate core project management functionalities such as board creation, deletion, list management, and list archiving.

The automation suite verifies **API responses, status codes, headers, default values, and data integrity**, and generates execution results showing **PASS/FAIL status** for each test case and scenario.

Additionally, Swagger was used for **API exploration and manual validation** before automation.

---

## 📊 Project Summary
| Item | Description |
|-----|-------------|
| **Domain** | API Testing |
| **Application** | Trello |
| **API Type** | REST APIs |
| **Project Type** | Graduation Project |
| **Program** | Udacity Nanodegree |
| **Training Partner** | Sprints.ai |
| **Sponsor** | MCIT – Egypt |
| **Automation Tool** | Postman |
| **API Documentation** | Swagger |
| **Authentication** | API Key & Token |
| **Reporting** | Postman Collection Runner (JSON Export) |

---

## 🧪 Automated Test Coverage

### 🔹 FakerestAPI (Swagger Practice)
- GET /api/v1/Authors
- POST /api/v1/Authors
- GET /api/v1/Authors/authors/books/{idBook}
- PUT /api/v1/Authors/{id}
- GET /api/v1/Authors/{id}

✔ Status code validation  
✔ Response body validation  
✔ Mandatory field checks  
✔ Integration testing across endpoints  

---

### 🔹 Trello REST APIs
The following Trello APIs were automated and validated:

| Feature | API |
|------|-----|
| Get user boards | GET /1/members/me |
| Create board | POST /1/boards |
| Get boards | GET /1/members/me?boards=open |
| Delete board | DELETE /1/boards/{id} |
| Create list | POST /1/lists |
| Get lists on board | GET /1/boards/{id}/lists |
| Archive / Unarchive list | PUT /1/lists/{id}/closed |

---

## 🧪 Test Validations Implemented
- Status code validation (200, 201, 400)
- Response body key existence
- Default values validation (closed, permissions, limits)
- Header validation (Set-Cookie)
- Dynamic data handling using variables
- Collection-level execution
- Integration validation between APIs
- Looping over response arrays for data consistency

---

## 🏗️ Project Structure (Postman)

Trello-API-Automation/
```
│
├── Swagger practicing & Postman Testcase
│ ├── Authors.postman_collection.json
│ ├── Live.postman_environment.json
│ └── Explore and practice on the Swagger online website.txt
│
├── Trello's APIs testing
│ ├── Trello doc.txt
│ ├── Trello Rest APIs.postman_collection.json
│ └── workspace.postman_globals.json│
└── README.md
```


---

## 🔐 Authentication
Trello APIs are authenticated using:
- **API Key**
- **API Token**

Credentials are passed via **Query Parameters** as per Trello documentation.

---

## 🚀 Execution Steps
1. Import Postman collection
2. Import environment / global variables
3. Configure API key & token
4. Run requests individually or via **Collection Runner**
5. Export test execution results in JSON format

---

## 📄 Test Reporting
- Collection Runner execution
- PASS / FAIL status per request
- Script-level assertion results
- Execution time
- JSON report export

---

## 🌟 Project Highlights
✔ Graduation Project for **Udacity Nanodegree**  
✔ Sponsored by **MCIT (Egypt)**  
✔ Delivered with **Sprints.ai**  
✔ REST API testing with **Postman**  
✔ Swagger-based API exploration  
✔ Dynamic variables & scripting  
✔ Integration testing across endpoints  
✔ Professional execution reports  

---

## 👨‍💻 Author
**Ahmed Heikal**  
Software Test Automation Engineer  
📍 Egypt  

---
