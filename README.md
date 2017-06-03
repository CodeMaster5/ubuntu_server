# Item Catalog Server
This server host the Item Catalog project (https://github.com/CodeMaster5/item_catalog) as a wgsi app. The database of original project is changed to a PostgreSQL database.
URL: http://ec2-54-86-201-19.compute-1.amazonaws.com/catalog/

# Usage
To access the server: `ssh grader@54.86.201.19 -p 2200 -i newkey`

# Ongoing Issues
User login and Google Authorization are down. As of now, only the data from the database is presented.

# Configuration
Software: Python 2.7.12, PostgreSQL 9.5.7, Apache2, and mod_wsgi
Ports: 2200, 80, 123
SSH: password authorization and root login disabled
Path of Application: /etc/apache2/sites-available/FlaskApp.conf

# Sources for this Project:
Deploying to Linux Servers - Udacity
Configuring PostgreSQL and SQLAlchemy - http://www.vertabelo.com/blog/technical-articles/web-app-development-with-flask-sqlalchemy-bootstrap-part-1
How To Deploy a Flask Application on an Ubuntu VPS - https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps




