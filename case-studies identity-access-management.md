# Case Study: Identity and Access Management (MS-102)

## 🏢 Organization Background
A mid-size enterprise with approximately **5,000 users** operates in a
hybrid environment using **on-premises Active Directory** and **Microsoft 365**.
Users access email, SharePoint, Teams, and cloud applications remotely.

---

## ❗ Business Challenges
- Increased **password-based attacks**
- Legacy authentication still enabled
- No centralized access control
- Privileged accounts not monitored
- Users accessing data from unmanaged devices

---

## 🎯 Requirements
- Secure user sign-ins
- Reduce risk of credential compromise
- Enforce least-privilege access
- Support hybrid identity
- Improve visibility and auditing

---

## 🛠️ Solution Design (MS-102 Aligned)

### 1️⃣ Identity Architecture
- Implement **Microsoft Entra ID (Azure AD)**
- Configure **Azure AD Connect** for hybrid identity
- Enable **Password Hash Synchronization**

---

### 2️⃣ Authentication & Access Control
- Enable **Multi-Factor Authentication (MFA)** for all users
- Configure **Conditional Access policies**:
  - Require MFA for admin roles
  - Block legacy authentication
  - Restrict access from risky locations
  - Require compliant devices for sensitive apps

---

### 3️⃣ Privileged Access Management
- Implement **Privileged Identity Management (PIM)**
- Use just-in-time admin access
- Require approval and MFA for role activation
- Monitor admin activity

---

### 4️⃣ Identity Protection
- Enable **Identity Protection policies**
- Configure:
  - Sign-in risk policies
  - User risk policies
- Automatically remediate risky users

---

## 🔍 Implementation Steps (High Level)
1. Sync identities using Azure AD Connect
2. Enable MFA tenant-wide
3. Create Conditional Access policies
4. Configure PIM for admin roles
5. Monitor sign-in logs and audit logs

---

## 📈 Outcome & Benefits
- 65% reduction in identity-related security incidents
- Improved compliance posture
- Secure remote access
- Reduced admin risk exposure
- Better visibility into access patterns

---

## 🧠 MS-102 Exam Focus Points
- Conditional Access logic
- MFA enforcement strategies
- Identity Protection workflows
- Hybrid identity configuration
- PIM use cases

---

## 📝 Admin Tools Used
- Microsoft Entra Admin Center
- Microsoft 365 Admin Center
- Azure AD Connect
- Azure Monitor & Logs
