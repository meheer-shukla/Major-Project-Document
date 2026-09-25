<div align="center">

# 👥 Employee Management System (EMS)

**A full-featured HR platform built with Yii2, PHP & MySQL — streamlining employee data, attendance, payroll and performance management.**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Yii2](https://img.shields.io/badge/Yii2-Framework-00A6D6?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

## 📖 Overview

Employee Management Systems (EMS) have become essential tools for managing human resources effectively in modern enterprises. This project delivers a centralized, secure, and scalable platform that automates core HR processes — including **employee data management, attendance tracking, payroll processing, and performance evaluation** — reducing administrative overhead and improving accuracy across the organization.

Built on the **Yii2** framework (MVC architecture) with a **MySQL** backend and a responsive **HTML/CSS/Bootstrap** front end, the system is designed to scale with an organization's needs while keeping sensitive employee data secure.

---

## ✨ Key Features

| Module | Description |
|---|---|
| 🧑‍💼 **HRM** | Company setup, employee details, shift allotment, and leave settings |
| 🕒 **ATMS** | Attendance tracking, access-card assignment, and master-card configuration |
| 💰 **Payroll** | Salary structuring and payment processing |
| 📢 **ESS** | Employee self-service — announcements, birthdays, and personal info updates |
| 🔐 **Auth & RBAC** | Secure login system with role-based access control (Admin / Manager / HR / Employee) |
| 📊 **Reporting & Analytics** | Custom, exportable reports on attendance, performance, and departmental metrics |
| 🔄 **CRUD Operations** | Full create/read/update/delete support for employee records via Yii2's Gii-generated scaffolding |

## 🏗️ System Architecture

The system follows a classic **three-layer architecture**:

- **Frontend** — HTML5, CSS3, and Bootstrap for a responsive, cross-device interface
- **Backend** — Yii2 (PHP) implementing the MVC pattern for clean separation of concerns
- **Database** — MySQL, accessed through Yii2's ActiveRecord ORM for safe, efficient queries

### Entity-Relationship Diagram

Core entities include `EMPLOYEE`, `DEPARTMENT`, `PROJECT`, and `DEPENDENT`, related through associations such as `WORKS`, `MANAGES`, `Assigned to`, and `Supervision`.

---

## 🛠️ Tech Stack

- **Language:** PHP
- **Framework:** Yii2 (MVC)
- **Database:** MySQL
- **Frontend:** HTML5, CSS3, Bootstrap, JavaScript
- **Dependency Management:** Composer
- **Dev Tools:** Yii2 Gii (code generation), phpMyAdmin / MySQL Workbench

---

## 🔒 Security

- Password hashing via Yii2's built-in `Security` component
- CSRF protection and input sanitization on all forms
- Role-Based Access Control (RBAC) restricting data visibility by user role
- Encrypted storage for sensitive employee data

---

## 🗺️ Roadmap

- [ ] Payroll automation with tax deduction & payslip generation
- [ ] Predictive analytics for attendance/performance trends (ML-based)
- [ ] Native mobile app for on-the-go access
- [ ] Integration with third-party ERP/CRM systems
- [ ] Cloud-native deployment (Docker + Kubernetes)

---

## 📚 References

- [Yii2 Framework Documentation](https://www.yiiframework.com/)
- [MySQL Documentation](https://www.mysql.com/)
- [PHP Documentation](https://www.php.net/)

---

## 👤 Author

**Meheer Shukla**
B.Tech, Computer Science & Engineering — Manipal University Jaipur
*Developed under the supervision of Dr. Susheela Vishnoi*
