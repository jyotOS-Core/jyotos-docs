# Directory and ID Cards

{% hint style="info" %}
**Quick Facts**
* **Audience:** System Administrators, College Principal
* **Applies To:** StaffBridge
* **Route:** `/admin/directory`
* **Features:** Visual staff gallery, campus grouping, modal profile viewer, ID card export
{% endhint %}

The **Directory & ID Cards** page combines the institutional staff directory with digital ID card generation and bulk export capabilities in a single interface.

---

## Overview of Directory & ID Cards

Located at `/admin/directory`, this section provides an intuitive, visual representation of all registered staff across the institution.

[SCREENSHOT TO CAPTURE: Directory and ID cards gallery view with campus tabs]

---

## Campus Grouping and Navigation

The directory is organized with campus tabs for streamlined navigation:

* **Amroli Campus Tab:** Displays all faculty and staff assigned to the Amroli Campus.
* **Chaprabhatha Campus Tab:** Displays all faculty and staff assigned to the Chaprabhatha Campus.
* **All Staff View:** Displays the complete institutional roster.

Within each campus view, staff members are presented as visual cards (pills) displaying:
* Passport photo thumbnail
* Staff full name and official reference ID
* Primary department and official designation
* Profile status badge (e.g. Ready, Submitted, Coordinator Verified)
* Active status indicator

---

## Inspecting Staff Details

Clicking any staff card opens a detailed modal view:

* **Complete Profile Summary:** View contact details, employment history, and academic qualifications without navigating away from the directory.
* **ID Card Preview:** View the real-time front and back rendering of the staff member's official digital identity card.
* **Direct Actions:** Access quick links to review or edit profile verification.

---

## ID Card Generation and Export

Administrators can generate and export digital ID cards individually or in bulk:

* **Single Card Download:** Open a staff record modal and click **Download ID Card** to export a high-resolution PNG or PDF of the front and back card faces.
* **Bulk ID Card Export:** Select multiple staff members (or filter by campus/department) and click **Export Selected ID Cards** to download an archive (ZIP file) containing individual ID cards.

{% hint style="info" %}
**ID Card Availability**
Digital ID cards display the official verification seal once a profile reaches **Admin Verified** status. Unverified profiles display a draft watermark.
{% endhint %}
