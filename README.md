# django-boilerplate
Boilerplate template to quickstart a Django app

Python Version 3.4
Django Version 1.8.1

Installation

	virtualenv -p python3 venv
	source venv/bin/activate
	pip install -r requirements.txt
	python manage.py migrate

(Optional) If creating a new Django site from scratch:

	virtualenv -p python3 venv
	source venv/bin/activate
	pip install django
	django-admin startproject <NAME_OF_APP>
	python manage.py migrate

Generate a secret key and put it in a file named `secret.txt`

Run

	python manage.py runserver
