# Day 9 - LWC Communication

## Component Communication

Component communication in Lightning Web Components allows components to share data with each other.

### Types of Communication

#### Parent to Child

Data is passed using public properties with `@api`.

#### Child to Parent

Events are used to send data from child to parent components.

#### Unrelated Components

Lightning Message Service (LMS) is used for communication between unrelated components.

---

## Dashboard Design

The dashboard was designed using reusable Lightning Web Components.

### Features

* Responsive layout
* Dynamic data display
* Component-based structure
* User-friendly interface

### Components Used

* Header Component
* Sidebar Component
* Data Card Component
* Footer Component

---

## Data Flow Explanation

The application follows a structured data flow process.

1. User interacts with the UI.
2. Parent component sends data to child components.
3. Child components trigger events back to parent.
4. Salesforce backend processes data if required.
5. Updated data is displayed on the dashboard.

---

## Aura vs LWC

| Aura Components           | Lightning Web Components |
| ------------------------- | ------------------------ |
| Older framework           | Modern framework         |
| Less performance          | Faster performance       |
| Uses Aura syntax          | Uses standard JavaScript |
| More complex              | Simpler and reusable     |
| Event-driven architecture | Web standards based      |

---

## Reflection

In this project, I learned how Lightning Web Components communicate with each other using properties and events. I also understood the differences between Aura and LWC frameworks. Building a dashboard improved my understanding of reusable components and data flow in Salesforce applications.
