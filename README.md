# Docker Keycloak
## Description

This project is a Dockerized Keycloak server with a PostgreSQL database. It provides a secure and scalable authentication solution for your applications.

## Prerequisites

- Docker
- Docker Compose

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/PetitGourou1999/Docker-Keycloak.git
   ```

2. Copy the `.env.template` file to `.env.dev`:
   ```
   cp .env.template .env.dev
   ```

3. Update the `.env.dev` file with your desired configuration.

4. Start the Docker containers:
   ```
   docker-compose -f docker-compose.yml -p oidc_test --env-file .env.dev up -d
   ```

## Usage

To access the Keycloak admin console, open your browser and navigate to:
```
http://localhost:8090/auth/admin/
```
