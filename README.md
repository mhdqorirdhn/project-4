# Data Processing and Modeling Project

This project involves data production, consumption, and modeling using various services like Kafka, MongoDB, and PostgreSQL. It also includes Jupyter Notebooks for interactive development and testing.

## Getting Started

### Prerequisites

- Docker
- Docker Compose
- Python 3.x
- Jupyter Notebook

### Setting Up Services

To set up Kafka, MongoDB, and PostgreSQL services, use the following commands:

## Virtual Environment

```sh
docker-compose -f kafka-dc.yml up -d
docker-compose -f mongo-dc.yml up -d
docker-compose -f postgresql-dc.yml up -d

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

```

## Install Jupyter Notebook

```sh
pip install notebook
```

## Running Jupyter Notebook

```sh
jupyter notebook
```
