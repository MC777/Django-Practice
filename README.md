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

# Django REST Framework

* pip install djangorestframework
* pip install markdown       # Markdown support for the browsable API.
* pip install django-filter  # Filtering support

# Django web tokens

* pip install djangorestframework-simplejwt

# CORS
* pip install django-cors-headers

# Postgresql
* pip install psycopg2

# Other
* pip install python-decouple

# Deploy
* pip install django-storages # TODO: connect to S3 bucket 1
* pip install boto3 # TODO: connect to S3 bucket 1
* pip freeze > requirements.txt # TODO: deploy - save all packages for deploy
