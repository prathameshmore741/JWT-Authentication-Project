Title: Secure REST API with JWT Authentication & Role-Based Authorization (Admin & User Roles)

Description:
Developed a fully secure Spring Boot REST API implementing JWT-based authentication and role-based access control (RBAC). 
The application allows users to register, log in, and access protected resources based on assigned roles: ADMIN and USER. 
Security is enforced end-to-end using Spring Security 6, custom JWT filters, and stateless session management. 
The project uses MySQL as the primary database for storing user credentials, roles, and application data, ensuring reliable persistence 
and efficient query performance.

Key Features:
JWT Authentication
Role-Based Access Control
Secure REST API Endpoints
Password Encryption
Stateless Architecture

Technology Stack:
Spring Boot
Spring Security 6
JWT (JSON Web Tokens)
Spring Data JPA
MySQL
Maven

Highlights:
Implemented custom authentication & authorization logic using JWT.
Designed reusable security components: authentication entry point, token utilities, and custom filters.
Ensured secure access to APIs with strict separation of ADMIN and USER privileges.
Followed best practices for password hashing, exception handling, and token expiration.
