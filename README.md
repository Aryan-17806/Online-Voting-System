# 🗳️ Online Voting System

A secure, scalable, and robust **Online Voting System** built using **Java** and **JDBC**. The system leverages **Object-Oriented Programming (OOP)** principles and follows the **Model-View-Controller (MVC) architecture** to deliver a modular, clean, and maintainable codebase. Equipped with role-based access control, it ensures a seamless experience for both voters and administrators.

---

## 🚀 Key Features

### 👤 User & Role Management
* **Secure Registration & Authentication:** Secure onboarding for voters and administrators.
* **Role-Based Access Control (RBAC):** Distinct interfaces and privileges for Admins (managing elections) and Voters (casting votes).

### 📋 Candidate & Election Management
* **Admin Dashboard:** Full CRUD operations to add, update, and view running candidates.
* **Real-Time Tracking:** Instantaneous update of candidate profiles and active election statuses.

### 🔒 Secure Voting Engine
* **One-Vote Restriction:** Strict input validation and database constraints to guarantee each voter can only cast a single vote.
* **Real-Time Vote Counting:** Transparent, instantaneous background calculations as votes are cast.
* **Result Generation:** Automatic aggregation of metrics to display clear, finalized election results.

### 🛠️ Architecture & Reliability
* **MVC Pattern:** Decoupled business logic, database operations, and console/UI views.
* **Data Integrity:** Integrated with MySQL using JDBC, backed by robust exception handling to prevent transaction data loss.

---

## 🛠️ Tech Stack

* **Backend:** Java (JDK 8+)
* **Database:** MySQL
* **Connectivity:** JDBC (Java Database Connectivity)
* **Architecture:** Model-View-Controller (MVC)

---

## 🏗️ Database Schema Overview

The system utilizes a relational schema to manage persistent data across three primary modules:
* `users` — Stores account details, credentials, and access roles (`VOTER` / `ADMIN`).
* `candidates` — Holds candidate profiles, party affiliations, and active vote tallies.
* `votes` — Tracks voting logs to ensure auditability while strictly enforcing the one-vote-per-user constraint.

---

## ⚙️ Installation & Setup

### Prerequisites
* **Java Development Kit (JDK)** installed (version 8 or higher).
* **MySQL Server** up and running.
* MySQL JDBC Driver (`mysql-connector-j`).

### Step 1: Clone the Repository
```bash
git clone [https://github.com/Aryan-17806/Online-Voting-System.git](https://github.com/Aryan-17806/Online-Voting-System.git)
cd Online-Voting-System
