# Django-ReactJS-Framework-Listing-Application
This projects comprises the creation of a basic web application to list various technical frameworks, packages and databases and segregates the listed elements into completed and incomplete tabs.
The application offers options for the elements of the list to be deleted, edited or added along with a brief description.
## Technical aspects used in the project
- Django is a Python-based free and open-source web framework that follows the model–template–views (MTV) architectural pattern.  
- ReactJS is a free and open-source front-end JavaScript library for building user interfaces based on UI components.
- Representational state transfer (REST) is a software architectural style that was created to guide the design and development of the architecture for the World Wide Web.
- Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development.
-  Axios is a simple promise based HTTP client for the browser and node.js. Axios provides a simple to use library in a small package with a very extensible interface.
## Backend Development
-     mkdir app_name
      cd app_name
      python -m venv dar
      dar\Scripts\activate.bat
      pip install django
      pip install djangorestframework
      pip install django-cors-headers
      django-admin startproject backend
      code .
      cd backend
      python manage.py startapp todo
      python manage.py migrate
      python manage.py runserver 
      #After editing models.py
      python manage.py makemigrations
      python manage.py migrate 
      #After editing admin.py
      python manage.py createsuperuser
      python manage.py runserver    
## Frontend Development
-     dar\Scripts\activate.bat
      npx create-react-app frontend
      npm install reactstrap bootstrap
      npm install axios
      cd frontend
      npm start
## Images
![Screenshot (428)](https://user-images.githubusercontent.com/96294811/146544551-0e63ec65-0d65-49e7-8361-677b069476f6.png)![Screenshot (429)](https://user-images.githubusercontent.com/96294811/146544552-4d709a92-e36a-45c5-bc7f-36bf8c6d4d33.png)


