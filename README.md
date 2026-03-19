# 🚀 Halleyx Challenge 2 – Dashboard Builder & Order Management System

## 📌 Overview

This project is a full-stack application built for **Halleyx Challenge 2**.

It combines:

* A **drag-and-drop dashboard builder**
* A **customer order management system**

The goal was to build a system that is not just UI, but **functional, interactive, and deployable**.

---

## 🌐 Live Application

* Frontend: https://halleyx-challenge-2-bl35.vercel.app/
* Backend: https://halleyx-backend-zyse.onrender.com

---

## 🎯 Features

### Dashboard Builder

* Drag-and-drop widgets using Angular CDK
* Add, remove, and rearrange components
* Supports KPI cards, charts, and tables
* Responsive layout using SCSS

### Data Visualization

* Charts powered by Chart.js
* Dynamic updates based on data

### Customer Order Module

* Create and manage customer orders
* Handles customer details, product info, and pricing
* Automatic total calculation
* Backend API integration

---

## 🛠️ Tech Stack

**Frontend**

* Angular
* SCSS
* Angular CDK
* Chart.js

**Backend**

* Node.js
* Express.js
* SQLite

**Deployment**

* Vercel (Frontend)
* Render (Backend)

---

## ⚙️ Architecture

* Frontend and backend are separated
* REST APIs connect UI with server
* Backend handles business logic and data storage

---

## 🔗 API Endpoints (Sample)

* `POST /orders` → Create order
* `GET /orders` → Get all orders
* `GET /orders/:id` → Get order by ID
* `PUT /orders/:id` → Update order
* `DELETE /orders/:id` → Delete order

---

## 🚀 Running Locally

### 1. Clone the project

```bash
git clone <your-repo-link>
cd project-root
```

---

### 2. Frontend Setup (Angular)

```bash
cd frontend
npm install
ng serve
```

* Runs on: http://localhost:4200/
* Auto reloads on file changes

---

### 3. Backend Setup (Express)

```bash
cd backend
npm install
npm run dev
```

* Runs API server (default: http://localhost:3000 or your config)

---

## 🧪 Development Commands (Angular)

These are standard Angular CLI commands used in this project:

### Start development server

```bash
ng serve
```

### Generate components

```bash
ng generate component component-name
```

### Build project

```bash
ng build
```

* Output stored in `dist/`
* Production build is optimized

### Run tests

```bash
ng test
```

---

## 💡 Key Highlights

* Built a real-world dashboard system (not static UI)
* Implemented drag-and-drop functionality
* Clean Angular component architecture
* Integrated frontend with backend APIs
* Deployed full-stack application

---

## 👤 Author

Praveen D
Computer Science & Engineering
