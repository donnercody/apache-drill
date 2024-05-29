# apache-drill
Here is a dockerfile for kubernetes with the latest drill version

## Install Zookeeper before usage

Before you can run the dockerfile, you need to have the following installed on your machine:

```
helm install zookeeper oci://registry-1.docker.io/bitnamicharts/zookeepe
```

# Apache Drill Dockerfile

This repository contains **Dockerfile** of [Apache Drill](https://drill.apache.org/) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/dockerfile/apache-drill/) published to the public [Docker Hub Registry](https://registry.hub.docker.com/).

## Parameters

* `DRILL_VERSION` - version of Apache Drill (default: `1.16.0`)
* `ZOOKEEPER_HOSTNAME` - hostname of Zookeeper (default: `zookeeper`)

## Repo is inspired from:

https://github.com/Agirish/drill-containers