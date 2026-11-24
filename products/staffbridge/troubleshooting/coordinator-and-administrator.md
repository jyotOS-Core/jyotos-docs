# Coordinator and Administrator Troubleshooting

{% hint style="info" %}
**Quick Facts**
* **Audience:** Department Coordinators, System Administrators, College Principal
* **Applies To:** StaffBridge Management Portal
* **Key Topics:** Review queues, department mapping, email quotas, export filters
{% endhint %}

This guide helps Department Coordinators and System Administrators diagnose and resolve administrative queue, permission, communication, and reporting issues.

---

## Common Management Issues and Solutions

| Symptom | Likely Cause | Solution |
| :--- | :--- | :--- |
| **Staff Record Missing in Coordinator Queue** | Record belongs to a department not mapped to coordinator | Verify coordinator department mapping in Access Control. Coordinators only see submissions from their assigned department(s). |
| **Cannot Grant Final Admin Verification** | Profile status is still Submitted or Needs Correction | A profile must be approved by the Department Coordinator to reach **Coordinator Verified** before final Admin Verification can be granted. |
| **Email Campaign Fails to Send** | Daily 100-email safety quota reached | Check the daily quota meter in Communications. Wait for the 24-hour quota window to reset, or split large campaigns across multiple days. |
| **Reports & Exports Returns Empty File** | Active filters are too restrictive | Reset campus, department, and status filters in Reports & Exports to ensure the target records are included before clicking Export. |
| **Staff Member Inactive in Connected Applications** | Profile is Admin Verified, but Active Status is Inactive | Open the staff profile in Directory & ID Cards or Reports & Exports, toggle Active Status to **Active**, and save. |

---

## Permission and Role Escalation

* **Coordinators:** If you cannot access submissions from newly assigned departments, request a department mapping update from the System Administrator.
* **Administrators:** If system configuration or database sync issues occur, contact the technical platform team.
