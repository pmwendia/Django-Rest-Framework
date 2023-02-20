# Django-Rest-Framework
## Creating a simple BookListDRF app using Django-Rest-Framework
# Prerequisites
open cmd on windows and type the following commands respectively:

    mkdir Django-Rest-Framework && cd Django-Rest-Framework
    
    pip install pipenv

    pipenv shell      # this command creates a virtual environment for the project
    
    pipenv install django     # install django framework in the virtual environment
    
    django-admin startproject BookList .       # creates a project
    
    python manage.py startapp BookListDRF       # initializes the app
    
    pipenv install djangorestframework
    
    code .      # opens the project in Visual Studio Code
    
refer to https://docs.djangoproject.com/en/4.1/intro/tutorial01/
    
### configurations
Open the settings.py and add to the list of to the installed apps 
        
        'rest_framework',
        'BookListDRF',

### Database setup¶
run the following command:

    python manage.py migrate

Read more https://docs.djangoproject.com/en/4.1/intro/tutorial02/
### Creating models¶
![Alt text](models.PNG "a models")
### Views

### Pagination
Create a urls.py in the app's directory
