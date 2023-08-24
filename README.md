## Redash on Mac

Deploy [redash](https://github.com/getredash/redash) using docker-compose

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
- starts the service

```shell
make start
```

With the above command, You can access the local Redash from http://localhost:8000/

### Stop

```shell
make stop
```


### Redash version
If you wish to deploy a different version of Redash, please make direct edits to the ```./docker-compose.yml``` file.
Refer to the relevant version at: https://hub.docker.com/r/redash/redash/tags.
