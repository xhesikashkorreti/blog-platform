# Blog Platform
A full-featured blog web application built with Django that allows users to create, edit, and delete blog posts, leave comments, and register/login.
----
## Features
- User registration and authentication (login/logout)
- Create, update, delete blog posts
- Add and manage comments
- Responsive design using Bootstrap
- Admin panel for managing posts and users
___
## Tech Stack
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Python, Django
- **Database**: SQLite (can switch to PosstgreSQL)
___
## Screenshots
_Add screenshots of your homepage, postpage, and admin panel_
___
## Installation
1. Clone the repository:
```bash
git clone https://github.com/xhesiblog/blog-platform.git
cd blog-plarform
python -m venv env
# Windows
env\Scripts\activate
#macOS/Linux
source env/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
