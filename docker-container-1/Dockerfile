FROM ubuntu
MAINTAINER Ryan Baumann <ryan.baumann@gmail.com>

RUN apt-get update && \
    apt-get install -y inotify-tools

CMD inotifywait -e attrib /docker-inotify && echo "Hello from container 1!"
