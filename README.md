# docker-django-app

### Local environment
- docker 19.03
- docker compose 1.27.4
- git 2.17

### Environment to be created
- Python 3.8.5
- MySQL 8.0
- nginx 1.18

### Building Services
```
$ docker compose build
```

### Creating and launching containers
```
$ docker compose up -d
```

### Django installation commands
```
$ docker compose exec app django-admin.py startproject app .
```

### Restart app container
```
$ docker compose restart
```

Then you can access the app in the browser:
http://localhost:8000/

### Open bash shell of app container
```
$ docker compose exec app bash
```