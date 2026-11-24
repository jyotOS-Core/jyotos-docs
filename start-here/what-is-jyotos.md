# What is JyotOS?

{% hint style="info" %}
**Guide Quick Facts**

* **Estimated Reading Time:** 3 minutes
* **Target Audience:** All Institutional Personnel, Faculty, and Staff Members
* **Applies To:** JyotOS Ecosystem
* **Last Updated:** 24 November 2026
{% endhint %}

Welcome to **JyotOS** — the integrated institutional management ecosystem for higher education institutions.

JyotOS brings together specialized software applications into a single, cohesive framework designed to support academic administration, staff governance, event operations, and campus workflows.

Rather than relying on a single rigid system, JyotOS connects focused applications that share verified institutional identity while preserving dedicated workflows for every academic and operational department.

***

## Core Architecture

The JyotOS ecosystem operates across three interconnected layers:

```
┌────────────────────────────────────────────────────────┐
│             Single Identity Authority                  │
│                    StaffBridge                         │
│  (Verified Staff Profile & Institutional Google SSO)   │
└──────────────────────────┬─────────────────────────────┘
                           │ Single Sign-On
                           ▼
┌────────────────────────────────────────────────────────┐
│             Institutional App Launcher                 │
│                   JyotOS Central                       │
│    (Application Directory, Access Requests, Theme)     │
└──────────────────────────┬─────────────────────────────┘
                           │ Launch & Delegated Roles
                           ▼
┌────────────────────────────────────────────────────────┐
│             Specialized Campus Applications            │
│  StaffBridge · EventOS · ClassPulse Pro · HiTECH LMS   │
└────────────────────────────────────────────────────────┘
```

1. **The Identity Authority (StaffBridge):** StaffBridge serves as the institutional system of record. Every staff member has a single verified profile tied to their official college Google account. StaffBridge verifies identity once, eliminating repeated logins.
2. **The Unified App Launcher (JyotOS Central):** Accessible at [https://jyotos.vercel.app](https://jyotos.vercel.app), Central is the unified starting page for campus staff. Central displays accessible applications, presents discoverable locked tools, and manages access requests.
3. **Independent Ecosystem Applications:** Each campus tool—such as StaffBridge for staff rosters, EventOS for academic events, and ClassPulse Pro for academic timetables—operates with its own database and internal permissions.

***

## Key Principles

* **Sign in Once:** Use your official college Google account (`@amrolicollege.ac.in`) across all supported JyotOS applications.
* **Independent Authorization:** Gaining access in JyotOS Central lets you launch an application, but administrative roles inside that application (such as Coordinator or Evaluator) are managed within that specific tool.
* **Progressive Rollout:** Institutional applications are rolled out in structured phases. Core applications are available today, with additional tools joining the ecosystem progressively.
* **Data Privacy:** Applications exchange only necessary, verified identity claims. Personal contact numbers and sensitive records remain private.

***

## Who Uses JyotOS?

* **Faculty & Staff Members:** Launch everyday tools, review personal rosters, and participate in academic operations.
* **Department Coordinators & Heads of Department:** Manage department queues, review staff records, and coordinate events.
* **Institutional Leadership:** Maintain governance and cross-department operational visibility.
* **System Administrators:** Manage application registries, access audiences, and institutional audit logs.

***

## Next Steps

To begin using the JyotOS ecosystem:

1. Learn how authentication works in [Sign in once](sign-in-once.md).
2. Discover your accessible applications in [The app launcher](the-app-launcher.md).
3. Follow the 5-minute onboarding guide in [Your first 5 minutes](your-first-5-minutes.md).

***

**Last Updated:** 24 November 2026 | **Applies To:** JyotOS Ecosystem\
**Previous Step:** [← Welcome to JyotOS Help Center](../README.md) | **Next Step:** [Sign in once →](sign-in-once.md)\
**Related Guides:** [The app launcher](the-app-launcher.md) · [Your first 5 minutes](your-first-5-minutes.md) · [Getting help](getting-help.md)
