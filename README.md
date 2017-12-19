# What's this?
  This is a Django-Tutorial.
# first day
  ### Installation
  
      $ pip install django
      
  ### [Create a Project](https://overiq.com/django/1.10/creating-django-project/)
  
      $ django-admin startproject django_project

      django_project\db.sqlite3
      django_project\db.sqlite3
      django_project\django_project\init.py
      django_project\django_project\settings.py
      django_project\django_project\url.py
      django_project\django_project\wsgi.py
   
  ### Start a Project
      django_project$ python manage.py runserver
  ### Setting
      django_project\django_project\setting.py

      INSTALLED_APPS = [
                        'django.contrib.admin',
                        'django.contrib.auth',
                        'django.contrib.contenttypes',
                        'django.contrib.sessions',
                        'django.contrib.messages',
                        'django.contrib.staticfiles',
                        ] 
      TIME_ZONE = 'UTC',
      
  ### [Add an Admin-Interface](https://github.com/rosarior/awesome-django#admin-interface):[1-djamin](https://github.com/hersonls/djamin/)
      
      
      pip install -e git://github.com/hersonls/djamin.git#egg=djamin
      
      INSTALLED_APPS = [
                        'djamin',
                        'django.contrib.admin',
                        'django.contrib.auth',
                        'django.contrib.contenttypes',
                        'django.contrib.sessions',
                        'django.contrib.messages',
                        'django.contrib.staticfiles',
                        ] 
       http://127.0.0.1:8000/admin/ 
