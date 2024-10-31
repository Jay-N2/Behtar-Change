# BehtarChange : NGO
A Kind Heart charity NGO website project in Django 

# Setup Virtual Environment
* Create a new folder for Django Project
* Open windows git bash

* install vertualenv
`pip install virtualenv`

* create vertualenv
`python -m venv venv`

* Activate virtualenv 
`source venv/Scripts/activate`
(If not getting activated '`Set-ExecutionPolicy Unrestricted -Scope Process`')

# Setup Django Project
* Clone Project repo
`git clone https://github.com/Jay-N2/Behtar-Change.git`

* install packages
`pip install django`
`pip install pillow`

* Make migrations 
`python manage.py migrate`

* Create a Superuser
`python manage.py createsuperuser`

* Run Django server
`python manage.py runserver`

* Open browser visit
`http://127.0.0.1:8000/admin`
