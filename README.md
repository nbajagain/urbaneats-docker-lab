# Docker Multi-Service Application

This project demonstrates a multi-container Docker application including:
- Web service (Node.js)
- API service
- Worker service
- Redis (cache)
- PostgreSQL (database)
- RabbitMQ (message queue)

## Requirements
- Docker
- Docker Compose

## How to Run

1. Clone the repository:
git clone (https://github.com/nbajagain/urbaneats-docker-lab/blob/main/README.md)

2. Navigate to project folder:
cd docker-project

3. Run the application:
docker compose up --build

4. Access services:
- Web: http://localhost
- API Health: http://localhost/api/health
- RabbitMQ: http://localhost:15672

## Stop the Application
docker compose down
