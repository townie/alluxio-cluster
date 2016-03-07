

Build and run
```
docker-compose build && docker-compose up -d && docker exec -ti alluxiocluster_alluxio-master_1 bash
```


Stop, build & run
```
docker-compose stop && docker-compose rm -f && docker-compose build && docker-compose up -d
```

Scale up
```
docker-compose scale alluxio-slave=3
```


Admin UI
```
http://192.168.99.100:19999/home
```

Master shell
```
docker exec -ti alluxiocluster_alluxio-master_1 bash
```