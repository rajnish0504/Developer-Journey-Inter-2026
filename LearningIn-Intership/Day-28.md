# Day 28 - Node.js Relational Mapping, Authentication & Product API Development
**Date: 17/06/2026**

## What I Learned Today

* Studied a complete order processing workflow to understand how data flows between different modules in a backend application.
* Analyzed relationships between multiple entities and explored how associated data is managed across the system.
* Improved understanding of Relational Mapping concepts in Node.js, including model dependencies and associations.
* Worked on a practical Order Module implementation to understand backend workflow and business logic.
* Explored One-to-Many Relationship Mapping between User and Address entities.
* Learned how a single user can be associated with multiple addresses using model associations.
* Studied how relational mappings are implemented and how related data is retrieved and managed efficiently.
* Created User Registration and Login APIs with proper validations and database integration.
* Implemented authentication-related functionality and tested registration and login workflows.
* Developed a Product Creation API with input validations and database operations.
* Improved understanding of API development, data modeling, authentication flow, and backend architecture.

## Skills Practiced

* Node.js
* Relational Mapping
* Sequelize Associations
* One-to-Many Relationships
* User Registration API
* Login API
* Product Creation API
* Authentication
* Input Validation
* Database Integration
* Backend Development
* Data Modeling
* Request Handling
* Response Handling
* CRUD Operations
* API Testing
* Business Logic Implementation

## Flow Charts / Workflows Understood

### User and Address Relationship

User
 ↓
Addresses

One User → Multiple Addresses

### User Registration Flow

User Input
     ↓
Validation
     ↓
Database Save
     ↓
Success Response

### Login Flow

User Credentials
       ↓
Validation
       ↓
Authentication
       ↓
Success / Failure Response

### Product Creation API Flow

Request
   ↓
Validation
   ↓
Controller
   ↓
Database Insert
   ↓
Response