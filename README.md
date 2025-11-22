
# Odoo x Amalthea Hackathon 2025: Intelligent Expense Management System

### Project Title 

**Odoo x Amalthea Hackathon 2025: Intelligent Expense Management System (Developed by Team Codex)**

### Problem Solved

This project addresses the industry struggle with manual, error-prone, and non-transparent expense reimbursement processes. We provide a simple, robust solution that supports complex, multi-level, and conditional approval flows.

---

## Core Features Demonstrated

| Feature Area | Key Functionality | Page/File |
| :--- | :--- | :--- |
| **Submission** | **OCR Simulation:** Employee scans a receipt, and the form auto-fills required fields (amount, date, category, description)| `expense-submission.html` |
| **Approval Logic** |**Sequential Flow** (Manager → Finance → Director) and **Conditional Rules** (Percentage/Specific Approver/Hybrid) | `approval-config.html` |
| **Role Management** | Admin can create users, assign roles (Employee/Manager), and **define manager relationships**. | `frontend.html` |
| **Financial Oversight** | Manager sees expense amount visible in company's default currency. | `manager-review-page.html` |
| **Reporting** | Role-specific views of expense status and history (e.g., Employee views their history; Admin views all expenses). | `team-expenses.html`, `all-expenses-report.html` |

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

**Start Time:** 8:00 AM, 4th October 2025
**Coding End Time:** 5:00 PM

1.  **Clone Repository:** 
2.  **Open Index:** Open the **`loginpage.html`** file directly in any modern web browser (e.g., Chrome, Edge).
3.  **No Server Required:** The entire application runs using HTML, CSS, and **JavaScript** for state management (Local Storage). No local server (`backend.py`) or database (`integration.sql`) is required. This demonstrates planning for offline or local solutions.

### 🔄 Demo Control & Reset

To reset the Manager's approval queue for a fresh demonstration run:

* Log in as **Admin** or **Manager**, and click the **"Reset Demo State"** button. This clears the approval history in Local Storage.



