#Commands
django-admin startproject drfEcommerce

./manage.py runserver

from django.core.management.utils import get_random_secret_key

print(get_random_secret_key())