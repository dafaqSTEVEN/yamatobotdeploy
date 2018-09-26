$ ls
Pipfile		Pipfile.lock	Procfile	web.py

$ heroku create --buildpack heroku/python

$ git push heroku master
…
-----> Python app detected
-----> Installing python-3.6.6
-----> Installing pip
-----> Installing requirements with Pipenv 2018.5.18…
       ...
       Installing dependencies from Pipfile…
-----> Discovering process types
       Procfile declares types -> (none)
