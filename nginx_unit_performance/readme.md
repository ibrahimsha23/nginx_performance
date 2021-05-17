
docker build --tag 'flask-nunit:latest' .
docker run -p 8080:8080 flask-nunit

ab -n 10000 -c 500 http://localhost:8080
