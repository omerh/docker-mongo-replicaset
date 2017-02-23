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

