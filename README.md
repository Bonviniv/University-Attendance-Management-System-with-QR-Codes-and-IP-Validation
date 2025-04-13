# University Attendance Management System with QR Codes and IP Validation

A smart attendance tracking solution developed for the **Architecture and Software Development** course in a Master's program. Designed to address common issues in classroom management and student presence validation, the system leverages **QR codes**, **IP validation**, and a **web-based interface** for streamlined attendance collection.

## 📋 Project Overview
- Real-time **attendance tracking** for university classrooms
- Developed using **QR code scanning** and **web-based forms**
- Aims to improve **classroom space usage** and reduce manual processes
- Emphasis on **accessibility**, **data integrity**, and **scalability**

## 🔍 Key Features
- **QR code scanning** to identify classrooms
- **Student input** via mobile-friendly web interface
- **IP address validation** to prevent duplicate or false submissions
- Secure attendance confirmation flow via multi-step pages
- Potential for future expansion with **geolocation** and **biometric verification**

## 💡 Additional Functionalities
- Fast and intuitive check-in using a mobile device
- Real-time tracking and export of attendance records
- Scalable architecture suitable for integration with university systems
- Lightweight and user-friendly frontend experience

## 🧪 Development & Methodology
- Frontend developed with **HTML**, **JavaScript**, and **Python (Flask/FastAPI)**
- Modular flow:
  - `frontend.py`: receives student number and scans QR code
  - `landingpage`: receives data and confirms presence
  - `confirmacao`: user is redirected after successful check-in
  - `index`: displays attendance list
- Project hosted at: **[Testes-afk.github.io](https://testes-afk.github.io)**
- Version control with **Git**, focused on iterative development and usability testing

---

An innovative attendance solution that blends simplicity and security, with a strong foundation for real-world application and future enhancement in academic environments.
