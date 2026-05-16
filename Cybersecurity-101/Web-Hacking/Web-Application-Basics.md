# 🌐 Web Application Basics — TryHackMe Room

<p align="center">
  <img src="https://github.com/Grishank/cybersecurity-roadmap-tryhackme/blob/main/assets/images/Web-Application-Basics-banner.png?raw=true" alt="Web Application Basics Banner" width="900"/>
</p>

---

**Platform:** TryHackMe  
**Path:** Cybersecurity 101  
**Module:** Web Fundamentals  
**Difficulty:** Easy  
**Date Completed:** Apr 2026  
**Room Link:** https://tryhackme.com/room/webapplicationbasics  
**Status:** ✔ Completed  

---

# 🧠 Room Overview

The **Web Application Basics** room introduces the core concepts behind how modern web applications work.

The room focuses on:
- URLs
- HTTP requests and responses
- Headers and body data
- HTTP methods
- Status codes
- Security headers
- Practical web requests

This room builds the foundation required for:
- Web security
- API testing
- Burp Suite
- Web exploitation
- SOC traffic analysis

---

# 🎯 Learning Objectives

- Understand web application architecture
- Learn how HTTP communication works
- Analyze request and response structure
- Understand status codes and headers
- Learn common HTTP methods
- Understand security-related headers
- Practice making web requests manually

---

# 🌍 Task 2 — Web Application Overview

A web application usually contains:
- Frontend
- Backend
- Database
- Web server

## Common Components

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- PHP
- Python
- Node.js
- Java

### Database
- MySQL
- PostgreSQL
- MongoDB

---

# 🔗 Task 3 — Uniform Resource Locator (URL)

A URL identifies a resource on the web.

## Example URL

```text
https://example.com/login?id=1
```

## URL Components

| Component | Example |
|---|---|
| Protocol | https |
| Domain | example.com |
| Path | /login |
| Parameter | id=1 |

---

# 📨 Task 4 — HTTP Messages

HTTP communication consists of:
- Requests
- Responses

## HTTP Request Example

```http
GET /index.html HTTP/1.1
Host: example.com
User-Agent: Mozilla/5.0
```

## HTTP Response Example

```http
HTTP/1.1 200 OK
Content-Type: text/html
```

---

# 📥 Task 5 — HTTP Request Line and Methods

HTTP methods define actions.

## Common HTTP Methods

| Method | Purpose |
|---|---|
| GET | Retrieve data |
| POST | Submit data |
| PUT | Update data |
| DELETE | Remove data |

---

# 📦 Task 6 — HTTP Headers and Body

Headers provide metadata about the request or response.

## Common Request Headers

- Host
- User-Agent
- Authorization
- Cookie
- Content-Type

## Request Body

Used mainly with:
- POST
- PUT

Example:

```json
{
  "username": "admin",
  "password": "password123"
}
```

---

# 📤 Task 7 — HTTP Response Status Codes

Status codes indicate server responses.

## Common Status Codes

| Code | Meaning |
|---|---|
| 200 | OK |
| 301 | Redirect |
| 403 | Forbidden |
| 404 | Not Found |
| 500 | Internal Server Error |

---

# 📄 Task 8 — HTTP Response Headers and Body

Responses contain:
- Status line
- Headers
- Body content

## Common Response Headers

- Server
- Set-Cookie
- Content-Type
- Cache-Control

---

# 🛡️ Task 9 — Security Headers

Security headers improve web application protection.

## Important Security Headers

| Header | Purpose |
|---|---|
| Content-Security-Policy | Prevent XSS |
| X-Frame-Options | Prevent clickjacking |
| Strict-Transport-Security | Force HTTPS |
| X-Content-Type-Options | Prevent MIME sniffing |

---

# 🧪 Task 10 — Practical HTTP Requests

The room included practical interaction with web requests.

## Skills Practiced

- Sending requests
- Viewing responses
- Understanding headers
- Identifying status codes
- Working with HTTP methods

---

# 🛡️ SOC / Blue Team Perspective

Understanding HTTP traffic helps analysts:
- Detect malicious requests
- Analyze phishing traffic
- Identify suspicious headers
- Investigate web attacks
- Monitor authentication attempts

Common attacks visible in HTTP traffic:
- SQL Injection
- XSS
- Directory traversal
- Brute force attacks
- Malicious file uploads

---

# 🧾 Key Concepts Learned

- Web application structure
- URL components
- HTTP requests and responses
- HTTP methods
- Headers and body data
- Status codes
- Security headers
- Practical web communication

---

# 💬 Key Takeaway

> “Understanding HTTP is one of the most important foundations in cybersecurity because most modern attacks interact with web applications.”

---

# 🚀 Next Steps

- Learn Burp Suite basics
- Study OWASP Top 10
- Practice packet analysis with HTTP traffic
- Learn cookie and session security
- Explore web vulnerabilities hands-on
