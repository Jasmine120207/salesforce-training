# 🚀 Day 3 – Salesforce Data Modeling & Business Logic

## 1. Difference Between App, Object, Record, Field

- **App**: A collection of related objects, tabs, and features used for a business purpose.  
  Example: Sales App (Accounts, Leads, Opportunities)

- **Object**: A table in Salesforce used to store data.  
  Example: Student, Course, Faculty

- **Record**: A single entry in an object.  
  Example: One student record like “Rahul Kumar”

- **Field**: A column in an object that stores specific information.  
  Example: Name, Age, Email
  

## 2. Standard vs Custom Objects

- **Standard Objects**: Predefined by Salesforce.  
  Example: Account, Contact, Opportunity

- **Custom Objects**: Created by users based on business needs.  
  Example: Student, Course, Faculty

Standard objects are ready-made, while custom objects are created for specific requirements.


## 3. College Data Model (My System Design)

### Objects:
- Student
- Faculty
- Course
- Department

### Relationships:
- Department → Faculty (Lookup, One-to-Many)
- Department → Course (Lookup, One-to-Many)
- Faculty → Course (Lookup, One-to-Many)
- Student → Course (Lookup / Enrollment)

### Diagram:
Department → Faculty → Course → Student


## 4. Formula Fields (Examples)

### 1. Full Name
FirstName + LastName  
Reason: Automatically combines name for consistency.

### 2. Age Calculation
TODAY() - Birthdate  
Reason: Automatically updates age every year.

### 3. Remaining Seats
Total Seats - Enrolled Students  
Reason: Shows real-time availability.


## 5. Validation Rules (Examples)

### 1. Email cannot be empty
Prevents saving records without email.

### 2. Student age cannot be negative
Ensures valid real-world data.

### 3. Course seats cannot exceed limit
Prevents overbooking of courses.


## 6. Reflection – Why Structured Data Matters

Companies cannot use Excel because:
- Data becomes messy and duplicated
- No relationships between data
- No automation or validation
- Not scalable for large businesses
- No security control

Structured systems like Salesforce solve this by:
- Connecting data using relationships
- Automating business processes
- Ensuring clean and valid data
- Supporting large-scale enterprise systems
- Providing security and access control


## ✅ Final Summary

Today I learned:
- How Salesforce structures business data
- Difference between objects, fields, and records
- Importance of relationships in enterprise systems
- Formula fields vs validation rules
- How Salesforce enables no-code business logic
