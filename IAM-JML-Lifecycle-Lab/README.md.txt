# IAM Joiner-Mover-Leaver (JML) Lifecycle Lab

## Project Overview

This project demonstrates the complete Joiner-Mover-Leaver (JML) lifecycle within a Windows Active Directory environment, simulating how Identity & Access Management (IAM) teams provision, modify, and revoke user access throughout an employee's journey within an organization.

The lab combines business-driven IAM processes with Active Directory administration, PowerShell automation, Identity Governance, Role-Based Access Control (RBAC), audit logging, and documentation to reflect a realistic enterprise IAM workflow.

---

# Project Scenario

The fictional organization **corp.local** hired a new batch of employees across multiple business departments.

As the Identity & Access Management (IAM) Administrator, I was responsible for managing each stage of the employee lifecycle:

* Provisioning new employee accounts (Joiner)
* Updating access following approved internal transfers (Mover)
* Revoking access during employee offboarding (Leaver)

Every phase was supported with business requests, approvals, audit logs, documentation, and implementation evidence to simulate a real-world IAM environment.

---

# Technologies Used

* Windows Server
* Active Directory Domain Services (AD DS)
* Active Directory Users and Computers (ADUC)
* Windows PowerShell
* Role-Based Access Control (RBAC)

---

# Repository Structure

```text
IAM-JML-Lifecycle-Lab
│
├── Audit-Logs
│   ├── 01-Mover-Phase-Audit-Log.md
│   └── 02-Leaver-Phase-Audit-Log.md
│
├── Documentation
│   ├── 01-Joiner-Phase.md
│   ├── 02-Mover-Phase.md
│   └── 03-Leaver-Phase.md
│
├── Lifecycle-Requests
│   ├── 01-Employee-Transfer-Requests.md
│   ├── 02-Manager-Approvals.md
│   ├── 03-Termination-Requests.md
│   └── 04-HR-Offboarding-Approvals.md
│
├── Screenshots
│
└── README.md
```

---

# Project Phases

## 1. Joiner Phase

During the Joiner phase, a new batch of employees was onboarded into the Active Directory environment.

Activities completed included:

* Creating multiple Active Directory user accounts using PowerShell.
* Creating and validating departmental security groups.
* Assigning users to security groups based on their job roles.
* Verifying successful user provisioning and access assignment.
* Collecting screenshots and implementation evidence.

IAM concepts demonstrated:

* Identity Provisioning
* Active Directory Administration
* Role-Based Access Control (RBAC)
* Security Group Management
* PowerShell Automation

---

## 2. Mover Phase

The Mover phase simulated employees changing roles within the organization.

Approved transfer requests and management approvals were processed before access changes were implemented manually through Active Directory Users and Computers (ADUC).

Activities completed included:

* Reviewing approved transfer requests.
* Removing obsolete departmental access.
* Granting new role-based access.
* Verifying updated security group memberships.
* Recording audit logs for governance purposes.

IAM concepts demonstrated:

* Identity Lifecycle Management
* Identity Governance
* Access Modification
* Principle of Least Privilege
* Change Management
* Audit Readiness

---

## 3. Leaver Phase

The Leaver phase simulated employee offboarding following approved HR termination requests.

Activities completed included:

* Reviewing approved offboarding requests.
* Removing departmental security group memberships.
* Disabling user accounts using PowerShell.
* Verifying successful account disablement.
* Recording audit logs to support compliance and future audits.

IAM concepts demonstrated:

* Identity Deprovisioning
* Access Revocation
* Active Directory Administration
* Identity Governance
* PowerShell Automation
* Audit Compliance

---

# Key IAM Skills Demonstrated

* Identity Lifecycle Management (JML)
* Active Directory User Administration
* Identity Provisioning
* Identity Deprovisioning
* Role-Based Access Control (RBAC)
* Security Group Management
* Identity Governance
* Principle of Least Privilege
* PowerShell Automation
* Audit Documentation
* Access Verification
* Change Management

---

# Key Learning Outcomes

This project reinforced the importance of managing identities throughout their entire lifecycle rather than focusing solely on account creation.

It demonstrated how effective Identity & Access Management combines business processes with technical implementation through documented requests, approvals, access provisioning, access modification, secure offboarding, verification, and audit logging.

Completing this lab provided practical experience with enterprise IAM workflows while strengthening my understanding of governance, security, compliance, and lifecycle management within an Active Directory environment.

---

# Author

**Destiny Akhabue**

Aspiring Identity & Access Management (IAM) Analyst

Building hands-on IAM experience through practical enterprise lab projects focused on Active Directory, Microsoft Entra ID, PowerShell automation, Identity Governance, Privileged Access Management (PAM), and Identity Lifecycle Management.
