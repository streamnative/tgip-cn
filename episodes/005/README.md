# Episode 005: Cluster deployment

- Hosted by @sijie
- Recorded on 03/08/2020

![](/image/005.png)

## Table of Content

- 00:00:00 - Welcome to TGIP-CN!
- 00:02:00 - Week in Review

## Week in Review

- TGIP-CN: https://github.com/streamnative/tgip-cn


## Show Notes

- Learn
  - Component Dependencies
    - ZooKeeper
    - BookKeeper
       - Bookie
       - AutoRecovery
    - Broker
    - Proxy
- Network Connectivities
  - ZooKeeper <-> ZooKeeper
  - Bookie <-> ZooKeeper
  - AutoRecovery <-> ZooKeeper
  - AutoRecovery <-> Bookie
  - Broker <-> ZooKeeper
  - Broker <-> Bookie
  - Broker <-> Broker
- Startup Sequences
  - ZooKeeper
  - Cluster metadata setup
  - Bookies
  - Brokers
  - Proxies
- Monitoring Stack
  - Prometheus
  - Grafana
  - Pulsar Manager
- Hands-on: https://github.com/streamnative/pulsar-tutorials

## Reference 

- Study note: https://hackmd.io/oo1zy_XARMybULcYzCtSjA?view
