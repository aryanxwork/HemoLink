# 🩸 HemoLink – Blood Bank Management System

**HemoLink** is a database-driven **Blood Bank Management System** designed to manage blood donation, storage, requests, and distribution in a healthcare environment.

The project focuses on **database design and backend implementation using SQL and PL/SQL**, while also providing a **modern administrative dashboard UI** for interacting with the database.

The system demonstrates how a well-designed relational database can power a real-world healthcare application while ensuring **data integrity, automation, and efficient query processing**.

---

# 🎯 Project Objective

The main objective of **HemoLink** is to build a robust **DBMS-based system** capable of managing blood bank operations efficiently.

The system handles:

- Donor registration and management
- Blood inventory tracking
- Hospital blood requests
- Blood unit issuing
- Administrative monitoring and audit logging

The project emphasizes core **Database Management System concepts** such as:

- ER Data Modeling
- Relational Schema Design
- Normalization
- Transaction Management
- SQL Query Processing
- PL/SQL Automation

---

# 🗄️ Database Architecture

The system is built around a **normalized relational database** implemented using SQL.

### Core Entities

| Entity | Description |
|------|-------------|
| **BLOOD_BANK** | Stores blood bank center details |
| **DONOR** | Contains donor information and donation data |
| **USER_ADMIN** | Administrative users managing the system |
| **HOSPITAL** | Hospitals requesting blood units |
| **BLOOD_UNIT** | Individual blood packets stored in banks |
| **DONATION_RECORD** | Links donors to blood units |
| **BLOOD_REQUEST** | Requests raised by hospitals |
| **ISSUE_RECORD** | Tracks blood units issued to hospitals |
| **AUDIT_LOG** | Logs administrative activities |

The schema is normalized up to **Third Normal Form (3NF) / BCNF** to ensure:

- Minimal data redundancy
- Strong data integrity
- Efficient query performance

---

# ⚙️ Backend Implementation (SQL / PL-SQL)

The backend system is implemented using **SQL and PL/SQL**.

### SQL Components

- Table creation (DDL)
- Data insertion and updates (DML)
- Joins and subqueries
- Aggregation queries
- Views for simplified data access

### PL/SQL Components

The project implements multiple automation features using PL/SQL:

- Stored Procedures
- Functions
- Triggers
- Cursors
- Exception Handling

### Key Procedures

| Procedure | Description |
|----------|-------------|
| `register_donor` | Registers new donors with validation |
| `issue_blood` | Issues blood units to hospitals |
| `approve_request` | Approves hospital blood requests |
| `show_available_blood` | Displays available blood stock |

### Functions

| Function | Purpose |
|--------|--------|
| `check_stock()` | Returns available units for a blood group |

### Triggers

| Trigger | Purpose |
|--------|--------|
| `trg_log_issue` | Logs blood issuing actions |
| `trg_check_expiry` | Automatically marks expired blood units |

---

# 🖥️ User Interface (Dashboard)

Although the project focuses mainly on the **database layer**, a modern administrative dashboard interface has been created to interact with the database.

The UI follows a **minimal and professional design philosophy** inspired by modern dashboard systems.

Features include:

- Blood inventory monitoring
- Donor management
- Blood issuing workflows
- Request processing
- Activity tracking

---

# 📊 Dashboard Features

### Dashboard Overview

Displays key system metrics:

- Total donors
- Available blood units
- Issued units
- Pending requests

---

### Blood Inventory

Displays detailed information about blood units:

- Unit ID
- Blood group
- Status (Available / Issued / Expired)
- Collection date
- Expiry date
- Blood bank location

---

### Donor Management

Allows administrators to:

- Add donors
- View donor records
- Search and filter donor information

---

### Issue Blood

Handles the blood issuing workflow by connecting available blood units with hospitals.

---

### Request Management

Manages hospital blood requests with:

- Pending requests
- Approval and rejection workflows
- Status tracking

---

### Reports & Analytics

Provides summarized insights into blood bank operations.

---

### Audit Logs

Tracks administrative activities such as:

- Blood issuing
- Request approvals
- System actions

---

# 🔒 Data Integrity & Transactions

The system ensures reliable healthcare data management through:

- Primary and Foreign Key constraints
- Unique and Check constraints
- Transaction control (`COMMIT`, `ROLLBACK`)
- Automated triggers
- Structured relational schema

These mechanisms maintain **ACID properties** for database transactions.

---

# 🛠️ Technologies Used

### Database

- Oracle SQL
- PL/SQL

### Development Tools

- Oracle SQL Developer
- GitHub (version control)

### Interface

- Modern Dashboard UI
- Responsive web interface

---

# 📚 Academic Context

This project was developed as part of a **Database Management Systems (DBMS) course**.

Key learning areas demonstrated:

- ER Modeling
- Relational Schema Design
- Database Normalization
- SQL Query Optimization
- PL/SQL Programming
- Transaction Management

---

# 🚀 Future Improvements

Possible enhancements include:

- Full API integration with the database
- Real-time blood shortage alerts
- Mobile application interface
- Predictive analytics for blood demand forecasting
- Multi-branch blood bank integration

---


---

# 👨‍💻 Author

**Aryan Sharma**

B.Tech – Computer Science  
Database Management Systems Project

---

