# Salesforce Summer Program – Day 4: Flow Builder

## 1. What is Flow Builder?

Flow Builder is a no-code automation tool in Salesforce that allows users to automate business processes visually. It helps create workflows that can collect data, update records, send emails, post to Chatter, and perform complex business logic without writing code.

Flow Builder uses a drag-and-drop interface where we can define triggers, conditions, decisions, and actions.


## 2. Types of Flows

### 1. Screen Flow
Screen Flows are interactive flows where users manually input data through screens.  
They are used when user interaction is required.

Example:
- Creating a student registration form
- Collecting feedback from users


### 2. Record-Triggered Flow
Record-Triggered Flows run automatically when a record is created, updated, or deleted.

They do not require user interaction.

Example:
- Sending email when a new lead is created
- Updating account status when opportunity is closed


## 3. Automation Ideas (College Management System)

1. Auto email confirmation after student registration  
2. Automatically generate Student ID  
3. Notify faculty when a course is full  
4. Send fee payment reminder before due date  
5. Auto-update attendance status when class is completed  

### Why automation helps:
- Reduces manual work
- Avoids human errors
- Saves time
- Improves communication speed
- Ensures consistency in data


## 4. Flow Diagram (Example Automation)

### Automation: Student Registration Confirmation

**Trigger:**
- When a new student record is created

**Steps:**
1. System detects new registration
2. Validate required fields (name, course, email)
3. Generate Student ID automatically
4. Send confirmation email to student

**Decision Points:**
- If email is missing → stop process and notify admin
- If course is full → redirect to waitlist

**Final Action:**
- Student record is saved
- Email confirmation sent
- Student ID assigned


## 5. Manual vs Automated Process

### Manual Process:
- Admin manually checks new student registrations
- Sends confirmation email manually
- Assigns Student ID manually
- Updates records in Excel or system

### Problems in Manual Process:
- Time-consuming
- High chance of human error
- Delays in communication
- Difficult to scale

### Automated Process (Salesforce Flow):
- System automatically triggers workflow
- Email sent instantly
- Student ID generated automatically
- Data updated in real time

### Improvement:
Automation makes the process faster, accurate, and scalable with minimal human effort.


## 6. Reflection – Why Automation Matters

Companies automate repetitive business processes because it improves efficiency, reduces operational costs, and increases accuracy. Automation ensures that tasks are completed consistently without delays or mistakes.

In enterprise systems like Salesforce, automation helps teams focus on important decision-making instead of repetitive manual work. It also improves customer experience by ensuring quick responses and real-time updates.
