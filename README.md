# Profiles REST API
This Profile API is a Django REST Framework based API that provides basic functionality for managing user profiles.




## Dependencies:
Python (2.7, 3.2, 3.3, 3.4, 3.5, 3.6)\
Django (1.10, 1.11, 2.0)\
Vargant\
VirtualBox


## Getting Started


#### Creating development server
Running vagrant file
   1. Change directories to Vagrant fold inside project.
   2. Run ```Vagrantfile``` with command ```vagrant up``` 
   3. ssh into vagrant server with command ```vagrant ssh```   
 ```
Make sure you are in the same directory as the Vagrantfile when you use
the vagrant command. When you run all the vagrant file all the environment 
setting, variables, and dependencies with be installed for the project.
 ```
 
 
#### Importing All Requirements
We will importing all the required libraries into our python 
environment that is needed to build and run the api.
   1. Create python virtual environmant in vagrant box if doesn't not exist ```mkvirtualenv profiles-rest-api```
   2. Activating the python environment if not already activated ```workon profiles-rest-api``` 
   3. Change directories to project folder ```cd /opt/workspace/Profiles-rest-api/```
   4. intall all requiremenets ```pip install -r requirements.txt```  
   
   
#### Setting up the Database for the api
 By using Django rest framework we are able to setup database based on the 
 model, migrate any changes, run service, and debug while developing.
   1. Make sure that the python env is activate if not then ```workon profiles-rest-api```
   2. Change directories to project folder ```cd /opt/workspace/Profiles-rest-api/src/profiles_project```  
   3. Command for creating DB Migration ```python manage.py makemigrations```
  
   
#### Running Profiles API
Make sure you have the vagrant server running, your ssh into the server, 
have the python env activate, and you are in the correct direct
   1. Activate the python virtualenv with command ```workon profiles-rest-api```
   2. Change directory to the project folder ```cd /opt/workspace/Profiles-rest-api/src/profiles_project```
   3. Make sure that the database configuration is up to date with command ```python manage.py makemigrations```
   4. Run Python Django development server to host api ```python manage.py runserver 0.0.0.0:8081```

## Links:
Link for local machine: 

[http://127.0.0.1:8081](http://127.0.0.1:8081/api/ "Profiles API")
## Setup Django Admin


