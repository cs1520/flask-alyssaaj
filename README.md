# flask-basics
A minimal app using the Flask framework

## Installing Flask in a VirtualEnv

To set up this repository on a local machine, I would recommend running the following commands:

```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip3 install -r requirements.txt
```

This will create a new Python virtualenv and download Flask. 
Virtualenvs are directories that hold all of the dependencies for a specific Python project.
It is considered good practice to create a new virtualenv at the root of a directory when starting a new Python project.

## Running the app locally

To run this application locally, you can run the `app.py` script like you would run any other Python application:

```
python3 app.py
```

This will start a server process at `http://localhost:5000` which you can use to preview your application. On Cloud Shell, you can click the "Preview" button in the top right of the page.

## Deploying to App Engine

Each time this command is run, it will publish a new version of your application to App Engine.
The first time that you run this it will ask you to specify a project and location if you have not run it before.

```
$ gcloud app deploy app.yaml
```

