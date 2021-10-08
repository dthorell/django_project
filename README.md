# Django Project Template
A Django template with black/pre-commit hooks

## How to install

Create folder structure:

```
$ mkdir project_name
$ cd project_name
$ mkdir src
```

Install virtualenv dependencies using:

```
$ pipenv install
```

Initialize git repo
```
$ git init
$ pre-commit install
```

Create a new project based on this template using:

```
$ pipenv shell
$ django-admin.py startproject --template=https://github.com/dthorell/django-project/archive/master.zip project_name src
$ git add .
$ git commit -m "Initial project setup"
```
