# Pre-Setup
Create directory to store etcd data and change the permission to 775.
```
mkdir -p etcd-data
chmod -R 775 etcd-data
```

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
