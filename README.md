# Kafka-Elasticsearch-Kibana-PostgreSQL Log Analysis Stack

Repository for setting up a comprehensive log analysis stack. This configuration will help you orchestrate a multi-container Docker application that includes Kafka, Elasticsearch, Kibana, and PostgreSQL.

## Overview

Our stack consists of the following components:

- **Apache Kafka**: A distributed streaming platform that handles our log ingestion.
- **Elasticsearch**: A distributed, RESTful search and analytics engine capable of addressing a growing number of use cases.
- **Kibana**: A visualization dashboard for Elasticsearch that allows for the exploration and visualization of Elasticsearch data.
- **PostgreSQL**: A powerful, open-source object-relational database system with over 30 years of active development.

## Getting Started

To get this stack up and running, you will need Docker and Docker Compose installed on your machine. Clone this repository, configure the environment variables for PostgreSQL, and run:

```bash
docker-compose up
 
