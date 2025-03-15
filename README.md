# Django - creating API

## About
This repository is my twelfth homework assignment from the Python Pro course. This is my first introduction to the Django framework.
I will make web-site that calls pet-shelter. Tha main idea for this site is to allow users to schedule visits with animals in a shelter. 
The platform enables potential adopters to browse available pets and book appointments to meet them in person.

I have added four app`s to the project:
    - main
    - user
    - blog
    - animals

Those apps registered in pet_shelter/settings.py.
Also I have created endpoints in urls.py and view functions in views.py but http methods are not implemented yet.
Added templates, models, migrations.

## Run API
1. Clone the repository:  
   ```bash
   git clone https://github.com/OleksiiUzu/django-api-homework-12.git
   cd django-api-homework-12
2.(Optional) Create and activate a virtual environment:
  python -m venv venv
  source venv/bin/activate

3.Install dependencies:
  pip install -r requirements.txt

4.run command:
    python manage.py runserver
