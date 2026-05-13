# Day 5 – Apex Introduction

## What is Apex?

Apex is Salesforce’s programming language used to add custom business logic to applications on the Salesforce platform. It is similar to Java and runs on Salesforce servers.

Apex helps developers:
- Automate complex business processes
- Perform advanced validations
- Integrate Salesforce with external systems
- Handle logic that cannot be done using only clicks and flows

Apex is:
- Object-oriented
- Strongly typed
- Database integrated
- Cloud-based


# Difference Between Flow vs Apex

| Flow | Apex |
|------|------|
| No-code / low-code tool | Programming language |
| Built using drag-and-drop | Written using code |
| Easier for admins | Used by developers |
| Best for simple automation | Best for complex logic |
| Limited flexibility | Highly flexible |
| Faster development | More customization possible |


# Difference Between Configuration vs Coding

| Configuration | Coding |
|--------------|---------|
| Uses clicks and setup tools | Uses programming |
| Faster to build | Takes more development time |
| Easy maintenance | Requires coding knowledge |
| Limited for advanced logic | Can handle complex business rules |
| Best for standard processes | Best for custom requirements |


# Real Examples Where Apex Is Needed

## 1. Complex Fee Calculation
A university may calculate fees based on:
- Scholarship percentage
- Attendance
- Course type
- Hostel facility
- Late payment penalties

This logic becomes too complex for normal flows, so Apex is needed.


## 2. External Payment Integration
When students pay fees using external payment gateways like Razorpay or Stripe, Salesforce must:
- Send payment requests
- Receive payment confirmations
- Update records automatically

Such API integrations require Apex code.


## 3. Advanced Eligibility Logic
Suppose student eligibility depends on:
- Attendance percentage
- Internal marks
- Backlogs
- Department-specific rules

Flows become difficult to manage for this level of logic, so Apex provides better control.


# Integrated College Management System Design

## CRM Concept
The College Management System works like a CRM where student information, courses, admissions, and faculty details are managed centrally.

## Objects Used

### Standard/Custom Objects
- Student__c
- Course__c
- Faculty__c
- Admission__c
- Attendance__c

## Relationships

| Object | Relationship |
|--------|--------------|
| Student ↔ Course | Many-to-Many |
| Faculty ↔ Course | One-to-Many |
| Student ↔ Attendance | One-to-Many |

## Validation Rules

Examples:
- Student email cannot be empty
- Attendance cannot exceed 100%
- Fee amount cannot be negative

## Formula Fields

Examples:
- Remaining Seats = Total Seats - Filled Seats
- Attendance Percentage Calculation
- Total Fee After Scholarship

## Flow Automation

Flows can:
- Send admission confirmation emails
- Create welcome tasks automatically
- Notify faculty when attendance is low
- 
## Apex Usage

Apex can:
- Calculate advanced fee structures
- Integrate payment systems
- Apply custom admission eligibility rules
- Handle bulk student data processing
- 

# Pseudocode Examples

## Example 1 – Seat Availability

```text
IF available seats = 0
THEN block student registration
ELSE allow admission
```

## Example 2 – Attendance Warning

```text
IF attendance percentage < 75
THEN send warning notification to student
```

## Example 3 – Scholarship Eligibility

```text
IF marks > 90 AND attendance > 85
THEN apply scholarship
ELSE no scholarship
```

# Reflection

Enterprise systems cannot rely only on clicks and configuration because real businesses often require:
- Complex calculations
- External integrations
- Dynamic business logic
- Large-scale data processing
- Advanced automation

Declarative tools like Flows are powerful, but they have limitations. Apex programming provides flexibility, scalability, and full control over business processes.

Developers should prefer no-code solutions whenever possible because they are easier to maintain and faster to build. However, custom programming becomes necessary when business requirements become highly complex.

Programming increases flexibility by allowing developers to build customized solutions that exactly match business needs.
