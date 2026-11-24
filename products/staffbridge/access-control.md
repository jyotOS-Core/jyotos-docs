# Access Control

{% hint style="info" %}
**Quick Facts**
* **Audience:** System Administrators
* **Applies To:** StaffBridge
* **Route:** `/admin/access-control`
* **Managed Entity:** User profiles table (`user_profiles`)
{% endhint %}

The **Access Control** section gives system administrators centralized governance over user roles, account approval statuses, and department coordinator assignments.

---

## Accessing Access Control

Select **Access Control** from the administrator navigation menu, or navigate directly to `/admin/access-control`.

[SCREENSHOT TO CAPTURE: Access control user management table with role assignment dropdown]

---

## User Roles Hierarchy

StaffBridge defines five primary user roles within the system:

| Role | Scope | Permissions |
| :--- | :--- | :--- |
| `admin` | College-wide | Full access to all 5 admin sections, verification, settings, exports, and access control. |
| `principal` | College-wide | Executive review, verification approval, reports, and directory oversight. |
| `coordinator` | Department-level | Access to assigned department submissions, verification up to `coordinator_verified`, and correction requests. |
| `staff` | Personal | Access to personal onboarding form, dashboard, profile updates, and digital ID card. |
| `pending` | None | Newly registered user awaiting role assignment and account approval. |

---

## Managing User Roles

1. In `/admin/access-control`, locate the user record using the search bar or role filter.
2. Click the **Role** dropdown next to the user's name.
3. Select the appropriate role (`admin`, `principal`, `coordinator`, or `staff`).
4. Confirm the role change when prompted. The updated permissions take effect immediately on the user's next request.

---

## Assigning Department Coordinators

Coordinators require explicit mapping to one or more academic or administrative departments:

1. Locate the coordinator's profile in the Access Control roster.
2. Click **Manage Departments**.
3. Select the department(s) for which the coordinator is responsible (e.g. Computer Science, Commerce, Administration).
4. Save the mapping.
5. The coordinator's review queue will now display only submissions from their assigned department(s).

---

## Account Approval and Revocation

Administrators can control whether a user account has active access to StaffBridge:

* **Approve User:** Moves an account from `pending` status to an approved role, granting login access.
* **Suspend Access:** Temporarily disables access for an account without deleting profile or history records.
* **Audit Trail:** All role modifications and status changes are recorded with administrator timestamps.
