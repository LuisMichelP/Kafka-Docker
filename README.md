# Kafka connector test project

The project consist in a python fake data generator which pushes data to a topic in kafka along with its schema and then
this data is sent to a postgres database using Kafka connector and a sink configuration


In order to start the connector sink service, you have to ensure that all the services in the docker compose are running
after that, run the start-connector.sh text on terminal.