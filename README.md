# Project Template by Luxu

## Este template foi feito com:

* [Python 3.10.6](https://www.python.org/)
* [Django 4.1.*](https://www.djangoproject.com/)


Now we can pull Django Quickstart Structure to Project

django-admin startproject --template https://github.com/henriquebastos/django-quickstart/archive/master.zip --name=Procfile,.env myproject .

And then, proceed with the installation of quickstart's requirements.


# Criar o *.env*
* rode ``python contrib/env_gen.py``
* Fazer as alterações necessárias

## Como rodar o projeto?


* Crie um virtualenv com Python.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

```
git clone https://github.com/rg3915/django-htmx-tutorial.git
cd django-htmx-tutorial
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser --username="admin" --email=""
python manage.py runserver
```
