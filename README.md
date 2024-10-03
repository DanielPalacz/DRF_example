# DRF_example

###### Build a Web API with Django and display data from it on a Web Page Project
###### https://www.youtube.com/watch?v=RrVdko3Zgbw&list=PLOLrQ9Pn6cazTA2QyG2R2UT7MQCAOK3W4&index=12

## 1. Write web api (DRF)
## 2. Write web page using the web api from point 1

# Steps

##### Prepare project:
######  - install Django
######  - create django project
######  - create Django 'myapi' app (adn register it)
######  - create superuser / run migrations

#### 1. myapi app:

###### write model 'Post'
###### register model in admin space

###### pip install djangorestframework
###### register 'rest_framework' in settings.py INSTALLED_APPS

###### Telling to rest_framework about Model and how to serialize the data:
######  - serializers.py

###### Writing view, class-based view using 'viewset.ModelViewSet' from rest_framework
###### Setup urls
######  - router from DRF (router = routers.DefaultRouter())

#### 2. home endpoint rendering data collected by requests
##### - basic template