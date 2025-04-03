# Local Infrastructure Services

## Background

This is an experiment of an idea to run common services, which I will conveniently call "infrastructure" for lack of a better word, to run as independent Docker containers instead of being included as a "service" in a containerized app's `compose.yaml`. These services may include, but are not limited to, (1) Postgres server, (2) Redis/ValKey server, (3) MQTT server, etc.

This idea came about because I wanted to try out [Keycloak](https://www.keycloak.org/) -- an Open Source Identity and Access Management tool -- as the IAM solution for signing in to web applications during development in my local development machine. Since Keycloak uses the Postgres database, I wanted to try if I can run one Keycloak container, one Postgres container, and multiple web applications to connect to both services. Thus the idea for `local-infra-services`.

## Understanding

TBD

## Implementation

TBD

## Lesson(s) Learned

TBD

## Deliverables

TBD
