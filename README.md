# Django Music Player

A music player built with django web framework
## Requirements

Python 3.8+, django, pillow

## Instalation

First, clone this repository.

    $ git clone https://github.com/sumitmallick/MusicApp/
    $ cd MusicApp

After, create virtual env for the app and install all necessary packages to run:

    $ python3 -m venv venv
    $ source venv/bin/activate
    $ pip install -r requirements.txt

Than, run the application:

	$ python3 manage.py makemigrations
    $ python3 manage.py migrate
    $ python3 manage.py createsuperuser
    $ python3 manage.py runserver

To see your application, access this url in your browser: 

	http://127.0.0.1:8000/

To see your application's admin, access this url in your browser:

    http://127.0.0.1:8000/admin