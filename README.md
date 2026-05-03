<h1 align="center">Shopora Nexus (शॉपोरा नेक्सस)</h1>
<h3 align="center"> “Everything You Need. All in One Place.” </h3>
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=250&section=header&text=Shopora%20Nexus&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Enterprise%20Multi-Vendor%20E-Commerce%20Platform&descAlignY=55&descAlign=50" />
</p>
Production-ready full-stack eCommerce platform with customer, seller, and admin modules. Built with Java, Spring Boot, React, Redux, and PostgreSQL featuring secure JWT authentication, Stripe payments, product management, order processing, and scalable REST APIs.

Here’s a **FAANG-level System Design + Project Documentation (README-ready)** for **Shopora Nexus (शॉपोरा नेक्सस)** including **problem statement, solution, architecture, features, workflow, scalability, and tech stack with icons style**.

You can directly paste this into your GitHub README.

---

# 🛍️ Shopora Nexus (शॉपोरा नेक्सस)

🚀 Enterprise Multi-Vendor Full-Stack E-Commerce Platform
Built using Spring Boot + React + AWS with scalable microservices architecture.

---

# 📌 1. Problem Statement

In traditional e-commerce systems, platforms often suffer from several structural and architectural limitations that impact scalability, security, and overall efficiency. Most existing solutions are not designed to handle a growing ecosystem of multiple vendors, which leads to bottlenecks when the user base and product catalog expand. Additionally, there is often weak or poorly implemented role-based access control, resulting in confusion between admin, seller, and customer responsibilities. Security is another major concern, as many systems rely on outdated or insufficient authentication mechanisms, making them vulnerable to unauthorized access. Product and order management processes are frequently inefficient and not optimized for real-time updates or large-scale operations. Furthermore, most traditional platforms lack a subscription-based monetization model, limiting their ability to generate recurring revenue streams. Finally, many of these systems are not built with cloud-native principles, which restricts their scalability, deployment flexibility, and ability to handle modern production-level workloads effectively.

👉 There is a need for a **scalable, secure, multi-vendor marketplace system** that supports real-world enterprise requirements like Amazon or Flipkart.

---

# 💡 2. Solution Overview

Shopora Nexus solves these problems by introducing:

Shopora Nexus addresses these limitations by introducing a modern, scalable, and secure e-commerce architecture designed for real-world production use. It implements a multi-vendor marketplace structure that allows seamless onboarding and management of multiple sellers on a single platform. The system follows a strict role-based access model, clearly separating functionalities for customers, sellers, and administrators to ensure controlled and secure operations. Security is strengthened through a JWT-based authentication system, providing stateless and reliable user session management. The backend is built using a scalable Spring Boot microservices-oriented architecture, enabling high performance and modular development. For payments, it integrates a Stripe-based secure payment gateway, ensuring safe and efficient transaction processing. The platform is also designed with a cloud-ready AWS deployment architecture, supporting scalability, reliability, and high availability. Additionally, Shopora Nexus is structured to support a subscription-based SaaS expansion model, enabling future monetization and enterprise-level growth.

---

# 🧠 3. Introduction

Shopora Nexus is a **full-stack enterprise e-commerce platform** designed to simulate real-world marketplace systems. It supports product listing, cart management, secure payments, order tracking, and admin analytics.

The system is built using **modern software engineering principles** including:

* Layered architecture (Controller → Service → Repository)
* Microservices-ready backend design
* Cloud-native deployment (AWS)
* Secure authentication and authorization system

---

# ⚙️ 4. Tech Stack (With Icons)

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=24&duration=2500&pause=700&color=00F5FF&center=true&vCenter=true&width=900&lines=⚡+EcommerceHub+Full+Stack+Tech+Stack;🚀+Enterprise+Grade+System+Design;🔥+Spring+Boot+%7C+React+%7C+AWS+%7C+Docker" />

<br><br>

<!-- FRONTEND -->
<h2>🖥️ Frontend</h2>

<img src="https://skillicons.dev/icons?i=react,redux,tailwind,html,css,js,ts,nextjs,vite,figma,webpack,babel" 
style="filter: drop-shadow(0px 0px 10px #00f5ff);" />

<br>

⚛️ React.js → UI | 🔄 Redux → State | 🎨 Tailwind → Styling | 🌐 HTML/CSS → Structure | 📜 JS/TS → Logic | ⚡ Next.js → SSR | ⚡ Vite → Build | 📦 Webpack → Bundling | 🔧 Babel → Transpiling | 🎨 Figma → UI Design  

