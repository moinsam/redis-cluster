# redis-cluster

redis-cli --cluster create redis01-master:6379 redis01-slave:6380 173.17.0.30:6381 173.17.0.40:6384 173.17.0.50:6382 173.17.0.60:6383 --cluster-replicas 1

redis-cli --cluster create redis01-master:6379 redis01-slave:6382 --cluster-replicas 1