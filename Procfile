web: gunicorn pokedex_project.wsgi
release: python manage.py migrate users && python manage.py migrate && python manage.py load_pokemon