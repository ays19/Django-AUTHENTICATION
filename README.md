**Django-AUTHENTICATION**
APP CREATION

django-admin startproject authetication
python manage.py startapp account

settings.py in authentication folder-->
Include account in the INSTALLED_APPS= []
Include BASE_DIR / 'templates' in TEMPLATES under 'DIRS':[]
Include this line:
STATICFILES_DIRS = [BASE_DIR / 'static']
