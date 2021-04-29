# Yidan Gong

# Building docker container:

```
docker-compose up -d --build
docker-compose up
```
docker-compose up --build
# Developing environment:
```
pip install virtualenv or pip install venv
virtualenv env
source env/bin/activate
pip install -r requirements.txt
```
* Run server:
```
./start
uvicorn main:app/
```
* exit environment
```
deactivate
```
* API information can be checked at http://localhost:8000/docs

# Database:

* This service have its own database. It will use http requests to retrieve stage id.

