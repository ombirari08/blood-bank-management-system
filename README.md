# 🩸 Blood Donor Management System

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![License](https://img.shields.io/badge/license-Custom--Restricted-red)](#)
[![Made with Django](https://img.shields.io/badge/built%20with-Django-092E20.svg)](https://www.djangoproject.com/)
[![MySQL](https://img.shields.io/badge/database-MySQL-blue.svg)](https://www.mysql.com/)

---

> ⚠️ **Notice**  
> This repository is for demonstration and educational purposes only.  
> Unauthorized use, copying, or redistribution of this code is strictly prohibited.  
> To request permission or inquire about collaboration, contact me at: **your.email@example.com**

---

## 📌 Project Overview

The **Blood Donor Management System** is a web-based application designed to streamline and automate the process of managing blood donors and recipients. It is intended for hospitals and healthcare centers to efficiently manage a digital database, improving operational efficiency, communication, and accuracy.

---

## 🚀 Key Features

- 📁 Minimal Paper Records  
- 🔍 Easy Data Access  
- ⏱️ Reduced Time for Operations  
- 🔐 Data Security & Backup  
- 📊 Real-Time Reporting

---

## 💻 Technology Stack

- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** Django (Python)  
- **Database:** MySQL

---

## ⚙️ System Requirements

### Hardware
- Processor: Intel Core i3 or equivalent  
- RAM: 4 GB  
- Storage: 1 TB HDD  

### Software
- OS: Windows 10 or compatible OS  
- Tools: VS Code, PyCharm, or Sublime Text  

---

## 🛠️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/blood-donor-management.git
   cd blood-donor-management

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
4. **Set Up MySQL Database**
   - Create a MySQL database (e.g., blood_donor_db)
   - Open settings.py and update your database configuration:  
   ```bash
       DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.mysql',
            'NAME': 'blood_donor_db',
            'USER': 'your_username',
            'PASSWORD': 'your_password',
            'HOST': 'localhost',
            'PORT': '3306',
        }
    }
5. **Apply Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py makemigrations
2. **Run the Server**
   ```bash
   python manage.py runserver

   
