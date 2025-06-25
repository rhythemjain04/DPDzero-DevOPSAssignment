# DevOps Intern Assignment: Nginx Reverse Proxy + Docker

This project sets up a Docker Compose-based system with an Nginx reverse proxy routing requests to two backend services: a Golang application (`service1`) and a Python application (`service2`).

## Project Structure

```
.
├── docker-compose.yml
├── nginx
│   ├── nginx.conf
│   └── Dockerfile
├── service_1
│   └── Dockerfile
├── service_2
│   └── Dockerfile
└── README.md
```
## docker image build
docker-compose up --build

## logs
logs are also there

## to check the endpoints these are the curls

curl http://localhost:8080/service1/ping
curl http://localhost:8080/service1/hello

curl http://localhost:8080/service2/ping
curl http://localhost:8080/service2/hello

