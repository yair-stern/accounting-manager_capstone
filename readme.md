# Accounting Manager - Capstone
### Full Stuck Python, John Bryce

## using detail:
install & create virtual environment:
pip install virtualenv env
python -m virtualenv env

active env
env\Scripts\activate

install all requirements:
pip install -r "requirements.txt"

create .env file:
DEBUG=True
SECRET_KEY=change-this-key
ALLOWED_HOSTS=__REPLACE_WITH_YOUR_DOMAIN__
CORS_ALLOWED_ORIGINS=https://__REPLACE_WITH_YOUR_FRONTEND__
DB_NAME=replace-with-your-db-name
DB_USER=postgres
DB_PASSWORD=1234
        "ENGINE": "django.db.backends.postgresql",
        "NAME": "mydatabase",
        "USER": "mydatabaseuser",
        "PASSWORD": "mypassword",
        "HOST": "127.0.0.1",
        "PORT": "5432",