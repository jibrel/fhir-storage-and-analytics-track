# FHIR Storage, Query & Analytics

Submitting WG/Project/Implementer Group - 
No such group, should we form it?


## Justification 

More and more developers about to start design storage for FHIR data.
Some start from existing schema, others wish to design for FHIR from beginning.
We hope this group/track will share experience about FHIR storage implementation,
as well as analytics on FHIR datasets.

* How to store FHIR data?
* What is database schema design?
* Which databases can be used?
* What i have to do to be part of it?
* How to approach FHIR search?

TODO


## Topics

* Build FHIR API on top of existing database
  * on fly convertion data & queries
  * intermidiate FHIR database (replication problem)
* Design generic FHIR storage
  * document oriented (json, xml, protobuf)
  * relational
* Feed FHIR data into analytical databases
  * transaction log for replication

## Scenarios

* Implement basic FHIR search functionality
* Implement complex queries on FHIR resources
* Implement FHIR server integration with analytic database




## Databases

### Relational

* PostgreSQL

### Document databases

* MongoDB

### Analytical

* ElasitcSearch
* ClickHouse
* Biq Query

### Integration bus

* Kafka


## Participants

* [Health Samurai](http://health-samur.ai)
