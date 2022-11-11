gunicorn app:application --preload -b 0.0.0.0:8000
python manage.py collectstatic --noinput
manage.py migrate