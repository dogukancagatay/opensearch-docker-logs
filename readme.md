# Opensearch Log Collector for Docker Containers

Opensearch based container log collector sample with fluentd and fluentbit.

## Running

`docker-compose.yml` starts the [Spring PetClinic Sample Application](https://github.com/spring-projects/spring-petclinic) container and collect logs via [*fluentbit*](https://fluentbit.io/) and [*opensearch*](https://opensearch.org/).

```sh
docker-compose up -d
```

### Fluentd

`docker-compose.fluentd.yml` includes [*fluentd*](https://www.fluentd.org/) instead of *fluentbit*.

```sh
docker-compose -f docker-compose.fluentd.yml up -d
```
