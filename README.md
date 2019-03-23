[Get Started With Django Part 1: Build a Portfolio App](https://realpython.com/get-started-with-django-1/)

[GitHub repo for Portfolio App](https://github.com/realpython/materials/tree/a639f1c2f85032334fbb4dca88f3e8dc88397f6d/rp-portfolio)

[Oreilly book](learning.oreilly.com/library/view/practical-django-2/)

### NOTES:

```
$ mkdir booktime or rp-portfolio
$ cd booktime or rp-portfolio
pipenv shell or python3 -m venv venv
$ pipenv --three install Django 
pipenv shell or source venv/bin/activate and pip install Django

django-admin startproject booktime . !!!! or django-admin startproject personal_portfolio
./manage.py runserver
./manage.py startapp main or  python manage.py startapp hello_world

add main or hello_world to INSTALLED_APPS in settings.py

./manage.py test
```