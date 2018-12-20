# neo4j_docker
Docker compose for UHL ne04j

## Development Installation

1. Download the code from github

```bash
git clone https://github.com/LCBRU/influxdb_docker.git
```

2. Enviroment

Copy the file `example.env` to `.env`.  The values in the
example.env should be fine, but you can change them if you want.

3. Further Configuration

See the [Neo4j Docker documentation](https://neo4j.com/docs/operations-manual/current/docker/)
for more configuration options.

## Building

To build the development instance, use the command:

```bash
docker-compose build
```

## Running

To run the development instance, use the command:

```bash
docker-compose up
```