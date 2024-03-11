
# Employee Management System
This project is a simple Employee Management System built with Java Spring Boot, this version does not use Spring Data JPA nor Spring Data REST. It provides a RESTful API where clients can perform CRUD operations on the `Employee` entity.
This was mainly made for practise with making a DAO and service layer, before taking advantage of Spring Data JPA & Spring Data Rest which I will use in the next 2 projects by refactoring this one.

## Features
- Retrieve all employees (`GET /api/employees`)
- Retrieve an employee by ID (`GET /api/employees/{employeeId}`)
- Add a new employee (`POST /api/employees`)
- Update an existing employee (`PUT /api/employees`)
- Delete an employee (`DELETE /api/employees/{employeeId}`)

## REST API
The REST API is exposed on `localhost:8080` and provides the following endpoints:

- `GET /api/employees`: Returns a list of all employees.
- `GET /api/employees/{employeeId}`: Returns the employee with the specified employeeId.
- `POST /api/employees`: Create a new employee.
- `PUT /api/employees`: Update an existing employee.
- `DELETE /api/employees/{employeeId}`: Delete the employee with the specified employeeId.

Note: For add and update operations, the employee data should be sent as a JSON in the request body.
