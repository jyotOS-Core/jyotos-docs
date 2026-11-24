# JyotOS Institution Management System Overview

{% hint style="info" %}
**Quick Facts**
* **Audience:** Institutional Leaders, College Management, Department Heads, System Administrators
* **Applies To:** JyotOS Institution Management System (IMS)
* **Status:** Multi-application ecosystem supporting Amroli Campus and Chaprabhatha Campus
{% endhint %}

The JyotOS Institution Management System provides an integrated digital environment designed for higher education institutions. It connects faculty, departmental leadership, and campus administration through a shared identity layer and specialized operational applications.

---

## Architecture & Ecosystem Design

JyotOS is structured around three core operational layers:

1. **Unified Identity & Onboarding (StaffBridge):**
   * Serves as the verified institutional staff directory.
   * Faculty and staff sign in with their official college Google account (`@amrolicollege.ac.in`).
   * A two-stage verification process (Coordinator Review followed by Administrator Verification) establishes official staff records.

2. **Central Application Launcher (JyotOS Central):**
   * Acts as the single entry point for all connected institutional tools.
   * Displays application tiles based on verified access permissions.
   * Provides self-service access requests and administrative governance.

3. **Domain-Specific Applications:**
   * Each operational application focuses on a specific workflow domain.
   * Applications maintain their own internal roles and permissions while integrating with the central identity framework.

---

## Current Application Availability

The JyotOS ecosystem comprises both live applications in active deployment and upcoming solutions in development:

### Live Applications Today

| Application | Primary Purpose | Key User Roles |
| :--- | :--- | :--- |
| **JyotOS Central** | Centralized application launcher and access control hub | Staff, Administrators |
| **StaffBridge** | Staff onboarding, identity verification, and digital credential directory | Staff, Department Coordinators, Administrators |
| **EventOS** | Campus event proposal, executive approval, and participant registration | Staff, Event Coordinators, Principals, Administrators |
| **ClassPulse Pro** | Timetable reconciliation, faculty lecture tracking, and teaching diaries | Faculty, Department HODs, Principals, Administrators |

### Ecosystem Applications in Development

Additional specialized modules are being developed to support admissions, student services, operations, and academic management. 

→ See [More Applications](../products/more-apps.md) for details on upcoming tools including JyotAssist AI, ScholarCard AI, and GCAS AdmitTracker.

---

## Next Steps for Institutions

* Review [Institutional Onboarding Workflow](how-onboarding-works.md) to understand the staff onboarding path.
* Explore [Institutional Access Model & Roles](access-and-roles.md) for role assignments and permissions.
* Read [Institutional Data & Records Management](data-and-privacy.md) for details on information handled across applications.
* Distribute the [Staff Quick Reference Handout](staff-handout.md) during staff orientation.
