## Initialization Setup
```
git submodule update --init --recursive
```

## Start Services
```
docker-compose -f docker-compose.yml -f docker-compose.override.yml -f docker-compose.ports.yml up
```
