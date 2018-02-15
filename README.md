# Laravel Local Development

This repo contains a set of docker files and supporting files to run a Lavarel project with docker. This example includes the following services.

- App and Web service via Nginx
- Database service running MySql


**Contents**

- [Getting started](#Getting Started)


## Getting started

To install or be able to use this example within your project download or clone this repo to your computer. When that is complete copy the contents of the `src` folder into the root or base of your project.

To start the web server you need to run the following command.

```
docker-compose up
```

The `docker-compose up` command starts all of the docker containers needed to support a full and robust Laravel stack.

Once the containers are done building or launching your app will be running on [localhost:8000](http://localhost:8000).

## 