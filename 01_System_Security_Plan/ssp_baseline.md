# System Security Plan (SSP) - Baseline

## 1. System Overview
* **System Name:** Gecko Digital Banking & Ledger Platform
* **System Identifier:** SYS-BANK-01
* **FIPS 199 Categorization:** 
  * Confidentiality: Medium
  * Integrity: High
  * Availability: High
  * Overall Impact: High

## 2. System Environment & Boundaries
* **Boundary Definition:** Includes AWS cloud infrastructure, EC2 application instances, RDS PostgreSQL database, and Okta identity provider integration.
* **Network Architecture:** Segmented into public-facing load balancers, private application subnets, and isolated database subnets.

## 3. Core NIST SP 800-53 Control Families

### Access Control (AC)
* **AC-2 (Account Management):** Centralized provisioning and de-provisioning through AzureAD. Quarterly access reviews are mandatory.
* **AC-7 (Unsuccessful Login Attempts):** Accounts automatically lock after 2 consecutive failed attempts within a 5-minute window.

### Identification & Authentication (IA)
* **IA-2 (Identification and Authentication - Organizational Users):** Multi-factor authentication (MFA) via authenticator apps is enforced for all administrative and user sessions.

### System and Communications Protection (SC)
* **SC-13 (Cryptographic Protection):** All data at rest is encrypted using AES-256. Data in transit is protected using TLS 1.3.
