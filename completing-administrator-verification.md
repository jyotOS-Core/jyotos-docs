# Completing Administrator Verification

{% hint style="info" %}
**Guide Quick Facts**

* **Estimated Reading Time:** 5 minutes
* **Target Audience:** System Administrators, College Principal
* **Applies To:** StaffBridge
* **Last Updated:** 06 August 2026 | **Version:** Internal Preview v0.2 (Draft)
{% endhint %}

This guide documents the final administrative verification process required to approve staff profiles and enable access to connected JyotOS applications.

***

## Prerequisites for Final Approval

Before completing administrative verification:

* [ ] Profile status is **Coordinator Verified**.
* [ ] Official college email address ending with `@amrolicollege.ac.in` is validated.
* [ ] Primary campus, department, designation, and staff category match official employment records.

***

## How Do I Complete Administrator Verification?

📷 Screenshot Placeholder\
_&#x44;escription:_ Administrator Final Verification Interface\
_&#x52;equired View:_ Master verification queue with Admin Verify and Active Toggle controls\
_&#x4D;asking Required:_ Yes\
_&#x44;ummy Data Requirement:_ Use sample Coordinator Verified staff records\
_&#x53;uggested Caption:_ Figure 1: Administrator verification queue showing Admin Verify and Active Status controls\
_&#x41;ccessibility Alt Text:_ Interface showing staff record details, Admin Verify button, and Active Status toggle

1. Sign in using your official Google `@amrolicollege.ac.in` account.
2. Open the **Admin Portal** or **Staff Reports & Verification Roster** page.
3. Filter by status **Coordinator Verified**.
4. Open the staff profile sheet to perform final administrative evaluation.
5. Ensure staff Active Status is set to **Active**.
6. Click **Admin Verify / Final Approval**.
7. The system records your administrator ID and timestamp, and updates profile status to **Admin Verified**.

***

## Understanding Active Status vs. Profile Status

StaffBridge distinguishes between two independent status properties:

* **Profile Status:** Reflects the review lifecycle progress (**Submitted** ➔ **Coordinator Verified** ➔ **Admin Verified**).
* **Active Status:** Manages operational access enablement (**Active** / **Inactive**).

{% hint style="info" %}
**Ecosystem Access Eligibility** When a staff profile reaches **Admin Verified** status and its **Active Status** is enabled, the staff member's verified identity information becomes eligible for access to supported connected applications across the JyotOS ecosystem (such as EventOS). _(Note: Specific SSO integration mechanisms are subject to Product Owner confirmation)._
{% endhint %}

***

**Version:** Internal Preview v0.2 (Draft) | **Last Updated:** 06 August 2026 | **Applies To:** StaffBridge\
**Previous Step:** [← System Administrator Guide](./) | **Next Step:** Viewing Staff Reports →\
**Related Guides:** [System Administrator Guide](./) · Viewing Staff Reports
