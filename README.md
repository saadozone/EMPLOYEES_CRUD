# Go Backend Clean Architecture

This is Rest Api App with authentication and unit tests .
A Go (Golang) Backend Clean Architecture project with Gin, MongoDB, JWT Authentication Middleware, Test, and Docker.

![image](https://github.com/saadozone/EMPLOYEES_CRUD/assets/125872373/c7be6a7a-9821-41c3-a7c5-783985c98ba0)

Architecture Layers of the project :
1) Router
2) Handler
3) Service
4) Repository
5) Domain
![image](https://github.com/saadozone/EMPLOYEES_CRUD/assets/125872373/3bad2ded-a868-43d5-af95-9f6586c37dc0)

Public API Request Flow without JWT Authentication Middleware

![image](https://github.com/saadozone/EMPLOYEES_CRUD/assets/125872373/a2674c2e-3cd9-4b8c-a03a-35aac70a0872)

Private API Request Flow with JWT Authentication Middleware

![image](https://github.com/saadozone/EMPLOYEES_CRUD/assets/125872373/a5cc4085-3037-4f82-883a-e422c9d3680f)

How to run this project?

# Move to your workspace
```cd your-workspace```

# Clone this project into your workspace
```git clone https://github.com/saadozone/EMPLOYEES_CRUD.git```

# Run docker 
```docker-compose up```
# Run the backend and access it on localhost:8080 
``` go run main.go```

How to run the test?
# Run all tests
```go test ./...```


