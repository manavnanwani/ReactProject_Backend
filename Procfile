release: python manage.py makemigrations api --no-input
release: python manage.py migrate --no-input

web: gunicorn auth_system.wsgi