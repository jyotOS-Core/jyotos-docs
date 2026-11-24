# JDDS-001: JyotOS Documentation Design System

{% hint style="info" %}
**Guide Quick Facts**

* **Estimated Reading Time:** 15 minutes
* **Target Audience:** Lead Documentation Engineers, Product Architects, Technical Authors, and AI Subagents
* **Applies To:** All JyotOS Ecosystem Applications (StaffBridge, EventOS, Leave, Attendance, Admissions, Library, etc.)
* **Last Updated:** 05 August 2026 | **Version:** Internal Preview v0.1 | **Difficulty:** Architecture Level
{% endhint %}

The **JyotOS Documentation Design System (JDDS-001)** establishes the permanent, non-negotiable architectural standards for all technical and user-facing documentation across the JyotOS ecosystem. Every current and future JyotOS application must comply with this design system to ensure a unified user experience.

***

## 1. Purpose

The purpose of JDDS-001 is to guarantee that every documentation page across the JyotOS ecosystem maintains exceptional quality, seamless navigation, low cognitive load, and visual harmony. Whether a user reads documentation for StaffBridge, EventOS, or Leave Management, the structure, tone, visual presentation, and terminology must feel like part of one cohesive software product.

***

## 2. Documentation Philosophy

1. **Documentation is Part of the Product:** Documentation is treated as a core product feature, not an afterthought.
2. **User-Centric Design:** Written to solve real institutional tasks for non-technical users.
3. **Support Overhead Reduction:** Clear, proactive documentation eliminates preventable IT helpdesk tickets.
4. **Continuous Evolution:** Documentation evolves synchronously with software releases and user feedback.
5. **Strict Versioning:** Every document tracks its version, applicability, and revision date.

***

## 3. Documentation Types & Classification

| Document Type           | Primary Objective                                          | Target Audience       |
| ----------------------- | ---------------------------------------------------------- | --------------------- |
| **Welcome / Landing**   | Portal introduction and main navigation hubs               | All Users             |
| **Overview**            | Product purpose, user roles, and ecosystem fit             | New Users, Executives |
| **Getting Started**     | Fast-path onboarding checklists and high-level flows       | New Users             |
| **User Guide**          | Detailed step-by-step task procedures                      | Institutional Staff   |
| **Administrator Guide** | Roster verification, queue management, and system rules    | Coordinators & Admins |
| **Troubleshooting**     | Self-service resolution of status flags and system alerts  | All Users             |
| **FAQ**                 | Direct answers to frequently asked institutional questions | All Users             |
| **Release Notes**       | Version history, updates, and feature changes              | All Users             |

***

## 4. Standard Page Structure

Every documentation page in the JyotOS ecosystem must follow this exact structural sequence:

1. **Title (H1):** Clear, search-optimized title.
2. **Guide Quick Facts:** Standardized callout block at the top.
3. **Introduction / Executive Summary:** 1–2 short paragraphs introducing the topic.
4. **Before You Begin:** Checklist of prerequisites (if applicable).
5. **Step-by-Step Instructions:** Numbered procedures with clear action steps.
6. **Important Notes & Warnings:** Styled GitBook callouts (`hint`).
7. **Next Step & Related Guides:** Navigation cards and Markdown links.
8. **Metadata Footer:** Horizontal rule with version, update date, and applicability.

***

## 5. Guide Quick Facts Standard

Near the top of every page, authors must include the standard **Guide Quick Facts** callout block:

```markdown
{% hint style="info" %}
**Guide Quick Facts**  
* **Estimated Reading Time:** [X] minutes  
* **Target Audience:** [Roles]  
* **Applies To:** [Application / Module]  
* **Last Updated:** [Date] | **Version:** Internal Preview v0.1  
{% endhint %}
```

***

## 6. Writing Style Guide

* **Tone:** Professional, encouraging, authoritative, and instructional.
* **Paragraph Length:** Maximum 3–4 sentences per paragraph.
* **Heading Style:** Title Case for H1; Sentence case for H2 and H3.
* **Preferred Terminology:** Use action verbs (e.g. _Completing Onboarding_, _Submitting Updates_).
* **Forbidden Terminology:** Avoid internal developer jargon (e.g. _Supabase_, _SQL_, _API endpoints_, _Base64_, _RLS_).

***

## 7. Official Terminology Standard

To maintain institutional consistency, all documentation must adhere strictly to the following approved brand terms:

| Official Term              | Forbidden Variations (DO NOT USE)        |
| -------------------------- | ---------------------------------------- |
| **JyotOS**                 | jyotOS, Jyot-OS, JYOTOS                  |
| **StaffBridge**            | Staff Bridge, staffbridge, Staff-Bridge  |
| **JyotOS Help Center**     | Helpcenter, JyotOS Docs, Knowledge Base  |
| **Department Coordinator** | Dept Coordinator, Coordinator, Dept Head |
| **System Administrator**   | Admin, Superuser, IT Guy, Sysadmin       |
| **Staff Reference ID**     | Ref No, Staff Code, Application ID       |
| **Profile Status**         | State, Onboarding Status, User Flag      |

***

## 8. Navigation & Cross-Linking Rules

