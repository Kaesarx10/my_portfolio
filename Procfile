web: gunicorn my_portfolio.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate
