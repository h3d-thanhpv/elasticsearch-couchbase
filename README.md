ElasticSearch +  Couchbase Integration
------------------

### Config `max_map_count` on host machine

```
sysctl -w vm.max_map_count=262144
```

### Deploy compose file

```
docker-compose up --build
```

### Setup couchbase

Setup couchbase server with account admin: `Administrator/abc@123`

Setup XDCR for replicate couchbase to elastic search
