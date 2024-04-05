#### Change default php version

```console
sudo update-alternatives --config php
```
#### Apache Bench Example for REST API

```console
ab -n 100 -c 5 -H 'accept: application/json' -H 'Authorization: Bearer {JWT}' http://localhost:8080/
```
