### docker run
```shell
    docker-compose up -d
```

### connect with mongodb
-- doc for string connection with mongo
--- "https://www.mongodb.com/docs/mongodb-shell/connect/#connect-to-a-deployment-on-a-remote-host"
-- for development cases
```shell
    docker exec -it mongo-lab mongosh --host localhost --port 27017 --username root --password root
```

### cmd mongo
-- show dbs