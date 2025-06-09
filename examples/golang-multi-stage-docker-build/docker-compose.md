# Multi Stage Docker Build - Golang

This example demonstrates how to use multi-stage builds in Docker with a simple Go calculator program.

## Build and Run with Docker CLI

To build and run the app manually using the Docker CLI:

```bash
docker build -t golang-multistage .
docker run --rm golang-multistage
```

You should see:

```
The result of addition is: 30
```

---

## Run with Docker Compose

If you prefer using Docker Compose, follow these steps:

1. Make sure you have Docker Compose installed.
2. From this directory, run:

```bash
docker-compose up --build
```

3. You should see the same output:

```
The result of addition is: 30
```

4. To stop and remove the container:

```bash
docker-compose down
```

---

## What You'll Learn

- How to use multi-stage builds in Docker to create efficient Go containers.
- How to simplify container management with Docker Compose.

---

