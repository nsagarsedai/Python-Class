# Getting Started In Python

#### Create a repository (Git) and clone it locally

### For installing project specific requirements create virtual environment

`python -m venv venv `

### Activate the virtual env

* [ ] For windows:

`venv/Scripts/activate`

For Linux / Mac OS

`source venv/bin/activate`

### Now the setup is Complete

Install the required packages in virtual environment

`pip install Django`

### Create Django Project

`django-admin startproject core .`

### Run the django project

`python manage.py runserver`

### Git Add / Commit / Push Commands

`git add .`

`git commit -m "Your Commit Message Here"`

`git push origin main`


```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'mydb',
        'USER': 'root',
        'PASSWORD': 'admin',
        'HOST':'localhost',
        'PORT':'3306',
    }
}
```
