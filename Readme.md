# 🏨 Hotel Management System

A full-stack **Hotel Management System** built using **Node.js, Express.js, PostgreSQL, HTML, CSS, and JavaScript**. This project provides REST APIs for managing hotels, branches, rooms, guests, reservations, employees, services, billing, housekeeping, maintenance, and more.

---

# 📌 Features

- Hotel Management
- Branch Management
- Room Type Management
- Room Management
- Guest Management
- Reservation Management
- Check-In Management
- Check-Out Management
- Payment Management
- Billing System
- Employee Management
- Department Management
- Service Management
- Guest Service Requests
- Housekeeping Management
- Maintenance Management

---

# 🛠 Tech Stack

### Backend
- Node.js
- Express.js
- PostgreSQL
- pg
- dotenv
- cors

### Frontend
- HTML
- CSS
- JavaScript

---

# 📂 Project Structure

```
hotelmanagementsystem/
│
├── Api/
│   ├── routes/
│   ├── db.js
│   ├── server.js
│   ├── package.json
│   ├── .env
│   └── node_modules/
│
└── Frontend/
    ├── index.html
    ├── login.html
    ├── pages/
    ├── css/
    └── js/
```

---

# 📦 Installation

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/hotelmanagementsystem.git
```

or simply download the ZIP.

---

## 2. Go to API Folder

```bash
cd hotelmanagementsystem/Api
```

---

## 3. Install Dependencies

```bash
npm install
```

---

## 4. Create .env File

Example

```env
DB_USER=postgres
DB_HOST=localhost
DB_NAME=hotel_management
DB_PASSWORD=yourpassword
DB_PORT=5432

PORT=5000
```

---

## 5. Start PostgreSQL

Make sure PostgreSQL is running.

---

## 6. Import Database

Run your SQL schema and insert scripts.

Example

```sql
hotel_management.sql
```

---

## 7. Run Server

```bash
npm start
```

Server starts on

```
http://localhost:5000
```

---

# Development

If you use nodemon

```bash
npx nodemon server.js
```

or

```bash
nodemon server.js
```

---

# Available NPM Scripts

Start server

```bash
npm start
```

Install packages

```bash
npm install
```

Install a new package

```bash
npm install package-name
```

Install dev dependency

```bash
npm install --save-dev package-name
```

---

# REST API Endpoints

## Hotel

```
GET     /api/hotels
GET     /api/hotels/:id
POST    /api/hotels
PUT     /api/hotels/:id
DELETE  /api/hotels/:id
```

---

## Branch

```
GET     /api/branches
GET     /api/branches/:id
POST    /api/branches
PUT     /api/branches/:id
DELETE  /api/branches/:id
```

---

## Room Types

```
GET     /api/roomtypes
GET     /api/roomtypes/:id
POST    /api/roomtypes
PUT     /api/roomtypes/:id
DELETE  /api/roomtypes/:id
```

---

## Rooms

```
GET     /api/rooms
GET     /api/rooms/:id
POST    /api/rooms
PUT     /api/rooms/:id
DELETE  /api/rooms/:id
```

---

## Guests

```
GET     /api/guests
GET     /api/guests/:id
POST    /api/guests
PUT     /api/guests/:id
DELETE  /api/guests/:id
```

---

## Reservations

```
GET     /api/reservation
GET     /api/reservation/:id
POST    /api/reservation
PUT     /api/reservation/:id
DELETE  /api/reservation/:id
```

---

## Check-In

```
GET     /api/checkins
GET     /api/checkins/:id
POST    /api/checkins
PUT     /api/checkins/:id
DELETE  /api/checkins/:id
```

---

## Check-Out

```
GET     /api/checkouts
GET     /api/checkouts/:id
POST    /api/checkouts
PUT     /api/checkouts/:id
DELETE  /api/checkouts/:id
```

---

## Payments

```
GET     /api/payments
GET     /api/payments/:id
POST    /api/payments
PUT     /api/payments/:id
DELETE  /api/payments/:id
```

---

## Bills

```
GET     /api/bills
GET     /api/bills/:id
POST    /api/bills
PUT     /api/bills/:id
DELETE  /api/bills/:id
```

---

## Employees

```
GET     /api/employees
GET     /api/employees/:id
POST    /api/employees
PUT     /api/employees/:id
DELETE  /api/employees/:id
```

---

## Departments

```
GET     /api/departments
GET     /api/departments/:id
POST    /api/departments
PUT     /api/departments/:id
DELETE  /api/departments/:id
```

---

## Services

```
GET     /api/services
GET     /api/services/:id
POST    /api/services
PUT     /api/services/:id
DELETE  /api/services/:id
```

---

## Guest Services

```
GET     /api/guestservices
GET     /api/guestservices/:id
POST    /api/guestservices
PUT     /api/guestservices/:id
DELETE  /api/guestservices/:id
```

---

## Housekeeping

```
GET     /api/housekeeping
GET     /api/housekeeping/:id
POST    /api/housekeeping
PUT     /api/housekeeping/:id
DELETE  /api/housekeeping/:id
```

---

## Maintenance

```
GET     /api/maintenance
GET     /api/maintenance/:id
POST    /api/maintenance
PUT     /api/maintenance/:id
DELETE  /api/maintenance/:id
```

---

# HTTP Status Codes

| Code | Meaning |
|------|---------|
|200|Success|
|201|Created|
|400|Bad Request|
|404|Not Found|
|500|Internal Server Error|

---

# Common Commands

### Install Everything

```bash
npm install
```

### Run Server

```bash
npm start
```

### Run with Nodemon

```bash
npx nodemon server.js
```

### Check Installed Packages

```bash
npm list
```

### Update Packages

```bash
npm update
```

### Remove node_modules

```bash
rm -rf node_modules
```

Windows

```cmd
rmdir /s node_modules
```

### Reinstall Packages

```bash
npm install
```

---

# Dependencies

```
express
pg
cors
dotenv
nodemon
```

---

# Database

- PostgreSQL
- Primary Keys
- Foreign Keys
- Constraints
- CRUD Operations
- Joins
- Views (optional)
- Stored Procedures (optional)

---

---

# License

This project is for educational purposes.
