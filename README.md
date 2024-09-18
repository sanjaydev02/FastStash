# redis-go
This project is a basic implementation of a simple in-memory database with Append-Only File (AOF) persistence, similar to Redis. It includes a Redis Serialization Protocol (RESP) parser and supports writing and reading commands to ensure data durability. The database syncs data to disk every second, allowing for safe and persistent data storage.

# Simple In-Memory Database with AOF Persistence

This project is a basic implementation of a simple in-memory database with Append-Only File (AOF) persistence, similar to Redis. It includes a Redis Serialization Protocol (RESP) parser and supports writing and reading commands to ensure data durability. The database syncs data to disk every second, allowing for safe and persistent data storage.

## Features

- **In-Memory Storage**: Stores data in memory for fast access.
- **AOF Persistence**: Appends commands to a file and syncs it to disk every second to ensure data durability.
- **RESP Protocol**: Implements a parser and writer for Redis Serialization Protocol (RESP), supporting various RESP data types.

## Installation

Clone the repository:

```bash


