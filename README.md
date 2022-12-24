# ToyDB

*This project is in early development stage*

ToyDB is a Key Value NoSQL database that supports popular Redis protocol. It is written in Go.

## Features

- Supports basic Redis operation: PING, GET & SET
- Uses locking to update data OR uses update data asynchronous in a single thread 
- Pluggable database engine, might use RocksDB & in-memory

## Non-goals

- Transactions
- SQL parser
- MVCC
- ACID compliance

## References

- Olric
- LevelDB
- BoltDB
- LevelDB
- Codis
- Miniredis

There is nothing novel about this database. This is just me learning about database internals.
