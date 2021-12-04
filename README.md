# Fibonacci application
Krok 1 - Wersja “developerska”
Dockerfile.dev1 w folderze "app"

```
docker build -f Dockerfile.dev1 -t flask_app .
docker run -d -p 5000:5000 flask_app
```
