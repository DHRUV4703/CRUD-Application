# CRUD-Application
This simple CRUD (Create, Read, Update, Delete) application is built using Spring Boot and demonstrates how to manage records in a database. It offers basic functionality to create, retrieve, update, and delete data, serving as an educational tool for understanding RESTful API development with Spring Boot.

The application runs on http://localhost:8080 and exposes several API endpoints: POST /api/records to create a new record, GET /api/records to retrieve all records, GET /api/records/{id} to retrieve a specific record by ID, PUT /api/records/{id} to update an existing record, and DELETE /api/records/{id} to delete a record by ID.

Testing of these endpoints can be performed using Postman. This project utilizes an in-memory H2 database for simplicity and testing purposes.
