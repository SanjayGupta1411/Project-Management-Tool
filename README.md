# Project Management API – Setup & Usage Guide

This guide helps you set up and use the REST API for managing users, projects, tasks, and comments. Built with **Django** + **Django REST Framework** + **JWT Authentication**.

## ⚙️ Prerequisites
## Make sure you have the following installed:-

Python 3.8+
pip (Python package manager)
virtualenv (optional but recommended)
Postman (for testing API)

## 🚀 Project Setup

1. Clone the Repository

git clone <your_repo_url>
cd TechForing_Task

2. Create & Activate Virtual Environment

python -m venv venv
##  For Windows
venv\Scripts\activate   
# OR 
##  For Mac/Linux
source venv/bin/activate  

3. Install Dependencies
pip install -r requirements.txt

4. Apply Migrations

python manage.py makemigrations
python manage.py migrate

5. Create Superuser (Optional)
python manage.py createsuperuser

## 🛠 Run the Development Server

python manage.py runserver

## API will be accessible at:
📍 http://127.0.0.1:8000/api/


## Use the token in Postman
Authorization: Bearer <access_token>




