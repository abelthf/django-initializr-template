======================================
DJANGO 1.6 INITIALIZR TEMPLATE PROJECT
======================================

A project template for Django 1.6.

based in django-twoscoops-project

To use this project follow these steps:

#. Create your working environment
#. Install Django
#. Create the new project using the django-two-scoops template
#. Install additional dependencies
#. Use the Django admin to create the project

Installing Django
=================

To install Django in the new virtual environment, run the following command::

    $ pip install django

Creating your project
=====================

To create a new Django project called '**my-project**' using
django-twoscoops-project, run the following command::

    $ django-admin.py startproject --template=https://github.com/abelthf/django-initializr-template/archive/master.zip --extension=py,rst,html my_project

Installation of Dependencies
=============================

Depending on where you are installing dependencies:

In development::

    $ pip install -r requirements/local.txt

For production::

    $ pip install -r requirements.txt

*note: We install production requirements this way because many Platforms as a
Services expect a requirements.txt file in the root of projects.*

Acknowledgements
================

- Many thanks to Randall Degges for the inspiration to write the book and django-skel.
- All of the contributors_ to this project.

.. _contributors: https://github.com/twoscoops/django-twoscoops-project/blob/master/CONTRIBUTORS.txt
