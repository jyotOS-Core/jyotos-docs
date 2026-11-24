# Administrator Guide for EventOS

{% hint style="info" %}
**Quick Facts**
* **Audience:** System Administrators, College IT Operations
* **Applies To:** EventOS (Administrator Console)
* **Scope:** College-wide master data, user mapping, attendance exceptions, and archival
{% endhint %}

This guide explains how system administrators configure institutional master data, manage user role assignments, handle session attendance exceptions, and oversee final event archival.

---

## Administrator Console Overview

The Administrator Console provides college-wide administrative governance over EventOS operations:

* **Master Data Management:** Campuses, departments, venues, and committees.
* **User & Role Governance:** Role assignments and campus/department mappings.
* **Attendance Exceptions:** Session-level manual overrides and attendance audit logs.
* **Event Archival:** Long-term preservation of completed events and approved reports.

---

## Institutional Master Data Management

Administrators maintain the core organizational entities referenced across all events:

### 1. Campuses and Departments
* Ensure all active institutional campuses (**Amroli Campus** and **Chaprabhatha Campus**) are configured.
* Maintain academic and administrative departments mapped to their respective campuses.

### 2. Venues and Facilities
* Configure campus auditoriums, seminar halls, conference rooms, laboratories, and outdoor grounds.
* Specify seating capacities and venue availability parameters.

### 3. Committees and Event Categories
* Maintain institutional committees, cells, clubs, and professional associations.
* Configure standard event categories (e.g., Academic Conferences, Workshops, Faculty Development Programs, Cultural Events, Sports Tournaments).

---

## User Mapping and Role Governance

EventOS operates with independent role-based permissions mapped from verified StaffBridge identities:

1. **Staff Identity Ingestion:** Verified staff records from StaffBridge are linked to EventOS profiles.
2. **Role Assignment:** Administrators assign operational roles based on institutional duties:
   * **Administrator:** Full administrative governance across all campuses.
   * **Principal:** Executive approval authority for campus-specific event proposals and reports.
   * **Department Coordinator:** Authority to draft proposals, coordinate sessions, and submit reports within their assigned campus.
   * **Staff Member:** Default self-service access to discover events, register, and attend sessions.
3. **Organizational Mapping:** Administrators ensure each staff profile is correctly mapped to an institutional campus and department. Staff profiles without department mappings cannot register for department-restricted events.

---

## Attendance Exceptions and Overrides

EventOS supports administrative controls to resolve attendance anomalies while preserving an auditable record:

* **Session Attendance Reopening:** If technical connectivity issues or delayed sessions prevent timely check-ins, an administrator can reopen a closed session's attendance window.
* **Recorded Attendance Exceptions:** If a registered participant attended a session but could not scan their pass due to device failure, an administrator can record a manual attendance exception.
* **Audit Trail:** Every administrative attendance adjustment records the administrator account identifier, timestamp, and justification note in the event audit log.

---

## Event Cancellation and Archival

Administrators share cancellation and archival responsibilities with campus leadership:

### Event Cancellation
* Administrators can cancel an individual session or an entire event when required, recording an official administrative reason.
* Cancellation locks all active registrations and updates the event status across all public and internal views.

### Permanent Archival
* Once an event concludes and its post-event report package has received formal approval, the event enters the archival phase.
* Administrators confirm the completeness of report records and archive the event.
* Archived events remain permanently searchable in the institutional archive, while private participant contact details remain protected from public exposure.
