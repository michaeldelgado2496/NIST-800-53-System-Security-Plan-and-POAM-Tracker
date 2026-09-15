# Plan of Action and Milestones (POA&M) Log

## Overview
This log tracks identified security weaknesses, associated risk levels, corrective action plans, and milestone target dates for the Mango Digital Banking platform.

---

## Active POA&M Entries

| POA&M ID | Control ID | Weakness Description | Risk Level | Corrective Action Plan (CAP) | Milestone Date | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **POA&M-01** | SC-13 | Legacy TLS 1.0/1.1 protocols still enabled on secondary edge proxy. | High | Disable legacy protocols and enforce TLS 1.3 exclusively across all endpoints. | 2026-9-3 | Open |
| **POA&M-02** | AC-2 | Service accounts missing mandatory quarterly manual access reviews. | Moderate | Implement automated tracking and schedule recurring quarterly reviews in Okta. | 2026-9-26 | Open |
