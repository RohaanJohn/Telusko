release: python manage.py migrate && chmod u+x management/__init__.py && ./management/__init__.py
web: python manage.py migrate && gunicorn telusko.wsgi
