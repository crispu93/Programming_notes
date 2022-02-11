# Useful commands and information to build python projects from scratch

If you want to create a Flask app, here they describe very well the structure that should be followed:
 https://www.digitalocean.com/community/tutorials/getting-started-with-flask-a-python-microframework

## Create a virtual environment (see virtualEnvironments.md)
```shell
$ python -m venv path/to/venv
```

## Create the requirements file
```shell
$ pip freeze > requirements.txt
```

## Create app directory
- It should have the name of the app not just 'app'.
- In the case of a Flask app, create inside the folders 'templates' and 'static'.

## Run a flask application (F)
```shell
$ export FLASK_APP=name_of_the_app.py
$ flask run
```