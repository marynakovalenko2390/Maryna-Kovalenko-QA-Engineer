
### Postman Collection

This repository contains a Postman collection organized into 5 folders, each representing a group of related API requests.

Collection-level Scripts
### Pre-request Scripts

Executed before requests at the collection level. These scripts can be reused by requests as needed.

Examples:
<ls>

* User registration ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_uCQr4xN71v.png)

* Creating an article ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_Anx0kH41P0.png)

* Following a user ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_b4r4Tq2zw7.png)

* Creating a second user ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_x027WomRCn.png)

* Creating comments ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_jpXJq2a1X5.png)

### Post-response Scripts

Executed after requests at the collection level to validate responses. These scripts can also be called at the request level.

Examples:
<ls>

* Checking response status code ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_kxja3MYSRL.png)

* Validating response time ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_OVfjPK9Cr7.png)

* Verifying response properties ![screenshot of sample](https://raw.githubusercontent.com/marynakovalenko2390/Maryna-Kovalenko-QA-Engineer/main/Postman/img/Postman_nBJZbaOJJC.png)


Collection-level scripts can be called at the request level whenever needed, allowing for reusable logic across multiple requests without duplicating code.

### Benefits
<ls>

* Centralized script management (pre-request and post-response scripts)

* Reusable scripts for common tasks

* Easy to maintain and extend

