### Complete Guide to CRUD Using MyBatis and Spring Boot

Create `users` Table:
```sql
CREATE DATABASE mydatabase;

USE mydatabase;

CREATE TABLE users (
    id BIGINT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL
);
```

Article Link: https://medium.com/@cibofdevs/complete-guide-to-crud-using-mybatis-and-spring-boot-d6c165167cdd