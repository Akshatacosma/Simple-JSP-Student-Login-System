# 🎓 Simple JSP Student Login System

A simple Java web application that demonstrates a basic **student login and authentication system** using **JSP, HTML, Maven, and Apache Tomcat**.

The application provides a login page where students enter their username and password. The credentials are validated, and the user is redirected to a welcome page after successful login.

---

## 📌 Project Overview

This project was developed to understand the fundamentals of **Java web application development using JSP**.

It demonstrates:

- Creating web pages using JSP and HTML
- Accepting username and password input
- Processing login requests
- Validating user credentials
- Redirecting users between JSP pages
- Building a Java web application using Maven
- Deploying the application on Apache Tomcat

---

## ✨ Features

- 👤 Student username input
- 🔐 Password input
- ✅ Basic credential validation
- ❌ Invalid login message
- 🎉 Welcome page after successful login
- 🌐 JSP-based web interface
- 📦 Maven-based project
- 🚀 Apache Tomcat deployment

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Java** | Programming language |
| **JSP** | Dynamic web pages and login processing |
| **HTML** | Login form structure |
| **Maven** | Build and dependency management |
| **Apache Tomcat 9.0.112** | Web server |
| **XML** | Web application configuration |
| **Git & GitHub** | Version control |

---

## 📂 Project Structure

```text
Simple-JSP-Student-Login-System/
│
├── src/
│   └── main/
│       └── webapp/
│           ├── WEB-INF/
│           │   └── web.xml
│           │
│           ├── login.jsp
│           └── welcome.jsp
│
├── pom.xml
├── target/
│   └── student-login.war
│
└── README.md
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/akshatacosma/Simple-JSP-Student-Login-System.git
```

### 2. Navigate to the Project

```bash
cd Simple-JSP-Student-Login-System
```

### 3. Build the Project

Run the following Maven command:

```bash
mvn clean package
```

After a successful build, the WAR file will be generated inside the `target` folder:

```text
target/student-login.war
```

### 4. Deploy on Apache Tomcat

Copy the generated WAR file into the Tomcat `webapps` directory:

```bash
cp target/student-login.war <tomcat-folder>/webapps/
```

### 5. Start Apache Tomcat

Run:

```bash
<tomcat-folder>/bin/startup.sh
```

### 6. Open the Application

Open the following URL in your browser:

```text
http://localhost:8080/student-login/login.jsp
```

For ByteXL or another cloud development environment, open the exposed **8080** port and navigate to:

```text
/student-login/login.jsp
```

---

## 🧪 Testing

### ✅ Successful Login

1. Open the Student Login page.
2. Enter the correct username.
3. Enter the correct password.
4. Click **Login**.

**Expected Result:**  
The user is redirected to the welcome page.

### ❌ Invalid Login

1. Open the Student Login page.
2. Enter an incorrect username or password.
3. Click **Login**.

**Expected Result:**  
An invalid login message is displayed.

---

## 👩‍💻 Author

**Akshata**

B.Tech CSE (AI & ML) Student
⭐ If you find this project useful, feel free to explore the repository.

**This is the version I'd use on your GitHub, dear.** ❤️ It's detailed enough to show what you learned, but it doesn't look unnecessarily bloated like a college report.
