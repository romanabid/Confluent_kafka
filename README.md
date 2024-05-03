# Confluent Platform Docker Compose Configuration

This repository contains a Docker Compose configuration for setting up the Confluent Platform, including Zookeeper, Kafka broker, Schema Registry, Kafka Connect, Control Center, and Kafka REST Proxy.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository:

   ```sh
   git clone https://github.com/your-username/confluent-docker-compose.git
2. Navigate to the cloned directory:
   sh
   cd confluent-docker-compose

3. Run Docker Compose:
   sh
   docker compose up -d

# Components
Zookeeper: Apache ZooKeeper is an open-source server that reliably coordinates distributed processes.
Kafka Broker: Kafka is a distributed streaming platform capable of handling trillions of events a day.
Schema Registry: Schema Registry provides a serving layer for your metadata.
Kafka Connect: Kafka Connect is a framework for scalably and reliably streaming data between Apache Kafka and other data systems.
Control Center: Control Center enables you to easily manage and monitor your Kafka clusters.
Kafka REST Proxy: Kafka REST Proxy allows you to interact with Kafka using HTTP RESTful method

# Configuration
The docker-compose.yml file contains the configuration for all the components. You can customize the configuration by modifying this file.

# Accessing Services
Zookeeper: localhost:2182
Kafka Broker: localhost:9098
Schema Registry: localhost:8081
Kafka Connect: localhost:8085
Control Center: localhost:9021
Kafka REST Proxy: localhost:8084

# Monitoring
Monitoring for Kafka Connect, Kafka Broker, Schema Registry, and Control Center is enabled by default. You can access monitoring metrics using the respective service URLs.
