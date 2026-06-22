# Day 31 - Role-Based Authorization, User APIs & Cart Functionality
**Date: 22/06/2026**

## What I Learned Today

* Implemented Role-Based Access Control (RBAC) by introducing an Admin role in the application.
* Configured the system to restrict admin registration from public access and manage admin credentials securely from the backend.
* Developed functionality for administrators to view all registered users.
* Implemented Category Creation and Product Creation features accessible only to authorized admin users.
* Practiced JWT-based Authorization to secure admin-specific operations and restrict unauthorized access.
* Developed User APIs to support application functionality and data access.
* Created a Get All Products API to allow users to view available products.
* Implemented a Get User Details API for the Profile section, ensuring users can access only their own information.
* Applied Authentication and Authorization mechanisms to secure user-specific endpoints.
* Implemented Add to Cart functionality for users.
* Created a dedicated Cart Model and established relationships between User, Product, and Cart entities.
* Practiced relational mapping and API integration for efficient cart management.
* Designed and studied the complete Add to Cart workflow and data flow between application modules.
* Improved understanding of backend architecture, access control, authentication, authorization, and entity relationships.

## Skills Practiced

* Node.js
* JWT Authorization
* Role-Based Access Control (RBAC)
* Authentication
* Authorization
* Admin Module Development
* User Management APIs
* Product APIs
* Profile APIs
* Cart Functionality
* Relational Mapping
* One-to-Many Relationships
* Database Modeling
* API Development
* API Security
* Backend Development
* Access Control
* Data Modeling

## Flow Charts / Workflows Understood

### Role-Based Authorization Flow

User Login
      ↓
JWT Token Generation
      ↓
Role Verification
      ↓
Admin / User Access Check
      ↓
Authorized Resource Access

### Add To Cart Flow

User
  ↓
Select Product
  ↓
Add To Cart API
  ↓
Cart Validation
  ↓
Cart Database Update
  ↓
Success Response

### Entity Relationship Flow

User
 ↓
Cart
 ↓
Product

One User → Multiple Cart Items
One Product → Multiple Cart Entries