<br><br>

<!-- BACKEND -->
<h2>🔧 Backend</h2>

<img src="https://skillicons.dev/icons?i=java,spring,nodejs,express,hibernate,graphql,python,flask" 
style="filter: drop-shadow(0px 0px 10px #00ff99);" />

<br>

☕ Java → Core | 🌱 Spring Boot → Framework | 🔐 Spring Security → Auth | 🧩 Hibernate/JPA → ORM | 🟢 Node.js → Runtime | ⚙️ Express → APIs | 🔗 GraphQL → Queries | 🐍 Python → Services | 🌶️ Flask → Microservices  

<br><br>

<!-- DATABASE -->
<h2>🗄️ Database</h2>

<img src="https://skillicons.dev/icons?i=postgresql,mysql,mongodb,redis,firebase,sqlite" 
style="filter: drop-shadow(0px 0px 10px #4db8ff);" />

<br>

🐘 PostgreSQL → SQL DB | 🐬 MySQL → Relational | 🍃 MongoDB → NoSQL | ⚡ Redis → Cache | 🔥 Firebase → Realtime | 🪶 SQLite → Local DB  

<br><br>

<!-- CLOUD & DEVOPS -->
<h2>☁️ Cloud & DevOps</h2>

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,jenkins,linux,nginx,terraform,gcp" 
style="filter: drop-shadow(0px 0px 10px #ffcc00);" />

<br>

☁️ AWS EC2 → Deploy | 📦 S3 → Storage | 🗄️ RDS → DB Hosting | 🐳 Docker → Containers | ☸️ Kubernetes → Orchestration | ⚙️ Jenkins → CI/CD | 🐧 Linux → Server | 🌐 Nginx → Proxy | 🏗️ Terraform → Infra as Code | 🌍 GCP → Cloud  

<br><br>

<!-- TESTING -->
<h2>🧪 Testing & API Tools</h2>

<img src="https://skillicons.dev/icons?i=postman,jest,cypress,selenium" 
style="filter: drop-shadow(0px 0px 10px #ff4dff);" />

<br>

📮 Postman → API Testing | 🧪 Jest → Unit Testing | 🤖 Cypress → E2E | 🧭 Selenium → Automation  

<br><br>

<!-- TOOLS -->
<h2>🧑‍💻 Tools</h2>

<img src="https://skillicons.dev/icons?i=git,github,vscode,idea,maven,gradle,npm,yarn,linux" 
style="filter: drop-shadow(0px 0px 10px #ffffff);" />

<br>

🧑‍💻 Git/GitHub → VCS | 💻 VS Code/IntelliJ → IDE | 📦 Maven/Gradle → Build | 📦 npm/yarn → Packages | 🐧 Linux → CLI  

<br><br>

<!-- SECURITY -->
<h2>🔐 Security</h2>

🔐 JWT → Tokens | 🔑 OAuth2 → Auth Flow | 🛡️ Spring Security → Protection  

<!-- INTEGRATIONS -->
<h2>💳 Integrations</h2>

💳 Stripe → Payments | 📧 Mailchimp → Emails | 📲 Twilio → SMS/OTP Services  
</div>

---

# 🧭 5. Core Modules & Features

## 👤 Authentication System

* 🔑 **Register new user** → Creates a new user account in the system
* 🔐 **Login / Logout** → Authenticates user and manages active session
* 🚪 **Sign-in / Sign-out** → Controls secure entry and exit from the platform
* 🛡️ **JWT-based secure authentication** → Issues and validates secure token-based access
* 👮 **Role-based access (User / Seller / Admin)** → Restricts features based on assigned user roles

---

## 🛍️ Product Module

* 🔑 **Register new user** → Creates a new user account in the system
* 🔐 **Login / Logout** → Authenticates user and manages active session
* 🚪 **Sign-in / Sign-out** → Controls secure entry and exit from the platform
* 🛡️ **JWT-based secure authentication** → Issues and validates secure token-based access
* 👮 **Role-based access (User / Seller / Admin)** → Restricts features based on assigned user roles

---

## 🛒 Cart System

* ➕ **Add product (Seller)** → Allows sellers to list new products on the platform
* ✏️ **Update product** → Enables editing of existing product details and pricing
* ❌ **Delete product** → Removes products from the marketplace inventory
* 🔍 **Search & filter products** → Helps users find products using keywords and filters
* 📦 **Category management** → Organizes products into structured categories for easy browsing


---

## 📦 Order System

