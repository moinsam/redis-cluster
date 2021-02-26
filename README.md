# redis-cluster

redis-cli --cluster create redis01-master:6379 redis02-master:6380 redis03-master:6381 redis01-slave:6382 redis02-slave:6383 redis03-slave:6384 --cluster-replicas 1

172.31.13.112
redis-cli --cluster create 172.31.13.112:6379 172.31.13.112:6380 172.31.13.112:6381 172.31.13.112:6382 172.31.13.112:6383 172.31.13.112:6384 --cluster-replicas 1


54.250.209.43
redis-cli --cluster create 54.250.209.43:6379 54.250.209.43:6380 54.250.209.43:6381 54.250.209.43:6382 54.250.209.43:6383 54.250.209.43:6384 --cluster-replicas 1

redis-cli --cluster create 127.0.0.1:6379 127.0.0.1:6380 127.0.0.1:6381 127.0.0.1:6382 127.0.0.1:6383 127.0.0.1:6384 --cluster-replicas 1

redis-cli --cluster create redis01-master:6379 redis01-slave:6382 --cluster-replicas 1