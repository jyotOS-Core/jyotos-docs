# JyotOS Central Troubleshooting

{% hint style="info" %}
**Guide Quick Facts**

* **Estimated Reading Time:** 4 minutes
* **Target Audience:** All Institutional Personnel, Faculty, and System Administrators
* **Applies To:** JyotOS Central (https://jyotos.vercel.app)
* **Last Updated:** 24 November 2026
{% endhint %}

This guide details resolutions for common alerts and operational issues encountered when using JyotOS Central.

***

## Common Sign-In & Access Issues

### 1. Alert: "Sign-in Denied" or Access Refused

* **Symptoms:** After authenticating with Google, you are redirected back to the login page with an alert stating access was denied.
* **Cause:** Your staff profile in StaffBridge is not in an active or admin-verified status, or you used an unapproved email address.
* **Resolution Steps:**
  1. Confirm you selected your official `@amrolicollege.ac.in` Google account, not a personal email address.
  2. Log in directly to **StaffBridge** to check your profile status.
  3. Ensure your profile completion status is **Furnished** and verification status is **Admin Verified**.
  4. If your profile is pending review or requires corrections, contact your Department Coordinator.

### 2. Alert: "Session Expired" or Sign-In Timeout

* **Symptoms:** The browser indicates the sign-in attempt timed out or failed to complete.
* **Cause:** The authorization window remained idle longer than the allowable handshake period (90 seconds).
* **Resolution Steps:**
  1. Return to [https://jyotos.vercel.app](https://jyotos.vercel.app).
  2. Click **Sign in with College Account** to initiate a fresh session.
  3. Complete Google authentication promptly without leaving the tab idle.

### 3. Application Card Displays a Padlock (Locked Tile)

* **Symptoms:** An application appears on your dashboard, but its card shows a lock badge and cannot be opened directly.
* **Cause:** The application's audience is set to "Granted only" or "Pilot staff," and your account has not yet received an active grant.
* **Resolution Steps:**
  1. Click on the locked card.
  2. Enter a brief note stating your institutional requirement in the request dialog.
  3. Click **Submit Request**.
  4. Once an institutional administrator reviews and approves your request, the card will unlock automatically.

### 4. Display Theme Resets to Default

* **Symptoms:** You selected Dark or Light theme previously, but the portal reverted to Auto mode.
* **Cause:** Themes are stored in your browser's local device storage. Clearing browser cache or signing in from a new device resets preferences to default.
* **Resolution Steps:**
  1. Open the user menu at the top right of the navigation bar.
  2. Re-select your preferred theme (**Light** or **Dark**).
  3. The setting is saved immediately on that device.

### 5. Application Card Fails to Open in New Tab

* **Symptoms:** Clicking an active application card does nothing or a blank page appears.
* **Cause:** Your browser's pop-up blocker may have prevented opening a new tab, or the destination service is temporarily unreachable.
* **Resolution Steps:**
  1. Check your browser address bar for a blocked pop-up icon and select **Always allow pop-ups from jyotos.vercel.app**.
  2. Refresh your browser page and click the application card again.
  3. If the destination application displays a maintenance screen, check with your IT helpdesk.

### 6. Name or Department Displays Outdated Information

* **Symptoms:** Your display name or department in Central does not match your current college assignment.
* **Cause:** Central displays read-only identity data synchronized from StaffBridge.
* **Resolution Steps:**
  1. Update your employment or personal records in StaffBridge.
  2. Once your coordinator and administrator verify the changes in StaffBridge, log out of Central and sign back in to refresh the displayed data.

***

## Still Need Assistance?

If these steps do not resolve your problem:

* Review the [Central Frequently Asked Questions](faq.md).
* Consult the [Getting Help Guide](../../start-here/getting-help.md) for institutional escalation contacts.
* Share unexpected behavior via the [Feedback & Suggestions](../../feedback-and-suggestions.md) page.

***

**Last Updated:** 24 November 2026 | **Applies To:** JyotOS Central\
**Previous Step:** [← Central Administrator Guide](administrator-guide.md) | **Next Step:** [Central FAQ →](faq.md)\
**Related Guides:** [Central Overview](overview.md) · [Central Staff Guide](staff-guide.md) · [Getting help](../../start-here/getting-help.md)
