# Requirement Specification

# **External Interface Requirements**

## **User Interfaces**

The system provides a web-based user interface accessible through modern browsers. Users can register, log in, create or join coding rooms, write and execute code, and communicate via chat. The interface includes a collaborative code editor, problem panel, output console, and user dashboard displaying performance statistics.

---

## **Hardware Interfaces**

The system does not require specialized hardware. It operates on standard devices such as laptops, desktops, or tablets with internet connectivity. Input is provided through keyboard and mouse.

---

## **Software Interfaces**

The system interacts with:

- Web browsers (Chrome, Edge)
- Backend server (Node.js)
- Database (PostgreSQL)
- Code execution environment (Docker-based sandbox)
- Real-time communication system (WebSockets / Socket.io)

---

## **Communication Interfaces**

The system uses internet protocols (HTTP/HTTPS) for client-server communication and WebSockets for real-time features such as collaborative editing and chat

# **Functional Requirements**

---

## **Use Cases**

| **Use Case Title** | **Description** |
| --- | --- |
| Register | User creates a new account |
| Login | User logs into the system |
| View Profile | User views stats and performance |
| Create Room | User creates a collaborative coding room |
| Join Room | User joins an existing room |
| Write Code | Users collaboratively write code |
| Run Code | System executes code and shows output |
| Chat | Users communicate via text chat |
| Select Problem | User selects coding problem |
| View Stats | User views progress and performance |

---

# **Scenario: Register**

**Description:**

User creates a new account.

**Functional Response:**

System stores user data and creates a new account.

---

# **Scenario: Login**

**Description:**

User logs into the system.

**Functional Response:**

System verifies credentials and grants access to dashboard.

---

# **Scenario: Create Room**

**Description:**

User creates a coding session.

**Functional Response:**

System generates a room ID and initializes session.

---

# **Scenario: Join Room**

**Description:**

User joins an existing room.

**Functional Response:**

System connects user to shared session.

---

# **Scenario: Write Code**

**Description:**

Users collaboratively write code.

**Functional Response:**

System syncs code changes in real-time.

---

# **Scenario: Run Code**

**Description:**

User executes code.

**Functional Response:**

System sends code to execution engine and returns output.

---

# **Scenario: Chat**

**Description:**

Users communicate in a room.

**Functional Response:**

Messages are delivered instantly to all participants.

---

# **Scenario: Select Problem**

**Description:**

User selects a coding problem.

**Functional Response:**

System loads problem details into workspace.

---

# **Scenario: View Stats**

**Description:**

User views performance.

**Functional Response:**

System displays solved problems, success rate, and streak.

# **Non-functional Requirements**

---

## **Performance Requirements**

| **Requirement** | **Description** |
| --- | --- |
| Response Time | System should respond within 2–3 seconds |
| Real-time Sync | Code updates should reflect instantly |
| Workload | System should support multiple users per room |
| Scalability | System should handle increasing users |

---

## **Safety Requirements**

| **Requirement** | **Description** |
| --- | --- |
| Data Protection | User data should not be lost |
| Error Handling | System should handle failures gracefully |
| System Stability | Prevent crashes during execution |

---

## **Security Requirements**

- User authentication is required
- Passwords must be encrypted
- Secure communication (HTTPS)
- Code execution must be sandboxed

---

## **Software Quality Attributes**

| **Attribute** | **Description** |
| --- | --- |
| Reliability | System should work without frequent failure |
| Usability | Interface should be easy to use |
| Maintainability | Code should be modular |
| Efficiency | System should perform tasks quickly |
| Scalability | System should support growth |

---

## **Business Rules**

- Only registered users can create rooms
- Users must log in to access features
- Each room can have multiple participants
- Code execution is limited to supported languages
- System tracks user progress and statistics