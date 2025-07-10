# 🎓 Student Management Dashboard

This is a Django-based web application that allows authenticated users to add, view, edit, and delete student records. It features a modern, animated front end with persistent data storage using a PostgreSQL or SQLite backend.

---

## 🔥 Features

- User Authentication (Login / Logout)
- Add, Edit, Delete Student Records
- Persistent Storage (Django ORM)
- Responsive and Animatic UI
- Powered by HTML, CSS, JavaScript, and Django

---

## 🚀 Demo

![Dashboard Screenshot](demo_screenshot.png) <!-- Replace with your screenshot or remove -->
![image alt](https://github.com/KIRUBAKARAN9840/student_project1/blob/7260705abf309898e4a00f146887b5c20dbe1dda/Screenshot%202025-07-10%20084149.png)
---

## 🛠️ Technologies Used

- Python 3.x
- Django 4.x
- HTML5, CSS3
- JavaScript (ES6)
- SQLite (default) or PostgreSQL (optional)

---

## 📦 Installation

### 1. Clone the repository

```bash
https://github.com/KIRUBAKARAN9840/student_project1.git

cd student_project

--------------------------------------------
RUN THESE IN TERMINAL

python -m venv venv
source venv/bin/activate      # On Linux/macOS
venv\Scripts\activate         # On Windows
pip install -r requirements.txt
pip install django
python manage.py makemigrations
python manage.py migrate

----------------------------------
2.Create a superuser (optional)

python manage.py createsuperuser

----------------------------------

3.Run the server
python manage.py runserver
