web: python manage.py migrate --run-syncdb --noinput && gunicorn core.wsgi:application --bind 0.0.0.0:$PORT
