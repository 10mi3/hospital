web: gunicorn GH.wsgi.application
release: python manage.py makemigrations --noinput
release: python manage.py migrate --noinput
release: python manage.py createsuperuser --noinput