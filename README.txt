# Item catalog app

## Introduction
This application allows users to create categories and place items in those categories. Only signed in users can create, update and delete items and categories, and they can only manage their own categories and items.

## Requirements
Flask == 0.10.1
SQLAlchemy == 0.8.4
httplib2 == 0.9.1

## Set Up Environment & Installation
To set up, install the vagrant environment on your computer (provided by Udacity).
- start the virtual machine: ```vagrant up```
- login to the virtual machine: ```vagrant ssh```
- go to the item catalog directory: ```cd /vagrant/catalog```
- setup the database: ```python database_setup.py```
- start the server: ```python project.py```
- visit http://localhost:3000 to see the project running

## Usage
When the user is logged in, the user will have the option to create, update and delete categories and items.
