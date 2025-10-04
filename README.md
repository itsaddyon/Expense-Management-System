<<<<<<< HEAD
# Odoo x Amalthea Hackathon 2025: Intelligent Expense Management System

### Project Title (Developed by Team Codex)

**Odoo x Amalthea Hackathon 2025: Intelligent Expense Management System**

### Problem Solved

[cite_start]This project addresses the industry struggle with manual, error-prone, and non-transparent expense reimbursement processes[cite: 22]. [cite_start]We provide a simple, robust solution that supports complex, multi-level, and conditional approval flows[cite: 25, 55, 61].

---

## Core Features Demonstrated

| Feature Area | Key Functionality | Page/File |
| :--- | :--- | :--- |
| **Submission** | [cite_start]**OCR Simulation:** Employee scans a receipt, and the form auto-fills required fields (amount, date, category, description)[cite: 66]. | `expense-submission.html` |
| **Approval Logic** | [cite_start]**Sequential Flow** (Manager → Finance → Director) [cite: 42, 45, 47, 50] [cite_start]and **Conditional Rules** (Percentage/Specific Approver/Hybrid)[cite: 58, 59, 60]. | `approval-config.html` |
| **Role Management** | [cite_start]Admin can create users, assign roles (Employee/Manager), and **define manager relationships**[cite: 32, 34]. | `frontend.html` |
| **Financial Oversight** | [cite_start]Manager sees expense amount visible in company's default currency[cite: 63]. | `manager-review-page.html` |
| **Reporting** | [cite_start]Role-specific views of expense status and history (e.g., Employee views their history; Admin views all expenses)[cite: 39, 63]. | `team-expenses.html`, `all-expenses-report.html` |

---

## 🔑 Demo Credentials

To experience the full role-based workflow, please open **`loginpage.html`** and use the following simulated credentials:

| Role | Userid | Password | Primary Demo Goal |
| :--- | :--- | :--- | :--- |
| **Admin** | `admin` | `password` | Configure Approval Rules (`approval-config.html`) and Manage Users (`frontend.html`). |
| **Manager** | `manager` | `password` | Approve/Reject Expenses quickly or in detail on the Review Page. |
| **Employee**| `employee` | `password` | Submit new expense using the **OCR Simulation** feature. |

---

## 🛠️ Setup and Running the Project

[cite_start]**Start Time:** 8:00 AM, 4th October 2025 [cite: 19]
[cite_start]**Coding End Time:** 5:00 PM [cite: 19]

1.  [cite_start]**Clone Repository:** (Ensure frequent pushes were made before 5:00 PM)[cite: 19].
2.  **Open Index:** Open the **`loginpage.html`** file directly in any modern web browser (e.g., Chrome, Edge).
3.  **No Server Required:** The entire application runs using HTML, CSS, and **JavaScript** for state management (Local Storage). No local server (`backend.py`) or database (`integration.sql`) is required. [cite_start]This demonstrates planning for offline or local solutions[cite: 12].

### 🔄 Demo Control & Reset

To reset the Manager's approval queue for a fresh demonstration run:

* Log in as **Admin** or **Manager**, and click the **"Reset Demo State"** button. This clears the approval history in Local Storage.
=======
# Expense-Management-System
>>>>>>> b10d3dc5e72407ed2936d588a3f1a1d64c3ad9d0
