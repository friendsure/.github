---
name: Security Review
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

## 🛡️ Security Review Request

This issue serves as the official record of the security review for a new feature, change, or integration.  
Please complete all sections below before submitting.

---

### 📌 Requestor Information
- **Name / Email:**  
- **Project / Repository:**  
- **Date Submitted:**  

---

### 🧩 Description of Change
Briefly describe the purpose and technical scope of this feature or change.  
> _Example: New API endpoint for payment webhook integration._

---

### ⚠️ Potential Security Risks
Identify possible vulnerabilities, data exposure risks, or access control implications.  
> _Example: User input validation, file upload, data encryption, etc._

---

### 🔒 Data Classification Involved
Mark one:
- [ ] Public  
- [ ] Internal  
- [ ] Confidential  
- [ ] Restricted  

---

### 🧰 Mitigation Measures
List existing or planned security controls to address identified risks.  
> _Example: Input sanitization, TLS enforcement, least privilege IAM roles._

---

### 🧾 Requires Penetration Testing?
Select one:
- [ ] No  
- [ ] Yes (Pre-release)  
- [ ] Yes (Post-release)

---

### 🕵️ Security Review Result _(to be completed by Security Officer)_
- **Reviewed by:**  
- **Date of Review:**  
- **Findings Summary:**  
- **Risk Rating:** ☐ Low ☐ Medium ☐ High  
- **Decision:** ☐ Approved ☐ Rejected  
- **Comments / Recommendations:**  

---

### 📁 Attachments / References
Link any supporting documentation (BRD, FSD, screenshots, test results, etc.)  
> _Example: [FSD-1234 Security Section](https://link.to.document)_

---

**Status:** Pending Review  
**Next Step:** Security Officer to review and update findings.
