# Can't Access StaffBridge

{% hint style="info" %}
**Guide Quick Facts**

* **Estimated Reading Time:** 4 minutes
* **Target Audience:** All Staff Members, Department Coordinators, Administrators
* **Applies To:** StaffBridge Authentication & Access
* **Last Updated:** 06 August 2026 | **Version:** Internal Preview v0.2 (Draft)
{% endhint %}

This guide helps users diagnose and resolve sign-in and access issues when attempting to log into StaffBridge.

***

## Access Decision Flowchart

Follow this step-by-step decision path to identify your access problem:

```
Can't Access StaffBridge
          │
          ▼
Are you using an official @amrolicollege.ac.in Google email?
   ├── NO  ──► Use official @amrolicollege.ac.in email address
   └── YES ──► Is your profile in Active Status?
                 ├── NO  ──► Contact System Administrator to enable Active Status
                 └── YES ──► Are you attempting initial onboarding registration?
                              ├── YES ──► Access public portal directly at /staff/onboarding
                              └── NO  ──► Verify registered email matches Google account
```

***

## Common Sign-In Symptoms & Fixes

| What You Experience            | Likely Cause                                           | What To Do                                                                                        |
| ------------------------------ | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| **Google Sign-In Rejected**    | Attempting sign-in using personal email (Gmail, Yahoo) | Sign out of personal Google account and sign in using your official `@amrolicollege.ac.in` email. |
| **"Account Inactive" Alert**   | Active Status set to Inactive by administrator         | Contact your System Administrator to request Active Status enablement.                            |
| **Dashboard Access Denied**    | Signed-in email has no registered StaffBridge profile  | If you are a new staff member, complete registration at `/staff/onboarding`.                      |
| **Admin Portal Access Denied** | Google account lacks Coordinator or Admin role         | Contact System Administrator to verify your role assignment in institutional settings.            |

***

## Verified Error Messages

* **Message:** _"Access restricted to official institutional domain."_\
  _&#x57;hat It Means:_ You selected a personal Google account during sign-in.\
  _&#x57;hat You Should Do:_ Select your official `@amrolicollege.ac.in` account on the Google authentication screen.

***

## Still Need Help?

If you continue to experience access difficulties after verifying your `@amrolicollege.ac.in` email, contact your designated System Administrator for assistance.

***

**Version:** Internal Preview v0.2 (Draft) | **Last Updated:** 06 August 2026 | **Applies To:** StaffBridge\
**Previous Step:** [← Troubleshooting Center](./) | **Next Step:** Troubleshoot Staff Onboarding →\
**Related Guides:** Getting Started with StaffBridge · Troubleshoot Staff Onboarding
