# Bookinfo Detail Service

Detail service has been developed on Ruby

# How to run details service

## Prerequisite

* Ruby 2.7

## How to run with Docker

```bash
# Build Docker Image for rating service
docker build -t details .

# Run ratings service on port 8081
docker run -d --name details -p 8081:8081 details
```

* Test with path `/details/1` and `/health`

## How to run with Docker Compose

```bash
docker-compose up
```

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
