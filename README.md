# workshop_management
Activity management of workshop technicians

# INSTALLATION

- pip install django
- pip install djangorestframework
- pip install mysqlclient (only Python 3.7.x)
- pip django-admin startproject soporte
- pip install pylint (linter for python)

# INITIAL CONFIGURATION

- set configuration connection to access database
- manage.py migrate (migrate the default models that come in the django framework)
- manage.py startapp users (within the base directory created by django for the project)
- manage.py createsuperuser
- manage.py runserver 
