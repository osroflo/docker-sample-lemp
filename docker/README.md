# Docker LEMP Sample
This sample is useful to integrate docker into any existing project quickly.

It contains a virtualhost in nginx.

## Setup
- Update the nginx/host.conf to set your app hostname.
- Add the app hostname url entry into your /etc/hosts
- Set the name of your db under mysql service (docker-compose.yml)

## Install
```
docker-compose up --build
```

## Import DB
- Using mysqlworkbench or CLI use the localhost port 3307

## Test
- Go to your browser http://<your app hostname>:8081