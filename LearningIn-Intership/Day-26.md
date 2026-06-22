# Day 26 - Database Relationships in Node.js & WMS Testing
**Date: 15/06/2026**

## What I Learned Today

* Performed testing on order processing workflows and validated successful order creation and synchronization.
* Verified order assignment functionality and ensured orders were correctly allocated and updated throughout the process.
* Executed multiple testing scenarios to validate workflow accuracy and status updates.
* Tested inventory allocation behavior and validated product selection based on inventory management rules.
* Verified expiry-date-based prioritization and ensured proper stock allocation during order processing.
* Conducted scenario-based testing to confirm inventory accuracy and order processing consistency.
* Learned Relational Mapping concepts in Node.js and understood how models are associated within backend applications.
* Studied different relationship types including One-to-One, One-to-Many, and Many-to-Many relationships.
* Explored how model associations are implemented and used in real-world backend development.
* Performed practical implementation of relational mapping by creating associated models and testing relationships.
* Improved understanding of database design, data associations, and relationship management using APIs and database operations.

## Skills Practiced

* Node.js  
* Relational Mapping  
* Database Relationships  
* One-to-One Relationship  
* One-to-Many Relationship  
* Many-to-Many Relationship  
* Model Associations  
* API Development  
* Database Operations  
* Backend Development  
* Sequelize Associations  
* Data Modeling  
* Functional Testing  
* Scenario-Based Testing  
* Inventory Validation  
* Order Processing Validation  

## Flow Charts / Workflows Understood

### One-to-One Relationship

User
  ↓
Profile

One User → One Profile

### One-to-Many Relationship

User
  ↓
Orders

One User → Multiple Orders

### Many-to-Many Relationship

Students
    ↕
Courses

One Student → Multiple Courses
One Course → Multiple Students

### Sequelize Association Flow

Model Creation
      ↓
Association Definition
      ↓
Database Relationship
      ↓
API Implementation
      ↓
Data Retrieval with Include
      ↓
Response Generation