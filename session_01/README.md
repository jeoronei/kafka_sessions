# session 01

The objective around this session is garantee everyone has Kafka running in your machine. In order to keep the setting up process simple, we decided to use docker and docker-compose to execute kafka. 

The first task is run the docker-compose.yml file using docker, access the docker container, create 3 different topics with different number of partitions, send messages to the topics and consume that messages.

Tips: For this first session you can use the container command line bash to create the topics, send and consume the messages.

Some helpfull commands:
 - kafka-topics --bootstrap-server localhost:9092 --create --topic first_topic
 - kafka-topics --bootstrap-server localhost:9092 --list
 - kafka-console-producer --bootstrap-server localhost:9092 --topic first_topic
 - kafka-console-consumer --bootstrap-server localhost:9092 --topic first_topic

Auxiliar documentation about kafka running into a docker container: https://www.baeldung.com/ops/kafka-docker-setup

Good luck :)