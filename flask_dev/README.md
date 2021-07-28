The Basic App builds on the QuickStart App by adding the following features:

    Register and Login with an email
    Confirm emails, Change passwords
    Role-base authorization
    Enable translations

Unlike the QuickStart App, the Basic App requires proper SMTP settings and the installation of Flask-BabelEx.

# Create a development environment

We recommend making use of virtualenv and virtualenvwrapper:

# Create virtual env
mkvirtualenv my_app
workon my_app

# Create working directory
mkdir -p ~dev/my_app           # or  mkdir C:\dev\my_app
cd ~/dev/my_app                # or  cd C:\dev\my_app

Install required Python packages

# Uninstall Flask-Babel if needed
pip uninstall Flask-Babel

# Install Flask-BabelEx and Flask-User
pip install Flask-BabelEx
pip install Flask-User

