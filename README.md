# 🌐 Request Header Parser Microservice

This is a full-stack JavaScript application built for the FreeCodeCamp **APIs and Microservices Certification**.

The project extracts information from request headers and returns details such as:
- IP Address
- Preferred Language
- Software / Browser Information

---

## 🚀 Live Demo

👉 [Click here to view live project](https://3b021fac-5a74-4f92-ada3-3cabab01d286-00-3cym64228dix6.sisko.replit.dev/)

---

## 📖 FreeCodeCamp Project Instructions

👉 [View FreeCodeCamp Task](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice)

---

## 📌 Project Objective

Build a Request Header Parser Microservice similar to:
https://request-header-parser-microservice.freecodecamp.rocks/

The API returns information from the incoming request headers in JSON format.

---

## ⚙️ Technologies Used

- Node.js
- Express.js
- JavaScript (ES6)
- HTML / CSS

---

## 📡 API Endpoint

### GET `/api/whoami`

Returns information about the client request headers.

---

## 📥 Example Response

```json
{
  "ipaddress": "192.168.1.1",
  "language": "en-US,en;q=0.9",
  "software": "Windows NT 10.0; Win64; x64"
}
