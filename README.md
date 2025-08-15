# OpenWebUI Playground

This project provides a playground environment for OpenWebUI, including a presentation powered by [reveal-md](https://github.com/webpro/reveal-md) and a Docker Compose setup.

## Prerequisites

- [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/) installed
- [Node.js](https://nodejs.org/) and npm (for running reveal-md locally)

## Running with Docker Compose

To start all services defined in `docker-compose.yml`, run:

```bash
docker compose up -d
```

To stop the services:

```bash
docker compose down
```

## Accessing OpenWebUI

Once the Docker Compose services are running, open your web browser and navigate to:

```
http://localhost:4444
```

## Running the Presentation

Run `npx presentomatic`