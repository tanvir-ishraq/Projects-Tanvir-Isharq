# NowWeather - A django weather web application project
Web app to view detailed weather attributes of any location. Connecting third party API and clean responsive bootstrap rich UI. 

Temprature, pressure, humidity, forcast, description, coordinate

## instructions: 
run:

python manage.py makemigrations

python manage.py runserver

## Description
A django weather web application project:
* Search functionality for any location. Provides temprature, pressure, humidity, forcast, description, coordinate for locations.
* Api integration. Then process JSON with python dictionary to deliver to frontend.
* csrf token for form submission. Cross-site request forgery protection.
* Use of bootstrap to be faithul to responsiveness

tags: POST method, url patterns

## Created with:
django-admin startproject weatherproject

python manage.py startapp main
  
note: will require internet connection for frontend UI. uses CDN for frontend UI      
  
*sign-in functionality to be added*
