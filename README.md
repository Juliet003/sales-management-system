Sales Management System

This project is a Sales Management System implemented using the Spring Boot framework. It provides a RESTful API for managing products, clients, sales operations, and reporting. It includes features for user authentication, logging, and auditing to track important system activities.

Features

Products Management: Manage product details including name, description, category, quantity, and price.

Clients Management: Manage client details including name, last name, mobile, email, and address.

Sales Operations Management: Manage sales transactions including creation, update, and viewing of sales.

Reporting: Generate various reports related to sales, clients, and products.

User Authentication: Secure the API with authentication and authorization.

Logging and Auditing: Track and log important system activities and changes.

Technologies

Spring Boot

Spring Data JPA

Spring Security

Hibernate

MySQL/PostgreSQL (or any other relational database)

Lombok

API Endpoints

Products Management

GET /products: Fetch all products.

GET /products/{id}: Fetch a product by ID.

POST /products: Create a new product.

PUT /products/{id}: Update an existing product.

DELETE /products/{id}: Delete a product.

Clients Management

GET /clients: Fetch all clients.

GET /clients/{id}: Fetch a client by ID.

POST /clients: Create a new client.

PUT /clients/{id}: Update an existing client.

DELETE /clients/{id}: Delete a client.

Sales Operations

GET /sales: Fetch all sales operations.

GET /sales/{id}: Fetch a sale by ID.

POST /sales: Create a new sale with multiple transactions.

PUT /sales/{id}: Edit quantities and prices of a sale.

Reporting

GET /reports/sales: Generate a sales report for a specific date range.

GET /reports/clients: Generate a client report.

GET /reports/products: Generate a product report.


