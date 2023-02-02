shop for a django

############
install server
python -m venv env
env/Scripts/activate.bat
pip install django
django-admin startproject puddle
cd puddle

################
lets start server
python manage.py runserver

python manage.py startapp core
