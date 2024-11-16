# codtech-task-1
To start a Zookeeper 
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
To start a Server
.\bin\windows\kafka-server-start.bat .\config\server.properties
To start a topic 
kafka-topics.bat --create --bootstrap-server localhost:9092 --topic codtech
To start Producer
kafka-console-producer.bat --broker-list localhost:9092 --topic codtech
To start a Customer
kafka-console-consumer.bat --topic codtech --bootstrap-server localhost:9092 --from-beginning
To stop a server
.\bin\windows\kafka-server-stop.bat .\config\server.properties
