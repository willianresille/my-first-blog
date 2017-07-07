python3 -m venv myvenv
source myvenv/bin/activate
pip install django==1.8.5 whitenoise==2.0
pip freeze > requirements.txt

django-admin startproject mysite . (cria o manager)
python manage.py migrate (cria tabelas manage)
python manage.py runserver ( inicia servico)
python manage.py startapp blog (cria projeto blog)
python manage.py makemigrations blog (cria arquivo de migrations do blog)
python manage.py createsuperuser (cria usuario admin)
