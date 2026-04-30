# secure-task-portal
A secure full-stack task management web application built with Django, featuring user authentication, database-backed task storage, and a clean minimal UI. Designed to demonstrate foundational web development, backend architecture, and secure application design. 

## Features
- User authentication (login/logout)
- Create, view, and delete tasks
- User-specific task ownership
- Admin panel for database management
- Clean, minimal UI for task tracking

## Tech Stack
- Backend: Django (Python)
- Frontend: HTML, CSS
- Database: SQLite
- Version Control: Git & GitHub

## How to Run Locally
1. Clone the repository:
```bash
git clone https://github.com/tvy-m/secure-task-portal.git
cd secure-task-portal
```

2. Create a virtual environment:
``` bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```
3. Install dependencies:
``` bash
pip install django
```
4. Run migrations:
```bash
python manage.py migrate
```
6. Start the server:
``` bash
python manage.py runserver
```
7. Open in browser:
``` bash
http://127.0.0.1:8000/
```
