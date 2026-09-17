# To-Do-App
To-Do App Python Flask Project.

# To-Do Web Application

A simple **To-Do Web Application built with Python Flask** that allows users to log in and manage their tasks through a clean web interface.

## Features

* 🔐 User login and session management
* ➕ Add new tasks
* 🔄 Change task status between **Pending, Working, and Done**
* 🗑️ Delete individual tasks
* 🧹 Clear all tasks
* 💬 Flash messages for user feedback
* 💾 SQLite database using SQLAlchemy
* 🎨 Clean and responsive HTML/CSS interface

## Tech Stack

* **Python**
* **Flask**
* **Flask-SQLAlchemy**
* **SQLite**
* **HTML**
* **CSS**
* **Jinja2**

## Project Structure

```text
todoapp/
│
├── app/
│   ├── routes/
│   │   ├── auth.py
│   │   └── tasks.py
│   ├── static/
│   │   └── css/
│   │       └── style.css
│   ├── templates/
│   │   ├── base.html
│   │   ├── login.html
│   │   └── tasks.html
│   ├── __init__.py
│   └── models.py
│
└── run.py
```

## What I Learned

Through this project, I practiced:

* Creating Flask applications and routes
* Working with GET and POST requests
* Using Jinja2 templates
* Handling HTML forms with Flask
* Managing user sessions
* Performing database CRUD operations
* Using SQLAlchemy models
* Organizing a Flask application using Blueprints
* Connecting a Flask application with SQLite

## How to Run

1. Clone the repository.
2. Install the required dependencies:

```bash
pip install flask flask-sqlalchemy
```

3. Run the application:

```bash
python run.py
```

4. Open the local URL shown in the terminal.

### Demo Login

```text
Username: admin
Password: 123
```

> **Note:** The login credentials are hardcoded for demonstration purposes and should not be used in a production application.

## Future Improvements

* User registration
* Password hashing
* User-specific task lists
* Edit task functionality
* Task deadlines and priorities
* Search and filtering
* Better authentication and security
