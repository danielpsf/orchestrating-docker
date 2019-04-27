## Dockerizing a Flask app with Docker Compose

Featuring:
- Docker Compose v1.23.2
  - Static website
  - Python Flask app
  - PostgreSQL database

### Running

```docker-compose up --build -d```

```docker-compose run web /usr/local/bin/python create_db.py```

Voila! Access http://localhost

### Original post

https://realpython.com/blog/python/dockerizing-flask-with-compose-and-machine-from-localhost-to-the-cloud/
