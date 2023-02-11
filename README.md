Django Rest Framework (DRF) Project
===================================

A project built using the Django Rest Framework, an open source, well-documented framework for building APIs in Django.

Features
--------

-   Built with Django and Django Rest Framework
-   Supports authentication and permissions through DRF's built-in features
-   Customizable through the use of DRF's wide range of settings and customizable views
-   Supports CRUD operations on your models through the use of generic views and viewsets
-   Easy to implement with a clear, concise documentation

Requirements
------------

-   Python (3.7+)
-   Django (3.1+)
-   Django Rest Framework (3.12+)

Installation
------------

1.  Clone the repository to your local machine



`git clone https://github.com/<username>/drf-project.git`

2.  Change into the project directory and create python virtual env

`cd drf-project`

`python -m venv env`

3.  Active virtual env

-For Linux/Mac

`source ./env/bin/activate`

-For Windows

`.env\Scripts\activate`

4.  Install the required packages

`pip install -r requirements.txt`

5.  Apply the migrations

`
python manage.py migrate
`

6.  Run the development server


`python manage.py runserver`

Usage
-----

The project comes with a pre-built Django app with model, serializer, and views. You can use this as a starting point for your own project, or you can easily add new apps to the project and build out your own APIs.

To access the API, go to `http://localhost:8000/api/` in your browser. You will see the DRF Browsable API, which provides a simple, human-readable interface for interacting with your API.

Documentation
-------------

For more information on the Django Rest Framework and its features, check out the official documentation: <http://www.django-rest-framework.org/>
