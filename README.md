# My Blog Platform

A simple blog platform built with Django that allows users to create and view blog posts.

Features

	•	Create and display blog posts
	•	Django Admin panel for managing posts
	•	Responsive design using HTML & CSS
	•	Database migrations with Django ORM

Getting Started

Prerequisites

Ensure you have the following installed:
	•	Python 3
	•	pip (Python package manager)
	•	Django

Installation

	1.	Clone the repository

git clone https://github.com/yourusername/django-blog.git  
cd django-blog  


	2.	Create and activate a virtual environment (optional but recommended)

python -m venv venv  
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`  


	3.	Install dependencies

pip install -r requirements.txt  


	4.	Apply database migrations

python manage.py makemigrations  
python manage.py migrate  


	5.	Create a superuser for the Django Admin panel

python manage.py createsuperuser  


	6.	Run the development server

python manage.py runserver  

Access the app at: http://127.0.0.1:8000/

Usage

	•	Visit the homepage to see blog posts.
	•	Log in to the admin panel (/admin) to create, edit, or delete posts.

Project Structure

django-blog/
│── blog_project/   # Main Django project folder
│── blog/           # Blog app with models, views, templates
│── templates/      # HTML templates
│── static/         # Static files (CSS, JS)
│── db.sqlite3      # SQLite database
│── manage.py       # Django management script
│── requirements.txt # List of dependencies
│── README.md       # Project documentation

Contributing

	1.	Fork the project
	2.	Create your feature branch (git checkout -b feature-branch)
	3.	Commit your changes (git commit -m 'Add new feature')
	4.	Push to the branch (git push origin feature-branch)
	5.	Open a pull request

