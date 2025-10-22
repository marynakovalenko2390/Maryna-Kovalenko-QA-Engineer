
### Postman Collection

This repository contains a Postman collection organized into 5 folders, each representing a group of related API requests.

Collection-level Scripts
### Pre-request Scripts

Executed before requests at the collection level. These scripts can be reused by requests as needed.

Examples:
<ls>

* User registration

* Creating an article

* Following a user

* Creating a second user

* Creating comments

### Post-response Scripts

Executed after requests at the collection level to validate responses. These scripts can also be called at the request level.

Examples:
<ls>

* Checking response status code

* Validating response time

* Verifying response properties


Collection-level scripts can be called at the request level whenever needed, allowing for reusable logic across multiple requests without duplicating code.

### Benefits
<ls>

* Centralized script management (pre-request and post-response scripts)

* Reusable scripts for common tasks

* Easy to maintain and extend

