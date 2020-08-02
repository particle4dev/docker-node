# Dockerized [node with dumb-init](https://github.com/Yelp/dumb-init)

This repository contains Dockerized [node with dumb-init](https://github.com/Yelp/dumb-init). Repository name in Docker Hub: [particle4dev/node](https://hub.docker.com/r/particle4dev/node)

<br />

[![CircleCI](https://circleci.com/gh/particle4dev/docker-node.svg?style=svg)](https://circleci.com/gh/particle4dev/docker-node)

## Usage

#### Show usage

```
$ docker run --rm particle4dev/json-server
```

#### Server example

```
$ docker run  \
      -d -p 8888:8888 -v $(pwd)/data.json:/data/db.json   \
      particle4dev/json-server                            \
      --watch db.json
```

#### More examples

Most examples documented in [JSON Server project site](https://github.com/typicode/json-server) will work.
