
Docker imaji: curl, wget, ping, netcat, nslookup,host, dig, psql, mysql

## Kullanim

Kubernetes
```
kubectl run --rm utils -it --generator=run-pod/v1 --image gulnihalugur/testutils bash

# You will be seeing a bash prompt
$ psql -h hostname -U test -d test
...
$ exit
```


Docker Engine 
```
$ docker pull gulnihalugur/testutils
$ docker run --rm -it gulnihalugur/testutils bash

# konteynir icinde
$ ping google.com
$ ifconfig
...
$ exit
```