* **Linear Journeys:** Every series of guides must provide a clear `Previous Step` and `Next Step` link at the bottom.
* **Bidirectional Links:** If Page A links to Page B, Page B must reference Page A in its `Related Guides` footer.
* **Relative Paths:** Always use clean relative Markdown paths (e.g. `./getting-started` or `../about-jyotos`).

***

## 9. GitBook Design Standards

* **Cards (`{% cards %}`):** Use grids of cards for section indexes and recommended next steps.
* **Callouts (`{% hint %}`):** Use `info` for tips, `warning` for strict requirements, `success` for completions.
* **Tables:** Use markdown tables only for comparative data or multi-column mappings.
* **Tabs & Expandable Blocks:** Use sparingly for advanced options to avoid hiding critical steps.

***

## 10. Screenshot Standards

When UI screenshots are captured for documentation:

* **Placeholder Format:** `📷 Screenshot Placeholder — Description: [Text] | Required View: [View] | Masking Required: [Yes/No]`
* **Masking Rules:** Always mask real personal email addresses, phone numbers, and private IDs.
* **Alt-Text:** Provide descriptive captions for accessibility tools.

***

## 11. Visual Design Rules

* **Spacing:** Insert horizontal rules (`---`) between major topic sections.
* **Lists:** Use numbered lists (`1.`, `2.`) for sequential steps; bulleted lists (`*`) for un-ordered options.
* **Emojis:** Limit emoji usage to standard GitBook icons and functional indicator symbols (e.g. 📷, ❌, 🟢).

***

## 12. Accessibility Standards

* **Reading Level:** Plain English suitable for non-technical institutional staff (Grade 8–10 reading level).
* **Text Contrast:** Ensure high contrast against light backgrounds.
* **Keyboard Navigation:** Structure headings hierarchically (H1 ➔ H2 ➔ H3) to support screen readers.

***

## 13. Documentation Lifecycle (12 Stages)

```
1. App Development ──► 2. Audit ──► 3. Source Pack ──► 4. Foundation ──► 5. User Guide ──► 6. DQR Review
                                                                                               │
                                                                                               ▼
12. Maintenance ◄── 11. Publish ◄── 10. Release Notes ◄── 9. FAQ ◄── 8. Troubleshooting ◄── 7. Admin Guide
```

***

## 14. Versioning Policy

* **Major Versions (1.0, 2.0):** Applied when major application workflows or user interfaces change.
* **Minor Versions (1.1, 1.2):** Applied when minor field updates or clarifying instructions are added.
* **Deprecation Notice:** Deprecated guides must feature a prominent warning callout directing users to current guides.

***

## 15. Pre-Publication Review Checklist

Before any documentation page is approved for publishing, it must pass this 10-point checklist:

* [ ] **Quick Facts:** Header block present with all required fields.
* [ ] **Navigation:** Valid `Previous Step`, `Next Step`, and `Related Guides` links.
* [ ] **Terminology:** Verified against Official Terminology Table.
* [ ] **No Developer Jargon:** Free of internal technical implementation details.
* [ ] **Screenshots:** Valid placeholders or masked screenshots with captions.
* [ ] **Formatting:** Clean markdown hierarchy with zero text walls.
* [ ] **Searchability:** Action-oriented titles and section headings.
* [ ] **Accessibility:** Low cognitive load, clear lists, and valid alt-text.
* [ ] **Footer:** Standardized metadata footer present.
* [ ] **Completeness:** All steps verified against actual application behavior.

***

## 16. Future AI Workflow Rules

AI assistants and subagents operating within the JyotOS documentation workspace:

* **May:** Draft pages, suggest structural improvements, refactor markdown, format tables, and perform DQR reviews.
* **Must NOT:** Invent unverified features, expose secrets/credentials, execute automatic site publishing, or alter verified facts.

***

## 17. JDDS Pre-Publication Compliance Checklist

Use this checklist for evaluating future JyotOS application documentation:

* [ ] Section parent page created with grid cards.
* [ ] Quick Facts header block present on every page.
* [ ] 100% compliance with Brand Terminology standard.
* [ ] Linear step-by-step navigation active.
* [ ] Clean DQR score (10/10 across all metrics).

***

## 18. Standard Reusable Templates

### Template 1: User Guide Page

```markdown
# [Action-Oriented Page Title]

{% hint style="info" %}
**Guide Quick Facts**  
* **Estimated Reading Time:** [X] minutes  
* **Target Audience:** [Audience]  
* **Applies To:** [Application]  
* **Last Updated:** [Date] | **Version:** Internal Preview v0.1  
{% endhint %}

[Brief introductory summary of the task]

---

## Before You Begin

* [ ] [Prerequisite 1]
* [ ] [Prerequisite 2]

---

## Step-by-Step Instructions

### Step 1: [First Action]
[Detailed instruction step]

---

**Version:** Internal Preview v0.1 | **Last Updated:** [Date] | **Applies To:** [Application]  
**Previous Step:** [← Previous Guide](./prev) | **Next Step:** [Next Guide →](./next)  
**Related Guides:** [Related Guide 1](./rel1) · [Related Guide 2](./rel2)
```

***

**Version:** Internal Preview v0.1 | **Last Updated:** 05 August 2026 | **Applies To:** JyotOS Ecosystem\
**Previous Step:** [← Documentation Standards](./) | **Next Step:** Return to Help Center Homepage\
**Related Guides:** [Documentation Standards](./) · Welcome to JyotOS Help Center
