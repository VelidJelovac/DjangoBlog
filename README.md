# Blog application
This is a blog application created with Python and Django with a little bootstrap help that allows users to create, edit, and delete posts. The homepage will list all blog posts, and there will be a dedicated detail page for each individual post. Also the user must be registered to edit blog posts. Unregistered users can only read posts that have been posted.

# Setup
You need to have python version 3.6 or above and django version 2.2 or above installed.
You need to set up your virtual env to be able to use all the necessary requirements for this app.
Set Databse with simple commands:
```
python manage.py makemigrations
python manage.py migrate
```
Create you SuperUser so you could make first login into the app.
```
python manage.py createsuperuser
```

# Start the project with the command
```
python manage.py runserver
```

# That's it. You're ready to go.
