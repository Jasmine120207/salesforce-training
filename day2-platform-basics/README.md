# Day 2 - Salesforce Platform Basics

## 1. What is Salesforce Platform?

Salesforce Platform is a cloud-based CRM platform that helps businesses manage customer relationships, store data, automate workflows, and build applications. It allows organizations to manage their business processes without maintaining servers or infrastructure manually.
Salesforce provides tools for:
* Data management
* Workflow automation
* Reporting and dashboards
* Application development
* API integrations
* Security and user management
Salesforce uses a multi-tenant architecture where multiple companies share the same infrastructure securely while keeping their data separate.


# 2. App, Object, and Tab in Salesforce

## What is an App?
An App in Salesforce is a collection of related tabs, objects, and tools grouped together for a specific business purpose.
Example:
A Sales App may contain:
* Accounts
* Contacts
* Opportunities
* Reports
Apps help users access all related functionality in one place.

## What is an Object?
An Object in Salesforce is like a database table used to store information.
Objects contain:
* Records (rows)
* Fields (columns)
Examples of Objects:
* Account
* Contact
* Opportunity
* Lead
Salesforce provides:
* Standard Objects
* Custom Objects
Custom objects are created based on business requirements.

## What is a Tab?
A Tab is used to access objects, reports, dashboards, or applications inside Salesforce.
Examples:
* Accounts Tab
* Contacts Tab
* Opportunities Tab
Tabs help users navigate easily through Salesforce.


# 3. Difference Between Configuration and Coding

Salesforce customization can be done in two ways:

## Configuration (No Code)
Configuration means customizing Salesforce using clicks instead of programming.
Used when:
* Standard features are enough
* Faster implementation is required
* Simple automation is neede
Examples:
1. Creating custom objects
2. Validation rules
Advantages:
* Easy to maintain
* No coding knowledge required
* Faster development

## Coding (Apex Development)
Coding means writing custom logic using Apex and Lightning Components.
Used when:
* Complex business logic is required
* Advanced integrations are needed
* Standard tools are not sufficient
Examples:
1. Payment gateway integration
2. Complex automation using Apex Triggers
Advantages:
* Advanced customization
* Greater flexibility
* Supports complex business requirements
  

# 4. System Design - College Management System

## App Name
College Management App

## Objects Inside the App

| Object Name | Purpose                    |
| ----------- | -------------------------- |
| Student     | Stores student details     |
| Faculty     | Stores faculty information |
| Course      | Stores course details      |
| Admission   | Stores admission records   |
| Attendance  | Stores attendance details  |

## User Interaction

### Admin
* Manages admissions
* Maintains student records
* Generates reports
### Faculty
* Updates attendance
* Uploads marks
* Manages course details
### Students
* View attendance
* Check marks
* Access course information
Users interact with the system using Tabs inside the College Management App.


# 5. Screenshots from Trailhead

## Agentforce 360 Platform Basics
![Screenshot 1](screenshot1.png)

## Agentforce 360 Platform Development Basics
![Screenshot 2](screenshot2.png)


# Conclusion

From this activity, I learned how Salesforce Platform is structured using Apps, Objects, and Tabs. I also understood the difference between configuration and coding, and how Salesforce developers extend platform functionality using Apex, APIs, and Lightning Components.

I also learned how CRM concepts fit into Salesforce and how real-world systems can be designed using Salesforce applications and objects.
