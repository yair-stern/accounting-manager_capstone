# Accounting Manager - Capstone
### Full Stack Python, John Bryce

## using detail:
install & create virtual environment:
pip install virtualenv
python -m virtualenv env

activate env
env\Scripts\activate

install dependencies:
pip install -r "requirements.txt"

create .env file:
```
DEBUG=True
SECRET_KEY=change-this-key
ALLOWED_HOSTS=__REPLACE_WITH_YOUR_DOMAIN__
CORS_ALLOWED_ORIGINS=https://__REPLACE_WITH_YOUR_FRONTEND__
DB_NAME=replace-with-your-db-name
DB_USER=replace-with-your-db-user
DB_PASSWORD=replace-with-your-db-password
DB_HOST=replace-with-your-db-host
DB_PORT=replace-with-your-db-port
```