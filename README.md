# Collaborative Real-Time Coding Platform

## Project Overview

The Collaborative Real-Time Coding Platform is a web-based system designed to support real-time collaborative programming sessions. The platform enables multiple users to collaboratively edit code, execute programs securely, communicate through integrated chat, and track coding performance within shared coding rooms.

The project was developed as part of the Software Engineering course and progressively evolved through Requirements Engineering, Scrum-based Project Management, Architectural Design, and Detailed UML System Modeling.

---

# Core Features

- Real-Time Collaborative Code Editing
- Shared IDE Environment
- WebSocket-Based Synchronization
- Secure Code Execution
- Coding Rooms & Sessions
- Integrated Chat Communication
- Performance Tracking
- Admin Monitoring Features
- Auto Save & Recovery
- Syntax Highlighting
- Collaboration Cursor Tracking

---

# Technologies Used

| Layer | Technology |
|---|---|
| Frontend | React.js |
| Backend | Node.js / Express |
| Real-Time Communication | Socket.io |
| Database | PostgreSQL |
| Execution Environment | Docker |
| UML Modeling | PlantUML |
| Project Management | Jira |

---

# Project Structure

```text
Assignment-1/
│── Requirements Engineering
│── SRS Documentation
│── Use Case Diagrams

Assignment-2/
│── Scrum Management
│── Jira Sprint Planning
│── Architectural Design
│── Sprint Reports

Assignment-3/
│── Structural UML Models
│── Dynamic UML Models
│── Design Patterns
│── Detailed Design Documentation
```

---

# Assignment Coverage

## Assignment 1 — Requirements Engineering
- Software Requirements Specification (SRS)
- Functional & Non-Functional Requirements
- Business Use Cases
- Product Backlog
- Use Case Diagrams

---

## Assignment 2 — Scrum & Architectural Design
- Scrum Sprint Planning
- Jira Task Management
- Sprint Stand-up Meetings
- Burnup & Burndown Reports
- Cumulative Flow Diagrams
- Architectural Design
- High-Level System Architecture

---

## Assignment 3 — Detailed Design
- UML Class Diagram
- Sequence Diagrams
- State Diagram
- Activity Diagram
- Observer Design Pattern
- Dynamic & Structural Models

---

# Design Pattern Used

## Observer Pattern

The Observer Pattern is implemented for real-time collaborative synchronization. The `CodeEditor` acts as the Subject, while connected users act as Observers. Whenever code changes occur, updates are broadcasted through WebSockets to all connected participants.

---

# System Workflow

1. User Authentication
2. Create or Join Coding Room
3. Initialize Collaborative Session
4. Real-Time Collaborative Editing
5. Code Execution & Output Display
6. Chat Communication
7. Performance Tracking
8. Session Management & Logout

---

# Repository Contents

This repository contains:
- Assignment Reports
- UML Diagrams
- Architectural Models
- Sprint Evidence
- Jira Reports
- PlantUML Source Code
- Additional Design Artifacts

---

# Team Members

- Hassan Mehmood
- Usman Raza
- Abdul Tawwab

---

# Course Information

Course: Software Engineering  
Project Type: Collaborative Academic Project  
Methodology: Scrum Agile Development  

---

# Conclusion

This project demonstrates the application of Software Engineering principles including Requirements Engineering, Agile Scrum Management, Architectural Design, and UML-based Detailed System Modeling to design a scalable and collaborative real-time coding platform.
