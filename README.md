# django-graphql
django testing with graphql

# Do it step by step

```

with the virtual environment activated:

pip install django
pip install graphene_django
pip install django-filter

django-admin startproject djangographql

cd djangographql

python3 manage.py startapp movies

python3 manage.py makemigrations movies
python3 manage.py migrate

python3 manage.py runserver
```