* 🧾 **Place order** → Allows customers to create and confirm purchases
* 📍 **Track order status** → Provides real-time updates on order progress
* 📜 **Order history** → Displays all past orders for user reference
* 🔁 **Order lifecycle management** → Manages full order flow from placement to delivery and completion

---

## 💳 Payment System

* 💳 **Stripe payment integration** → Enables secure online payments using Stripe API
* 🔒 **Secure transaction processing** → Ensures encrypted and safe financial transactions
* 💰 **Refund handling** → Manages customer refunds and payment reversals
* 📊 **Payment status tracking** → Tracks real-time payment success, failure, and pending states

---

## 👨‍💼 User Roles
Here are **short one-line role descriptions for each point**:

* 🔑 **Register new user** → Creates a new user account in the system
* 🔐 **Login / Logout** → Authenticates user and manages active session
* 🚪 **Sign-in / Sign-out** → Controls secure entry and exit from the platform
* 🛡️ **JWT-based secure authentication** → Issues and validates secure token-based access
* 👮 **Role-based access (User / Seller / Admin)** → Restricts features based on assigned user roles
* 
---

## 👤 Customer User 

* Browse products → Allows users to explore available products
* Add to cart → Enables adding items to shopping cart for purchase
* Place orders → Confirms purchase and creates an order
* View profile → Displays personal account details and activity
  
<div align="center">
  <img src="DOCS LISCENCED/SUB DIRECTORY/User1.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/User2.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/User3.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/User4.png" width="400" style="margin: 10px;">

   <img src="DOCS LISCENCED/SUB DIRECTORY/User5.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/User6.png" width="400" style="margin: 10px;">
</div>

---

## 🛒 Seller Panel

* Manage products → Handles creation, update, and removal of products
* Track sales → Monitors total sales and performance metrics
* Inventory control → Maintains stock levels and availability

<div align="center">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Seller1.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Seller2.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Seller3.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Seller4.png" width="400" style="margin: 10px;">
</div>
---

## 🧑‍💼 Admin Panel

* User management → Controls user accounts and access permissions
* Product moderation → Reviews and approves product listings
* System analytics → Analyzes platform performance and usage data
* Platform control → Oversees overall system operations and governance

<div align="center">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin1.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin2.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin3.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin4.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin5.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin6.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin7.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin8.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin9.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin10.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin11.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin12.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin13.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Admin14.png" width="400" style="margin: 10px;">
</div>

---

## 🛒 Cart Section

* Cart management → Review selected products, quantities, and pricing
* Cart invoice → Displays subtotal, taxes, discounts, and final payable amount
* Payment method selection → Choose secure payment options like Stripe or PayPal
* Final payment → Complete transaction on Stripe/PayPal and receive order/payment confirmation

<div align="center">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart1.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart2.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart3.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart4.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart5.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart6.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart7.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart8.png" width="400" style="margin: 10px;">

  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart9.png" width="400" style="margin: 10px;">
  <img src="DOCS LISCENCED/SUB DIRECTORY/Cart10.png" width="400" style="margin: 10px;">
</div>

---

## 👤 Profile System

* 🧑 Avatar profile upload → Allows users to set and update profile image
* ✏️ Edit profile details → Enables updating personal information
* 📊 Order history view → Shows all past purchases and transactions
* 🔐 Secure account settings → Manages password and security preferences

---

## 📄 Static Pages

* ℹ️ About page → Provides information about the platform and mission
* 📞 Contact page → Enables users to reach support and submit queries

---

---

# 🔄 6. Workflow (System Flow)

## 🧭 User Flow

```text id="w3kflow"
Register/Login → Browse Products → Add to Cart → Checkout → Payment (Stripe) → Order Confirmation → Email Notification
```

## 🧑‍💼 Seller Flow

```text id="sellerflow"
Login → Add Product → Manage Inventory → Track Orders → View Earnings
```

## 🧑‍💻 Admin Flow

```text id="adminflow"
Login → Manage Users → Approve Products → Monitor Orders → Analytics Dashboard
```

---

# 🏗️ 7. Backend Architecture

```text id="archflow"
Controller → Service → Repository → PostgreSQL
```

✔ Clean separation of concerns
✔ Scalable microservices-ready structure
✔ REST API-based communication
✔ Secure backend design

---

# ☁️ 8. Cloud Architecture

```text
🌐 Frontend (React on CDN) → 🚪 API Gateway (Routing + JWT Validation) → ⚙️ Backend (Spring Boot on AWS EC2) → 🗄️ PostgreSQL (AWS RDS) → 📦 AWS S3 (Images / Files)
```
---

