# 🩺 Online Doctor Appointment System

A full-stack web-based application to simplify the process of scheduling medical appointments between patients and doctors. Built using Java EE technologies, JSP, Servlets, and MySQL, the platform enables streamlined access to healthcare services for patients and operational convenience for doctors and administrators.

---

## 📌 Project Overview

This project is designed to address challenges such as long waiting lines, manual appointment scheduling, and lack of accessibility to local doctors. It allows:

- **Patients** to register, search for doctors based on specialization and location, book appointments, view history, and provide feedback.
- **Doctors** to manage appointment slots, update treatment statuses, and access patient feedback.
- **Admins** to monitor the system, remove fraudulent doctors, and view feedback reports.

---

## 🚀 Features

### 👩‍⚕️ For Doctors
- Profile creation and update
- View daily appointment list
- Update check-up status
- Access patient feedback

### 🧑‍💼 For Patients
- Register/login securely
- Search doctors by specialization and location
- Book, reschedule, or cancel appointments
- View medical history and give feedback

### 🛠️ For Admin
- View all patients and doctors
- Access appointment and feedback logs
- Remove unverified doctors

---

## 🏗️ Tech Stack

| Layer        | Technologies                         |
|--------------|--------------------------------------|
| Frontend     | HTML, CSS3, JavaScript, JSP          |
| Backend      | Java 1.8, Servlets, JSP, Hibernate 5 |
| Database     | MySQL                                |
| Build Tool   | Maven                                |
| IDE Used     | Eclipse, Visual Studio Code          |
| OS           | Windows 10                           |

---

## ⚙️ Modules

- **Admin Module**: Full system access to manage users and monitor activity.
- **Doctor Module**: Interface for appointments and check-up records.
- **Patient Module**: Search, schedule, and manage appointments.
- **Database Schema**: 4 primary tables - `Doctor`, `Patient`, `CheckUpRecord`, `FeedbackForDoctor`.

---

## 🔐 Security Features

- Authentication via login credentials for all user roles
- Admin authority to remove users with suspicious or malicious activity
- Only authorized access for each module

---

## 🧪 Testing

- **JUnit** for unit testing
- **Integration Testing** for module-level verification
- **Validation Testing** for user input and boundary conditions

---

## 📈 Future Enhancements

- Integrate **online payments**
- Add **pharmacy/lab modules**
- Enable **video consultation**
- **Rating system** for doctors
- AI-driven **appointment suggestions**

---
