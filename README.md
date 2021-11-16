## Flask Rest API Boilerplate

### Technology used
* Python3.8
* Flask
* Flask-restplus
* Sqlite

### Features
* JWT Authentication 
* Swagger Documentation
* User CRUD
* Unittest

### Setup in your local machine
1. Clone project
```
git clone https://github.com/morshedmasud/flask-rest-api-boilerplate
```
2. Create virtualenv
```
virtualenv -p python3 venv
```
3. Active virtualenv
```
. venv/bin/activate
```
4. Go to project root path and install all dependency
```shell script
make install
```
5. Database migrations
```shell script
python manage.py db init
python manage.py db migrate --message 'initial database migration'
```
6. Database Update
```shell script
python manage.py db upgrade
```
7. Run Application
```shell script
make run
```
8. To Tests
```shell script
make tests
```

#### Open the following url for view swagger documentation
http://127.0.0.1:5000/
