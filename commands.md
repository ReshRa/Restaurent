#commands
./manage.py runserver

from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())


#creating for  package version that installed in this proj 
pip freeze > dev.txt 
pip install -r dev.txt     

#packages
asgiref==3.8.1
cffi==1.17.0
cryptography==43.0.0
Django==5.1
djangorestframework==3.15.2
iniconfig==2.0.0
mysqlclient==2.2.4
packaging==24.1
pluggy==1.5.0
pycparser==2.22
PyMySQL==1.1.1
pytest==8.3.2
python-dotenv==1.0.1
sqlparse==0.5.1




pip install python-dotenv
python-dotenv-1.0.1
pip install --upgrade pip