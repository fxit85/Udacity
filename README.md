This is the catalog project for the udacity full stack nano degree program.
It provides a place to create catalog categories and items in the catalog.
It uses a 3rd party Oauth registration and login in system,
which ensures only authorized users can manage their own data in the db.

****** secure api endpoint *******
It also has a secure api endpoint which you can access at
http://localhost:5000/api/json 
- username = world | password = hello -

I reused code from api developer website's and from previous Udacity 
projects like the Full Stack Foundations and Authentication and Authorization courses.

******** getting started *********
1. First install the following in your python 2.7 environment.

sqlalchemy, flask, itsdangerous, passlib, flask_httpauth, oauth2client

2. Run application.py and open http://localhost:5000 in your browser



	*****************************
	!!!!**** !IMPORTANT! ****!!!!
	*****************************

This app was developed using python version 2.7 and might not work
properly in other versions..
