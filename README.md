#  Income Tax Management System

### Web-Based Income Tax Management Platform

An **Income Tax Management System** designed to organize and manage interactions between taxpayers, tax professionals, and tax authorities through a centralized web-based platform.

The system provides functionality for managing taxpayer information, professional details, revenue records, comments, document uploads, and tax-related data using a structured relational database.

---

## 🎯 Project Overview

Managing income tax information can involve multiple stakeholders and large amounts of financial and taxpayer data.

This project was developed to provide a structured platform where:

* **Taxpayers** can manage their information and interact with the system.
* **Tax Professionals** can manage client-related information and assist with tax-related activities.
* **Tax Authorities** can access and manage relevant tax information.
* The system maintains structured records using a **relational database**.

The project combines a **PHP-based web application** with a relational database to demonstrate practical concepts in web development and database management.

---

## 🚀 Key Features

### 👤 User Management

* User registration and login
* Password management
* Role-based access for different types of users
* Separate workflows for taxpayers, tax professionals, and tax authorities

### 💼 Taxpayer Management

* Manage taxpayer information
* Maintain revenue-related records
* View relevant tax information
* Upload supporting documents
* Interact with tax professionals through the platform

### 👨‍💼 Tax Professional Management

* Add and manage tax professionals
* Maintain professional information
* View and manage client-related details
* Access relevant taxpayer information

### 🏛️ Tax Authority Management

* Manage tax-related records
* Access taxpayer and professional information
* Support centralized tax information management

### 📄 Document Management

* Upload supporting files
* Store document references within the system
* Manage uploaded taxpayer-related documents

### 💬 Communication

* Add comments
* View comments
* Support communication between relevant users

### 🗄️ Database Management

* Structured relational database
* SQL-based database schema
* Database triggers for automated database operations
* Persistent storage of taxpayer and tax-related information

---

## 🛠️ Technology Stack

| Category           | Technology                |
| ------------------ | ------------------------- |
| Frontend           | HTML, CSS                 |
| Backend            | PHP                       |
| Database           | MySQL                     |
| Database Scripting | SQL                       |
| Testing            | Python                    |
| Styling            | CSS                       |
| Development        | Web-based PHP Application |

---

## 🏗️ System Architecture

```text
                ┌─────────────────────┐
                │       Users         │
                │                     │
                │ Taxpayer            │
                │ Tax Professional    │
                │ Tax Authority       │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │   PHP Web Layer     │
                │                     │
                │ Authentication      │
                │ User Management     │
                │ Tax Management      │
                │ File Management     │
                │ Comments            │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │    MySQL Database   │
                │                     │
                │ Taxpayer Data       │
                │ Revenue Data        │
                │ Professional Data   │
                │ User Data           │
                │ Documents           │
                └─────────────────────┘
```

---

## 👩‍💻 My Role

### Backend & Database Developer

I contributed primarily to the **backend functionality and database integration** of the system.

My responsibilities included:

* Developed and maintained **PHP backend functionality** for different system modules.
* Worked with **MySQL** to store and retrieve taxpayer, professional, and revenue-related information.
* Implemented database operations for **adding, viewing, updating, and deleting records**.
* Worked on backend handling for **tax professional and taxpayer information**.
* Integrated PHP modules with the relational database.
* Worked with **SQL scripts and database triggers** for managing application data.
* Contributed to **file upload and document management functionality**.
* Worked on system modules for **comments and user interactions**.
* Contributed to testing and debugging application functionality.
* Helped organize the application into separate modules based on user roles and system responsibilities.

> **Role:** Backend & Database Developer
> **Primary Areas:** PHP · MySQL · SQL · Database Integration · Backend Logic

---

## 🗃️ Database Design

The project uses a relational database to organize the application's core entities and their relationships.

The repository includes:

* Database schema
* SQL table definitions
* Database triggers
* Sample database structure
* Relationships between system entities

A relational schema document is also included in the repository for reference.

---

## 📂 Major Modules

