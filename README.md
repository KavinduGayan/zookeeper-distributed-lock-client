# Zookeeper Distributed Lock Client

A small Java/Maven project scaffold intended for experimenting with a ZooKeeper-backed distributed lock client.

## Requirements

- Java 8+
- Maven 3.6+
- Apache ZooKeeper 3.7.0 (server running for integration)

## Build

```bash
mvn -q clean package
```

## Notes

- This repository currently contains the Maven build configuration and IDE module files only.
- Add your lock client implementation under `src/main/java` and tests under `src/test/java`.
