# Day 30 - JWT Authentication, Category & Product APIs
**Date: 19/06/2026**

## What I Learned Today

* Implemented Category Creation and Product Creation APIs with proper request handling and database integration.
* Configured relationships between Category and Product models to establish accurate data mapping.
* Tested APIs using Postman and verified successful data creation, validations, and response handling.
* Strengthened understanding of relational mapping and model associations in backend development.
* Learned the complete JWT Authentication workflow through a flowchart-based approach.
* Understood the requirements for implementing JWT Authentication, including user login, token generation, secret keys, and protected routes.
* Studied the complete authentication lifecycle from login request to authorization.
* Explored token generation, token storage, token verification, and secure route protection mechanisms.
* Implemented a practical JWT-based authentication system including User Registration, Login, and Protected Route Access.
* Tested authentication workflows to verify secure API access and authorization handling.
* Improved understanding of backend security concepts and token-based authentication systems.

## Skills Practiced

* Node.js
* JWT Authentication
* JWT Authorization
* Category API Development
* Product API Development
* Relational Mapping
* Model Associations
* User Registration API
* Login API
* Protected Routes
* Token Generation
* Token Verification
* API Security
* Database Integration
* Postman Testing
* Request Handling
* Response Handling
* Backend Development

## Flow Charts / Workflows Understood

### Category & Product Relationship

Category
    ↓
Products

One Category → Multiple Products

### JWT Authentication Flow

Login Request
      ↓
Credential Validation
      ↓
JWT Token Generation
      ↓
Token Storage
      ↓
Protected API Request
      ↓
Token Verification
      ↓
Authorization Check
      ↓
Access Granted / Denied

### Protected Route Flow

Client Request
      ↓
JWT Token Present?
      ↓
Token Verification
      ↓
Authorized User
      ↓
Protected Resource Access