# 🚀 9. Future Scalability

## 💰 Subscription Model (SaaS Expansion)

                              ┌────────────────────────────────┐
                              │        🌐 CLIENT LAYER         │
                              │   React.js / Mobile App UI     │
                              └───────────────┬────────────────┘
                                              │
                                              ▼

                          ┌──────────────────────────────────────┐
                          │     ☁️ API GATEWAY (AWS ALB)         │
                          │  Routing • Load Balancing • Auth     │
                          └───────────────┬──────────────────────┘
                                          │
        ┌─────────────────────────────────┼─────────────────────────────────┐
        ▼                                 ▼                                 ▼

┌──────────────────────┐     ┌──────────────────────┐     ┌──────────────────────┐
│ 👤 USER SERVICE      │     │ 🛒 PRODUCT SERVICE   │     │ 📦 ORDER SERVICE    │
│ Spring Boot          │     │ Spring Boot          │     │ Spring Boot          │
│ JWT Auth / RBAC      │     │ Catalog / CRUD       │     │ Cart / Orders        │
└─────────┬────────────┘     └─────────┬────────────┘     └─────────┬────────────┘
          │                            │                            │
          ▼                            ▼                            ▼

┌──────────────────────┐     ┌──────────────────────┐     ┌──────────────────────┐
│ 💳 PAYMENT SERVICE   │     │ 🏪 SELLER SERVICE   │     │ 📊 ANALYTICS SERVICE │
│ Stripe Integration   │     │ Inventory Control    │     │ Reports / Insights   │
│ Transactions/Refunds │     │ Listings / Pricing   │     │ AI Insights Ready    │
└─────────┬────────────┘     └─────────┬────────────┘     └─────────┬────────────┘
          │                            │                            │
          └──────────────┬─────────────┴──────────────┬────────────┘
                         ▼                             ▼

        ┌──────────────────────────────┐   ┌──────────────────────────────┐
        │ ⚡ EVENT BUS (Kafka)         │   │ 🔐 AUTH SERVICE             │
        │ Real-time Event Streaming     │   │ JWT / OAuth2 Security       │
        └──────────────┬───────────────┘   └──────────────┬───────────────┘
                       ▼                                  ▼

        ┌──────────────────────────────────────────────────────────────┐
        │ 🗄️ DATA LAYER                                                │
        │ PostgreSQL • MySQL • MongoDB • Redis (Caching Layer)         │
        └──────────────────────────────┬───────────────────────────────┘
                                       ▼

        ┌──────────────────────────────────────────────────────────────┐
        │ ☁️ AWS CLOUD INFRASTRUCTURE                                  │
        │ EC2 → Compute Servers                                        │
        │ S3 → Image & File Storage                                    │
        │ RDS → Managed Database                                       │
        │ Lambda → Event Processing                                    │
        │ CloudWatch → Monitoring & Logs                               │
        │ Kubernetes (EKS) → Container Orchestration                   │
        └──────────────────────────────────────────────────────────────┘

---

## 📈 Scalability Enhancements

* 🔄 **Microservices expansion** → Enables scalable system growth by splitting services into independent modules
* ⚡ **Kafka event-driven architecture** → Supports real-time data flow and asynchronous communication between services
* 🧠 **AI product recommendation system** → Provides personalized product suggestions based on user behavior
* 📱 **Mobile app (React Native)** → Extends platform access to Android and iOS users via a unified mobile app
* ☁️ **Kubernetes deployment** → Ensures container orchestration for scalable, reliable cloud deployment

---

## 💼 Subscription-Based Model

* 💳 **Tiered subscription plans** → Offers Basic, Pro, and Enterprise plans for different user needs
* 🏪 **Seller premium plans** → Provides advanced tools like analytics, promotion, and priority listing
* 🚀 **Priority features access** → Unlocks exclusive features based on subscription level
* 📊 **Revenue analytics dashboard** → Tracks subscription earnings and user engagement metrics
* 🔐 **Role-based subscription control** → Restricts or enables features based on active plan level


---

# 🧾 10. Summary

Shopora Nexus is a **production-grade enterprise e-commerce platform** built with scalability, security, and cloud-native architecture in mind. It demonstrates strong expertise in full-stack development, backend system design, REST API development, AWS deployment, and real-world SaaS architecture.

---

# 🏗️ System Architecture Diagram — Shopora Nexus

