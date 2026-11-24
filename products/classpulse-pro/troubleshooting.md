# ClassPulse Pro Troubleshooting

{% hint style="info" %}
**Quick Facts**
* **Audience:** Faculty members, Department Coordinators, Principal, Administrators
* **Applies To:** ClassPulse Pro (Diagnostic & Operational Support)
* **Escalation Hierarchy:** Instructor → Department Coordinator → Principal → Administrator
{% endhint %}

This guide provides troubleshooting solutions for common questions and operational scenarios encountered while using ClassPulse Pro.

---

## Common Operational Scenarios

### 1. Sign-In Rejected or Password Not Accepted
* **Symptom:** Entering your college email and password displays an authentication error.
* **Likely Cause:** Typographical error in credentials, or your account has not yet been assigned to the pilot staff roster.
* **Resolution:**
  1. Confirm you are entering your official college email ending in `@amrolicollege.ac.in`.
  2. Verify your pilot password carefully (passwords are case-sensitive).
  3. If your password continues to fail, contact your System Administrator to reset your pilot credentials.

---

### 2. "Your Timetable is Not Linked Yet" Notice
* **Symptom:** On **My Teaching Portal**, a notice indicates your profile is not linked to the master timetable.
* **Likely Cause:** Your instructor profile in the system has not yet been mapped to your assigned teaching slots in the master timetable spreadsheet.
* **Resolution:**
  1. You can continue logging daily classroom sessions and topics in your diary; your entries are stored.
  2. Contact your Department Coordinator with your name and assigned course codes.
  3. The coordinator will verify your timetable mappings so that your weekly load and delivery percentages calculate accurately.

---

### 3. Top Navigation Bar Displays "Syncing DB..."
* **Symptom:** When clicking month buttons (June 15–30, July, August, or Term to Date), the top navigation bar briefly displays a pulsing `Syncing DB...` indicator.
* **Explanation:** **This is normal system behavior.** ClassPulse Pro calculates delivery metrics dynamically by querying live database logs for your chosen date range and subtracting non-working calendar days. The indicator confirms that live numbers are being refreshed.
* **Resolution:** No action is needed. The indicator returns to `Live Sync` once calculations conclude.

---

### 4. Cross-Division Course Displays a Spread Alert
* **Symptom:** On the **Subject Division Matrix**, a course displays an alert badge (e.g., `Parity: 62% (±5 lecs)`).
* **Likely Cause:** One division has conducted significantly fewer sessions than its parallel division, often due to weekday holidays falling unevenly on specific timetable slots or unrescheduled instructor leaves.
* **Resolution:**
  1. Click **Compare** on the course card to review conducted sessions and syllabus topics for each division side by side.
  2. Click **Notice** to generate an Equalization Directive specifying the current pacing gap.
  3. Coordinate with the assigned instructor to schedule compensatory lectures for the lagging division before exam preparation weeks.

---

### 5. Dual-Contract Instructor Shows Combined Weekly Load
* **Symptom:** An instructor teaching in both BBA and M.Com EM shows a weekly load higher than a single department schedule.
* **Explanation:** This is by design. For instructors holding teaching assignments across multiple departments, ClassPulse Pro links timetable allocations from all assigned programs (e.g., 12 periods in BBA + 6 periods in M.Com = 18 periods per week).
* **Resolution:** All conducted sessions logged in either department count toward the instructor's combined teaching target.

---

### 6. Cannot Find B.Sc Data Science Courses Under BCA
* **Symptom:** A coordinator searching for Data Science subjects cannot find them in the BCA division listing.
* **Explanation:** B.Sc Data Science operates at Chaprabhatha Campus as an independent degree stream. Although both programs belong to computer studies, they are maintained as separate discipline streams to prevent artificial cohort grouping.
* **Resolution:** Select **B.Sc Data Science** from the department dropdown filter to view its dedicated course matrix.

---

## Support Escalation

If an operational issue cannot be resolved using these steps, escalate through the institutional hierarchy:

```
Teaching Faculty ──► Department Coordinator ──► College Principal ──► System Administrator
```

* **Faculty Members:** Contact your Department Coordinator for timetable mapping and session logging questions.
* **Coordinators:** Contact the College Principal for pacing directives, or the System Administrator for user permissions and master timetable uploads.
