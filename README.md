# Cinema API

API created to manage cinema activities, written on DRF

## Installing using GitHub

```
git clone https://github.com/pazyn404/cinema-api.git
cd cinema-api
pythom -m venv venv
venv\Scripts\Activate
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Run with Docker
```
docker-compose build
docker-compose up
```

## Getting access

* Create user via /api/user/register/
* Get access token via /api/user/token/
* Refresh token via /api/user/token/refresh

## Features
* JWT authentication
* Powerful admin panel for advanced managing
* Detailed documentation
