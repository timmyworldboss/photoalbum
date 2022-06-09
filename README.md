## Description
Gallery is a picture gallery made with a Django application that allows user to display own photos for others to view.

## Setup Instructions:
# Requirements
1. Clone the repository
Clone the the repository by running

git clone https://github.com/timmyworldboss/worldbossBazugallery.git
or download a zip file of the project from github

Navigate to the project directory


## 2. Create a virtual environment
Install Virtualenv

python3 -m venv venv
To create a virtual environment named env

python3 -m venv env
To activate the virtual environment we just created

source virtual/bin/activate
## 3. Create a django and create django projects
Install django

pip install django
Create django project

django-admin startproject gallery.


django-admin startapp news
## 5. Create a database
You'll need to create a new postgress database, Type the following command to access postgress

 $ psql
Then run the following query to create a new database 

# create database 
## 4.Install dependencies
To install the requirements from requirements.txt file,

pip install -r requirements.txt
## 5.Create Database migrations
Making migrations on postgres using django


python manage.py migrate
## 6.Run the app
To run the application on your development machine,

python3 manage.py runserver
## Technologies Used
Django
Python
Html
Css
Bootstrap3
Django-Admin
## Bugs
There are no known bugs at the moment


# Collaboration Information
Clone the repository
Make changes and write tests
Push changes to github
Create a pull request
Contacts
timmyworldboss@gmail.com

## About
This is a gallery application that a user can be able to view images and share the link with their friends


