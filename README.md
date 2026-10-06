# Simple JSP Student Login System

A simple Java web application developed to demonstrate a basic student authentication system using **JSP, HTML, Maven, and Apache Tomcat**.

The application provides a student login form where the entered username and password are validated. If the credentials are correct, the student is redirected to a welcome page. If the credentials are incorrect, an appropriate error message is displayed.

---

## 📌 Project Overview

The **Simple JSP Student Login System** is a beginner-friendly Java web application designed to demonstrate how a basic login workflow works in a Java web environment.

The project uses **JSP (JavaServer Pages)** to create the web pages and process the login request. Maven is used for project and dependency management, while Apache Tomcat is used as the web server for running the application.

This project is mainly created for learning and understanding:

- JSP-based web applications
- HTML forms
- HTTP GET/POST requests
- Request parameter handling
- Username and password validation
- Page redirection
- Maven project structure
- Apache Tomcat deployment

---

## ✨ Features

- 🎓 Student login form
- 👤 Username input
- 🔐 Password input
- ✅ Username and password validation
- 🚫 Invalid username/password message
- 🎉 Login success page
- 🔄 Automatic redirection after successful login
- 📦 Maven-based project
- 🌐 Runs on Apache Tomcat
- 📁 Standard Java web application structure

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Java** | Programming language |
| **JSP** | Creating dynamic web pages |
| **HTML** | Designing the login form |
| **Jakarta JSP API** | JSP functionality |
| **Apache Tomcat** | Web server/application server |
| **Maven** | Build and dependency management |
| **XML** | Web application configuration |

---

## 📂 Project Structure

```text
student-login/
│
├── src/
│   └── main/
│       └── webapp/
│           │
│           ├── WEB-INF/
│           │   └── web.xml
│           │
│           ├── login.jsp
│           └── welcome.jsp
│
├── target/
│
├── pom.xml
│
└── README.md
