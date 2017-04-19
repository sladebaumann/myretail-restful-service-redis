# myretail-restful-service-redis
Redis DB container for interaction with [myretail-restful-service](https://github.com/sladebaumann/myRetail-RESTful-service)

Redis DB.

## Using Docker to run this application

### Build
  - `docker build --tag myretail-restful-service-redis .`

### Run
  - `docker run \
    --name myretail-restful-service-redis \
    -p 6379:6379 \
    myretail-restful-service-redis`

### Interact
  - Use redis-py to interact in python
  - Use redis-cli locally with localhost:6379