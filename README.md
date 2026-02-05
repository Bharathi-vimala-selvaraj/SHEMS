# SHEMS
🏢 Smart Hostel Energy Management System (SHEMS)
📌 Project Overview

The Smart Hostel Energy Management System (SHEMS) is a web-based application designed to monitor, control, and analyze electrical energy usage in hostel environments.
The system helps reduce energy wastage by providing real-time device control, secure access, and data-driven analytics for hostel administrators and students.

🎯 Problem Statement

In hostels, electrical devices such as lights, fans, and ACs are often left ON in empty rooms, leading to:

High electricity bills

Energy wastage

Lack of centralized monitoring

Manual and inefficient control

✅ Proposed Solution

SHEMS digitizes hostel energy management by:

Providing centralized control for wardens

Allowing limited device control for students

Tracking real-time energy consumption

Generating analytical insights and cost estimates

🛠️ Technology Stack

Backend: Spring Boot (Java)

Security: Spring Security, JWT Authentication

Database: MySQL

ORM: JPA (Hibernate)

Frontend: Web Dashboard

Architecture: Controller–Service–Repository (Layered Architecture)

🧩 System Architecture

The system follows a layered architecture:

Controller Layer: Handles user requests

Service Layer: Contains business logic

Repository Layer: Manages database operations

Database Layer: Stores users, devices, and energy data

🔐 Module 1: Authentication & Role Management

Features:

User signup and login

JWT-based authentication

Role-Based Access Control (RBAC)

Admin (Warden) and User (Student) roles

Key Learning: Secure access control using Spring Security.

🔌 Module 2: Smart Device Management

Features:

Add and manage smart devices

Remote ON/OFF control

Role-restricted device access

Global control for administrators

Key Learning: Transaction-safe device state management.

⚡ Module 3: Real-Time Energy Tracking

Features:

Automatic energy logging on device state change

Timestamp-based energy usage storage

Accurate energy calculation

Persistent usage history

Key Learning: Handling real-time and time-series data using transactions.

📊 Module 4: Analytics Dashboard

Features:

Total, daily, and monthly energy analysis

6-month consumption trends

High-consumption room/device identification

Electricity cost estimation

Visual charts and graphs

Key Learning: Read-only transactional analytics and data aggregation.

🔄 Workflow Summary

User logs in securely

Devices are controlled remotely

Energy usage is tracked in real time

Usage data is stored in the database

Analytics dashboard generates insights

Admin takes action to reduce wastage

🚀 Key Benefits

Reduces electricity costs

Prevents energy wastage

Improves hostel management efficiency

Enables data-driven decision-making

Promotes sustainable energy usage

⚠️ Challenges Addressed

Concurrent user access

Data consistency

Secure analytics access

Large data storage and processing

📚 Learning Outcomes

Spring Boot application development

Secure authentication and authorization

Transaction management in Java

Real-time data handling

Analytics and visualization concepts

🧑‍💻 Team & Domain

Domain: Smart Hostel & IoT Automation
Project Type: Academic / Capstone Project

📌 Conclusion

The Smart Hostel Energy Management System (SHEMS) provides a secure, scalable, and efficient solution for managing energy consumption in hostels. By integrating real-time monitoring with analytics, the system promotes responsible energy usage and cost optimization.
