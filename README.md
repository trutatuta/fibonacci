# Fibonacci application
Aplikacja stworzona za pomocą języka Python oraz framework'u Flask
![Screenshot_32](https://user-images.githubusercontent.com/61692272/144723719-b1266f8b-8416-49fa-acec-792661177fcd.png)
![Screenshot_33](https://user-images.githubusercontent.com/61692272/144723724-674b46f2-10d6-464d-ab17-40d7d9ce9db9.png)

Krok 1 - Wersja “developerska”
Dockerfile.dev1 w folderze "app"


```
docker build -f Dockerfile.dev1 -t flask_app .
docker run -d -p 5000:5000 flask_app
```

Krok 2 
Plik Dockerfile.dev2 w folderze "app" oraz plik docker-compose.yml

```
docker compose up --build
```

Krok 3
Wersja produkcyjna, Dockerfile w folderze "app" oraz plik docker-compose1.yml

```
docker compose -f docker-compose1.yml up --build
```
