# Quiz-App
It is django based quiz app for multiple choice questions.
Installations
Make sure to have python version 3 install on you pc or laptop. If not install it from here
Clone repository
https://github.com/sswapnil2/django-quiz-app.git
cd django-quiz-app

Installing dependencies
It will install all required dependies in the project.
pip install -r requirements.txt

Migrations
To run migrations.
python manage.py makemigrations
python manage.py migrate

Create superuser
To create super user run.
python manage.py createsuperuser
After running this command it will ask for username, password. You can access admin panel from localhost:8000/admin/

Running locally
To run at localhost. It will run on port 8000 by default.
python manage.py runserver
