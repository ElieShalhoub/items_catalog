Project 3 - Items Catalog version 1.0 20/06/2016

Description

This project is a web application that provides a list of items within a variety of categories and integrates third party user registration and authentication. Authenticated users have the ability to post, edit, and delete their own items.

What's included

The following files and directories are included in the project:
├── client_secrets.json
├── fb_client_secrets.json
├── database_setup.py
├── database_setup.pyc
├── application.py
├── catalog.db
├── README.md
├── templates
    ├── deleteCategory.html
    ├── editCategory.html
    ├── editcategoryitem.html
    ├── publiccategories.html
    ├── newCategory.html
    ├── newcategoryitem.html
    ├── categoryitems.html
    ├── publiccategoryitems.html
    ├── categories.html
    ├── login.html
    ├── main.html
    ├── deletecategoryitem.html
├── static
    ├── blank_user.gif
    ├── top-banner.jpg
    ├── styles.css



database_setup.py contains the sqlite table defintion statements.
application.py contains the project implementation (the controller implementation).
The templates folder contains the html pages to be displayed (the view implementation).
The static folder contains the css file, and images used in the front end.

Running the code

Make sure that you have Python 2.7 and sqlite installed on your computer.

On a mac or linux, open terminal, and navigate to where you downloaded the project files, then:
- Type python application.py to run the application.

On windows, Open the file application.py in IDLE, and make sure that all the downloaded files are in the same directory, and then select: Run > Run Module

A successful run results in: running a web application that can be accessed through: http://localhost:5000

Creator:

Elie Shalhoub
