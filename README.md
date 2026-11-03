# 🔐 CIA Triad Risk Assessment: OsCorp Research Document

## 📌 Project Overview

This project is a GRC case study applying the CIA Triad to assess the security of a highly confidential drug research document.

The assessment considers three core information security objectives:

- Confidentiality
- Integrity
- Availability

The objective is to identify potential risks, consider their impact, and propose appropriate security controls.

> **Note:** This is a simulated case study created for cybersecurity and GRC learning purposes. OsCorp is a fictional organization.

---

## 🎯 Scenario

OsCorp is developing a highly confidential new medication.

The project is in early development and is led by the Chief Scientist, Harry Osborn.

The research information is contained in a Microsoft Word document that includes ingredients required for experimentation.

Because the document contains sensitive research information, protecting its confidentiality, integrity, and availability is important.

---

# 🔒 1. Confidentiality

### Assessment Question

> Who should be able to access the document, and how can unauthorized access be prevented?

### Key Assessment Questions

- Who currently has access to the document?
- Who actually requires access?
- Is access restricted to authorized members of the research team?
- Are former employees or unauthorized third parties able to access it?
- Are different access levels defined?
- Is Multi-Factor Authentication (MFA) enabled?
- Is the document encrypted at rest?
- Is the document encrypted during transmission?
- Can users download, copy, or externally share the document?
- Is access to the document logged and monitored?

### Potential Risks

- Unauthorized access
- Unauthorized disclosure
- Intellectual property exposure
- External sharing of sensitive research information

### Potential Controls

- Role-Based Access Control (RBAC)
- Least privilege
- Multi-Factor Authentication (MFA)
- Encryption
- Data Loss Prevention (DLP)
- Access logging and monitoring
- External sharing restrictions
- Periodic access reviews

---

# 🛡️ 2. Integrity

### Assessment Question

> How can OsCorp ensure that the information in the document is not changed incorrectly or maliciously?

### Key Assessment Questions

- Who can modify the document?
- Can everyone with read access also edit it?
- Are editing permissions restricted?
- Is version history enabled?
- Can changes be attributed to individual users?
- Is there a formal review or approval process?
- Are sensitive changes independently reviewed?
- Can previous versions be restored?

### Potential Risks

- Unauthorized modification
- Accidental changes
- Incorrect research information
- Loss of trustworthy or accurate data

### Potential Controls

- Restricted edit permissions
- Version history
- Change logging
- Approval workflows
- Document integrity monitoring
- Digital signatures where appropriate
- Versioned backups
- Separation of duties

---

# ☁️ 3. Availability

### Assessment Question

> Can authorized researchers access the document when they need it?

### Key Assessment Questions

- Where is the document stored?
- What happens if the storage system becomes unavailable?
- Are backups available?
- How frequently is the document backed up?
- Can the document be recovered if accidentally deleted?
- What happens if ransomware affects the document?
- Is there a disaster recovery process?
- How quickly would access need to be restored?
- Is there a single point of failure?

### Potential Risks

- Loss of access to research information
- Accidental deletion
- System outage
- Ransomware
- Loss of productivity
- Research disruption

### Potential Controls

- Regular backups
- Versioned backups
- Disaster recovery procedures
- Business continuity planning
- Redundant storage
- Recovery testing
- Availability monitoring

---

# 📊 CIA Risk Assessment Summary

| CIA Principle | Key Question | Example Risk | Potential Controls |
|---|---|---|---|
| Confidentiality | Who can access the document? | Unauthorized disclosure | MFA, RBAC, encryption, DLP |
| Integrity | Can unauthorized users modify the information? | Incorrect or malicious changes | Access restrictions, version control, approval workflows |
| Availability | Can authorized users access the document when needed? | Document becomes unavailable | Backups, redundancy, recovery procedures |

---

# 🧠 GRC Assessment Approach

This exercise follows a basic GRC risk assessment thought process:

**Asset → Risk → Impact → Control → Evidence → Testing**

### 1. Asset

Highly confidential drug research document.

### 2. Risk

The document could be:

- Disclosed to unauthorized individuals
- Modified incorrectly or maliciously
- Lost or become unavailable

### 3. Impact

Potential impacts could include:

- Loss of intellectual property
- Research disruption
- Financial loss
- Competitive disadvantage
- Regulatory or legal consequences
- Potential research or safety consequences

### 4. Controls

Potential controls include:

**Confidentiality**

- MFA
- RBAC
- Least privilege
- Encryption
- DLP

**Integrity**

- Version history
- Change logging
- Approval workflows
- Restricted editing

**Availability**

- Backups
- Redundancy
- Disaster recovery
- Recovery testing

### 5. Evidence and Control Testing

A GRC analyst would not simply assume that a control is working.

Evidence could include:

- Access lists
- Access review records
- Authentication configuration
- Audit logs
- Version history
- Backup records
- Recovery test results

Examples of control-testing questions:

> "Show me the current access list."

> "Show me evidence of the last access review."

> "Show me the audit logs."

> "Show me the backup."

> "Show me evidence that the backup can be successfully restored."

---

# 📚 Key Concepts Demonstrated

This case study demonstrates my understanding of:

- CIA Triad
- Confidentiality
- Integrity
- Availability
- Risk Assessment
- Security Controls
- Least Privilege
- Role-Based Access Control
- Multi-Factor Authentication
- Encryption
- Data Loss Prevention
- Access Reviews
- Audit Logging
- Version Control
- Backup and Recovery
- Disaster Recovery
- Control Testing
- Evidence Collection

---

# 💡 Key Learning

The CIA Triad provides a framework for identifying what needs to be protected within an organisation.

Through this assessment, I learned to approach information security from a risk and control perspective. I considered:

→ What information or asset needs protection?

→ What could go wrong?

→ What would the impact be if the risk occurred?

→ What security controls could reduce the risk?

→ What evidence would demonstrate that the controls are in place?

→ How would I test whether those controls are operating effectively?

This helped me understand how the CIA Triad connects to practical GRC activities, particularly risk identification, control selection, evidence collection and control testing.

---

## 🛠️ Tools & Technologies

- Microsoft Word
- GitHub
- Markdown

---

## 📖 Learning Context

This project was created as part of my ongoing cybersecurity and Governance, Risk & Compliance (GRC) learning journey.
