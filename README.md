
Project Title: Yet another Kafka <br>
An attempt to create clone of Kafka using socket programming.
<br><br>
Here are key concepts and components of Apache Kafka:<br><br>
Topics:<br>
In Kafka, data is organized into topics, which are similar to message categories or channels.
Producers publish messages to topics, and consumers subscribe to topics to receive and process the messages.
<br><br>Producers:<br>
Producers are responsible for publishing (producing) messages to Kafka topics.
They send messages to specific topics, and these messages are then stored in the Kafka cluster.
<br><br>Consumers:<br>
Consumers subscribe to one or more topics and process the messages produced to those topics.
Kafka allows multiple consumers to subscribe to the same topic, forming consumer groups, where each message is delivered to only one consumer within the group.
<br><br>Brokers:<br>
Kafka is designed as a distributed system, and it consists of one or more servers called brokers.
Brokers store and manage the data, and they communicate with each other to ensure data consistency and fault tolerance.
<br><br>ZooKeeper:<br>
Kafka uses Apache ZooKeeper for distributed coordination and to manage the configuration and metadata of the Kafka brokers.
<br><br>Partitions:<br>
Each topic can be divided into partitions, which allows Kafka to horizontally scale and distribute the load across multiple brokers.
Each partition is an ordered and immutable sequence of messages.
<br><br>Replication:<br>
Kafka provides data redundancy and fault tolerance through replication. Each partition can have multiple replicas, and these replicas are distributed across different brokers.
<br><br>Offsets:<br>
Every message within a partition has a unique identifier called an offset. Consumers use offsets to keep track of the messages they have consumed.
<br><br>Retention Period:<br>
Kafka retains messages for a configurable period. This retention period allows consumers that may have fallen behind to catch up.
<br><br>Streams API:<br>
Kafka includes a Streams API that enables developers to build stream processing applications, allowing for real-time data transformation and analysis.
