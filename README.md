# hacktiv8-assigment2

It is a just simple REST API built with Go using gin and gorm (An ORM for Go).


## Running API Server
Before running API server, you should set the database config with yours, the configuration file can be found on `/configs/config.json`
```json
{
    "host": "localhost",
    "port": "5432",
    "user": "postgres",
    "password": "kworks",
    "database": "orders_by"
}
```

```
# Running server
go run main.go

# API Endpoint : http://127.0.0.1:8080
```

## API Documentation
The API Documentation can be accessed on `http://127.0.0.1:8080/swagger/index.html` after you running the API server
