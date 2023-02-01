# django-fastapi-example


pip install -r requirements.txt
cd django_fastapi/
python manage.py migrate
python manage.py createsuperuser 


## Running

```
uvicorn project.asgi:app --debug
```

## Routes

The Django app is available at `http://localhost:8000/django/admin/`

The FastAPI app is is available at `http://localhost:8000/api/items/`
