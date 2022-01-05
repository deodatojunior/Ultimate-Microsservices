# Microsservices

## To Run
Enter in /src for terminal and write this code:
```
docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d
```

## Endpoints:
### Catalog Api Documentation:
localhost:8000/swagger

### Basket Api Doucumentation
localhost:8001/swagger

### Discount Api Documentation
localhost:8002/swagger

### Discount.Grpc Api Documentation
localhost:8003/swagger

### Pg Admin
localhost:5050

user: admin@aspnetrun.com
password: admin1234

if the server is not listed, click servers with the right button, add a server, type the desired name and in the connection tab, add the host: discountdb, and in the username and password, add: admin and password: admin1234

### Portainer for monitoring containers
localhost:9000

create user and done
