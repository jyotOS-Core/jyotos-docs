# Communications

{% hint style="info" %}
**Quick Facts**
* **Audience:** System Administrators
* **Applies To:** StaffBridge
* **Provider:** Resend email service
* **Daily Limit:** 100 emails per day safety quota
{% endhint %}

The **Communications** section (Notification Center) provides administrators with tools to send transactional notifications and announcements to staff members.

---

## Accessing the Notification Center

Select **Communications** from the administrator menu to open the Notification Center.

---

## Daily Delivery Quota

To ensure reliable email delivery and prevent unintended broadcast spam, StaffBridge enforces a strict safety limit:

* **Daily Quota:** 100 emails per 24-hour rolling window.
* **Quota Meter:** The interface displays the current daily quota usage and remaining email balance in real time.
* **Delivery Provider:** Emails are dispatched through the institutional Resend delivery integration.

{% hint style="warning" %}
**Quota Management**
If the 100-email threshold is reached, additional outgoing emails will be queued until the quota resets. Plan large communications across multiple distribution windows.
{% endhint %}

---

## Notification Templates

StaffBridge includes pre-configured transactional email templates:

1. **Verification Complete:** Notifies a staff member when their profile has achieved final **Admin Verified** status and their identity record is Ready.
2. **Correction Reminder:** Sends a prompt to staff members whose profiles are currently in **Needs Correction** status, detailing the remaining required actions.
3. **JyotOS Ecosystem Ready:** Informs verified personnel that their institutional account is active and ready for single sign-on access across connected JyotOS applications.
4. **General Announcement:** Allows administrators to draft a custom institutional message to a filtered group of staff members.

---

## Sending a Notification Campaign

1. Open the **Communications** section.
2. Select the desired email template from the template selector.
3. Choose the recipient group by applying filters (e.g. by status, department, or campus).
4. Review the recipient list and verify that the count fits within your remaining daily quota.
5. Preview the email message content.
6. Click **Send Campaign** to initiate dispatch.
7. Monitor the delivery status log to confirm successful delivery.
