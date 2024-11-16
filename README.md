# codtech-task-1

.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

.\bin\windows\kafka-server-start.bat .\config\server.properties

kafka-topics.bat --create --bootstrap-server localhost:9092 --topic codtech

kafka-console-producer.bat --broker-list localhost:9092 --topic codtech

kafka-console-consumer.bat --topic codtech --bootstrap-server localhost:9092 --from-beginning

.\bin\windows\kafka-server-stop.bat .\config\server.properties
