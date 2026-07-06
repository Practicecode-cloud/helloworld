<div align="center">

# 🏨 Hotel Management System

### A Modern Full Stack Hotel Management System

<img src="https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge&logo=node.js">
<img src="https://img.shields.io/badge/Express.js-Backend-black?style=for-the-badge&logo=express">
<img src="https://img.shields.io/badge/PostgreSQL-Neon-blue?style=for-the-badge&logo=postgresql">
<img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-orange?style=for-the-badge">

---

A complete **Hotel Management System** developed using **Node.js**, **Express.js**, **PostgreSQL (Neon Database)**, and **Vanilla JavaScript**.

Designed to simplify hotel operations by managing hotels, branches, rooms, reservations, guests, employees, billing, housekeeping, maintenance, payments, and services through RESTful APIs.

</div>

---

# 📸 Preview

> Dashboard showing hotel analytics, reservations, room management, payments, and more.

*(Add screenshots here later)*

---

# ✨ Features

### 🏨 Hotel Management
- Create Hotel
- Update Hotel
- Delete Hotel
- View Hotels

### 🌍 Branch Management
- Multiple Branch Support
- Branch Information
- Branch CRUD

### 🛏 Room Management
- Room Types
- Room Availability
- Room Status
- Room CRUD

### 👤 Guest Management
- Register Guests
- Update Guest Details
- Search Guests
- Delete Guests

### 📅 Reservation System
- Book Rooms
- Cancel Reservations
- Reservation History
- Check Availability

### 💳 Payment Management
- Payment Records
- Multiple Payment Methods
- Payment History

### 🧾 Billing System
- Generate Bills
- Service Charges
- Room Charges
- Taxes

### 👨‍💼 Employee Management
- Employee Records
- Departments
- Salary Information

### 🧹 Housekeeping
- Cleaning Schedule
- Room Status
- Staff Assignment

### 🔧 Maintenance
- Maintenance Requests
- Issue Tracking
- Repair Status

### 🛎 Guest Services
- Service Requests
- Room Service
- Additional Services

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| 🟢 Node.js | Backend Runtime |
| ⚡ Express.js | REST API |
| 🐘 PostgreSQL | Database |
| ☁️ Neon DB | Cloud Database |
| 🌐 HTML5 | Frontend |
| 🎨 CSS3 | Styling |
| ⚙️ JavaScript | Frontend Logic |

---

# 📁 Project Structure

```
HotelManagementSystem
│
├── Api
│   │
│   ├── routes
│   ├── controllers
│   ├── db.js
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   └── .env
│
├── Frontend
│   │
│   ├── index.html
│   ├── login.html
│   ├── css
│   ├── js
│   ├── images
│   └── pages
│
└── README.md
```

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/HotelManagementSystem.git
```

or simply download the ZIP.

---

## 2️⃣ Open Project

```bash
cd HotelManagementSystem
```

---

## 3️⃣ Install Dependencies

```bash
npm install
```

This installs all required Node packages.

---

## 4️⃣ Configure Environment Variables

Create a **.env** file inside the **Api** folder.

```env
DATABASE_URL=your_neon_database_connection_string

PORT=5000
```

Example

```env
DATABASE_URL=postgresql://username:password@ep-example.us-east-2.aws.neon.tech/hoteldb?sslmode=require

PORT=5000
```

---

## ☁️ Neon PostgreSQL Database

This project uses **Neon PostgreSQL Cloud Database**.

Simply copy your connection string from your Neon Dashboard and paste it inside your `.env` file.

---

## ▶️ Run Server

Move inside the API folder

```bash
cd Api
```

Run the server

```bash
node server.js
```

If everything is configured correctly you will see

```
Server running on port 5000
Connected to Neon PostgreSQL Database
```

---

## 🌐 Open Frontend

Simply open

```
Frontend/index.html
```

or use

**VS Code Live Server**

---

# 📦 Install Required Packages

```bash
npm install express
```

```bash
npm install pg
```

```bash
npm install cors
```

```bash
npm install dotenv
```

Install all at once

```bash
npm install express pg cors dotenv
```

---

# 📂 API Endpoints

| Module | CRUD |
|---------|------|
| 🏨 Hotels | ✅ |
| 🌍 Branches | ✅ |
| 🛏 Rooms | ✅ |
| 📦 Room Types | ✅ |
| 👤 Guests | ✅ |
| 📅 Reservations | ✅ |
| 💳 Payments | ✅ |
| 🧾 Bills | ✅ |
| 👨‍💼 Employees | ✅ |
| 🏢 Departments | ✅ |
| 🛎 Services | ✅ |
| 🧹 Housekeeping | ✅ |
| 🔧 Maintenance | ✅ |
| ✔ Check-In | ✅ |
| ✔ Check-Out | ✅ |

---

# 🔥 Example API

### Get Hotels

```
GET /api/hotels
```

### Get Hotel by ID

```
GET /api/hotels/:id
```

### Create Hotel

```
POST /api/hotels
```

### Update Hotel

```
PUT /api/hotels/:id
```

### Delete Hotel

```
DELETE /api/hotels/:id
```

*(Every module follows the same CRUD structure.)*

---

# 💻 Available Commands

## Install Packages

```bash
npm install
```

---

## Start Server

```bash
node server.js
```

---

## Install New Package

```bash
npm install package-name
```

---

## Remove Package

```bash
npm uninstall package-name
```

---

## List Installed Packages

```bash
npm list
```

---

## Update Packages

```bash
npm update
```

---

## Check Node Version

```bash
node -v
```

---

## Check NPM Version

```bash
npm -v
```

---

# 📊 Database

Database Provider

> ☁️ Neon PostgreSQL

Features

- Primary Keys
- Foreign Keys
- Constraints
- Relationships
- CRUD Operations
- SQL Joins
- Normalized Schema

---

# 🔒 Environment Variables

```
DATABASE_URL=

PORT=
```

Never commit your `.env` file.

---

# 📈 Future Improvements

- 🔐 JWT Authentication
- 👨‍💼 Admin Dashboard
- 📊 Charts & Analytics
- 📄 PDF Invoice Generation
- 📧 Email Notifications
- 📱 Responsive Mobile UI
- 🔍 Advanced Search
- 📂 Image Uploads
- 📥 Export Reports
- 🌙 Dark Mode

---

# 🤝 Contributing

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Muhammad Ayaan**

SZABIST University

Full Stack Developer

---

# ⭐ Support

If you found this project helpful,

**⭐ Star the repository on GitHub!**

---

<div align="center">

Made with ❤️ using Node.js, Express.js & Neon PostgreSQL

</div>
