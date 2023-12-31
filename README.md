# TaskTales (Solo Project - My First Full Stack App)

This is a Django application implemented with Python, utilizing Django's authentication system and a built-in SQLite database.
The front-end is developed using HTML and CSS.

------------------------------

The following steps and terminal commands guide you through creating a new virtual environment 
and installing the dependencies for Django and software development.


1.  Change the directory to the desired location where you want to clone the repository:

    `cd replace/with//path/to/your/local/directory`

2.  Now, you can use the git clone command to clone the repository:
   
    `git clone 'replace_with_actual_repository_url'`

3.  Create a new virtual environment in the repository directory for the project:
   
    `python -m venv venv`

4.  Activate the virtual environment (on Unix or MacOS):
   
    `source venv/bin/activate`

5.  Activate the virtual environment (on Windows):
   
    `.\venv\Scripts\activate`

6.  Upgrade pip (optional, but recommended):
   
    `pip install --upgrade pip`
      
7.  Install Django:
   
    `pip install Django`

8.  Install black:

    `pip install black`

9.  Install flake8:

    `pip install flake8`

10. Install djlint:

    `pip install djlint`

11. Deactivate your virtual environment:

    `deactivate`

12. Activate your virtual environment:

    `python -m venv venv`

13. Use pip freeze to generate a requirements.txt file:

    `pip freeze > requirements.txt`

14. Run migrations to apply model changes to the database:

    `python manage.py makemigrations`

15. Apply migrations to update the database schema:

    `python manage.py migrate`

16. Run the Django development server:
   
    `python manage.py runserver`

17. Starting the Development Server:

    The development server has been initiated, and you can access your application at http://127.0.0.1:8000/.

18. Quitting the Server:

    To stop the server, use CONTROL-C. If you need to restart it, use the command mentioned in step 16 above.

------------------------------

This Django application has a Django project named 'tracker', which includes three Django apps named 'accounts', 'projects', and 'tasks'. 

The following is the implementation process. In the repository directory:

1. Create a Django project named tracker so that the manage.py file is in the top directory;
   
3. Create a Django app named accounts and install it in the tracker Django project in the INSTALLED_APPS list;
   
4. Create a Django app named projects and install it in the tracker Django project in the INSTALLED_APPS list;
   
5. Create a Django app named tasks and install it in the tracker Django project in the INSTALLED_APPS list;
   
6. Run the migrations;
    
7. Create a super user.
    

