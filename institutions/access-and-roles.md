# Institutional Access Model & Roles

{% hint style="info" %}
**Quick Facts**
* **Audience:** System Administrators, Institutional Leadership, Department Coordinators
* **Applies To:** Access Governance Across JyotOS Applications
* **Model:** Centralized application access with application-managed roles
{% endhint %}

JyotOS implements a role-based access framework across its connected applications, ensuring users only access features appropriate to their institutional responsibilities.

---

## Key Roles Across the Ecosystem

The JyotOS ecosystem recognizes four primary tiers of institutional users:

| User Tier | Key Responsibilities | Primary Applications |
| :--- | :--- | :--- |
| **Faculty & Staff** | Complete profile onboarding, browse and register for events, maintain teaching diary | StaffBridge, EventOS, ClassPulse Pro, Central |
| **Department Coordinators & HODs** | Review departmental staff onboarding, propose campus events, oversee department academic delivery | StaffBridge, EventOS, ClassPulse Pro, Central |
| **Principal & Campus Leadership** | Review campus-wide academic metrics, approve proposed events, oversee institutional operations | EventOS, ClassPulse Pro, Central |
| **System Administrators** | Manage Central catalog, grant application access, verify staff profiles, configure venue settings | Central, StaffBridge, EventOS, ClassPulse Pro |

---

## JyotOS Central Access Management

JyotOS Central controls user entry into individual ecosystem applications:

* **Access Granted per Person:** Administrators can provision application access directly to specific staff member accounts.
* **Target Audience Provisioning:** Applications can be granted collectively to predefined groups based on campus or department criteria.
* **Self-Service Access Requests:** When a staff member needs access to an unassigned tool, they can click **Request Access** on the application card in Central. Administrators review and approve these requests from the administration dashboard.
* **Central Platform Roles:** Users are assigned platform roles within Central (such as Platform Administrator or Staff) that determine administrative capabilities within the launcher itself.

---

## Pilot Phase vs Campus-Wide Rollout

Institutions often deploy new applications through progressive phases:

* **Pilot Staff Groups:** Initial access is granted to designated pilot coordinators and faculty members to validate workflows and review configurations. For example, ClassPulse Pro currently operates with pilot credentials for participating departments.
* **Campus-Wide Deployment:** Following pilot validation and administrator verification, application access is extended across all academic and administrative departments.

---

## Related Documentation

* [Guides by Role](../guides/staff.md) - Role-specific workflows for staff, coordinators, principals, and administrators
* [Central Administrator Guide](../products/central/administrator-guide.md) - Managing applications and access requests
* [StaffBridge Administrator Guide](../products/staffbridge/administrator-guide.md) - Profile verification and roster management
