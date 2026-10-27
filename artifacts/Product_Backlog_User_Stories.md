# Product Backlog & Agile User stories
**Project:** Automated Dental Appointment Reminder & Intake System
**Author**: Business Analyst

---

## Product Backlog Overview

| Story ID | User Persona | Core Feature / Requirement | Business Value | Priority |
| :--- | :--- | :--- | :--- | :--- |
| **US-01** | Patient | Receive automated SMS/email reminders with 1-click confirmation | Reduces 25% appointment no-show rate | High |
| **US-02** | Receptionist | Digital medical history forms sent 48 hours in advance | Saves front-desk time and eliminates waiting room delays | High |
| **US-03** | Lead Dentist | Real-time daily dashboard tracking confirmed vs. unconfirmed slots | Optimizes clinical chair time and allows waitlist backfilling | Medium |
| **US-04** | Clinic Manager | Automated pre-appointment instruction alerts (e.g., fasting/sedation rules) | Prevents last-minute appointment cancellations | Medium |

---

## Detailed User Stories & Acceptance Criteria

### User Story: US-01 (Automated 1-Click Reminder)
* **As a** Patient,  
* **I want to** receive an automated SMS reminder 48 hours before my scheduled visit and reply with '1' to confirm,  
* **So that** I can easily keep track of my dental care without receiving intrusive phone calls.

**Acceptance Criteria (Definition of Done):**
1. System triggers an automated SMS text 48 hours prior to appointment time.
2. Replying '1' updates the appointment status to **Confirmed** in real time.
3. Replying '2' triggers an automated link to select a new appointment slot.
4. Failure to respond within 24 hours flags the record on the front-desk dashboard for manual review.

---

### User Story: US-02 (Pre-Visit Mobile Digital Form)
* **As a** Receptionist,  
* **I want** medical intake forms to be automatically sent to patients to complete at home before check-in,  
* **So that** waiting room time is minimized and patient check-in is efficient.

**Acceptance Criteria (Definition of Done):**
1. Digital form link is included in the initial 48-hour automated SMS/email alert.
2. System enforces mandatory fields (Name, DOB, Medical History updates, Insurance Policy ID).
3. Submitted form data populates directly into the practice EHR without manual front-desk keying.
4. Portal complies with WCAG 2.1 Level AA standards (screen readers, high-contrast, dynamic fonts).
