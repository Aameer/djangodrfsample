django DRF (django rest framework) Sample Project
================

The project is a working model of (DRF) Django REST Framework 
Requirements
------------
* Django==1.7.1
* Markdown==2.5.2
* argparse==1.2.1
* django-filter==0.9.1
* djangorestframework==3.0.2
* wsgiref==0.1.2

Configration
------------
Setup it just like a usual django project.
To test if you have configured everything correctly, run the server `python manage.py runserver` and check the following link

* *http://localhost:8000/*, You should result like

![Sample output Image deals](https://raw.githubusercontent.com/Aameer/djangodrfsample/master/quickstart/static/img/main.png)
![Sample output Image deals](https://raw.githubusercontent.com/Aameer/djangodrfsample/master/quickstart/static/img/user1.png)
![Sample output Image deals](https://raw.githubusercontent.com/Aameer/djangodrfsample/master/quickstart/static/img/user2.png)
![Sample output Image deals](https://raw.githubusercontent.com/Aameer/djangodrfsample/master/quickstart/static/img/json.png)
![Sample output Image deals](https://raw.githubusercontent.com/Aameer/djangodrfsample/master/quickstart/static/img/group.png)


Add a superuser for your database and after authentication you can add new users by POST, You can also GET the present users.You will see users information like `username`,`first_name`,`last_name`, `email`,`groups`. Similar information is shown for Groups. 
