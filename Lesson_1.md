# Just Django Notes

# How to create venv?
 pip3 install virtualenv
 virtualenv *name_of_env*
# Linux
 source *name_of_env*/bin/activate
# Windows
 source *name_of_env*\Scripts\activate


# How to install django?
 pip install django

# Create project
 django-admin startproject *name_of_project* .

# RUN SERVER
 python manage.py runserver

# MIGRATION
 python manage.py migrate

# SETTINGS.PY (center of django projects)
 DEBUG = True VS DEBUG = False <-when deploy is False
 installed apps
 databases
 static url

# URLS.PY
all path and urls like /admin /home etc will be added here

# WSGI.PY
 for deploying Junicron

# ASGI.PY
asynco?
