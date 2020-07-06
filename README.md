# OpenJRE Docker
This is built to create an [Alpine-based](https://hub.docker.com/_/alpine) image to run Java projects.

## Java Version
This will start with [openjdk11-jre](https://pkgs.alpinelinux.org/package/edge/community/x86_64/openjdk11-jre) and has the following tags:

- `:11.0`, `:11` and `:latest` (OpenJRE 11)
- `:8.242` and `:8` (OpenJRE 8) (see tags or DockerHub)

## Build it
```
docker build -t maddhacker/openjre:11.0 . \
    && docker tag maddhacker/openjre:11.0 maddhacker/openjre:11 \
    && docker tag maddhacker/openjre:11.0 maddhacker/openjre:latest
```

# DockerHub
This is already built and on [Docker Hub](https://hub.docker.com/r/maddhacker/openjre)

# Slack
This is one of several projects that are in the works, so feel free to reach out on [Slack](https://maddhacker.slack.com/).  Please email `slack at maddhacker dot com` for an invite.

# Issues
Please use the [Issues tab](../../issues) to report any problems or feature requests.

# License
This is licensed under `Apache 2.0`.  Have fun!
