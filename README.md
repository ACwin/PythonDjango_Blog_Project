# PythonDjango_Blog_Project



[![](https://img.shields.io/badge/python-3.8.0-orange.svg)](https://www.python.org/downloads/release/python-370/)
[![](https://img.shields.io/badge/django-3.2-green.svg)](https://docs.djangoproject.com/en/2.1/releases/2.1/)
[![](https://img.shields.io/badge/bootstrap-4.1.3-blue.svg)](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
[![](https://img.shields.io/badge/license-CC_BY_NC_4.0-000000.svg)](https://creativecommons.org/licenses/by-nc/4.0/)


## Code usage instructions




```bash
python -m venv env
```


Install all dependencies automatically:

```bash
pip install -r requirements.txt
```

Then perform data migration:
```bash
python manage.py migrate
```

Finally run the test server:
```bash
python manage.py runserver
```

The project is up and running.

If you want to clear all data and media files, just delete them and run:

```bash
python manage.py createsuperuser
```

The administrator account can be recreated.
