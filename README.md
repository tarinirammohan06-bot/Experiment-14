# Student Management System Using Django

## 📌 Project Description

The **Student Management System** is a web-based application developed using Python and the Django framework. It provides user registration and login functionality, along with dedicated Contact and About pages. The project demonstrates Django URL routing, form handling, user authentication, and database integration using SQLite.

## ✨ Features

- **User Registration:** Allows new users to register with their username, email, and password.
- **User Login:** Authenticates registered users using their credentials.
- **Student Profile:** Collects additional information such as phone number and address.
- **Home Page:** Provides navigation to the main pages of the application.
- **Contact Page:** Displays contact information.
- **About Page:** Provides information about the project.
- **Logout:** Allows users to log out of their accounts.
- **Database Integration:** Uses SQLite for storing application data.
- **Django URL Routing:** Enables navigation between different pages.

## 🛠️ Technologies Used

- Python
- Django
- HTML
- SQLite
- Django Forms
- Django Authentication System

## 📂 Project Structure

```text
student_management/
├── manage.py
├── db.sqlite3
├── student_management/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
└── students/
    ├── admin.py
    ├── apps.py
    ├── forms.py
    ├── models.py
    ├── views.py
    └── templates/
        └── students/
            ├── home.html
            ├── register.html
            ├── login.html
            ├── contact.html
            └── about.html
```

*Note: The structure above represents the intended project layout. Ensure the listed files and folders exist in your repository.*

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd student_management
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install Django

```bash
pip install django
```

### 5. Apply database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

### 7. Open the application

Visit the following URL in your browser:

http://127.0.0.1:8000/

## 🌐 Application Pages

| Page | URL |
|---|---|
| Home | `/` |
| Registration | `/register/` |
| Login | `/login/` |
| Contact | `/contact/` |
| About | `/about/` |
| Logout | `/logout/` |

## 🎯 Project Objectives

- Understand the fundamentals of Django web development.
- Implement user registration and authentication.
- Learn Django forms and model-based data handling.
- Configure URL routing and page navigation.
- Integrate a relational database using SQLite.

## 🎓 Learning Outcomes

This project provides practical experience in developing web applications with Django, managing user information, handling forms, configuring routes, and connecting an application to a database.

## 🚀 Future Enhancements

- Add an admin dashboard to manage student records.
- Implement student record creation, updating, and deletion.
- Improve the interface with CSS and Bootstrap.
- Add password reset functionality.
- Add role-based access for students and administrators.

## 👩‍💻 Author

**Your Name**

## 📄 License

This project is created for educational and academic purposes.
