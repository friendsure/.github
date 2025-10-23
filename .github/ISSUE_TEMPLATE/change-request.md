---
name: Change Request
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

## 🔄 Change Request Summary

This issue serves as the official record for requesting, approving, and documenting changes to existing systems, applications, or environments.

---

### 🧾 Requestor Information
- **Name / Email:**  
- **Department / Team:**  
- **Date Submitted:**  
- **Related Repository / System:**  

---

### ⚙️ Description of Change
Describe what change is being requested and why it’s necessary.  
> _Example: Update CI/CD pipeline to add OSV security scan before build._

---

### ⚠️ Impact Assessment
Describe the potential effect of this change on systems, users, or services.  
> _Example: Temporary downtime expected during deployment; affects only staging environment._

- **Environment Affected:**  
  - [ ] Stage  
  - [ ] UAT  
  - [ ] Production  
- **Estimated Downtime:**  
- **Rollback Plan:**  

---

### 🔒 Security & Compliance Check
- **Security Review Completed?**  
  - [ ] Yes  
  - [ ] No (attach or reference Security Review Issue)
- **Data Sensitivity Level:**  
  - [ ] Public  
  - [ ] Internal  
  - [ ] Confidential  
  - [ ] Restricted  

---

### 🧰 Testing and Validation
- **Testing Completed?**  
  - [ ] Yes  
  - [ ] No  
- **Validation Evidence:**  
  (Attach screenshots, test logs, or link to Jenkins build results)

---

### 👥 Approvals
| Role | Name | Approval Status | Date |
|------|------|------------------|------|
| Requestor |  |  |  |
| Technical Reviewer / Team Lead |  |  |  |
| DevOps / Infrastructure |  |  |  |
| Security Officer (if required) |  |  |  |

---

### 🧾 Additional Notes
Provide any other relevant context or dependencies for this change.  
> _Example: Linked Jira ticket, related pull request, or policy reference._

---

### 📁 Attachments / References
- [ ] Linked Pull Request:  
- [ ] Jenkins Build ID:  
- [ ] Related Feature / Security Review Issue:  
- [ ] Other Supporting Docs:  

---

### ✅ Status
- [ ] Draft  
- [ ] Pending Approval  
- [ ] Approved  
- [ ] In Progress  
- [ ] Completed  
- [ ] Rejected

---

**Next Step:**  
Once approved, DevOps will schedule the deployment.  
The final deployment details and validation results must be attached before closing this issue.
