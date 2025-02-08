release: python manage.py migrate
web: gunicorn config.asgi:application -k uvicorn_worker.UvicornWorker
