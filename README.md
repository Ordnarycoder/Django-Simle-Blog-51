Django Blog Project

A simple, minimalistic blog web application built using Django. This project allows users to create, view, and manage blog posts through a user-friendly interface and Django admin panel.

📌 Features

✅ Create Blog Posts: Easily create new posts with title and content.

✅ View Blog Posts: Display all blog posts neatly.

✅ Detailed Post View: Click to view individual posts in detail.

✅ Admin Panel: Manage posts directly via Django’s built-in admin.

🚀 Technologies Used

Python

Django Framework

Bootstrap 4

SQLite (Default Django Database)

⚙️ Installation

Follow these steps to run the project locally:

Clone the repository:

git clone https://github.com/Ordnarycoder/Django-Simple-Blog-51.git

Navigate to project directory:

cd django-blog-project

Create virtual environment:

python -m venv venv

Activate virtual environment:

# On Windows
venv\Scripts\activate

# On macOS/Linux
source venv/bin/activate

Install dependencies:

pip install django

Apply database migrations:

python manage.py makemigrations
python manage.py migrate

Create a superuser (for admin access):

python manage.py createsuperuser

Run the development server:

python manage.py runserver

Open in browser:

http://127.0.0.1:8000

🔐 Admin Panel

Access your admin panel at:

http://127.0.0.1:8000/admin

Use your previously created superuser credentials to log in.

📂 Project Structure

django-blog-project/
├── blog/             # Blog application
│   ├── migrations/
│   ├── templates/
│   │   └── blog/
│   │       ├── home.html
│   │       └── detail.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── myblog/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
└── manage.py

🌟 Future Improvements

User authentication and registration

Blog post editing from frontend

Image uploads and storage

Comments and tagging system

Pagination for blog posts

📄 License

This project is open-source and available under the MIT License. Feel free to modify and use it according to your needs.

Developed with ❤️ by Eyüp İrfan Çelik.

