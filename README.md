# Microsoft Entra ID Zero Trust IAM Project

![Azure](https://img.shields.io/badge/Microsoft%20Azure-0089D6?logo=microsoftazure&logoColor=white)

## 📌 Overview
This repository documents a complete Zero Trust Identity & Access Management (IAM) implementation using Microsoft Entra ID.  
It includes Conditional Access, Authentication Strengths, Identity Protection, Device Compliance, and Privileged Identity Management (PIM).

This project demonstrates real-world IAM engineering skills aligned with enterprise security best practices.

---

## 🔐 Features Implemented

### 1. Conditional Access Policies
- Require MFA for all users  
- Block legacy authentication  
- Require MFA for admin roles  
- Require compliant device for IT admins  
- High-Security MFA for Azure Portal  
- Sign-in risk policy (Medium+)  
- User risk policy (High)  

---

### 2. Authentication Strengths
Created a custom **High Security MFA** strength requiring:
- Passwordless Microsoft Authenticator  
- FIDO2 security key  
- Temporary Access Pass  

Applied to Azure Portal access.

---

### 3. Identity Protection
- Enforced MFA for medium+ sign-in risk  
- Forced password reset for high user risk  
- Integrated risk-based Conditional Access  

---

### 4. Device Compliance
- Integrated Intune device compliance  
- Required compliant device for privileged access  
- Enforced Zero Trust device posture  

---

### 5. Privileged Identity Management (PIM)
- Assigned eligible roles (least privilege)  
- Configured just-in-time (JIT) activation  
- Required MFA + justification  
- Added approval workflow  
- Time-bound privileged access  
- Demonstrated activation + approval process  

---

## 📁 Repository Structure

/screenshots
/CA_Policies
/PIM
/Authentication_Strengths
/Identity_Protection
/Architecture_Diagram.png
/Project_Report.pdf
/README.md


---

## 📊 Architecture Diagram

A layered Zero Trust IAM architecture was implemented:

Users & Devices
│
Microsoft Entra ID (Auth, SSO, MFA)
│
Conditional Access (MFA, device compliance, risk policies)
│
Identity Protection (sign-in risk, user risk)
│
Privileged Identity Management (JIT, approvals)
│
Protected Resources (Azure Portal, M365, Apps)

A full PNG diagram is included in this repository.

---

## 🧠 Skills Demonstrated
- Zero Trust architecture  
- Identity governance  
- Conditional Access design  
- Privileged Identity Management  
- Authentication hardening  
- Risk-based access control  
- Device compliance enforcement  
- Microsoft Entra ID administration  

---

## 📄 Project Report
A full employer-ready project report is included as `Project_Report.pdf`.

---

## 📬 Contact
For questions or collaboration, feel free to reach out.
