# Food_Blog_Django

# Commands

 # Create Virtual Environments
   mkdir Environments
   
   CD Environments
 
 # Create isolated virtual environments
   pip install virtualenv
   
   virtualenv --version   //verify a successful installation 
   
   virtualenv myenv
   
 # Activation
   myenv\Scripts\activate.bat
   
 # Install Django and Activate
   cd Desktop
   
   virtualenv django
  
   cd django
  
   Scripts\activate.bat
   
   pip install Django
   
 # Create a workspace for project
    
   cd Desktop
   
   mkdir mysite
   
   cd mysite
   
   django-admin startproject mysite // to start a django project
   
# Navigate into the outer directory where manage.py script exists

   cd mysite
   
   python manage.py startapp blog
   
 # To make migrations
    
   python manage.py migrate
   
   python manage.py runserver
   
 #  Create an Administration Site
    
   python manage.py createsuperuser
   
   python manage.py runserver
   
   
   
   
   
   
   
   
   
   
   
   
