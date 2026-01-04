# 📝 Django To-Do List App

A clean, modern **To-Do List web application** built using **Django**.  
This app helps users manage daily tasks efficiently with pending/completed tabs, due dates, and a simple responsive UI.

---

## 🚀 Features

- ➕ Add new tasks
- ✏️ Edit existing tasks
- ❌ Delete tasks
- ✅ Mark tasks as completed / undo
- 📅 Due date support
- 📂 Separate **Pending** and **Completed** task tabs
- 🎨 Clean and modern UI (CSS only)
- 📱 Responsive design (mobile friendly)
- 🗂 SQLite database (default Django DB)

---

## 🛠 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS
- **Database:** SQLite3
- **Version Control:** Git & GitHub

---

## 📂 Project Structure

todo-django-app/
│
├── tasks/
├── templates/
├── static/
├── todo_project/
├── manage.py
└── db.sqlite3

yaml
Copy code

---

## ▶️ Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Saniyashaikh02/todo-django-app.git
cd todo-django-app
2️⃣ Create virtual environment
bash
Copy code
python -m venv venv
Activate it:

bash
Copy code
venv\Scripts\activate
3️⃣ Install Django
bash
Copy code
pip install django
4️⃣ Run migrations
bash
Copy code
python manage.py migrate
5️⃣ Start server
bash
Copy code
python manage.py runserver
Open browser:

cpp
Copy code
http://127.0.0.1:8000/
