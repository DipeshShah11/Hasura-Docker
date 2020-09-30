# Installing Hasura on Docker

## Introduction

You find set of steps which helps to install Hasura GraphQL Engine on existing Postgres database in the local environment using Docker.
Most of the steps are the same which instructed on official website [Deploying Hasura using Docker](https://hasura.io/docs/1.0/graphql/core/deployment/deployment-guides/docker.html#deployment-docker).
Here we will install Postgres, pgAdmin and Hasura
 
### hasura-docker

```
Prerequisites
```
[Docker](https://docs.docker.com/get-docker/)

### List of steps for Installing Hasura
(1) Install Docker in your system.
(2) Download repository in your system.
(3) Navigate into the local folder in which the repository kept.
(4) Run "hasura-using-docker.yaml" on command prompt using following command.
	```hasura-using-docker up```
(5) You will see lot of log output.

### Time to open Hasura Console

Navigate to [Hasura Console](http://localhost:8080/console) for Hasura console.