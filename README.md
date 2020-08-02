# Dockerized [NodeJS](https://github.com/nodejs/docker-node) with [dumb-init](https://github.com/Yelp/dumb-init)

This repository contains Dockerized [NodeJS](https://github.com/nodejs/docker-node) with [dumb-init](https://github.com/Yelp/dumb-init). Repository name in Docker Hub: [particle4dev/node](https://hub.docker.com/r/particle4dev/node)

**dumb-init** is a simple process supervisor and init system designed to run as PID 1 inside minimal container environments (such as [Docker](https://www.docker.com/)). It is deployed as a small, statically-linked binary written in C.

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
