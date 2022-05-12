# Django-with-mongodb
Django with mongodb


pip install pip
pip install --upgrade pip

pip install django
pip install djongo


mongodb 5.4 version 

python manage.py migrations 
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 



DATABASES = {
    'default': {
        'ENGINE': 'djongo',
        'NAME': 'EmployeeDB',
    }
}
