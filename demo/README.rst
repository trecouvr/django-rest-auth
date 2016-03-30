
Commands
--------

..code::

    python manage.py runserver --settings=demo.settings 0.0.0.0:9090
    curl -X POST -d '{"code": "xxx"}' -H 'Content-Type: application/json' 'http://localhost:9090/rest-auth/facebook/'
    curl -X POST -d '{"access_token": "xxx"}' -H 'Content-Type: application/json' 'http://localhost:9090/rest-auth/facebook/'
