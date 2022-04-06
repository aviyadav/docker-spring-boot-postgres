
# docker-spring-boot-postgres

**Commands to build:**

    mvn clean package -DskipTests
    cp target/docker-spring-boot-postgres-0.0.1-SNAPSHOT.jar src/main/docker
    
	cd src/main/docker
    docker-compose up

## End & cleanup

    docker-compose down


## Rebuild

    cd src/main/docker
    docker-compose down
    docker rmi docker-spring-boot-postgres:latest
    docker-compose up
