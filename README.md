# Apache Nifi
- Automate the flow of data between systems.

    E.g.: JSON -> Database, FTP -> Hadoop, Kafka -> Elasticsearch
- Drag and drop interface
- Focus on configuratino of processors
- Scalable across a cluster of machines
- Guaranteed Delivery / No Data Loss

## Is good at
- Reliable and secure transfer of data between systems
- Delivery of data from sources to analytic platforms
- Enrichment and preparation of data:
    - Conversion between formats
    - Extraction/Parsin
    - Routing decisions


## Shouldn't be used
- Distributed Computation
- Complex Event processing
- Joins, rolling windows, aggregations operations


## Architecture


## How to run locally

### Nifi
Accessible at [localhost:8443](https://localhost:8443/nifi).

### Nifi Registry
Accessible at [localhost:18080](http://localhost:18080/nifi-registry).

## References
- [Stephane Maarek](https://www.youtube.com/watch?v=-T9xuBMfI50&ab_channel=StephaneMaarek)
- [Introduction nifi best practices](https://capgemini.github.io/development/introduction-nifi-best-practices/)
- [Docker Hub](https://hub.docker.com/r/apache/nifi)
