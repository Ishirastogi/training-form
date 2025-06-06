
# 🚀 Training Form Management System

A full-stack application to manage, submit, and analyze employee training data. The project features role-based access, data export, dashboards, and filtering capabilities.

---

## 📁 Project Structure


---


---

## ⚙️ Technologies Used

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js, Express  
- **Database**: PostgreSQL  
- **Charts**: Chart.js  
- **Excel Export**: SheetJS (xlsx)  
- **Authentication**: Role-based (stored in localStorage)

---

## 🔐 User Roles & Access

| Role    | Access Level             |
|---------|--------------------------|
| Admin   | All data and dashboard   |
| Manager | Unit 1 data only         |
| HR      | Unit 3 data only         |
| User    | Unit 2 data only         |

---

## 🛠 How to Run the Project

### 📦 Backend Setup

1. Open a terminal and navigate to the backend folder:

```bash
cd backend

node server.js


#  And how to start fronetnd
# Open index.html in your browser using Live Server
(Right-click → Open with Live Server in VS Code)