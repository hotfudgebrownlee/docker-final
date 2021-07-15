# Docker Compose Test

- To test the stedi pod: 
- `cd to the folder with the yaml file`
- `open a new terminal`
- `type "docker-compose up`
- `a miracle occurs`
- `check the docker container and run stedi externally`
- To run redis:
- `Log into stedi`
- `Create a customer`
- `From the terminal type: docker exec -it docker-final_redis_1 redis-cli`
- `From the terminal type: keys **`
- `You will see the list of all the Redis tables`
- `Type: zrange Customer 0 -1`