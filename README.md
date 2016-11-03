# docker-sbt - a Docker container for sbt

# DOCKER HUB

https://registry.hub.docker.com/u/mcandre/docker-sbt/

# EXAMPLE

```
$ make
docker run --rm mcandre/docker-sbt:latest sbt sbtVersion
[info] Set current project to root (in build file:/)
[info] 0.13.
```

# REQUIREMENTS

* [Docker](https://www.docker.com/)

## Optional

* [make](http://www.gnu.org/software/make/)
* [Node.js](https://nodejs.org/en/) (for dockerlint)
