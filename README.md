# Online-Food-Delivery-Platform
Built a food delivery website where users can find restaurants, browse food, add items to cart, place and track orders, and give reviews. Restaurants can manage menus and orders, while admins manage users and restaurants. Used React, Python, PostgreSQL, AWS, and Docker.
# 🍔 Online Food Delivery Platform

A full-stack food delivery platform where customers can discover restaurants, browse menus, place orders, track their orders, and give reviews. Restaurant partners can manage their menus and orders, while admins can manage users, restaurants, and platform activity.

## 🚀 Features

### 👤 Customer

* User registration and login
* Browse and search restaurants
* View food menus and prices
* Add/remove items from cart
* Place food orders
* Track order status
* View order history
* Rate and review restaurants

### 🏪 Restaurant Partner

* Restaurant dashboard
* Add, edit, and delete food items
* Update food availability and prices
* Accept or reject orders
* Update order status
* View orders and revenue

### 🛡️ Admin

* Admin dashboard
* Manage users and restaurants
* Approve or suspend restaurants
* Monitor platform orders
* View overall platform statistics

## 🛠️ Technologies Used

**Frontend**

* React.js
* Vite
* Axios
* Context API

**Backend**

* Python
* FastAPI
* SQLAlchemy
* Pydantic
* JWT Authentication

**Database**

* PostgreSQL
* SQLite for local development

**Cloud & DevOps**

* AWS EC2
* AWS RDS
* AWS S3
* AWS CloudWatch
* Docker
* Docker Compose
* GitHub Actions

## 🏗️ Project Structure

```text
online-food-delivery/
├── backend/
├── frontend/
├── deploy/
├── .github/
├── docker-compose.yml
└── README.md
```

## 🔐 Authentication

The application uses JWT-based authentication and role-based access control. Different features are available depending on whether the user is a Customer, Restaurant Partner, or Admin.

## 🐳 Running with Docker

Clone the repository:

```bash
git clone <your-repository-url>
cd online-food-delivery
```

Start the application:

```bash
docker-compose up --build
```

The frontend, backend, and PostgreSQL database will run as separate containers.

## ☁️ AWS Deployment

The project can be deployed using AWS services:

* **EC2** – Application hosting
* **RDS** – PostgreSQL database
* **S3** – Food image storage
* **CloudWatch** – Logs and monitoring

## 📌 Future Improvements

* Online payment integration
* Google Maps delivery tracking
* Email/SMS order notifications
* Recommendation system
* Restaurant delivery partner management
* Real-time notifications using WebSockets

## 👨‍💻 Author

**Abhishek Kamboj**

Built as a full-stack software development project to demonstrate React, Python, databases, cloud services, Docker, authentication, and CI/CD.
