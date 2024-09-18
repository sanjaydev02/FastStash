# redis-go
This project is a basic implementation of a simple in-memory database with Append-Only File (AOF) persistence, similar to Redis. It includes a Redis Serialization Protocol (RESP) parser and supports writing and reading commands to ensure data durability. The database syncs data to disk every second, allowing for safe and persistent data storage.
