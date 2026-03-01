# 🐦 Django Tweet Web Application

A full-stack microblogging web application built using **Django** that allows users to create, manage, and interact with short text-based posts (tweets). This project demonstrates backend development concepts including authentication, CRUD operations, database modeling, and Django’s MVT architecture.

---

## 📌 Project Description

The Django Tweet Application is a lightweight Twitter-like platform where authenticated users can create, edit, delete, and view tweets. The project focuses on implementing secure user authentication and structured backend logic using Django best practices.


This project helped strengthen understanding of:

- Django MVT Architecture
- User Authentication & Authorization
- CRUD Operations
- Template Rendering
- Backend Development Fundamentals

---
## 🚀 Features

### 🔐 Authentication System
- User Registration
- Login & Logout
- Secure Password Handling
- Restricted Access for Editing/Deleting Tweets

### 📝 Tweet Management
- Create Tweet (Max 280 Characters)
- View All Tweets
- Edit Own Tweets
- Delete Own Tweets
- Timestamp for Each Tweet


### 🛡️ Security
- CSRF Protection Enabled
- User-based Authorization
- ORM-based Database Protection (Prevents SQL Injection)


---

## 🛠️ Tech Stack
- **Backend:** Django
- **Frontend:** HTML, CSS (Django Templates)
- **Database:** SQLite (Default Django Database)
- **Language:** Python
- **Version Control:** Git & GitHub




---

---

## 🏗️ Project Architecture

The project follows a modular and scalable Django application structure.

```
django_tweet_project/
│
├── manage.py                  # Django project entry point
│
├── django_tweet_project/      # Main project configuration
│   ├── __init__.py
│   ├── settings.py            # Project settings and configurations
│   ├── urls.py                # Root URL configuration
│   ├── asgi.py                # ASGI configuration
│   └── wsgi.py                # WSGI configuration
│







### 📌 Architecture Explanation

- **Separation of Concerns:**  
  The project is divided into a main configuration module and a dedicated app module.


- **Reusable App Structure:**  
  `tweet_app` is designed as a modular Django app that can be reused or extended in larger systems.


- **Scalable Template Organization:**  
  Templates are organized inside app-specific folders to avoid conflicts in large-scale applications.







---

## 🔮 Future Scope

This project can be further enhanced with advanced features to make it more scalable and production-ready:
- ✅ Like and Comment functionality  
- ✅ Follow / Unfollow user system  
- ✅ REST API integration using Django REST Framework  
- ✅ Real-time updates using WebSockets  
- ✅ REST API integration using Django REST Framework  