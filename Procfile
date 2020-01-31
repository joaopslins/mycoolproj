web: gunicorn mycoolproj.wsgi --chdir backend --limit-request-line 8188 --log-file -
worker: celery worker --workdir backend --app=mycoolproj --loglevel=info
