# djangostripe

source bin/activate
.\Scripts\activate
deactivate

# Create superuser (admin)
python manage.py createsuperuser 

# Create app
python manage.py startapp {name} 

# Make changes
python manage.py makemigrations 
python manage.py migrate 

# Python edit 
python manage.py shell

# -> commands: (creaete new elements under apps)
from products.models import Product
Product.objects.all()
Product.objects.create(title = 'New product 2', decription = 'yay", price = '12314', summary = 'sweet')
