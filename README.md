Pine push server rabbitmq
==========================
Run rabbitmq using docker

Installation
-------------
Install docker (http://docs.docker.com/installation/ubuntulinux/)

Run
----
 8510 port : rabbitmq node
15672 port : rabbitmq web management

    sudo docker run \
      -ti \
      -p 127.0.0.1:8510:8510 \
      -p 15672:15672 \
      --name rabbitmq \
      reaperes/pine-push-server-rabbitmq

You can tail the logs using docker logs -f $container_id
