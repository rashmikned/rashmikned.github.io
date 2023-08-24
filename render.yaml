services:
  - name: web
    buildCommand: pip install -r requirements.txt && python manage.py migrate && python manage.py collectstatic --noinput
    startCommand: gunicorn spardha.wsgi --bind 0.0.0.0:$PORT
