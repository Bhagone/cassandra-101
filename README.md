# cassandra-101
    - https://cassandra.apache.org/

## Run cassendra using docker

First of all install docker and then follow the following steps:

1) Create a network for cassendra `docker network create some-network`

2) Pull and start cassendra server instance 
`docker run --name some-cassandra --network some-network -d cassandra:latest`

3) Connect to cassendra from cqlsh
`docker run -it --network some-network --rm cassandra cqlsh some-cassandra`

Thats it, enjoy 🚀
