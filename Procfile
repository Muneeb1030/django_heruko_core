web: gunicorn --config gunicorn.conf.py core_django.wsgi
release: python manage.py makemigrations
release: python manage.py migrate --no-input
release: python manage.py collectstatic --noinput
