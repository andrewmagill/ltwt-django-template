A Lightweight Django Template
=============================
From the book, [*Lightweight Django*](http://www.amazon.com/Lightweight-Django-Julia-Elman/dp/149194594X), by Julia Elman and Mark Lavin

### Requires ###
* Python 3.3 or 3.4
* Django 1.7

### Using the template ###
```bash
$ django-admin.py startproject --template=https://github.com/andrewmagill/ltwt-django-template/zipball/master <project_name>
```

Set DEBUG, SECRET_KEY, and ALLOWED_HOSTS environment variables
```bash
$ export DEBUG=off  # export will set env var only for current shell session
$ export ALLOWED_HOSTS=localhost,yourdomain.com
```