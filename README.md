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
https://etcd.io/docs/v3.5/dev-guide/interacting_v3/
https://etcd.io/docs/v3.5/tutorials/how-to-check-cluster-status/
