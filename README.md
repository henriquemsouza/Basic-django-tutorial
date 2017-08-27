# Basic-django-tutorial
Basic django tutorial from djangoproject for  version 1.9


Random info Organize later

https://docs.djangoproject.com/pt-br/1.9/intro/tutorial01/

virtualenv /home/henrique/Documentos/djangoteste/vtest/ -p python2.7

source /home/henrique/Documentos/djangoteste/vtest/bin/activate

pip install Django==1.9


django-admin startproject mysite
cd  mysite
python manage.py startapp polls

python manage.py runserver


 python manage.py migrate

python manage.py makemigrations polls

 python manage.py sqlmigrate polls 0001
python manage.py migrate


127.0.0.1:8000/polls/1/

*********************************************************************************************
 três passos para fazer mudanças nos seus modelos:

    Mude seus modelos (em models.py).

    Rode python manage.py makemigrations para criar migrações para suas modificações

    Rode python manage.py migrate para aplicar suas modificações no banco de dados.

*********************************************************************************************
 python manage.py shell

python manage.py createsuperuser

