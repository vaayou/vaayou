# Hey, I'm Pawan Raj! 👋

### Java Backend Developer | Microservices | Cloud | AI Enthusiast

Building full-stack applications, designing distributed systems, and deploying real-world projects to the cloud. 🚀

* 💼 Software Engineer at **Capgemini**, contributing to banking applications for **Standard Chartered Bank**
* ☕ Working with **Java, Spring Boot, REST APIs, GraphQL, and Microservices**
* ⚡ Exploring **Apache Kafka, event-driven architecture, Spring AI, and AI agents**
* ☁️ Deploying applications using **Docker, AWS, and cloud platforms**
* 🔭 Building projects that combine backend engineering, distributed systems, and modern UI

---

## 🌐 Connect with Me

<p align="left">
  <a href="https://github.com/vaayou">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/vaayou/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

# 🚀 Featured Projects

## 1. 📦 Order Inventory System

**A full-stack order and inventory management platform with a cloud-hosted Spring Boot backend and React frontend.**

<p align="center">
  <a href="https://ordermanage7.netlify.app/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Visit_Application-00C853?style=for-the-badge" alt="Live Demo"/>
  </a>
  <a href="https://github.com/vaayou/OrderInventorySystem">
    <img src="https://img.shields.io/badge/GitHub-Source_Code-181717?style=for-the-badge&logo=github" alt="Source Code"/>
  </a>
  <a href="https://foil-poinsettia-75d.notion.site/Order-Inventory-74bdd4829f9f4e41a25a510e7c5dd6f8">
    <img src="https://img.shields.io/badge/Notion-LLD_Document-black?style=for-the-badge&logo=notion" alt="LLD"/>
  </a>
</p>

### ✨ Key Features

* 📊 Interactive dashboard with inventory and order summaries
* 👥 Customer management with CRUD operations, search, and order histories
* 📦 Product catalog, inventory tracking, and stock visibility
* 🚚 Order fulfillment and shipment status tracking
* 🔎 REST APIs for customers, products, orders, and inventory
* 🔐 MySQL database connectivity secured with SSL/TLS
* 📱 Responsive React interface for desktop, tablet, and mobile

### 🏗️ Architecture & Deployment

| Component         | Technology                                | Hosting              |
| ----------------- | ----------------------------------------- | -------------------- |
| Frontend          | React 19, Vite, Material UI, Tailwind CSS | Netlify              |
| Backend           | Java 21, Spring Boot 3.5, Spring Data JPA | Render               |
| Database          | MySQL 8                                   | Aiven Cloud          |
| Security          | SSL/TLS database connection               | Aiven CA certificate |
| API Documentation | SpringDoc OpenAPI / Swagger               | Spring Boot          |

### 🔗 Useful Links

