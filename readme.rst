A basic blog, DDB style ;-)
=========================


Getting setup
-------------

::

    mkvirtualenv test1
    (clone this repo;-)
    cd ddbblog
    pip install -r requirements.txt
    python manage.py syncdb
    python manage.py runserver

Deploying to Heroku
-------------------

::

    heroku create
    git push heroku master
    heroku run python manage.py syncdb
    heroku open

