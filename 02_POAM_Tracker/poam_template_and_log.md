# Plan of Action and Milestones (POA&M) Log

## Overview
This document tracks known security weaknesses, vulnerabilities, and compliance gaps identified during system assessments, along with their assigned remediation milestones.

## Active POA&M Entries

### POA&M ID: POA&M-2026-01
* **Weakness Description:** Legacy service accounts lack automated rotation policies for access keys.
* **NIST Control Identifier:** AC-2 (Account Management)
* **Risk Level:** Moderate
* **Point of Contact:** IT Security Operations
* **Corrective Action Plan:** Implement automated secret rotation via AWS Secrets Manager for all internal service credentials.
* **Scheduled Completion Date:** 2026-11-30
* **Status:** Ongoing

### POA&M ID: POA&M-2026-02
* **Weakness Description:** Annual disaster recovery and backup restoration tests have not been formally documented or executed.
* **NIST Control Identifier:** CP-9 (Information System Backup)
* **Risk Level:** High
* **Point of Contact:** Infrastructure Team
* **Corrective Action Plan:** Schedule and execute a full database backup restoration test and document the recovery time objective (RTO) metrics.
* **Scheduled Completion Date:** 2026-10-15
* **Status:** Open
