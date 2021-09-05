# ms-user-openapi

User Miroservices api details
-----------------------------
Health: http://localhost:8080/openapi/actuator/health - GET

Find All User: http://localhost:8080/openapi/v1/users?pageSize=2&pageNo=0&sortBy=id - GET

Find User: http://localhost:8080/openapi/v1/users/1 - GET

Create User: http://localhost:8080/openapi/v1/users - POST

{
    "userId": "1000",
    "name": "Test",
    "email": "test@gmail.com",
    "photo": "/users/1000.jpg"
}

Update User - http://localhost:8080/openapi/v1/users - PUT

{
    "id":"1",
    "userId": "1000",
    "name": "Test Name",
    "email": "test.java@gmail.com",
    "photo": "/users/1000_small.jpg"
}

Delete Uer - http://localhost:8080/openapi/v1/users/1 - DELETE
