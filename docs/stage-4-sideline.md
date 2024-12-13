# stage-4-sideline | [readme](../readme.md)

### [Stage 4/7:Sideline](https://hyperskill.org/projects/374/stages/2234/implement)

### results
* 80/115 topics
* 54/59 project topics

![](./images/step-4-of-7-completed.png)


### Sideline

### Description
To ensure the proper functioning of the `fastapi-task-manager` service, incorporate additional tasks and commands into the docker-compose file. You need to map a port, create a network and define a dependency. Please follow the instructions below.

### Objectives
* Add more attributes to the `hyper-service` service;
    * Map the host port `8000` to the container port `8000`;
    * Add the `hyper-task-manager-network` network;
    * Define the dependency on the `mongodb` service.

### HINT by Hubert Michalec
```
just add depends_on
```

### [my docker-compose.yaml for this problem](./docker-compose-files/stage-4-docker-compose/docker-compose.yaml)

### [Dockerfile for this problem](./docker-compose-files/stage-4-docker-compose/Dockerfile)