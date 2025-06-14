
# Post-Retirement Finance Plan Tracker

A full-stack web application aimed at helping individuals plan their finances post-retirement. The system allows users to register, log in, enter their financial details, and receive insights on managing their future expenses and savings. This solution is built using modern web development technologies with a strong emphasis on security, performance, and user experience.

---

## 📌 Project Overview

This platform empowers users to simulate and analyze their financial standing after retirement. By inputting monthly expenses, savings, and investments, the application provides a comprehensive overview of financial readiness. It supports secure user authentication, intuitive dashboards, and easy data management through a MySQL-backed PHP server.

---

## 🧰 Tech Stack

### 🌐 Frontend
- **HTML5** – Semantic structure and accessibility
- **CSS3** – Responsive and consistent styling
- **JavaScript (Vanilla)** – Interactive UI and form validations

### 🔧 Backend
- **PHP (Core PHP)** – Server-side logic and database handling
- **MySQL** – Relational database for storing user credentials and financial data

### 🗃️ Database
- MySQL schema with tables for:
  - `users` (authentication)
  - `plans` (user financial data)
  - `expenses`, `investments` (detailed breakdown)

### ⚙️ Server Environment
- Recommended: **XAMPP / WAMP / LAMP**
- Apache server to run PHP
- MySQL for DB handling

---

## 📂 Directory Structure

```
Post-Retirement-Finance-Plan/
│
├── assets/               # Static files (CSS & JS)
│   ├── css/
│   └── js/
│
├── database/
│   └── finance_plan.sql  # SQL dump for DB schema and test data
│
├── includes/
│   ├── connection.php    # DB connection handler
│   └── functions.php     # Reusable PHP functions
│
├── pages/
│   ├── dashboard.php     # Financial overview & analytics
│   ├── login.php         # User authentication
│   ├── register.php      # User registration
│   └── plan.php          # Financial planning input form
│
├── images/               # Static image assets
├── index.php             # Landing page (redirects to login or dashboard)
```

---

## 🔒 Key Features

- ✅ **User Authentication** (Registration, Login, Session Management)
- 📈 **Financial Planning Dashboard** to input and review savings & investment data
- 🧮 Real-time **financial projections** based on user inputs
- 📊 **Data analytics** for expenses and savings (future scope includes charts)
- 🛡️ Secure form submissions and input sanitization

---

## 🚀 Getting Started

### Prerequisites
- PHP ≥ 7.2
- MySQL Server
- Apache (via XAMPP, WAMP, or native setup)

### Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Akhil70722/Post-Retirement-Finance-Plan.git
   ```

2. **Move Project to Server Directory**
   - For XAMPP: `C:\xampp\htdocs\Post-Retirement-Finance-Plan`
   - For WAMP: `C:\wamp\www\Post-Retirement-Finance-Plan`

3. **Import the Database**
   - Open phpMyAdmin
   - Create a database named `finance_plan`
   - Import `database/finance_plan.sql`

4. **Configure Database Credentials**
   - Open `includes/connection.php`
   - Update `servername`, `username`, `password`, and `dbname` as per your setup

5. **Run the Application**
   - Visit: [http://localhost/Post-Retirement-Finance-Plan/](http://localhost/Post-Retirement-Finance-Plan/)

---

## 📊 Planned Enhancements

- Integrate **Chart.js** or **Google Charts** for data visualization
- Export reports to **PDF**
- Add **Email Notifications** for reminders and savings tips
- Introduce **AI-based financial suggestions** using ML
- Make it **mobile responsive** with Bootstrap or Tailwind CSS

---
