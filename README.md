# ✅ ToDo Flask

A simple **To-Do List web application** built with **Python and Flask**, using **SQLite** and **SQLAlchemy** for data management.

## 📖 About the Project

This project was developed to practice building web applications with Flask and integrating a relational database.

The application allows users to create, update, and delete tasks through a web interface. The project also includes models for **users, profiles, tasks, and categories**.

## 🛠️ Technologies

* Python
* Flask
* Flask-SQLAlchemy
* Flask-Migrate
* Flask-Bootstrap
* Jinja2
* SQLite
* HTML/CSS

The project dependencies are listed in `requirements.txt`.

## ✨ Features

* Create tasks
* Edit task descriptions
* Delete tasks
* List tasks ordered by creation date
* Store data using SQLite
* Database models with SQLAlchemy
* Database migrations with Flask-Migrate
* Bootstrap integration for the interface

The main application routes handle task creation, listing, updating, and deletion.

## 📂 Project Structure

```text
ToDo-Flask/
│
└── Python/
    └── Iniciando/
        └── todo/
            ├── app.py
            ├── requirements.txt
            ├── todo.sqlite
            ├── migrations/
            └── templates/
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/EduPanage/ToDo-Flask.git
```

### 2. Navigate to the project directory

```bash
cd ToDo-Flask/Python/Iniciando/todo
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 5. Install the dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

The application will start using Flask's development server.

## 🎯 Purpose

This project is mainly focused on practicing:

* Flask fundamentals
* Routing
* Templates with Jinja2
* Form handling
* CRUD operations
* SQLAlchemy ORM
* Database relationships
* Flask migrations

## 👨‍💻 Author

**Eduardo Panage**

[GitHub](https://github.com/EduPanage/ToDo-Flask)
