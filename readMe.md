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
- To run zookeeper and kafka
- `Do a STEDI test`
- `On the timer page, toggle the simulated data toggle to ON`
- `Look for the RapidStepTest in Kafka (you should see JSON with test data)`
- `From the terminal type: docker exec -it [kafkacontainername] kafka-console-consumer --bootstrap-server localhost:19092 --topic stedi-events --from-beginning`