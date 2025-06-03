Docker compose file will run below containers :
- zookeeper
- kafka
- kafka-ui
- config-server
- jfd-registry
- worker-mgmt


<b>Command to start the containers mentioned in the docker compose file.</b><br>
$ docker-compose up -d --remove-orphans

<b>Command to stop all the containers mentioned in the docker compose file.</b><br>
$ docker-compose down -v --remove-orphans

Some more helpful commands :
<b>Remove all stopped/exited containers.</b><br>
$ docker container prune -f
