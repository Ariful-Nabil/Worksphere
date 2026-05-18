<<<<<<< HEAD
# Project Simulator
=======
## Project Overview
Nexus is a multi-role management system designed to streamline HR communications, client service tracking, and employee engagement.

---

## HR Manager Module
### Screen: Manage Notices
**User Story:** As an HR Manager, I want to publish and manage notices so that employees and clients can be informed.

**Acceptance Criteria:**
* Title and Notice Details cannot be empty.
* Audience must be selected before publishing.
* After publishing, notice appears on the target audience's notice board immediately.
* Edit button opens the form pre-filled with existing notice data.
* Delete removes the notice from DB and it no longer appears anywhere.
* Notice table is sorted by newest first.

---

## Client Module
### Screen: Client Dashboard
**User Story:** As a client, I want to view my dashboard so that I can see an overview of my orders and payments.

**Acceptance Criteria:**
* All counts are fetched live from DB for the logged-in client only.
* Unpaid Invoices count is highlighted if greater than 0.
* Recent Orders table shows: Order ID, Service, Date, Status.
* Status badges are color coded: Pending (Yellow), In Progress (Blue), Completed (Green).

### Screen: Order Tracking
**User Story:** As a client, I want to track my orders so that I can monitor the progress of my service requests.

**Acceptance Criteria:**
* Only orders belonging to the logged-in client are shown.
* Filter updates the list dynamically without page reload.
* View Details shows full order information including any notes added by HR.
* Status reflects any changes made by HR in real time.

---

## Employee Module
### Screen: Employee Dashboard
**User Story:** As an employee, I want to see my dashboard with notices so that I stay updated on company announcements.

**Acceptance Criteria:**
* Unread Notices count is shown as a badge and updates when notices are viewed.
* Pending Applications count shows only the logged-in employee's applications.
* Recent Notices table is sorted newest first.
* Clicking a notice marks it as read and opens the full notice content.

---

## Profile Module (All Roles)
### Screen: User Profile
**User Story:** As a user, I want to view my profile so that I can see my personal information.

**Acceptance Criteria:**
* All fields are fetched from DB for the logged-in user.
* No null values should be displayed on the profile.
* Edit Profile button navigates to the Edit Profile page.
* Change Photo button navigates to the Change Profile Photo page.
* Change Password button navigates to the Change Password page.

---

## Upcoming Modules
* [ ] Role: Financial Controller (TBD)
* [ ] Role: System Administrator (TBD)
* [ ] Role: External Consultant (TBD)

---

## Technical Stack
* **Frontend:** HTML5, CSS3 (Glassmorphism), JavaScript (ES6+)
* **Fonts:** Plus Jakarta Sans
>>>>>>> 0628123a73ca34f10219bbb0b6cc6dcdff6f91cd
