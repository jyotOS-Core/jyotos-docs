# Can't Access StaffBridge

{% hint style="info" %}
**Quick Facts**
* **Audience:** All Staff Members, Coordinators, Administrators
* **Applies To:** StaffBridge Authentication & Access
* **Login Method:** Official Google account (`@amrolicollege.ac.in`)
{% endhint %}

This guide helps diagnose and resolve sign-in, authentication, and permission issues when attempting to access StaffBridge.

---

## Access Decision Flowchart

Follow this decision tree to pinpoint your access issue:

```
Can't Access StaffBridge
          │
          ▼
Are you using an official @amrolicollege.ac.in Google email?
   ├── NO  ──► Use your official @amrolicollege.ac.in Google account
   └── YES ──► Is your account in Active Status?
                 ├── NO  ──► Contact System Administrator to enable Active Status
                 └── YES ──► Have you completed initial onboarding?
                               ├── NO  ──► Complete initial registration on the staff onboarding page
                               └── YES ──► Confirm your registered email matches your Google sign-in
```

---

## Common Sign-In Symptoms and Fixes

| Symptom | Likely Cause | Solution |
| :--- | :--- | :--- |
| **Google Sign-In Rejected** | Signed in with a personal Gmail or non-institutional account | Sign out of personal Google accounts and select your official `@amrolicollege.ac.in` account. |
| **"Account Inactive" Notice** | Profile Active Status is set to Inactive | Contact your System Administrator to verify your employment status and activate your account. |
| **Dashboard Access Denied** | Signed-in email has no registered onboarding record | If you are a new employee, complete initial registration on the staff onboarding page. |
| **Admin Portal Access Denied** | Google account lacks coordinator or administrator role | Role assignment is managed in Access Control. Contact the System Administrator to check your role. |

---

## Error Messages Explained

* **"Access restricted to official institutional domain":**\
  You attempted to sign in with a personal Google account (e.g. `@gmail.com`). StaffBridge requires authentication through an official Google Workspace account ending with `@amrolicollege.ac.in`.
* **"User profile not found":**\
  Your Google account is valid, but no matching onboarding submission exists. Complete registration on the staff onboarding page using your official college email.
