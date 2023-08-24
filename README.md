## Redash on Mac

deploy redash using docker-compose

Prerequisites:

- docker

- docker-compose

### Quickly Start

- clone

```shell
git clone git@github.com:hoosin/redash-deploy.git
```

- one time setup (first time only)

```shell
make setup
```

With the above command, You can access the local Redash from http://localhost:8000/

### Stop the service

```shell
make stop
```
