# Reservasi Dulu Frontend Templates


Clone the core repository to you local machine
```zsh
$ git clone git@github.com:icoldplayer/events.git

# move to events directory
$ cd events
```
Once you get the core project cloned into you machine, next is to clone the frontend / template.


```zsh
$ mkdir frontend & cd frontend 

# clone the frontend repo
$ git clone git@github.com:OkularID/RSTemplates.git
```

Create virtual environment on you machine
```zsh
$ python -m venv env

# activate it
$ source env/bin/activate
```

Install the project dependencies:
```zsh
$ pip install -r requirements.txt
```

Makemigrations & migrate

Linux / Mac
```zsh
# makemigrations
$ ./manage.py makemigrations

# migrate the dbs
$ ./manage.py migrate

# create superuser
$ ./manage.py createsuperuser
```

Windows
```bash
# makemigrate
$ python manage.py makemigrations

# dbs migrate
$ python manage.py migrate

# create user
$ python manage.py createsuperuser
```

Once all the project dependencies installed, you can now run the server with:

```zsh
# linux / mac
$ ./manage.py runserver

# windows
$ python manage.py runserver
```


To compress all assets objects, we use compressor init. <br>

```shell script
./manage.py collectstatic

./manage.py compress
```

Those command only works if the `DEBUG = False`.

That's all, and you're ready to go.

That's all.