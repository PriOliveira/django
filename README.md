<!-- https://tutorial.djangogirls.org/pt/django_start_project/ -->

Create the DB with:

```bash
python manage.py migrate
```

Then, run the server:

```bash
python manage.py runserver
```

Create app
```bash
python manage.py startapp <APP_NAME>
```

Update models
```bash
python manage.py makemigrations <APP_NAME>
python manage.py migrate <APP_NAME>
```

Create super user:
```bash
python manage.py createsuperuser
```