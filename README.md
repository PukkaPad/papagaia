Source Code for my portfolio (under construction)
=============================


Quickstart for Mac
==================

Requirements: Python 3.6, Pip, Virtualenv

1. Using terminal, create a folder somewhere

`mkdir portfolio`

1. Move into that folder

`cd portfolio`

1. Create a virtualenv folder

`python3 -m venv myvenv`

1. Download / clone this repo to a folder inside `portfolio`

1. Activate the venv

`source myvenv/bin/activate`

1. Change into the project directory

1. Install the requirements

`pip install -r requirements.txt`


1. To create your own empty database
    -  Create the database with

    `python manage.py migrate`

    -  Create a superuser with
    `python manage.py createsuperuser`

1. Run the development server from whichever folder manage.py is in

`python manage.py runserver`

1. Access the site at http://127.0.0.1:800 and http://127.0.0.1/admin


To Do List
==========

