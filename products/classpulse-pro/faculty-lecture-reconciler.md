# Faculty Lecture Reconciler in ClassPulse Pro

{% hint style="info" %}
**Quick Facts**
* **Audience:** Department Coordinators, College Principal, System Administrators
* **Applies To:** ClassPulse Pro (Faculty Workload Reconciliation)
* **Scope:** Individual instructor contract commitments versus conducted classroom sessions
{% endhint %}

The **Faculty Lecture Reconciler** is the institutional workload review workstation of ClassPulse Pro. It compares contracted weekly timetable commitments against actual conducted sessions logged in teacher diaries, providing an objective evaluation of workload delivery.

---

## Reconciliation Calculations

The reconciler calculates expected hours and delivery variances using transparent mathematical principles:

### 1. Expected Hours Calculation
Expected teaching hours depend on the instructor's contracted weekly load and the number of active instructional days in the selected date window:

$$\text{Expected Hours} = \left( \frac{\text{Weekly Timetable Load}}{6} \right) \times \text{Institutional Working Days}$$

* *Example:* For a professor with a 18-period weekly load evaluated over 21 working days:
  $$(18 / 6) \times 21 = 3.0 \times 21 = 63\text{ Expected Hours}$$

### 2. Workload Variance
The variance measures the difference between actual conducted sessions and calculated expected hours:

$$\text{Workload Variance} = \text{Actual Conducted Sessions} - \text{Expected Hours}$$

### 3. Individual Delivery Rate
The individual delivery percentage measures overall performance relative to target:

$$\text{Delivery Rate} = \left( \frac{\text{Actual Conducted Sessions}}{\text{Expected Hours}} \right) \times 100$$

---

## Status Classifications

ClassPulse Pro automatically categorizes each instructor's delivery performance:

| Status Class | Delivery Threshold | Visual Indicator | Recommended Action |
| :--- | :--- | :--- | :--- |
| **On Track** | $\ge 85\%$ Delivery Rate | Green (Emerald) | Meets institutional delivery benchmarks. No special action needed. |
| **Deficit** | $70\% - 84.9\%$ Delivery Rate | Amber | Mild pacing lag. Review during monthly departmental meetings. |
| **Critical Deficit** | $< 70\%$ Delivery Rate | Red (Rose) | Significant delivery gap. Requires a structured makeup timetable. |
| **Surplus** | $> 100\%$ Delivery Rate | Blue (Cyan) | Instructor conducted additional tutorial or substitute hours. |

---

## Special Faculty Categories

The reconciler accommodates diverse institutional staffing models:

### 1. Dual-Contract Faculty
Instructors who teach across multiple degree programs (such as teaching courses in both BBA and M.Com EM) are identified with a **Dual Contract** badge:

* **Consolidated Timetable Allocation:** The system links timetable slots across all authorized departments (e.g., 12 periods in BBA + 6 periods in M.Com = 18 periods per week).
* **Unified Target:** All conducted sessions logged across either program contribute toward the instructor's unified teaching target.

### 2. Visiting Faculty
Visiting lecturers and industry experts who do not hold fixed weekly timetable contracts are tagged with a **Visiting** badge:

* Their activity is tracked based on logged sessions and topics covered.
* Because they do not have fixed weekly hours, they are evaluated on conducted sessions rather than fixed deficit benchmarks.

---

## Step-by-Step Instructions

### Step 1: Selecting the Evaluation Window
1. In the **Date Tracker Bar**, choose a preset month (e.g., June 15–30, July, August) or Term to Date.
2. The system calculates effective working days by excluding Sundays and recognized college holidays.
3. Target hours for all instructors update immediately.

### Step 2: Searching and Filtering the Roster
1. Use the search field to find instructors by name, subject, or division.
2. Switch between **Card View** and **Table View** to scan or sort by weekly load, conducted sessions, or delivery rate.
3. Identify instructors marked with **Deficit** or **Critical Deficit** to review required makeup hours.

### Step 3: Inspecting Session Details
1. Click **View Details & Syllabus** on any instructor row.
2. In the modal, review the chronological session list, timetable slot matches, and recorded curriculum topics.
3. Verify whether substitute or extra sessions have been appropriately logged.
