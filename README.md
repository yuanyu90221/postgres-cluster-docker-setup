# postgres-cluster-docker-setup

https://hub.docker.com/r/bitnami/pgpool/

## usage

use [repmgr](https://repmgr.org) to make two postgresql as cluster

use pg-pool as proxy

## structure

pg-pool as postgresql proxy host on 5436(exported port)

pg-0 as master postgresql database on 5434(exported port)

pg-1 as master postgresql database on 5435(exported port)

## repmgr for postgresql cluster

https://repmgr.org

## setup reference

https://www.itread01.com/content/1544524924.html