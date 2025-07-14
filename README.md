# Threading in Java

This repository contains examples of client-server communication using Java Sockets:

## Folder Structure
```
Threading-in-Java/
├── SingleThreaded/
│ ├── Client.java
│ └── Server.java
├── MultiThreaded/
│ ├── Client.java
│ └── Server.java
```

## Features

- **Single-threaded server**: handles one client at a time.
- **Multi-threaded server**: handles multiple clients concurrently using threads.

## How to Run

1. **Compile** the server and client:
```
javac Server.java
javac Client.java
```
3. **Start the server** (from one terminal):
```
java Server
```
5. **Start the client** (from another terminal or multiple clients):
```
java Client
```
## Requirements

- Java 8 or above
- Any IDE or command line
