# Understanding Profile Status

This guide explains each status code displayed on your StaffBridge dashboard, what it indicates about your registration, and what action you should take.

***

## Profile Review Lifecycle

Your staff record moves through a structured, multi-tier review process:

```
Submitted ──► Coordinator Verified ──► Admin Verified (Ready)
    │                  │
    ▼                  ▼
Needs Correction ◄─────┘
    │
    ▼
Correction Submitted
```

***

## Status Reference Guide

StaffBridge tracks your profile using seven distinct statuses:

### 1. Submitted

* **Meaning:** Your onboarding registration has been successfully received by the system.
* **Current Review Level:** In queue awaiting initial review by your assigned Department Coordinator or System Administrator.
* **Staff Action Required:** None. Your submission is in the review queue.

### 2. Coordinator Verified

* **Meaning:** Your Department Coordinator has reviewed your department mapping, designation, and academic qualifications, and approved your submission at the department tier.
* **Current Review Level:** Department review complete. Awaiting final administrative approval.
* **Staff Action Required:** None. Your profile is automatically queued for final administrator review.

### 3. Needs Correction

* **Meaning:** An administrator or coordinator has reviewed your submission and flagged one or more specific fields or media items that require correction, re-upload, or clarification.
* **Current Review Level:** Action required from staff member.
* **Staff Action Required:** Sign in to your dashboard using your official Google `@amrolicollege.ac.in` account. Open the **Pending Correction Fields** section, read the reviewer's instructions, enter the updated details, and click **Submit Update**.

### 4. Correction Submitted

* **Meaning:** You have submitted corrected values or uploaded updated media in response to a correction request.
* **Current Review Level:** Queued for administrative re-evaluation.
* **Staff Action Required:** None. The reviewer will inspect your resubmitted information alongside the original record.

### 5. Admin Verified ("Ready")

* **Meaning:** Your profile has received final approval from the System Administrator or College Principal.
* **Current Review Level:** Complete.
* **Staff Action Required:** None. Your profile is fully verified across the institution. With Admin Verified status, your identity is marked "Ready" and automatically enabled for single sign-on access across connected JyotOS applications (such as EventOS and Central).

### 6. Duplicate

* **Meaning:** The administration flagged this submission as a duplicate entry (for example, if you submitted the onboarding form more than once).
* **Staff Action Required:** If you submitted multiple forms, your newest valid record will be kept. If you believe your record was marked duplicate by mistake, contact your System Administrator.

### 7. Rejected

* **Meaning:** The registration could not be verified or accepted by the institution.
* **Staff Action Required:** Contact your Department Coordinator or the college IT Cell for guidance.

***

## Ecosystem Eligibility by Status

| Status | Meaning | Review State | JyotOS Ecosystem Access |
| :--- | :--- | :--- | :---: |
| **Submitted** | Registration received | Initial queue | Ineligible |
| **Coordinator Verified** | Department verification granted | Department approved | Ineligible |
| **Needs Correction** | Flagged for update | Action required from staff | Ineligible |
| **Correction Submitted** | Resubmitted by staff | Re-evaluation queue | Ineligible |
| **Admin Verified** | Final institutional approval | Final approval complete | **Eligible ("Ready")** |
| **Duplicate** | Duplicate submission | Duplicate record | Ineligible |
| **Rejected** | Submission rejected | Rejected by admin | Ineligible |

***

**Related Guides:** [Responding to Correction Requests](responding-to-correction-requests.md) · [Using Your Staff Dashboard](using-your-dashboard.md) · [Getting Started](getting-started.md)
