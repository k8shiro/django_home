
cd django-home
docker build -t django-home .
docker run --name django-home -p 8000:8000 -d django-home
