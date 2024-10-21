# Installation
* 1 - create a virtual .venv and activate
* source .venv\Scripts\activate
* 3 - cd into project "cd Django-Practice"
* 4 - pip install -r requirements.txt
* 5 - python manage.py runserver

* pip install pillow   < obsługa obrazów >
* pip install whitenoise < przy produkcji >

# Django Steps
* django-admin startproject devsearch
* python manage.py startapp projects
* python manage.py runserver
* python manage.py migrate
* python manage.py createsuperuser
* python manage.py makemigrations
* python manage.py startapp users

* python manage.py collectstatic   < przygotowanie plików static do produkcji >