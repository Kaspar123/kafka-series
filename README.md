# References
- https://kafka.apache.org/books-and-papers
- Kafka Definitive guide
- Apache Kafka documentation
- Mastering Kafka Streams and ksqlDB
- TMO Commissions project
- TMO D3 Snowflake project

# Structure
## session-01-kafka-business
- quotes from kafka creators
- to understand the mindset of kafka creators
- core capabilities
- what companies are using Kafka
- why linkedin created Kafka
- why should I ever think about Kafka
- what are the use cases for Kafka 
- event streaming

## session-02-internals
- kafka buzzwords
- in that session we try to explain one buzzword
- drawing of what are we going to build today (kafka + java client)
- build a Dockerfile for kafka
- use kafka tools to produce and consume event to kafka topic
- create a docker-compose for kafka cluster + kafka ui
- create a java producer script - Producer API
- create a java consumer script - Consumer API
- visualize metrics using JMX
- explain the concepts of partition and replication factor
- why is that - show the kafka storage folder structure

## session-03-kafka-streams
- drawing of what are we going to build today
- what is stream processing
- what is kafka topology
- practical use case of kafka topology
- explaining the duality of streams and tables
- write a kafka streams application
- implement kafka topology using Streams API
- show the visualization from kafka ui
- extend the docker compose with kafka stream application
- reference to the future session of KSQL

## session-04-kafka-connect
- drawing of what are we going to build today
- introduce Kafka Connect java interfaces
- implement our own Kafka Connector
- use postgresql connector as a second example
- extend the docker-compose with 2 standalone connectors
- visualize the consumer in kafka-ui and that the data ends up in the target store
- reference to the future session of Snowflake

## session-05-kafka-spring
- drawing of what are we going to build today
- using kafka inside spring application
- produce events with spring application
- consume events with spring application
- consumer group

## session-06-managed-kafka
- drawing of what are we going to build today
- add an extra kafka cluster to kafka-ui - aws msk cluster
- replace the self-hosted cluster with MSK
- show that the system works again end-to-end

## session-07-ksql-ksqldb
- drawing of what are we going to build today
- drawing of how KSQL works - an abstraction of everything we have seen before
- using KSQL to define streams, tables, connectors, views etc
- reference back to duality of streams and tables
- chess - set of events vs a current state
- take example from the existing presentation 

## session-08-metadata-dtiven-development
- drawing of what are we going to build today
- real-life application of kafka in Nortal US project
- introduction to Snowflake by Newel Rice
- introduction to Snowflake Kafka Connector
- use case of kafka in an ongoing D3 Snowflake project
- project overview, performance testing kafka related system with millions of events

## session-09-certification
- how does the certification look like
- what are the domains of kafka certificate
- retrospective of what we did in the kafka workshop series