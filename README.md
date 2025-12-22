# Infrastructure

This folder contains the Docker Compose configuration for the Israel Weather Hub project.

## Services

*   **maps-api**: The NestJS API service for serving maps.
*   **minio**: S3-compatible object storage for storing map images.
    *   Console: [http://localhost:9001](http://localhost:9001)
    *   User: `minioadmin`
    *   Password: `minioadmin`
*   **redis**: In-memory data store for caching.

## Running the Stack

To start all services:

```bash
docker-compose up --build
```

To stop:

```bash
docker-compose down
```
