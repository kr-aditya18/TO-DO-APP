# Multi-User Todo App (Django)

A todo app where multiple users can register, create tasks, assign them to each other, and track status — not just a single-user checklist.

## Features

- User registration and authentication
- Create, edit, and delete tasks
- Assign tasks to specific users
- Mark tasks as completed
- Filter tasks by status and priority

## Local Setup

```bash
git clone https://github.com/kr-aditya18/TO-DO-APP.git
cd TO-DO-APP
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Then open `http://localhost:8000/`, register a user (or log in as the superuser), and start creating/assigning tasks.

## Live Demo

Deployed on Render: _add your live Render URL here once deployed_
