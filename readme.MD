# Simple Micro Blog With Django

This Repository covers a Simple Django Micro Blog.

### Tech Required
1. Python to actually use Django
2. VS Code as the  IDE of Choice
3. PythonAnywhere for hosting the website  visit ```www.pythonanywhere.com``` and open a free account.
4. git for keeping track of the project.
5. Github to host the project.



### To get Started

1. Create a Virtual Enviromnet using the command ```python -m venv myvenv ``` . Here the name of our Virtual Environment is ```myenv ```
2. Activate the Virtual Environment using ```myvenv\Scripts\activate ```
3.  Add a File called ```requirments.txt ``` and  add ```Django~=3.2.10 ``` to the text file.
4. Now by using the command ```python -m pip install -r requirements.txt ``` . Make sure to check the Spelling of the requirments file.
5. In the PythonAnywhereWebsite, in the account Section , Use api token to create an api token .
6. To Start the Project use ```django-admin.exe startproject mysite ```

### Django File Structure:
```django-admin.py ```is a script that will create the directories and files for you. You should now have a directory structure which looks like this:

SimpleBlog
├── manage.py
├── mysite
│   ├── asgi.py
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── myvenv
│   └── ...
└── requirements.txt

Note: in your directory structure, you will also see your myvenv directory that we created before.

```manage.py``` is a script that helps with management of the site. With it we will be able (amongst other things) to start a web server on our computer without installing anything else.

The ```settings.py ```file contains the configuration of your website.

Remember when we talked about a mail carrier checking where to deliver a letter? ```urls.py ```file contains a list of patterns used by urlresolver.

### Certain Useful Django Commands:

1. ```python manage.py runserver ``` =  starts the server
2. ```python manage.py migrate ``` = will migrate to changed settings. 