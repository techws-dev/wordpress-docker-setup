# wordpress-docker-setup

This project helps to work with wordpress, using docker 
to have a full development environment, with a persistant database.

### Instructions

Copy __.env.default__ to __.env__, and update values.

From the command line:

```console
make start
```

It will download and install wordpress + mysql from docker, then run 
the docker containers.

Your Wordpress site is up and running from http://localhost:8080/.
