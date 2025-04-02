# Library-management-system

A web-based library management system built using Django.

Installation and Setup
Step 1: Create a Virtual Environment

bash
python -m venv venv

Step 2: Activate the Virtual Environment

bash
# For Windows
env\Scripts\activate

# For Linux/Mac
source env/bin/activate

Step 3: Install Required Packages

bash
pip install django pillow

Step 4: Migrate Database

bash
python manage.py migrate

Step 5: Create Superuser for Admin Login

bash
python manage.py createsuperuser


Step 6: Run the Development Server

bash
python manage.py runserver


