# elastic-kibana-docker-compose

Run:
```bash
docker-compose up -d
```

### Potential issues

If elasticsearch container doesn't start up use:
```bash
docker logs elastic-workshop_elasticsearch
```

If there is a problem with not enough memory, assign it with below command:
```bash
sysctl -w vm.max_map_count=262144
```
