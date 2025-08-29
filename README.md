# Requirement Analysis in Software Development

## Introduction

This repository is dedicated to exploring the concept of **requirement analysis** in software development. Its purpose is to provide insights, examples, and structured documentation on how to identify, analyze, and manage requirements effectively. By organizing the processes and techniques of requirement analysis, this repository aims to serve as a helpful resource for students, developers, and project managers who want to understand the foundation of building successful software systems.

## What is Requirement Analysis?

Requirement Analysis is the process of **identifying, gathering, and defining the needs and expectations of stakeholders** for a software project. It is one of the most critical phases of the **Software Development Lifecycle (SDLC)**, as it lays the foundation for designing, building, and delivering a system that meets user needs. It is is the **blueprint stage** of software development, ensuring that the final product is useful, usable, and valuable.

During this phase, developers, analysts, and stakeholders work together to:

- Understand the **functional requirements** (what the system should do).
- Define the **non-functional requirements** (how the system should perform, e.g., speed, security, usability).
- Document clear and testable requirements that guide the entire project.

### Importance in the SDLC

1. **Clarity of Goals** – Ensures all stakeholders have a shared understanding of the project objectives.
2. **Reduced Errors** – Detects and resolves ambiguities or conflicts early, preventing costly mistakes later.
3. **Improved Planning** – Provides a solid base for estimating time, cost, and resources.
4. **Higher Quality Software** – Leads to systems that align closely with user expectations and business needs.
5. **Efficient Development** – Minimizes rework by providing a clear roadmap for developers and testers.

## Why is Requirement Analysis Important?

Requirement Analysis is critical in the Software Development Lifecycle (SDLC) because it ensures the software being developed truly meets the needs of users and stakeholders. Without it, projects risk going over budget, missing deadlines, or failing to deliver value.

### Key Reasons:

1. **Prevents Miscommunication**

   - Clearly documents the needs of stakeholders, reducing misunderstandings between clients, developers, and project managers.

2. **Saves Time and Cost**

   - Identifying and fixing requirement issues early is far less expensive than correcting them during coding or after deployment.

3. **Improves Software Quality**
   - By defining precise functional and non-functional requirements, the final product is more reliable, efficient, and aligned with user expectations.

## Key Activities in Requirement Analysis

The process of requirement analysis involves several structured activities that ensure requirements are accurate, complete, and useful for guiding software development. The five key activities include:

- **Requirement Gathering**

  - Collecting raw information from stakeholders, customers, users, and existing systems.
  - Serves as the initial step to understand what the project is expected to achieve.

- **Requirement Elicitation**

  - Engaging with stakeholders through interviews, surveys, workshops, and observation.
  - Focuses on uncovering both stated and hidden needs that the system must address.

- **Requirement Documentation**

  - Recording requirements in a structured and accessible format, such as Software Requirement Specifications (SRS).
  - Provides a formal reference that guides developers, testers, and managers.

- **Requirement Analysis and Modeling**

  - Examining requirements to ensure they are consistent, complete, and feasible.
  - May involve using models, diagrams, or prototypes to visualize system behavior and structure.

- **Requirement Validation**
  - Confirming that the documented requirements reflect the true needs of stakeholders.
  - Ensures accuracy and helps prevent costly changes during later phases of development.

## Types of Requirements

In software development, requirements are generally categorized into **Functional** and **Non-functional Requirements**. Both are essential for ensuring that the system delivers the intended value to users.

### Functional Requirements

Functional requirements describe **what the system should do** — the specific features, behaviors, and services it must provide.

**Definition:**  
They define the interactions between the system and its users or other systems, focusing on the _functions_ to be performed.

**Examples for the Booking Management Project:**

- The system must allow users to **create, view, and cancel bookings**.
- The system should send **confirmation emails/SMS notifications** after a successful booking.
- Users should be able to **search for available rooms by date and type**.
- The system must provide an **admin panel for staff to manage bookings and customer details**.

### Non-functional Requirements

Non-functional requirements describe **how the system should perform** — the quality attributes, performance standards, or constraints that must be met.

**Definition:**  
They define the operational characteristics of the system rather than specific behaviors.

**Examples for the Booking Management Project:**

- The system must handle **at least 500 concurrent users** without performance degradation.
- Page load times should not exceed **3 seconds** under normal usage.
- The system must be available **24/7 with 99.9% uptime**.
- All user data must be encrypted to ensure **security and privacy compliance**.

## Use Case Diagrams

**What are Use Case Diagrams?**  
Use Case Diagrams are a visual representation of the interactions between **actors** (users or external systems) and the **system**. They show the functionality of a system from the user’s perspective and help communicate what the system is supposed to do without going into technical details.

### Benefits of Use Case Diagrams

- Provide a **clear overview** of system functionality.
- Help stakeholders and developers **communicate effectively**.
- Identify **primary actors** (e.g., users, admins) and their interactions with the system.
- Serve as a **foundation for requirement analysis and testing**.

### Use Case Diagram for the Booking Management System

**Actors:**

- Customer
- Admin/Staff

**Use Cases:**

- Create Booking
- View Booking
- Cancel Booking
- Search Availability
- Receive Confirmation
- Manage Bookings (Admin)
- Manage Customer Details (Admin)

![Booking System Use Case Diagram](images/Untitled%20Diagram.drawio.png)

## Acceptance Criteria

Acceptance Criteria are the conditions that a software feature must satisfy to be considered complete and accepted by stakeholders. They play a critical role in **Requirement Analysis** by:

### Importance of Acceptance Criteria

- Defining clear expectations between developers, testers, and stakeholders.
- Ensuring that requirements are **testable and measurable**.
- Reducing ambiguity by providing a shared understanding of what “done” means.
- Guiding the testing process to verify if the system behaves as intended.

### Example: Checkout Feature in the Booking Management System

**Acceptance Criteria:**

- The system must allow users to proceed to checkout only if a booking has been selected.
- The checkout page must display booking details (room type, dates, and price) before payment.
- Users must be able to select a payment method (e.g., credit card, PayPal, mobile money).
- Payment must be processed securely, and the system should confirm a successful transaction.
- A confirmation email/SMS must be sent automatically after successful checkout.
- If payment fails, the system must display an error message and allow retry without losing booking details.
