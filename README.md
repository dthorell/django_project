# Django Project Template
A Django template with black/pre-commit hooks

## How to install

Create folder structure:

```
$ mkdir project_name
$ cd project_name
$ git clone git@github.com:dthorell/python_project.git .
$ mkdir src
```

Install virtualenv dependencies using:

```
$ pipenv install --dev
$ pipenv install django
$ pipenv shell
```

Initialize git repo
```
$ git remote remove origin
$ git remote add origin git@github.com:username/{{YOUR_GIT_REPO}}.git 
$ pre-commit install
```

Create a new project based on this template using:

```
$ django-admin.py startproject --template=https://github.com/dthorell/django_project/archive/main.zip project_name src
$ git add .
$ git commit -m "Initial project setup"
```
