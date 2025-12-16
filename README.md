# Beginner Azure Security Demo – Microsoft Defender for Cloud

[![Azure](https://img.shields.io/badge/Azure-Cloud-blue)](https://azure.microsoft.com/) 
[![Security](https://img.shields.io/badge/Security-Detected-red)](https://azure.microsoft.com/en-us/services/defender-for-cloud/)

---

## Project Overview
This project demonstrates fundamental cybersecurity skills in Azure.  
It focuses on creating a free-tier Storage Account, monitoring it using **Microsoft Defender for Cloud**, and implementing **preventive/corrective security controls**.  
It is designed for beginners building a portfolio with practical Azure security experience.

---

## Project Steps

### Step 1 – View Security Recommendations (Detective Control)
- Accessed **Microsoft Defender for Cloud** from the Storage Account.
- Clicked **View all recommendations** to identify potential security issues.
- Example recommendations:
  - Enable Storage Account encryption
  - Enable secure transfer
- **Screenshot:**  
![Step1_Recommendations](./screenshots/Step1_Recommendations.png)

> **Skill demonstrated:** Monitoring and identifying security risks (detective control).

---

### Step 2 – Apply Preventive/Corrective Control
- Navigated to **Storage Account → Settings → Encryption**.
- Enabled **Microsoft-managed keys** (standard Azure encryption at rest).
- Verified encryption is applied.
- Optional: Enabled **Secure Transfer** for enhanced preventive control.
- **Screenshot:**  
![Step2_RemediationApplied](./screenshots/Step2_RemediationApplied.png)

> **Skill demonstrated:** Implementing preventive/corrective security controls to protect data.

---

### Step 3 – Azure Resource Organization
- Resources grouped in a dedicated **Resource Group**: `CyberSecurityDemoRG`.
- Keeps project organized and simplifies management.
- **Screenshot:**  
![Step3_ResourceGroup](./screenshots/Step3_ResourceGroup.png)

> **Skill demonstrated:** Azure governance and resource management.

---

## Tools / Technologies
- Azure Portal (Free Tier)
- Microsoft Defender for Cloud (Free Tier)
- Azure Storage Account (General Purpose v2, Blob Storage, LRS)
- Screenshot tool (Snipping Tool / Mac Screenshot)

---

## Key Takeaways
- Learned to navigate **Microsoft Defender for Cloud** for security monitoring.
- Applied **encryption and secure transfer** as preventive controls.
- Gained experience with **Azure resource group organization**.
- Built a **portfolio-ready beginner Azure Security project**.

---
## Optional Next Steps
- Explore **alerts and policies** in Microsoft Defender for Cloud.
- Add **role-based access control (RBAC)** for further preventive measures.
- Try **network restrictions or private endpoints** for advanced security.

---

