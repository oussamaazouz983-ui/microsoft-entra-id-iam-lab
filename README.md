<div align="center">

# 🔐 Microsoft Entra ID – IAM Hands-On Lab

### Student Hands-On Identity & Access Management Lab

Microsoft Entra ID • Identity Management • Authentication • Authorization • Security • Governance

<br>

![Microsoft Entra ID](https://img.shields.io/badge/Microsoft%20Entra%20ID-0078D4?style=for-the-badge&logo=microsoft)
![IAM](https://img.shields.io/badge/Identity%20%26%20Access%20Management-6A1B9A?style=for-the-badge)
![Cloud Security](https://img.shields.io/badge/Cloud%20Security-00A4EF?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=for-the-badge)

</div>

---

## 🎯 Project Overview

This repository documents my **hands-on learning and lab practice** with **Microsoft Entra ID** and **Identity & Access Management (IAM)**.

The project is part of my development as a **Computer Science Engineering student**, with a particular interest in **cloud infrastructure, cybersecurity, and IAM**.

The goal is to build practical understanding of:

- Identity management
- Authentication and MFA
- Authorization and RBAC
- Conditional Access
- Identity governance
- Privileged access
- Enterprise applications and SSO
- Identity monitoring
- IAM automation

> This is a personal learning laboratory designed to develop practical skills and document my progress. It does not represent production enterprise experience.

---



<div align="center">



</div>

---

## 🎯 Objectives

<table>
<tr>
<td width="50%">

### 🔐 Identity & Security

- 👤 User and group management
- 🔑 Authentication methods
- 🔐 Multi-Factor Authentication (MFA)
- 🔄 Self-Service Password Reset (SSPR)
- 🛡️ Conditional Access
- 🔒 Least-privilege access

</td>

<td width="50%">

### 🏢 IAM & Governance

- 🎭 Role-Based Access Control (RBAC)
- 👑 Privileged Identity Management (PIM)
- 🔄 Access Reviews
- 📦 Enterprise Applications
- 🔗 Single Sign-On (SSO)
- 📊 Identity monitoring and auditing

</td>
</tr>
</table>

---

## 🏆 Microsoft Applied Skills

### Get started with identities and access using Microsoft Entra

I successfully completed the **Microsoft Applied Skills** assessment for Microsoft Entra identity and access.

| Credential | Details |
|---|---|
| 🏢 Issuer | Microsoft |
| 📅 Earned | July 7, 2026 |
| 🔗 Credential | Online Verifiable |
| 🟢 Status | Completed |

<br>

<div align="center">

![Microsoft Applied Skills Credential](https://github.com/user-attachments/assets/07c7a3f5-7d20-4cb2-9799-ba7010ee5361)

</div>

---

# 🧪 Lab Topics

<table>
<tr>
<td width="33%">

### 👤 Identity Management

- Users
- Groups
- Security Groups
- Administrative Units
- Dynamic Groups
- User Lifecycle
- Group Naming Policies

</td>

<td width="33%">

### 🔐 Authentication

- MFA
- Authentication Methods
- SSPR
- Password Policies
- Sign-in Security
- Identity Protection

</td>

<td width="33%">

### 🛡️ Access Control

- RBAC
- Role Assignments
- Built-in Roles
- Custom Roles
- Least Privilege
- Administrative Scopes

</td>
</tr>

<tr>
<td>

### 🚦 Conditional Access

- CA Policies
- MFA Enforcement
- User Targeting
- Application Targeting
- Device Conditions
- Location Conditions

</td>

<td>

### 👑 Privileged Access

- PIM
- Eligible Roles
- Just-in-Time Access
- Role Activation
- Approval Workflows
- Privileged Monitoring

</td>

<td>

### 🏢 Enterprise Applications

- Enterprise Apps
- App Registrations
- SSO
- SAML
- OAuth 2.0
- OpenID Connect

</td>
</tr>

<tr>
<td>

### 🔄 Identity Governance

- Access Reviews
- Access Packages
- Entitlement Management
- Lifecycle Workflows
- Access Certification

</td>

<td>

### 📊 Monitoring

- Sign-in Logs
- Audit Logs
- Authentication Logs
- Security Monitoring
- Troubleshooting

</td>

<td>

### ⚙️ Automation

- Microsoft Graph API
- Graph Explorer
- PowerShell
- Azure CLI
- IAM Automation
- Reporting

</td>
</tr>
</table>
# 🧪 Hands-On IAM Scenarios

The laboratory is designed around realistic enterprise Identity & Access Management scenarios.

---

## 👤 1. User Lifecycle Management

### 🔄 Identity Lifecycle

**New Employee → Create Identity → Assign Groups → Assign Applications → Apply Security Policies → Enable MFA → Monitor Sign-In Activity**

### Key Activities

- Create and manage users
- Assign security groups
- Configure dynamic group membership
- Apply authentication methods
- Assign enterprise applications
- Configure access based on role
- Disable and remove identities
- Review remaining permissions

---

## 🔐 2. Authentication & MFA

### Authentication Flow

**User Sign-In → Authentication → MFA Challenge → Conditional Access Evaluation → Access Granted / Blocked**

### Key Activities

- Configure authentication methods
- Configure MFA
- Explore SSPR
- Test authentication policies
- Analyze authentication activity
- Understand authentication risks
- Investigate failed sign-ins

---

## 🚦 3. Conditional Access

Conditional Access is used to control access based on **identity, device, application, location, and risk**.

### Example Policy

**User → Application → Device / Location / Risk → Conditional Access Policy → MFA / Block / Allow → Access Decision**

### Key Activities

- Create Conditional Access policies
- Target specific users and groups
- Require MFA
- Target cloud applications
- Configure location-based conditions
- Explore device-based conditions
- Understand policy evaluation
- Test access scenarios

---
## 🛡️ 4. RBAC & Least Privilege

Role-Based Access Control (RBAC) is used to assign the appropriate permissions to identities while following the principle of least privilege.

### Access Model

**Identity → Role → Scope → Permission → Resource Access**

### Key Activities

- Explore Microsoft Entra roles
- Assign built-in roles
- Review role permissions
- Explore custom roles
- Apply least-privilege principles
- Understand administrative scopes
- Review role assignments

---

## 👑 5. Privileged Identity Management

Microsoft Entra PIM provides controlled and time-limited access to privileged roles.

### Privileged Access Flow

**User → Eligible Role → MFA → Role Activation → Privileged Task → Role Deactivation**

### Key Activities

- Explore Microsoft Entra PIM
- Configure eligible roles
- Activate privileged roles
- Understand Just-In-Time access
- Configure approval requirements
- Review activation history
- Monitor privileged activity

---

## 🏢 6. Enterprise Applications & SSO

Enterprise applications allow organizations to manage application access and authentication through Microsoft Entra ID.

### Authentication Flow

**User → Microsoft Entra ID → Enterprise Application → SSO → Application**

### Identity Protocols

- SAML 2.0
- OAuth 2.0
- OpenID Connect
- Single Sign-On (SSO)

### Key Activities

- Explore Enterprise Applications
- Explore App Registrations
- Configure application access
- Understand SSO
- Explore SAML authentication
- Understand OAuth authorization
- Explore OpenID Connect
- Manage application permissions

---

## 🔄 7. Identity Governance

Identity governance helps organizations manage and review user access throughout the identity lifecycle.

### Key Topics

- Access Reviews
- Access Packages
- Entitlement Management
- Lifecycle Workflows
- Access Certification
- User access reviews

---

## 📊 8. Monitoring & Auditing

Understanding identity logs is essential for troubleshooting and security monitoring.

### Key Topics

- Sign-in Logs
- Audit Logs
- Authentication Logs
- Identity Monitoring
- Basic Troubleshooting

---

## ⚙️ 9. IAM Automation

Exploring automation tools used to manage identities and access more efficiently.

### Technologies

- Microsoft Graph API
- Graph Explorer
- PowerShell
- Azure CLI

---

## 📚 Key Learnings

Through this lab, I am building practical knowledge of:

- Microsoft Entra ID fundamentals
- Identity and Access Management (IAM)
- User and group administration
- Authentication and MFA
- Conditional Access
- RBAC and least-privilege access
- Privileged Identity Management (PIM)
- Enterprise applications and SSO
- Identity governance
- Identity monitoring and auditing
- Microsoft Graph and IAM automation

---

## 🛠️ Technologies

**Microsoft Entra ID • Active Directory • Windows Server • PowerShell • Microsoft Graph • Azure CLI**
