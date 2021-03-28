# Useful commands

**Create virtual environment
```bash
python -m venv venv
```

**Start virtual environment
```bash
.\venv\Scripts\activate
```

**Install dependencies
```bash
pip install django
```

**Create django project
```bash
django-admin startproject tutorialdjango
```

**Access the folder
```bash
cd tutorialdjango
```


**Start local development server
```bash
python manage.py runserver
```

**Apply migrations
```bash
python manage.py migrate
```

**Create an app
```bash
python manage.py startapp blog
```

**Create migration file
```bash
python manage.py makemigrations blog
```

**Run migrations
```bash
python manage.py migrate blog
```

**Create django super user
```bash
python manage.py createsuperuser
```