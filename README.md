# 🏥 Hospital Management Database System

## 📋 Project Overview

This project is a **relational database schema** designed for managing core hospital operations, including patient records, doctor information, appointments, prescriptions, and medication tracking. It is built using **MySQL** and follows best practices in database normalization and referential integrity.

---

## 🧾 Features

- **Patient Records**: Store and manage detailed information about patients.
- **Doctors & Departments**: Handle doctors' specialties and their association with hospital departments.
- **Appointments**: Track doctor-patient appointments and their statuses.
- **Prescriptions & Medications**: Record prescriptions issued during appointments and associated medications with dosage and instructions.
- **Relational Integrity**: All foreign keys use `ON DELETE CASCADE` to ensure clean deletion of dependent records.

---

## 🛠️ Database Schema (ERD)

You can view the Entity Relationship Diagram (ERD) for this project:

📸 **[erd.png]**  


---

## 🚀 Getting Started

### 📥 Importing the SQL Schema

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hospital-management-db.git
   cd hospital-management-db
