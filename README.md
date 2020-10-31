# Adminer - PostgreSQL - Compose
Basic configuration with docker-compose

## Prerequisite
1. Install docker-compose

### Setup environment
1. Create the postgres network
    ```docker
    docker network create postgres
    ```
2. Create the `.env` file with your data

### Run the container
```
docker-compose up -d
```
### Connection Database
Add your information. In the server section add `db` (the name of service) and voilà !