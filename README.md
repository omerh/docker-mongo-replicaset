# docker-mongo-replicaset
Launching a mongo replicaset in docker automatically

To run with pulling from Dockerhub the minion image run
```
docker-compose up -d
```

To run with building locally the minion image run
```
docker-compose -f docker-compose-build.yml build
docker-compose -f docker-compose-build.yml up -d
```

To access the replica set from local machine run
```
mongo --port 27020
```

From some IDE's there is a need to add to the host file the follwing so it will work from within the IDE
```
172.0.0.1 mongo1  mongo2  mongo3
```
