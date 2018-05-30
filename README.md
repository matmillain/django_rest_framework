# Create a virtual environment and install packages
$ pipenv install

# Activate the virtual environment
$ pipenv shell 

# Create and migrate the database then run the local development server
$ python manage.py migrate
$ python manage.py runserver