* **Live application:** https://ordermanage7.netlify.app/
* **Backend API:** https://orderinventorysystem-1y9i.onrender.com/api/v1/customers
* **Health endpoint:** https://orderinventorysystem-1y9i.onrender.com/api/health
* **Low-Level Design:** [Read the LLD](https://foil-poinsettia-75d.notion.site/Order-Inventory-74bdd4829f9f4e41a25a510e7c5dd6f8)

**What this project demonstrates:** Full-stack development, REST API design, relational data modeling, Docker-based deployment, cloud database integration, and secure database connectivity.

---

## 2. 🏆 Owned OS — Microservices E-Commerce Platform

**An event-driven e-commerce and digital asset management platform built using Spring Boot microservices, Kafka, and a containerized AWS deployment.**

<p align="center">
  <a href="http://3.6.39.23/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Explore_Owned_OS-00C853?style=for-the-badge" alt="Live Demo"/>
  </a>
  <a href="https://hub.docker.com/u/heavycoder">
    <img src="https://img.shields.io/badge/Docker_Hub-Container_Images-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Hub"/>
  </a>
  <a href="https://github.com/vaayou">
    <img src="https://img.shields.io/badge/GitHub-Explore_Repositories-181717?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
</p>

### ✨ Key Features

* 🔐 User registration, authentication, JWT access tokens, and refresh tokens
* 🛍️ Product catalog with category filtering and 150+ product listings
* 🛒 Shopping cart, checkout, order history, and wallet-based purchases
* 💳 Payment workflow integration hooks for UPI, Stripe, and Razorpay
* 📚 Digital asset collection automatically updated from completed orders
* ⚡ Asynchronous communication using Apache Kafka
* 🔍 Dynamic service discovery with Netflix Eureka
* 🛡️ Centralized API routing and JWT validation through Spring Cloud Gateway
* 📦 Dockerized microservices deployed on AWS EC2

### 🏗️ Microservices Architecture

| Service            | Responsibility                                          |
| ------------------ | ------------------------------------------------------- |
| Eureka Server      | Service discovery and registration                      |
| API Gateway        | Request routing, JWT validation, and CORS               |
| User Service       | Authentication, profiles, and notifications             |
| Commerce Service   | Products, orders, checkout, wallet, and payments        |
| Collection Service | Digital asset ownership and collection management       |
| React Frontend     | E-commerce UI, shopping cart, checkout, and collections |
| Kafka              | Asynchronous events and service decoupling              |
| MySQL              | Persistent storage across service-specific databases    |

### 🔄 Event-Driven Order Flow

1. A user completes a purchase through the Commerce Service.
2. The service publishes an order-completed event to Kafka after the database transaction commits.
3. The Collection Service consumes the event asynchronously.
4. Purchased items are added to the user's digital collection.

This separates order processing from asset fulfillment and demonstrates asynchronous communication between independently deployed services.

### ☁️ Cloud Deployment

* **Cloud provider:** AWS EC2
* **Containerization:** Docker and Docker Compose
* **Reverse proxy:** Nginx
* **Service discovery:** Netflix Eureka
* **Messaging:** Apache Kafka in KRaft mode
* **Database:** MySQL
* **Image registry:** Docker Hub

**What this project demonstrates:** Microservices architecture, API gateway patterns, JWT authentication, event-driven communication, Kafka producers and consumers, Docker networking, cloud deployment, and service-to-service integration.

> The live demo currently uses HTTP. Avoid entering real passwords or payment details unless secure handling has been verified. Availability of the demo depends on the EC2 instance remaining online.

---

## 💻 Languages and Tools

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="42" alt="Java"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="42" alt="Spring Boot"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="42" alt="MySQL"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" height="42" alt="Apache Kafka"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="42" alt="Redis"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="42" alt="Docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg" height="42" alt="Kubernetes"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="42" alt="AWS"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="42" alt="React"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="42" alt="JavaScript"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="42" alt="Git"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="42" alt="Python"/>
</p>

**Backend:** Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, REST APIs, GraphQL, Microservices

**Messaging & Data:** Apache Kafka, MySQL, Redis, SQL, Event-Driven Architecture

**Cloud & DevOps:** Docker, Docker Compose, AWS EC2, Nginx, Netlify, Render, Aiven, Git

**Frontend:** React, Vite, JavaScript, Material UI, Tailwind CSS

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=vaayou&show_icons=true&theme=tokyonight&hide_border=true" alt="Pawan's GitHub Stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vaayou&layout=compact&theme=tokyonight&hide_border=true" alt="Most Used Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vaayou&theme=tokyonight&hide_border=true" alt="GitHub Contribution Streak"/>
</p>

---

## 🐍 My Contributions — Snake Game

Watch the snake hunt down my GitHub contribution cells!

<p align="center">
  <img src="https://raw.githubusercontent.com/vaayou/vaayou/output/snake.svg" alt="Animated GitHub contribution snake" width="100%"/>
</p>

<p align="center">
  <i>Every commit feeds the snake. Keep coding! 🚀</i>
</p>

---

<p align="center">
  <i>"Build consistently. Learn relentlessly. Ship boldly."</i>
</p>
