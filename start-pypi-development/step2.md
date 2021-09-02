After Warehouse containers are built, start them.

```
make serve
```{{execute}}

This pulls and starts all necessary containers, but the main
app will fail, because example database is not completely
synchronized at this point. Run this command to sync db.

```
make initdb
```{{execute}}

After `make initdb` is complete, the webapp should start
responding on this URL.

https://[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com/
