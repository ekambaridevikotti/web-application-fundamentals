# Web Application Fundamentals

---

## Q1. Role of Frontend (FE)

The **Frontend (FE)** is the part of a web application that users directly see and interact with in their browser.

### 1. User Interface (UI)

* Frontend is responsible for designing and displaying the layout of the website.
* It includes elements like buttons, forms, navigation bars, images, text, and colors.
* Technologies commonly used are **HTML** (structure), **CSS** (styling), and **JavaScript** (behavior).

### 2. User Interaction

* Frontend handles user actions such as clicks, typing in forms, scrolling, and selecting options.
* It provides instant feedback like form validation messages, loading indicators, and alerts.
* JavaScript is used to make the application interactive and dynamic without reloading the page.

### 3. Communication with Backend

* Frontend sends requests to the backend using **HTTP/HTTPS** (GET, POST, PUT, DELETE).
* It receives data (usually in JSON format) from the backend and displays it to the user.
* Example: Sending login details to the server and showing success or error messages.

---

## Q2. Role of Backend (BE)

The **Backend (BE)** is the server-side part of a web application that works behind the scenes.

### 1. Server-Side Processing

* Backend handles application logic that should not run in the browser.
* It processes requests received from the frontend and returns appropriate responses.
* Example: Calculating total price, checking availability, or processing form data.

### 2. Database Handling

* Backend connects to databases to store, retrieve, update, and delete data.
* It manages user data, product details, orders, and other application information.
* Common databases include **MySQL**, **MongoDB**, and **PostgreSQL**.

### 3. Security and Authentication

* Backend ensures secure access to the application.
* It handles user authentication (login, signup) and authorization (who can access what).
* Sensitive data like passwords are encrypted and never exposed to the frontend directly.

---

## Q3. Business Logic

**Business Logic** refers to the rules and conditions that define how a business operates within a web application. It decides *what should happen* when certain actions are performed.

### Explanation

* Business logic sits between the frontend and the database.
* It ensures that data is processed according to business rules.
* It helps maintain consistency, accuracy, and control in the application.

### Real-World Examples

1. **E-commerce Discount System**

   * If a user’s cart value is above ₹1000, apply a 10% discount.
   * This rule is business logic.

2. **Banking Application**

   * A user cannot withdraw money if the account balance is less than the withdrawal amount.
   * This validation is business logic.

3. **Online Exam System**

   * Once the exam time is over, answers cannot be submitted.
   * This rule is enforced using business logic.

---

## Q4. Client–Server Model

The **Client–Server Model** is a communication model where tasks are divided between service providers (servers) and service requesters (clients).

### Client

* The client is the user’s device or browser (Chrome, Edge, Firefox).
* It sends requests and displays responses.
* Example: A web browser requesting a webpage.

### Server

* The server is a system that processes requests and provides data or services.
* It hosts the backend application and database.

### Communication Between Client and Server

* Communication happens over the internet using **HTTP/HTTPS**.
* The client sends a request → server processes it → server sends a response.

```
Client (Browser) → HTTP Request → Server
Client (Browser) ← HTTP Response ← Server
```

---

## Q5. Three-Tier Architecture

**3-Tier Architecture** divides a web application into three separate layers to improve scalability and maintainability.

### 1. Presentation Layer

* This is the frontend layer.
* It handles UI and user interaction.
* Example: HTML, CSS, JavaScript, React.

### 2. Application (Business) Layer

* This layer contains business logic.
* It processes data, applies rules, and makes decisions.
* Example: Node.js, Java, Python backend code.

### 3. Data Layer

* This layer manages data storage.
* It includes databases and data access logic.
* Example: MySQL, MongoDB.

### Why 3-Tier Architecture is Used

* Better separation of concerns
* Easier maintenance and debugging
* Improved scalability and security

```
Presentation Layer
        ↓
Application Layer
        ↓
Data Layer
```

---

## Q6. JavaScript as a Backend Language

JavaScript is widely used as a backend language, mainly because of **Node.js**.

### 1. Performance

* Node.js uses an event-driven, non-blocking I/O model.
* It is fast and efficient for handling multiple requests at the same time.

### 2. Ecosystem

* JavaScript has a huge ecosystem with **npm** (Node Package Manager).
* Thousands of ready-made libraries and tools are available.

### 3. Popular Backend Frameworks

* **Express.js** – Lightweight and flexible
* **NestJS** – Structured and scalable
* **Fastify** – High performance

### Additional Advantage

* Same language for frontend and backend, making development easier and faster.

---

