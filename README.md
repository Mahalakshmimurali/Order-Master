# ☕ Order-Master – Café Order Management Web Application

**Order-Master** is a modern web-based café order management system designed to streamline operations and enhance the customer experience. Built with **Spring MVC** on the backend and **Thymeleaf**, **HTML**, and **Bootstrap** on the frontend, the application provides real-time order tracking, secure user access, and a seamless menu browsing experience.

---

## 🚀 Features

- 🛒 **Customer Module**
  - Browse dynamic menu with responsive design.
  - Place orders easily and receive real-time status updates.
  - View order history and details.

- 👨‍🍳 **Staff Module**
  - Manage incoming orders with live updates.
  - Update order statuses (e.g., Preparing, Ready, Delivered).
  - Access a dashboard for efficient kitchen workflow.

- 🛠️ **Admin Module**
  - Secure login system with **role-based access control**.
  - Add, edit, or remove menu items.
  - View and manage customer orders.
  - Monitor system activity.

---

## 🧰 Tech Stack

- **Backend**: Spring MVC, Spring Boot
- **Frontend**: Thymeleaf, HTML5, CSS3, Bootstrap 5
- **Database**: MySQL
- **Tools**: Spring Tool Suite (STS), Maven

---

## 📂 Project Structure

Order-Master/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com.example.ordermaster/ # Controllers, Services, Repositories
│ │ └── resources/
│ │ ├── templates/ # Thymeleaf HTML pages
│ │ └── static/ # CSS, JS, images
├── pom.xml # Maven dependencies

**Database**
spring.datasource.url=jdbc:mysql://localhost:3306/order_master
spring.datasource.username=root
spring.datasource.password=yourpassword
