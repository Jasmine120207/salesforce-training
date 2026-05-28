# Day 10 - Mini Project

## System Overview

This mini project is a Salesforce CRM application developed using Lightning Web Components (LWC), Apex, Flows, and Validation Rules. The system is designed to manage customer information efficiently and provide a user-friendly interface for handling CRM operations.

### Main Features

* Customer record management
* Dynamic user interface
* Data validation
* Automated workflows
* Secure backend processing

---

## CRM Concepts

CRM (Customer Relationship Management) helps businesses manage customer interactions and data.

### CRM Concepts Used

* Leads Management
* Contacts Management
* Account Handling
* Opportunity Tracking
* Customer Data Management

The project demonstrates how Salesforce CRM improves business productivity and customer relationship handling.

---

## Data Model

### Objects Used

| Object Name   | Purpose                             |
| ------------- | ----------------------------------- |
| Account       | Stores company details              |
| Contact       | Stores customer details             |
| Opportunity   | Tracks sales opportunities          |
| Custom Object | Stores project-specific information |

### Relationships

* One Account can have many Contacts
* One Account can have multiple Opportunities

---

## Validation Rules

Validation rules were created to maintain accurate data entry.

### Examples

* Email field must contain valid email format
* Phone number should contain only numbers
* Required fields cannot be empty
* Opportunity amount must be greater than zero

These rules help improve data quality and consistency.

---

## Flows

Salesforce Flows were used to automate business processes.

### Flow Features

* Automatic record updates
* Email notifications
* Task creation
* Approval process automation

Flows reduce manual work and improve efficiency.

---

## Apex Logic

Apex classes and triggers were used for backend processing.

### Apex Functionalities

* Database operations
* Business logic execution
* Record validation
* Dynamic data retrieval

Apex helps implement custom business requirements in Salesforce.

---

## Complete Data Flow

1. User enters data through the UI.
2. Validation rules check data accuracy.
3. LWC components process frontend interactions.
4. Apex backend handles business logic.
5. Salesforce database stores records.
6. Flows automate updates and notifications.
7. Updated data is displayed back to the user.

---

## Reflection

In this mini project, I learned how different Salesforce technologies work together to build a complete CRM application. I gained practical experience with Lightning Web Components, Apex, Validation Rules, and Flows. This project improved my understanding of frontend and backend integration in Salesforce development.
