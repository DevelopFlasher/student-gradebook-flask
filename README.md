# Student Gradebook Flask

A Dockerized gradebook application built with Flask and PostgreSQL. The project contains a small web application, SQL schema scripts, stored procedures, views, and a Docker Compose setup with pgAdmin for database inspection.

## Tech Stack

- Python
- Flask
- PostgreSQL
- pgAdmin
- Docker Compose

## Features

- Web interface for gradebook data
- PostgreSQL schema initialization
- Seed data scripts
- Database views and stored procedures
- Containerized local environment

## Run Locally

```bash
docker compose up --build
```

Open the Flask application:

```text
http://localhost:5000
```

Open pgAdmin:

```text
http://localhost:5050
```

Default demo credentials are defined in `docker-compose.yml`.

## Repository Structure

```text
app/              Flask application
db/               PostgreSQL Docker image and SQL scripts
docker-compose.yml
schema.drawio     Database schema diagram
```

## Portfolio Notes

This project demonstrates a simple database-backed Flask service with containerized PostgreSQL infrastructure and explicit SQL assets.

