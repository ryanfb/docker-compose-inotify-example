FROM ubuntu
MAINTAINER Ryan Baumann <ryan.baumann@gmail.com>

RUN mkdir /docker-inotify
VOLUME ["/docker-inotify"]

CMD echo "Hello from container 2!" && sleep 3 && touch /docker-inotify/semaphore && tail -f /dev/null
