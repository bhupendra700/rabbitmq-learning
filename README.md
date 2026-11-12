# RabbitMQ Learning

A hands-on learning repository for RabbitMQ, with practical examples in both Node.js (Express) and Python (FastAPI).

## Tech Stack

- RabbitMQ (via Docker)
- Node.js, Express, amqplib
- Python, FastAPI, pika / aio-pika

## Roadmap

- [X] Stage 1: Fundamentals (queues, exchanges, producers, consumers)
- [X] Stage 2: Setup (Docker and Management UI)
- [ ] Stage 3: Hello World (Node.js and Python)
- [ ] Stage 4: Core patterns (work queues, acknowledgements, exchange types, pub/sub)
- [ ] Stage 5: Framework integration (Express and FastAPI)
- [ ] Stage 6: Production concerns (retries, dead letter queues, reconnection)

## Getting Started

### Prerequisites

- Docker
- Node.js (v18 or later)
- Python (3.10 or later)

### Run RabbitMQ

```bash
docker compose up -d
```

Management UI: http://localhost:15672 (username: `guest`, password: `guest`)

## Project Structure

```
rabbitmq-learning/
├── nodejs/     # Node.js examples
└── python/     # Python examples
```