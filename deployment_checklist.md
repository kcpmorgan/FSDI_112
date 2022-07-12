# To deploy our project

1.  Update the allowed hosts setting in settings.py
2.  Install and configure whitenoise.
3.  Install gunicorn
    3.1 Update requirements.txt via 'pip3 freeze > requirements.txt'.
4.  Add a Procfile with instructions for a web app.
5.  Add a gitignore file with at least the following folders:
    venv
    '_**pycache**_'
    staticfiles
6.  Make sure to initialize a git repository and generate at least one valid commit
    6.1 (Optional) Rename your main branch to 'main' via 'git branch -M main'
7.  Create a new heroku app via heroku create
8.  Push to heroku via 'git push heroku main'
