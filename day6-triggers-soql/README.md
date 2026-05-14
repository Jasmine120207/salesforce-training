# Day 6 – Salesforce Triggers & SOQL

## 1. What is SOQL?

SOQL (Salesforce Object Query Language) is used to retrieve data from Salesforce database objects like Students, Courses, Accounts, etc.

It is similar to SQL but designed only for Salesforce.

Example use:
- Get student records
- Filter courses
- Retrieve related data between objects

SOQL helps in reading data from Salesforce efficiently.


## 2. What is an Apex Trigger?

An Apex Trigger is a piece of code that automatically runs when a data change happens in Salesforce.

Triggers respond to events like:
- Record creation
- Record update
- Record deletion

Example:
- When a student is registered → trigger sends a welcome email
- When attendance drops → trigger sends warning message

Triggers help automate business logic.


## 3. Difference: Flow vs Trigger

### Flow
- No-code / low-code tool
- Easy to maintain
- Best for simple automation
- Used by admins

### Trigger
- Written in Apex code
- Used for complex logic
- More powerful and flexible
- Used by developers


## Before vs After Trigger

### Before Trigger
- Runs BEFORE data is saved
- Used to modify records

Example:
- Auto-correct student name before saving

### After Trigger
- Runs AFTER data is saved
- Used to update related records or send notifications

Example:
- After student registration → send email
  

## 4. Trigger Use Cases (College Management System)

1. After student registration → send welcome email  
2. After course is full → notify faculty  
3. After attendance drops below 75% → send warning to student  
4. After fee payment → update student payment status  
5. After exam results published → notify students


## 5. Query Examples (English SOQL Thinking)

- Find all students in Course A  
- Find all courses handled by Faculty X  
- Find students with attendance below 75%  
- Find students who have not paid fees  
- Find courses with more than 50 students enrolled  


## 6. Reflection

### Why do enterprise systems need event-driven behavior?

Enterprise systems need event-driven behavior because they must respond automatically to changes in data without manual effort.

For example:
- When a student registers, the system should immediately send confirmation
- When fees are paid, records should update instantly

This improves speed, accuracy, and efficiency.
- Flows are declarative, Triggers are programmatic
- Before triggers modify data, After triggers act on saved data
- Event-driven systems improve automation and scalability
