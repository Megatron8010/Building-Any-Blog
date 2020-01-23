# Setting up Directories Initially

Download your template and create and activate a virtual environment in the same directory
``` 
virtualenv env
\env\Scripts\activate.bat
//for some reason I have to change directories to run this need to figure out a solution
```

Install Django and StartProject

```
pip install django
django-admin startproject project_name

```

Rename root Django Folder to SRC and create static and template folders inside it and move files
Add Template directory in the settings.py
