# Pre-Setup
Create directory to store etcd data and change the permission to 775.
```
mkdir -p etcd-data
chmod -R 775 etcd-data
```

# Pre-Setup For Multi-Cluster ETCD
Create directory to store etcd data and change the permission to 775.
```
mkdir -p cluster1-etcd1-data cluster1-etcd2-data cluster1-etcd3-data
chmod -R 775 cluster1-etcd1-data cluster1-etcd2-data cluster1-etcd3-data

mkdir -p cluster2-etcd1-data cluster2-etcd2-data cluster2-etcd3-data
chmod -R 775 cluster2-etcd1-data cluster2-etcd2-data cluster2-etcd3-data

mkdir -p cluster3-etcd1-data cluster3-etcd2-data cluster3-etcd3-data
chmod -R 775 cluster3-etcd1-data cluster3-etcd2-data cluster3-etcd3-data
```

cluster1-etcd1-data

# Some Useful ETCD Commands
```
etcdctl version
```
```
etcdctl --write-out=table member list
```
```
etcdctl --write-out=table endpoint status
```
```
etcdctl --write-out=table --endpoints= endpoint status
```
```
etcdctl get /apisix --prefix
```

# Reference
- https://etcd.io/docs/v3.5/dev-guide/interacting_v3/
- https://etcd.io/docs/v3.5/tutorials/how-to-check-cluster-status/
