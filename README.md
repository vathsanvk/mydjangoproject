# mydjangoproject


Learning Django


Instructions to begin with:

1. Use python3. Because future versions will just support python3
2. Install virtualenv globally using 'sudo pip3 install virtualenv'
3. Create a project folder
4. Create virtual env. inside the project folder using 'virtualenv venv -p python3'
5. Activate a virtual env. using 'source venv/bin/activate' (From the folder where venv is installed)
6. If you need to deactivate it, use 'deactivate'
7. To install django use 'pip install django'
8. To start a new django project use 'django-admin startproject myproject'
9. To create a new app inside projects use 'django-admin startapp <app-name>'
10. To run the server use 'python manage.py runserver'
11. After you create/update the models then instruct Django to create the database using 'python manage.py makemigrations'. See sql queries generated before going to next step using 'python manage.py sqlmigrate app_name file_name'.
12. And to apply the migration use 'python manage.py migrate'.
13. To invoke shell use 'python manage.py shell' (Useful if you want to update and access database values thru python shell)
14. To execure django's test module 'python manage.py test'
15. Create a superaccount using 'python manage.py createsuperuser'
16. Use this library to fix django forms API formatting 'pip install django-widget-tweaks'
17. To run tests for a specific app use 'python manage.py test boards'
and on a specific file using 'python manage.py test boards.tests.test_view_topic_posts'




Credits to Vitor Freitas for the series:
https://simpleisbetterthancomplex.com/series/beginners-guide/1.11/
