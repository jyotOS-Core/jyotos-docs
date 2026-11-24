# StaffBridge FAQ

{% hint style="info" %}
**Quick Facts**
* **Audience:** All Staff Members, Department Coordinators, Administrators
* **Applies To:** StaffBridge
* **Categories:** Onboarding, access, media, verification, administration, and privacy
{% endhint %}

Welcome to the **StaffBridge Frequently Asked Questions (FAQ)**. Find clear answers to common questions about onboarding, account access, media guidelines, profile status tracking, department coordination, and administrative functions.

---

## 1. Getting Started and Access

### What is StaffBridge?
StaffBridge is the official staff identity, onboarding, profile management, and verification system of Amroli College. It serves as the central identity authority for all JyotOS products.

### Who must complete StaffBridge onboarding?
All newly appointed and existing faculty members, administrative staff, laboratory personnel, library staff, and support personnel must complete onboarding.

### Do I need an account before completing onboarding?
No. Initial onboarding registration at `/staff/onboarding` is publicly accessible and does not require prior sign-in. After submitting your form, you sign in to your dashboard using your official Google `@amrolicollege.ac.in` account.

### Which email address should I use for StaffBridge?
You must use your official college email address ending with `@amrolicollege.ac.in`.

### Can I use a personal Gmail or other email account?
No. StaffBridge authentication restricts sign-in to the official institutional Google Workspace domain (`@amrolicollege.ac.in`). Personal email domains are not accepted.
→ See [Can't Access StaffBridge](troubleshooting/cant-access.md).

### What is my Staff Reference ID?
Your Staff Reference ID is a unique institutional tracking code (formatted as `STAFF-2026-XXXX`) generated upon registration. It appears on your confirmation receipt, digital ID card, and dashboard.

### What happens after I submit my onboarding form?
Your submission enters your department's verification queue under status **Submitted** (`submitted`). Your assigned Department Coordinator reviews your details.
→ See [Getting Started](getting-started.md).

---

## 2. Onboarding and Information

### Can I edit my information after submitting onboarding?
Once submitted, profile fields become read-only to preserve verification integrity. If changes are necessary, a Department Coordinator or System Administrator can flag specific fields for correction, unlocking them for editing.

### What should I do if I entered incorrect information?
Notify your Department Coordinator. They can issue a correction request that unlocks the specific fields for you to update on your dashboard.

### Why is the department dropdown empty?
You must select your **Primary Campus** (**Amroli Campus** or **Chaprabhatha Campus**) first. The department dropdown populates based on the chosen campus.

### What information should I prepare before starting onboarding?
Prepare your personal details, residential address with 6-digit PIN code, emergency contact information, official designation, date of joining, academic qualifications, passport photo, and digital signature.
→ See [Complete Onboarding](complete-onboarding.md) and [Personal and Employment Information](personal-and-employment-information.md).

---

## 3. Photo and Signature Media

### Are passport photo and signature mandatory?
Yes. Both a front-facing passport photo and a digital signature are required to complete onboarding and generate your digital ID card.

### Can I upload an existing photograph file?
Yes. You can upload an image file (JPEG, PNG, or WebP format up to 2 MB) or capture a photo directly using your device camera.

### Can I clear and redraw my signature?
Yes. You can tap or click **Clear Canvas** to erase your signature and redraw it as many times as needed before saving.

### Who can view my uploaded photograph and signature?
Your uploaded media is visible only to authorized Department Coordinators, System Administrators, and the College Principal for verification and ID card generation.
→ See [Photo and Signature Guidelines](photo-and-signature-guidelines.md).

---

## 4. Profile Status and Verification

### What does each Profile Status mean?
* **Submitted (`submitted`):** Registration submitted; waiting in department review queue.
* **Coordinator Verified (`coordinator_verified`):** Department Coordinator verified credentials and department assignment.
* **Needs Correction (`needs_correction`):** Reviewer flagged specific fields for update.
* **Correction Submitted (`correction_submitted`):** Updated details submitted by staff; awaiting re-evaluation.
* **Admin Verified (`admin_verified`):** Final institutional approval granted. When Active Status is Active, profile is **Ready**.
* **Duplicate / Rejected (`duplicate` / `rejected`):** Flagged as duplicate or rejected by administration.

### What is the difference between Profile Status and Active Status?
* **Profile Status:** Measures verification lifecycle progress (`submitted` → `coordinator_verified` → `admin_verified`).
* **Active Status:** Governs operational account enablement (`Active` / `Inactive`).

Both **Admin Verified** profile status and **Active** account status are required for an identity record to be **Ready** for single sign-on across connected JyotOS applications.
→ See [Understanding Profile Status](understanding-profile-status.md).

---

## 5. Correction Requests

### Why was my profile returned for correction?
A reviewer flagged one or more fields that were incomplete, formatted incorrectly, or contained low-contrast media.

### How do I know which fields need correction?
Sign in to your dashboard. Flagged fields are highlighted with reviewer remarks under the **Pending Correction Fields** section.

### Can I update fields that were not flagged for correction?
No. Unflagged fields remain locked to preserve verified data integrity.

### What happens after I resubmit corrected information?
Your profile transitions to **Correction Submitted** (`correction_submitted`), returning the record to your Department Coordinator's queue for re-evaluation.
→ See [Responding to Correction Requests](responding-to-correction-requests.md).

---

## 6. Staff Dashboard and Digital ID

### What can I see on my Staff Dashboard?
Your dashboard displays your current Profile Status badge, Staff Reference ID, personal and employment details summary, pending correction alerts, and digital ID card preview.

### Why does my ID card preview show a draft watermark?
The draft watermark remains until your profile reaches **Admin Verified** status. Once approved, the watermark is removed and the official verification seal is displayed.
→ See [Using Your Dashboard](using-your-dashboard.md).

---

## 7. Department Coordinators

### Which staff records can a Department Coordinator see?
Coordinators can view submissions, profile sheets, uploaded media, and correction responses for personnel assigned to their mapped department(s).

### Can a Department Coordinator approve records for other departments?
No. Coordinator access boundaries restrict review and verification to assigned departments only.

### What actions can a Coordinator take?
A coordinator can grant department verification (advancing the record to `coordinator_verified`) or request corrections (setting status to `needs_correction` with specific remarks).
→ See [Department Coordinator Guide](coordinator-guide.md).

---

## 8. System Administrators

### What sections does the administrator portal have?
The administrator portal features exactly five dedicated sections:
1. **Dashboard (`/admin`):** System metrics, pending actions, and activity overview.
2. **Directory & ID Cards (`/admin/directory`):** Visual staff directory grouped by campus with ID card generation and bulk ZIP export.
3. **Reports & Exports (`/admin/reports`):** Comprehensive roster filtering and export to CSV, XLS, and printable PDF.
4. **Communications (`/admin/notification-center`):** Notification Center for dispatching template-based emails under a 100 emails/day quota.
5. **Access Control (`/admin/access-control`):** User role management (`admin`, `principal`, `coordinator`, `staff`, `pending`) and coordinator department mapping.

### Who can perform final verification?
Final administrative verification (`admin_verified`) is performed exclusively by System Administrators and the College Principal.
→ See [Administrator Guide](administrator-guide.md) and [Completing Administrator Verification](completing-administrator-verification.md).

---

## 9. Data Governance and Privacy

### Why does StaffBridge collect staff information?
StaffBridge maintains the authoritative institutional staff directory for identity verification, administrative reporting, and access provisioning across JyotOS applications.

### Who has access to my submitted information?
Submitted records are accessible only to authorized Department Coordinators (for their assigned departments), System Administrators, and the College Principal.

### Is staff data shared with external parties?
No. StaffBridge identity data is managed within Amroli College systems and is not shared with external commercial entities.

---

## 10. JyotOS Ecosystem Access

### How does StaffBridge connect to other JyotOS applications?
StaffBridge serves as the central identity authority. Once an identity record achieves **Ready** status (`admin_verified` with Active Status `Active`), that identity is available for single sign-on across connected JyotOS applications such as EventOS and Central.

### Will I need to register again in other JyotOS products?
No. Connected JyotOS applications reference your authoritative StaffBridge identity record, avoiding redundant onboarding.
→ See [StaffBridge Overview](overview.md).
