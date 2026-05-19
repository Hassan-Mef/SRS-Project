# Overall Description

# **System Overview**

The system operates as a client-server web application where users interact through a browser interface.

System Flow:

1. User registers or logs in
2. User accesses dashboard
3. User creates or joins a coding room
4. Users collaboratively write code
5. Code is executed and results are displayed
6. Users communicate via chat
7. System updates user performance statistics

---

# **System Features (High-Level)**

**Feature	                       Description**

Authentication	      User registration and login
Coding Rooms	      Create/join shared sessions
Code Editor	              Real-time collaborative coding
Code Execution	      Run code and display output
Chat System	              Text-based communication
Performance Tracking	Stats and streak system

---

# **User Classes and Characteristics**

**User Type	          Description**

Registered User	Can access all features including rooms and stats
Admin (optional)	Manages system data and users

---

# **Operating Environment**

The system operates in the following environment:

Web browsers (Google Chrome, Microsoft Edge)

Internet-based platform

Runs on standard devices (PCs, laptops)

Backend hosted on server infrastructure

---

# **System Constraints**

Requires stable internet connection

Limited programming language support initially

No voice/video communication

Performance depends on server resources

---

# **Assumptions and Dependencies**

**Assumption	               Description**

Internet Access	       Users have stable internet
Basic Knowledge	       Users understand coding basics
Modern Browser	       Users use updated browsers

---

# **System Architecture**

The system follows a client-server architecture with real-time capabilities.

Components:

1. Frontend (Client):
Handles user interface, code editor, and interactions.
2. Backend (Server):
Manages authentication, rooms, APIs, and business logic.
3. Real-Time System:
Enables live code editing and chat using WebSockets.
4. Code Execution Engine:
Executes code securely and returns output.
5. Database:
Stores user data, rooms, problems, and statistics.

---

# **Technology Stack**

**Layer	             Technology**

Frontend	      React.js, Tailwind CSS, Monaco Editor
Backend	               Node.js (Express)
Real-time	       [Socket.io](http://socket.io/) (WebSockets)
Database	       PostgreSQL
Code Execution	Docker-based sandbox