## ☁️ High-Level AWS + Microservices Flow

```text id="a9xkq1"
                         ┌────────────────────────────┐
                         │        Frontend (React)     │
                         │   Redux Toolkit + UI Layer  │
                         └─────────────┬──────────────┘
                                       │
                                       ▼
                         ┌────────────────────────────┐
                         │       API Gateway Layer     │
                         │ JWT Auth | Rate Limiting    │
                         │ Request Routing Layer       │
                         └─────────────┬──────────────┘
                                       │
        ┌──────────────────────────────┼──────────────────────────────┐
        ▼                              ▼                              ▼
┌────────────────┐        ┌────────────────┐        ┌────────────────┐
│ User Service   │        │ Product Service│        │ Order Service  │
│ Spring Boot    │        │ Spring Boot    │        │ Spring Boot    │
│ Auth / RBAC    │        │ Catalog / CRUD │        │ Cart / Orders  │
└──────┬─────────┘        └──────┬─────────┘        └──────┬─────────┘
       │                         │                         │
       └──────────────┬──────────┴──────────┬──────────────┘
                      ▼                     ▼
            ┌────────────────────────────────────┐
            │         Payment Service             │
            │     Stripe Integration Layer        │
            └────────────────────────────────────┘
                      │
                      ▼
            ┌────────────────────────────────────┐
            │         Notification Service        │
            │      Email / Alerts System         │
            └────────────────────────────────────┘

                      ▼
        ┌────────────────────────────────────────┐
        │        Database Layer (PostgreSQL)     │
        │  JPA / Hibernate ORM Mapping           │
        │  Normalized Relational Schema          │
        └────────────────────────────────────────┘

                      ▼
        ┌────────────────────────────────────────┐
        │        AWS Cloud Infrastructure        │
        │ EC2 (Backend Deployment)              │
        │ S3 (File Storage)                     │
        │ RDS (Database Hosting)                │
        └────────────────────────────────────────┘
```
---

# ⚙️ Architecture Explanation (README Section)

Shopora Nexus follows a **cloud-native microservices-ready architecture** where the frontend communicates with backend services through a secure API Gateway. Each backend module (User, Product, Order, Payment) is built using **Spring Boot** and follows a strict **Controller → Service → Repository** pattern.

All services are secured using **JWT-based authentication with Spring Security**, ensuring stateless and scalable request handling. The **API Gateway** acts as the central entry point, handling routing, authentication validation, and request throttling.

The system uses **PostgreSQL as the primary database**, managed via **JPA/Hibernate ORM**, ensuring strong relational data consistency and optimized query performance.

For payment processing, the **Stripe API** is integrated as a dedicated service, while notifications are handled via an email service layer. The entire backend is deployed on **AWS Cloud (EC2, S3, RDS)**, making the system production-ready and scalable.
<br>
<img src="DOCS LISCENCED/ARCHITECTURE.png" align="center">

---

---

# 🔐 1. JWT Authentication Flow Diagram

```
            ┌────────────────────────────┐
            │        Frontend App        │
            │   (React / Mobile UI)      │
            └────────────┬───────────────┘
                         │ Login (email/password)
                         ▼
            ┌────────────────────────────┐
            │     Auth Controller        │
            │   Spring Boot API Layer    │
            └────────────┬───────────────┘
                         │ Validate Credentials
                         ▼
            ┌────────────────────────────┐
            │        User Service        │
            │   DB Check (users table)   │
            └────────────┬───────────────┘
                         │ valid user
                         ▼
            ┌────────────────────────────┐
            │     JWT Token Generator    │
            │   (Secret Key Signing)     │
            └────────────┬───────────────┘
                         │ JWT Token
                         ▼
            ┌────────────────────────────┐
            │        Frontend App        │
            │ Store Token (LocalStorage) │
            └────────────┬───────────────┘
                         │
                         ▼
        ┌────────────────────────────────────┐
        │  Future Requests (Authenticated)   │
        │  Authorization: Bearer JWT Token  │
        └────────────────────────────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │  JWT Filter / Middleware    │
            │  (Token Validation Layer)   │
            └────────────────────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │   Secure API Access Granted │
            └────────────────────────────┘
```
<p align="left">
  In this project, authentication is handled using JWT (JSON Web Token) to ensure secure and stateless user sessions. When a user logs in through the frontend application (built using React or mobile UI), their credentials are sent to the backend Auth Controller developed in Spring Boot. The controller forwards the request to the User Service, where the system validates the credentials against the database.
  <br>

