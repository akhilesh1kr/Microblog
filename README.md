# Welcome to Microblog!
A microblogging web application developed in Flask.

## Installation:
```bash
$ sudo -H pip3 install -U pipenv # only if pipenv is not installed in system

$ pipenv --python 3.6
$ pipenv shell

$ pip install -r requirements.txt

$ pip install Flask # Not needed anymore as Flask is now included in requirements.txt
$ export FLASK_APP=microblog.py # Not needed anymore as we are using python-dotenv and written this into .flaskenv file


$ flask run
```

## License
[MIT](https://choosealicense.com/licenses/mit/)