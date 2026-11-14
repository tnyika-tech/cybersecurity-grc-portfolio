# Cybersecurity Risk Register

## 1. Project Overview

This risk register assesses cybersecurity risks affecting Mzansi Digital Commerce (Pty) Ltd, a fictional South African online retailer selling consumer electronics.

The business relies on cloud-based systems, online payment processing, customer information, inventory management and third-party courier services.

## 2. Risk Scoring Methodology

Risk Score = Likelihood × Impact

| Score | Risk Rating |
|---|---|
| 1–4 | Low |
| 5–9 | Moderate |
| 10–16 | High |
| 17–25 | Critical |

## 3. Risk Register

| ID | Identified Risk | Business Impact | Likelihood | Impact | Score | Recommended Security Controls |
|---|---|---|---:|---:|---:|---|
| R001 | Phishing and compromised employee credentials | Unauthorised access to business systems and customer information | 4 | 4 | 16 | MFA, email filtering and security awareness training |
| R002 | Customer database breach | POPIA exposure, reputational damage and possible regulatory consequences | 3 | 5 | 15 | Encryption, access restrictions and database monitoring |
| R003 | Manipulation of prices, stock or orders | Financial losses, fraudulent transactions and customer disputes | 3 | 5 | 15 | RBAC, audit logs and transaction integrity controls |
| R004 | E-commerce platform outage | Lost sales and interrupted order fulfilment | 4 | 5 | 20 | Availability monitoring, redundancy and disaster recovery |
| R005 | Ransom ware infection | Business disruption and loss of access to operational data | 3 | 5 | 15 | EDR, patch management and protected backups |
| R006 | Third-party payment or cloud provider compromise | Interrupted transactions or exposure of business information | 3 | 5 | 15 | Supplier risk assessments and contractual security requirements |
| R007 | Backup failure | Permanent data loss and inability to restore operations | 3 | 5 | 15 | Isolated backups and scheduled restoration testing |
| R008 | Poor network segmentation | Attackers move from compromised systems into critical databases and cloud workloads | 4 | 5 | 20 | Network segmentation, private subnets and restrictive firewall rules |
| R009 | Malicious or counterfeit AI agents | Theft of credentials, sensitive information or unauthorised system activity | 3 | 5 | 15 | Approved AI services, least privilege and vendor security assessments |
| R010 | Excessive API permissions and exposed credentials | Unauthorised access through cloud integrations and automated agents | 3 | 5 | 15 | Secrets management, restricted API scopes and credential rotation |

## 4. Risk Treatment Priorities

**Critical risks**

- R004: E-commerce platform availability.
- R008: Network segmentation and prevention of lateral movement.

These risks require priority treatment because they could affect essential business operations and critical information assets.

**High risks**

R001–R003 and R005–R007, R009–R010 require documented treatment plans, assigned owners and ongoing monitoring.

## 5. Review and Monitoring

The risk register should be reviewed periodically and updated following significant business changes, security incidents, new vulnerabilities or changes in the threat environment.

Residual risk ratings should only be assigned after existing controls have been assessed and their effectiveness verified.

