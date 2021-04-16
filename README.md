# Django  Library
this proyect was made using how a reference the Django Mozilla tutorial

>- Models for books, book copies, genre, language and authors
>- Users can view list and detail information for books and authors
>- Admin users can create and manage models



To get this project up and running locally on your computer:
We recommend using a Python virtual environment.

## Commands more used in the django project
   ```
   pip3 install -r requirements.txt
   python3 manage.py makemigrations make migrations from models to mysqls as tables inside the database
   python3 manage.py migrate
   python3 manage.py collectstatic
   python3 manage.py test # Run the standard tests. These should all pass.
   python3 manage.py createsuperuser # Create a superuser that handle the endpoint with the manager settings
   python3 manage.py runserver # turn on the server
   ```
> - `http://127.0.0.1:8000/admin/` to open the admin site


