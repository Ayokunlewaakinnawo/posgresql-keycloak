#Postgresql-Service

### Prerequisites:

Ensure Docker is installed and running.

### VARIABLES
The file `.env-example` contains all the dynamic variables.
Create yours as `cp .env-example .env` and alter your variables to taste.

### Docker Initialization Guide:

Execute the Docker Compose command to build the .yml file.

```docker
docker-compose up -d
```

### Useful Docker cmd:

Once the container is started and running, you can view the newly created database either from the Docker Desktop console or by using the `Docker exec` command to access the database.

```docker
# psql -U keycloak
```
