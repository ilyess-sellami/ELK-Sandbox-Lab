# ELK Sandbox Lab

## 1. Project Overview

**ELK Sandbox Lab** is a hands-on, educational project designed to help security analysts and system administrators learn how to deploy and manage the ELK stack (Elasticsearch, Logstash, Kibana) using Docker.

This project demonstrates:

How to dockerize the ELK stack for local or server environments.

How to install Filebeat on Linux servers.

How to forward system and application logs to ELK via Logstash.

Basic log visualization and exploration in Kibana.

It is perfect for analysts who want a **safe, sandbox environment** to experiment with SIEM concepts and log processing pipelines.

## 2. Architecture

![ELK Architecture](screenshots/elk_architecture.png)

## 3. Project Requirements

### System Requirements

- Docker >= 20.x
- Docker Compose >= 1.29.x
- Ubuntu 20.04+ (or any Linux server for Filebeat)
- Minimum 4 GB RAM for Docker ELK stack

### Software Requirements

- ELK Stack Docker images ( Elasticsearch & Logstash & Kibana v7.10.2)
- Filebeat (installed on Linux server)

### Network Requirements

- Docker bridge network for ELK containers.
- Port access (Elasticsearch: `9200`, Logstash: `5044`, Kibana: `5601`)

