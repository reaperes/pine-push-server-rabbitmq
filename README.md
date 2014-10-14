Pine push server rabbitmq
==========================
Run rabbitmq using docker

Installation
-------------
Install docker (http://docs.docker.com/installation/ubuntulinux/)

Run
----
    docker run -d \
               -p 8510:5672 \
               -p 18510:15672 \
               reaperes/pine-push-server-rabbitmq

You can tail the logs using docker logs -f $container_id