```text
Authentication
│
├── Login
├── Signup
└── Password Management

Taxpayer
│
├── Taxpayer Information
├── Revenue Management
├── Document Upload
└── Comments

Tax Professional
│
├── Professional Management
├── Client Information
└── Client Details

Tax Authority
│
└── Tax Information Management
```

---

## 🔄 Core Workflow

```text
User
  │
  ▼
Authentication
  │
  ▼
Role Identification
  │
  ├───────────────┬────────────────┐
  ▼               ▼                ▼
Taxpayer     Tax Professional   Tax Authority
  │               │                │
  ▼               ▼                ▼
Tax Data       Client Data      Tax Records
  │               │                │
  └───────────────┴────────────────┘
                  │
                  ▼
             MySQL Database
```

---

## 🧪 Testing

The repository includes an `automated_testing.py` file for testing application functionality.

Testing was used to identify issues and verify important application workflows during development.

---

## ⚙️ Running the Project

### Prerequisites

Install the following before running the application:

* PHP
* MySQL
* Apache Server / XAMPP
* Web Browser
* Python (for automated testing)

### 1. Clone the Repository

```text
git clone https://github.com/kavyamoodi/income_tax_system.git
cd income_tax_system
```

### 2. Set Up the Database

Import the provided SQL database file into MySQL.

The repository contains:

```text
itms.sql
itms_trig.sql
```

### 3. Configure Database Connection

Update the database credentials in the PHP database configuration file according to your local MySQL setup.

### 4. Start the Server

If using XAMPP:

```text
Start Apache
Start MySQL
```

Place the project inside the appropriate XAMPP `htdocs` directory.

### 5. Open the Application

Open the application through your local Apache server using a browser.

---

## 📁 Project Structure

```text
income_tax_system/
│
├── images/
├── uploads/
│
├── add_comment.php
├── add_professional.php
├── add_revenue.php
├── automated_testing.py
├── db.php
├── delete_taxprofessional.php
├── fetch_preofessional_details.php
├── home.php
├── itms.sql
├── itms_trig.sql
├── login.php
├── password.php
├── signup.php
├── style_home.css
├── taxauthority.php
├── taxpayer.php
├── taxprofessional.php
├── upload_file.php
├── view_client.php
└── view_comment.php
```

---

## 📌 Project Highlights

* Built a functional **web-based Income Tax Management System**.
* Implemented backend functionality using **PHP**.
* Integrated the application with **MySQL**.
* Designed functionality around multiple user roles.
* Implemented taxpayer, tax professional, and tax authority modules.
* Worked with relational database design and SQL.
* Implemented database triggers for automated database operations.
* Added document upload functionality.
* Added comment-based interaction.
* Included automated testing support.
* Maintained a structured separation of application modules.

---

## 🎓 Key Learning Outcomes

This project strengthened my practical understanding of:

* PHP backend development
* MySQL database management
* SQL queries and relational database design
* CRUD operations
* Database triggers
* Backend and database integration
* Authentication workflows
* File upload handling
* Role-based application design
* Debugging and testing web applications

---

## 🔮 Future Improvements

Potential improvements include:

* Modernize the frontend using React.js or another modern frontend framework.
* Introduce a REST API layer for better frontend-backend separation.
* Implement stronger authentication and authorization.
* Add comprehensive input validation.
* Improve password security using modern password hashing practices.
* Add detailed tax calculation and reporting modules.
* Introduce dashboards for taxpayers, professionals, and authorities.
* Add automated unit and integration testing.
* Deploy the application to a cloud environment.
* Improve responsive design for mobile and tablet users.

---

## 📂 Repository

[**View Source Code →**](https://github.com/kavyamoodi/income_tax_system)

---

## 👩‍💻 Developer

### Kavya Moodi

Computer Science & Engineering Student | Full-Stack Developer

I build practical software solutions across **full-stack development, backend engineering, AI-powered applications, and cloud technologies**.

My experience includes working with:

**Java · Python · C++ · JavaScript · React.js · Node.js · Express.js · FastAPI · PHP · Spring Boot · MongoDB · MySQL · PostgreSQL · AWS · Docker**

---

⭐ **Explore the repository to see the implementation of the Income Tax Management System.**
