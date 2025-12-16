# WebBookApp 📚

A **Java-based Web Application** developed using **JSP, Servlets, JDBC, and MySQL** that demonstrates complete **CRUD operations** for managing books. This project is beginner-friendly and designed to clearly explain core Java web development concepts.

---

## 📌 Project Description

**WebBookApp** is a simple and practical web application that allows users to **add, view, update, and delete book records** from a database. It follows the **MVC architecture** and helps learners understand how JSP pages interact with Servlets and databases using JDBC.

This project is ideal for:

* Java beginners
* College practicals
* Interview preparation
* Understanding real-world Java web applications

---

## 🚀 Features

* Add new book details
* View all books
* Update existing book information
* Delete books
* Clean UI using HTML & CSS
* Proper request handling using Servlets
* MySQL database connectivity using JDBC

---

## 🛠️ Technologies Used

* **Java (Core Java)**
* **JSP (Java Server Pages)**
* **Servlets (Jakarta Servlet API)**
* **JDBC**
* **MySQL**
* **Apache Tomcat 10+**
* **HTML & CSS**
* **Eclipse IDE**

---

## 📂 Project Structure

```
WebBookApp
│
├── src/main/java
│   ├── com.book.db
│   │   └── DBConnect.java
│   ├── com.book.servlet
│   │   ├── AddBookServlet.java
│   │   ├── UpdateBookServlet.java
│   │   └── DeleteBookServlet.java
│
├── src/main/webapp
│   ├── index.jsp
│   ├── add_book.jsp
│   ├── edit_book.jsp
│   ├── view_books.jsp
│   └── css/style.css
│
├── web.xml
└── README.md
```

---

## 🧩 Database Setup

```sql
CREATE DATABASE webbookdb;

USE webbookdb;

CREATE TABLE books (
    id INT PRIMARY KEY AUTO_INCREMENT,
    title VARCHAR(100),
    author VARCHAR(100),
    price DOUBLE
);
```

---

## ⚙️ Configuration Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/ajaypratap5301/WebBookApp.git
   ```

2. Import the project into **Eclipse** as a Dynamic Web Project

3. Add **MySQL Connector/J** JAR file to:

   * Project Build Path
   * `WEB-INF/lib`

4. Configure database credentials in `DBConnect.java`

5. Run the project on **Apache Tomcat Server**

---

## 📸 Screenshots (Optional)

*Add screenshots here to make the project more attractive.*

---

## 🎯 Learning Outcomes

* Understanding JSP & Servlet flow
* Hands-on experience with JDBC
* MVC architecture basics
* RequestDispatcher and HTTP methods
* Database CRUD operations

---

## 📄 License

This project is for **educational purposes only**.

---

## 👨‍💻 Author

**Ajay Pratap Rav**
Java Developer | Full Stack Learner
GitHub: [https://github.com/ajaypratap5301](https://github.com/ajaypratap5301)

