# ✅ To-Do List Web Application

[![Python](https://img.shields.io/badge/python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/) 
[![Django](https://img.shields.io/badge/django-4.x-green?logo=django&logoColor=white)](https://www.djangoproject.com/) 
[![Bootstrap](https://img.shields.io/badge/bootstrap-5.3-purple?logo=bootstrap&logoColor=white)](https://getbootstrap.com/) 
[![SQLite](https://img.shields.io/badge/SQLite-3.x-orange?logo=sqlite&logoColor=white)](https://www.sqlite.org/index.html)  

A full-featured **To-Do List web application** built with **Python** and **Django**. Manage your tasks in a modern, responsive interface with secure user authentication.

---

## 🌟 Key Features

- 🔐 **User Authentication**: Register, log in, and manage your account securely.  
- ✏️ **CRUD Functionality**: Create, view, update, and delete tasks.  
- ✅ **Task Status Management**: Mark tasks as 'Pending' or 'Completed'.  
- 🗂️ **Task Categorization**: Organize tasks by categories (Work, Personal, etc.).  
- 🔎 **Advanced Filtering**: Filter tasks by status or category.  
- 📅 **Due Dates**: Set deadlines for tasks with date and time.  
- 📱 **Responsive Design**: Works smoothly on mobile, tablet, and desktop.  

---

## 🛠️ Technology Stack

- **Backend:** Python, Django  
- **Frontend:** HTML, CSS  
- **Database:** SQLite3 (default, configurable)  
- **Version Control:** Git  

---

## 📂 Project Structure
The project is organized into a main Django project directory (`todo`) and a primary application (`task`).
```csharp
├── todo/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py             # Main Django project directory
│   ├── wsgi.py
│   └── urls.py
├── task/             # The main application for handling tasks
│   ├── migrations/
│   ├── templates/    # HTML templates for the app
│   │   ├── task_list.html
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── pass_change.html
│   │   ├── task_detail.html
│   │   └── task_form.html
│   ├── admin.py
│   ├── forms.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── templates/        # Global templates
│   └── base.html
└── manage.py         # Django's command-line utility
```
---

## 🌐 Live Project

You can try out the deployed app here:  
[**To-Do Web App**](https://todo-web-app-kg5f.onrender.com)  

---

## 🚀 Local Setup
**1. Clone the repo**  
```bash
git clone https://github.com/turjo25/To-Do_Web_App_with_Django.git
cd todo
```
**2. Create a virtual environment**
```bash
python -m venv env
source env/bin/activate   # Linux / Mac
env\Scripts\activate      # Windows
```
**3. Apply migrations**
```bash
python manage.py migrate
```
**4. Create a superuser**
```bash
python manage.py createsuperuser
```
**5. Run the development server**
```bash
python manage.py runserver
```
>Open `http://127.0.0.1:8000` in your browser.
---
## 📝 Usage

Follow these steps to use the To-Do List Web Application:

1. **Register / Log In**  
   - Create a new account or log in with an existing one.  
   - Secure authentication ensures your tasks are private.

2. **View Profile**  
   - Access your profile to see your username, email, and basic account information.  
   - Provides an overview of your account before making any changes.

3. **Manage Profile**  
   - Update your username, email, or password.  
   - Access profile settings from the account menu after logging in.

4. **Create a Task**  
   - Click **"Add Task"** or similar button.  
   - Enter task title, description, category, and due date/time.  
   - Save to add it to your task list.

5. **Manage Tasks**  
   - **Edit:** Update the task details if needed.  
   - **Mark as Completed / Pending:** Toggle task status.  
   - **Delete:** Remove tasks you no longer need.

6. **Filter and Sort Tasks**  
   - Filter tasks by **status**: All, Pending, Completed.  
   - Filter tasks by **category**: Work, Personal, etc.

7. **View Task Details**  
   - Click on a task to see its detailed information, including due date and category.

8. **Responsive Design**  
   - Use on any device: desktop, tablet, or mobile.  

---

💡 **Tip:** Regularly mark completed tasks to stay organized and use the due date feature to prioritize urgent tasks.

---
## ⚡ Future Enhancements

- 🕒 Reminders & Notifications for due tasks

- 🌐 User Profile Customization

- 📊 Analytics Dashboard showing task completion trends

- 🔗 Sharing Tasks between users or teams

## 🛡️ License
MIT License © 2025 Turjo





