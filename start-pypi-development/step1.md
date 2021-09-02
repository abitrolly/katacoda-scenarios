Clone [Warehouse](https://github.com/pypa/warehouse) repo and `cd` into it.

```
git clone https://github.com/pypa/warehouse.git
cd warehouse
```{{execute}}

Install `docker-compose`.

```
curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
docker-compose --version
```{{execute}}

