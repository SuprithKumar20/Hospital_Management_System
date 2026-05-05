# 🏥 HospitalOS – Advanced Hospital Management System  
### Built with Django | Production-Ready Web Application  
<div align=\"center\">
 
  
  ![Django](https://img.shields.io/badge/Django-6.0.4-0E1116?style=for-the-badge&logo=django&logoColor=0CE2C7)
  ![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=F9C010)
  ![SQLite](https://img.shields.io/badge/SQLite3-07405E?style=for-the-badge&logo=sqlite&logoColor=FFFFFF)
  ![Windows](https://img.shields.io/badge/Windows11-Tested-00C6F8?style=for-the-badge&logo=windows11&logoColor=FFFFFF)
  ![MIT](https://img.shields.io/badge/License-MIT-E91E63?style=for-the-badge&logo=mit&logoColor=FFFFFF)

╔══════════════════════════════════════════════════════════════╗
║      🏥 HOSPITALOS v2.0 - ADMIN DASHBOARD PRO 🏥            ║
║                                                              ║
║  👨‍⚕️ Doctors    │  👥 Patients    │  📅 Appointments         ║
║  📧 Smart Queries│  🔐 Secure Login│  📊 Live Stats         ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
             🎯 Zero-Config | Runs in 90s | Django Powered

</div>

---

## 👨‍💻 Author  
**Suprith Kumar B L**

---

## 🚀 Overview  

HospitalOS is a full-stack Hospital Management System developed using Django.  
It simplifies hospital administration by managing doctors, patients, appointments, and queries through a secure and user-friendly interface.

This project demonstrates real-world application development with proper backend architecture, authentication, and database handling.

---

## ✨ Features  

### 🔐 Authentication & Security  
- Secure login using Django Authentication  
- Admin-only dashboard access  
- Session management and CSRF protection  

### 👨‍⚕️ Doctor Management  
- Add, update, delete, and view doctors  
- Store specialization and contact details  

### 👥 Patient Management  
- Maintain structured patient records  
- Full CRUD functionality  

### 📅 Appointment System  
- Assign patients to doctors  
- Schedule date and time  
- Dropdown-based selection  

### 📧 Query Management  
- Contact form integration  
- Mark queries as read/unread  
- Organized admin handling  

### 📊 Dashboard  
- Real-time statistics  
- Total doctors, patients, appointments, queries  
- Responsive UI with sidebar navigation  

---

## 🧱 Tech Stack  

- **Backend:** Django 6.x  
- **Language:** Python 3.12  
- **Database:** SQLite3  
- **Frontend:** HTML, CSS, Bootstrap, jQuery  

---

## ⚡ Installation & Setup  

```bash
# Clone repository
git clone https://github.com/your-username/HospitalOS.git

# Navigate into project
cd HospitalManagementSystem/HospitalManagementSystem

# Create virtual environment
py -m venv venv

# Activate environment (Windows)
venv\Scripts\activate

# Install dependencies
pip install django

# Run migrations
py manage.py makemigrations
py manage.py migrate

# Create superuser
py manage.py createsuperuser

# Start server
py manage.py runserver
