
Project Title: Yet another Kafka \n
An attempt to create clone of Kafka using socket programming.

Publisher sends messages of topics to the broker via a socket where it is stored and forwarded to subscribers of
that topic.Files were used for inter-process communication where the port numbers were updated to connect to
the active broker.Fault tolerance was achieved using multiple broker processes running in parallel and redundancy
of records were maintained
