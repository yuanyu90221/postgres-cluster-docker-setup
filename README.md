# postgres-cluster-docker-setup

https://hub.docker.com/r/bitnami/pgpool/

## usage

use pg-pool to make two postgresql as cluster

## structure

pg-pool as postgresql proxy host on 5436(exported port)
pg-0 as master postgresql database on 5434(exported port)
pg-1 as master postgresql database on 5435(exported port)