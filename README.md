## Introduction
Django REST framework is a powerful and flexible toolkit that makes it easy to build Web APIs.I have bulit a simple API to allow admin users to view and edit the users and groups in the system.
To build the API, I refered the http://www.django-rest-framework.org/

##Used Technologies
1.Django RestFramework
2.sqlite database

## Getting Started
 `serializers.py` file present in the `details` folder is the heart of this API.The API can be further improved using MODEL_Serializers

Staying in the root directory, execute the following commands :
```
python manage.py migrate
python manage.py createsuperuser

python manage.py runserver [port_number] #port number is optional

```

This should start the server running on your localhost
Point your browser to the link specified below
[http://localhost:8000](http://localhost:8000)
You will see the API root . You can navigate to users or the groups

[http://localhost:8000/users](http://localhost:8000/users)  takes you to the users list and
[http://localhost:8000/groups](http://localhost:8000/groups) takes you to the group list

## Contact
For any queries, feel free to reach me at  *sn.munendra52 [at] gmail [dot] com*

