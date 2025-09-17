# To-Do List Web Application

A full-featured To-Do List web application built with Python and the Django Framework. This application allows users to register, log in, and manage their tasks in a clean, modern interface.

## Key Features

-   **User Authentication**: Secure user registration and login system.
-   **CRUD Functionality**: Full Create, Read, Update, and Delete capabilities for tasks.
-   **Task Status Management**: Easily toggle tasks between 'Pending' and 'Completed'.
-   **Task Categorization**: Assign categories (e.g., Work, Personal) to tasks for better organization.
-   **Advanced Filtering**: Filter tasks by their status (All, Pending, Completed) or by category.
-   **Due Dates**: Set deadlines for each task, including date and time.
-   **Responsive Design**: A clean and intuitive user interface that works on various screen sizes.

## Technology Stack

-   **Backend**: Python, Django
-   **Frontend**: HTML, CSS
-   **Database**: SQLite3 (Default, configurable)
-   **Version Control**: Git

## Project Structure

The project is organized into a main Django project directory (`todo`) and a primary application (`task`).
```python
.
├── todo/             # Main Django project directory
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── task/             # The main application for handling tasks
│   ├── migrations/
│   ├── templates/    # HTML templates for the app
│   │   ├── task_list.html
│   │   ├── login.html
│   │   └── ...
│   ├── admin.py
│   ├── forms.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── templates/        # Global templates
│   └── base.html
└── manage.py         # Django's command-line utility
```

## Setup and Installation

Follow these steps to get the project running on your local machine.

### 1. Prerequisites

-   Python 3.8+
-   pip (Python package installer)
-   Git

### 2. Clone the Repository

```bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
cd your-repo-name
```
### 3. Create a Virtual Environment
It's highly recommended to use a virtual environment to manage project dependencies.

<b>On macOS/Linux:</b>

```Bash

python3 -m venv venv
source venv/bin/activate
```
<b>On Windows:</b>
```Bash

python -m venv venv
.\venv\Scripts\activate
```
### 4. Install Dependencies
The requirements.txt file contains all the necessary Python packages.

>Note: If you haven't created a requirements.txt file yet, you can generate one with:
pip freeze > requirements.txt

Then, install the dependencies:

```bash

pip install -r requirements.txt
```
### 5. Apply Database Migrations
This will set up the necessary database tables based on the models defined in task/models.py.

```Bash

python manage.py migrate
```
### 6. Create a Superuser
This creates an admin account to access Django's admin interface.

```Bash

python manage.py createsuperuser
```
Follow the prompts to create your username and password.

### 7. Run the Development Server
```Bash

python manage.py runserver
```
The application will be available at `http://127.0.0.1:8000/.`


### License
© 2025 To-Do App






