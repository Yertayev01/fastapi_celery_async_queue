# Asynchronous Tasks with FastAPI and Celery

Example of how to handle background processes with FastAPI, Celery, and Docker.

### Quick Start

Spin up the containers:

```sh
$ docker-compose up -d --build
```

Open your browser to [http://localhost:8004](http://localhost:8004)



GUIDANCE:
Take note of celery -A worker.celery worker --loglevel=info:

celery worker is used to start a Celery worker
-A worker.celery runs the Celery Application (which we'll define shortly)
--loglevel=info sets the logging level to info