<img src="DOCS LISCENCED/JWT WORKING.png" align="center">

If the user details are correct, a JWT token is generated using a secure secret key. This token contains important user information such as user ID, role (USER / ADMIN / SELLER), and expiration time. The generated token is returned to the frontend and stored securely in local storage or session storage.

For every subsequent API request, the frontend includes this token in the request header as a Bearer Token. On the backend, a JWT filter (middleware) intercepts incoming requests and validates the token’s signature and expiry. If the token is valid, the request is allowed to access protected resources; otherwise, access is denied. This ensures secure, scalable, and stateless authentication across the system.
</p>

# 💳 2. Stripe Payment Sequence Diagram

```
            ┌────────────────────────────┐
            │        Frontend App        │
            │  Checkout Button Click     │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │     Order Service API      │
            │  /create-payment-intent    │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │      Stripe Service        │
            │  Create Payment Intent     │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │        Stripe API          │
            │   (Card Validation etc.)   │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │  Payment Intent Response   │
            │   client_secret returned   │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │        Frontend App        │
            │ Stripe.js confirms payment │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │     Stripe Webhook         │
            │  payment_success / fail    │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │     Order Service DB       │
            │  Update Order Status       │
            └────────────┬───────────────┘
                         │
                         ▼
            ┌────────────────────────────┐
            │   Email / Notification     │
            │  Order Confirmation Sent   │
            └────────────────────────────┘
```
<p align="left">
  The payment system is implemented using Stripe API for secure and reliable transactions. When a user clicks the checkout button, the frontend sends a request to the backend Order Service API to create a payment intent.

The backend communicates with Stripe using its SDK and creates a payment intent with details such as amount, currency, and order ID. Stripe processes this request and performs necessary validations including card verification, balance checks, and fraud detection mechanisms.

Once the payment intent is created successfully, Stripe returns a client_secret, which is passed back to the frontend. The frontend uses Stripe.js to securely confirm the payment without exposing sensitive card details, ensuring PCI compliance.

After payment processing, Stripe sends a webhook event to the backend indicating success or failure of the transaction. Based on this event, the Order Service updates the order status in the database (PENDING → PAID → FAILED). Finally, the system triggers an email/notification service to send order confirmation to the user, completing the full payment lifecycle securely and efficiently.
</p>

<div align="center">
🏗️ System Workflow & ER Diagram
</div>

<p align="center">
  A complete overview of the platform architecture, request lifecycle, database relationships, 
  and how each component interacts across frontend, backend, storage, and security layers.
</p>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="DOCS LISCENCED/ER DIAGRAM.png" width="100%" />
      <br/><br/>
      <b>⚙️ Complete System Workflow</b>
      <br/>
      <sub>
        Frontend requests flow through API Gateway, authenticated via JWT, 
        processed by Spring Boot microservices, connected to database and storage.
      </sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="DOCS LISCENCED/COMPLETE WORKFLOW.png" width="100%" />
      <br/><br/>
      <b>⚙️ Complete System Workflow</b>
      <br/>
      <sub>
        Frontend requests flow through API Gateway, authenticated via JWT, 
        processed by Spring Boot microservices, connected to database and storage.
      </sub>
    </td>
  </tr>
</table>


<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=footer&text=Thanks%20for%20Visiting%20&fontSize=34&fontColor=ffffff&animation=fadeIn&fontAlignY=70" width="100%"/>💖

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=Built+with+Passion+%F0%9F%92%8E;Code+%7C+Innovation+%7C+Growth;See+You+Again+" />
</div>
<div align="center">

<a href="https://github.com/BlockNotes-4515/YOUR_REPO/stargazers">
  <img src="https://img.shields.io/badge/⭐%20Star%20This%20Repo-111111?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://github.com/sponsors/YOUR_USERNAME">
  <img src="https://img.shields.io/badge/💖%20Sponsor%20Me-e91e63?style=for-the-badge&logo=githubsponsors&logoColor=white" />
</a>

<a href="https://github.com/BlockNotes-4515/YOUR_REPO/issues/new">
  <img src="https://img.shields.io/badge/💡%20Give%20Suggestion-0A66C2?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://github.com/BlockNotes-4515/YOUR_REPO/fork">
  <img src="https://img.shields.io/badge/🍴%20Fork%20Repo-6f42c1?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://github.com/BlockNotes-4515?tab=followers">
  <img src="https://img.shields.io/badge/👀%20Follow%20Me-16a34a?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>
