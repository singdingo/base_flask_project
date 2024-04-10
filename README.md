After cloning the base Flask project:
- Create a virtual environment to run your project in (see below)
- Add Flask to your virtual environment using pip install Flask
- Create environment variables for the dev environment (see below)

To create a vitual environment.
- Go in to your project folder
- python -m venv <virtual_environment_name>
- source <virtual_environment_name>/bin/activate

To deactivate the virtual environment
- deactivate

To create the necessary environment variables, in a command line in your virtual env:
- export FLASK_ENV=development
- export FLASK_APP=hello.py
- export FLASK_DEBUG=1

This will allow you to run the app in debug mode. Any changes will automatically restart the web server.

You may call your main entry point file anything. In this case, it's hello.py, but yours could be app.py or anything else. 

TO RUN THE APP
- flask run

FEATURES OF THE BASE FLASK PROJECT
- Base level app set up
- A few simple routes
- Routes for error pages
- Some basic templates that includes base templates
- Some basic Bootstrap added

Most of this can be deleted and changed for your own app.
