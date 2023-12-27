## How to run the Dockerfile locally

docker build -t flask-smorest-api .

docker run -dp 5000:5000 flask-smorest-api

docker run -dp 5000:5000 -w /app -v "/D/REST-API-FLASK/Section-6-SQLAlCHEMY:/app" flask-smorest-api

use flask run instead of gunicorn