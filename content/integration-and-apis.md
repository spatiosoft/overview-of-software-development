# Integration and APIs

Integration means connecting different systems. 
They can be from the same app, the same company, or different companies.

Connecting systems is an essential part of software development that leads to great challenges.

One single app can live happily on its own, but a business process may require to interact with other systems.
These interactions can happen in the background, as soon as possible, App 1 will inform App 2 of a new event. 
This is an asynchronous call from App 1 to App 2. 
It will happen, but we don't know when.

Another way to interact is to wait for the response. 
This is required if an action depends on the result of another action.
This is a synchronous call.

## REST API

REST stands for Representational State Transfer.
The state of an entity is transferred from one system to another. 
The entity can be created, updated, or deleted.

[Restful API](https://restfulapi.net/)

## STREAM API

The streaming has its roots in the application messaging system.
One application would send a message to one or more applications via a message broker.
The message broker would then deliver the message to the applications.

The streaming has shifted the perspective from a simple message system with many various problems
to synchronize the data ans stay consistent.

The Event Driven Architecture is a way to design the system to be more resilient and scalable.
With the emergence of Kafka, streaming has become more popular.
An event is published in a topic, and the consumers can subscribe to the topic to receive the event.
This time the message remains indefinitely in the topic, and the consumer can replay the message if needed.
In that case, if a system fails, it can replay the message and continue the process.

[Kafka](https://kafka.apache.org/)
[Event Driven Architecture](https://www.confluent.io/learn/event-driven/)