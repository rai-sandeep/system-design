# system-design
System Design Concepts and Use Cases

## Distributed Systems

In a distributed system, components are spread across multiple computing devices (also called nodes) on a network.

## CAP Theorem

Any [distributed system](#distributed-systems) can guarantee only two of the following:
* **Consistency** - Every read receives the most recent value
* **Availability** - Every request receives a response, even when one or more nodes are unavailable or unreacheable
* **Partition Tolerance** - The system continues to function even when there is a communication break (partition) between nodes
