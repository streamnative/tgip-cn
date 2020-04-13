# Episode 009:  Pulsar performance tuning

- Hosted by Penghui Li
- Recorded on 04/12/2020

![](/image/009.png)

## Table of Content

- 00:00:00 - Introduction


## Show Notes

* Overview
    * 2.5.1 RC
    * PIP - 61 Advertised multiple addresses
    * PIP - 62 Move connectors, adapters and Pulsar Presto to separate repositories

* Basic concepts
* Message writing
    * Producer
        * Batch message
        * Compression
        * Pending queue
    * Broker
        * Persistence(E, Qw, Qa)
        * Bookie client ioNumThreads
        * Managed ledger worker threads
        * Broker ioNumThreads
    * Bookie
        * Journal and Ledger directories
        * Journal Sync Data
        * Journal group commit
        * Add worker threads and max pending add requests
        * DBStorage write cache
        * journalPageCacheFlushIntervalMSec(*)
* Message reading
    * Consumer
        * Receive queue size
    * Broker
        * Managed ledger cache
        * Dispatch batch
    * Bookie
        * numReadWorkerThreads
        * maxPendingReadRequestsPerThread
        * dbStorage_rocksDB_blockCacheSize
        * dbStorage_readAheadCacheMaxSizeMb
        * dbStorage_readAheadCacheBatchSize

## Reference 

- Recorded video: https://b23.tv/BV1T741147B6/p7
- Tech blog: 
