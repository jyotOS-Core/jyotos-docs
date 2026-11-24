# Completing Administrator Verification

{% hint style="info" %}
**Quick Facts**
* **Audience:** System Administrators, College Principal
* **Applies To:** StaffBridge
* **Target Status:** Coordinator Verified (`coordinator_verified`)
* **Resulting Status:** Admin Verified (`admin_verified` / "Ready")
{% endhint %}

This guide documents the final administrative verification process required to approve staff profiles and enable access to connected JyotOS applications.

---

## Prerequisites for Final Approval

Before granting administrator verification, ensure the following criteria are met:

* [ ] **Coordinator Approval:** Profile status is **Coordinator Verified** (`coordinator_verified`).
* [ ] **Institutional Email:** Official email address ending with `@amrolicollege.ac.in` is confirmed.
* [ ] **Employment Details:** Primary campus, department, designation, and category align with official employment orders.
* [ ] **Active Status:** Account is set to **Active**.

---

## Step-by-Step Approval Procedure

[SCREENSHOT TO CAPTURE: Administrator verification action panel with Admin Verify button and Active Status toggle]

1. Sign in to StaffBridge using your administrator Google account (`@amrolicollege.ac.in`).
2. Navigate to **Dashboard** (`/admin`) or **Reports & Exports** (`/admin/reports`).
3. Filter the roster by profile status **Coordinator Verified**.
4. Click on a staff member's record to open their complete review sheet.
5. Review the details, uploaded passport photo, and signature.
6. Verify that the **Active Status** toggle is set to **Active**.
7. Click **Admin Verify / Final Approval**.
8. The system updates the profile status to **Admin Verified** (`admin_verified`), records your administrator identity and timestamp, and marks the profile as **Ready**.

---

## Profile Status vs. Active Status

StaffBridge maintains two distinct status properties for every staff record:

* **Profile Status:** Tracks verification lifecycle progress (`submitted` → `coordinator_verified` → `admin_verified`).
* **Active Status:** Governs whether the staff member is currently an active employee (`Active` / `Inactive`).

{% hint style="info" %}
**Ecosystem Access Eligibility**
When a staff profile reaches **Admin Verified** status and its **Active Status** is **Active**, the profile achieves **Ready** status. The verified identity record serves as the authoritative source for single sign-on across connected JyotOS applications.
{% endhint %}
