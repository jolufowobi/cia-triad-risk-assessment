# 🔍 CIA Triad Risk Assessment | Pharmaceutical Research Document

> Assessment of confidentiality, integrity and availability risks to a highly confidential pharmaceutical research document, with recommended controls and the evidence needed to prove they work.

---

## 1. 📌 Executive Summary

This assessment examines information security risks associated with the protection of highly confidential pharmaceutical research information at a pharmaceutical research company developing a new medication.

The assessment applies the **Confidentiality, Integrity and Availability (CIA) Triad** to evaluate how sensitive research information could be exposed, modified without authorisation or become unavailable when required.

The analysis identifies potential security risks and recommends controls to protect the confidentiality, integrity and availability of the research document. It also considers the evidence an organisation would need to demonstrate that relevant security controls are appropriately designed, implemented and operating effectively.

The assessment follows a practical GRC approach, connecting information security principles to risk identification, control recommendations, evidence requirements and control validation.

---

## 2. 🏢 Business Context

The company is developing a highly confidential new medication. The early stages of the research project are led by the Chief Scientist.

Information relating to the medication, including ingredients required for experimentation, is documented in a Microsoft Word file.

Because the document contains sensitive research information, unauthorised access, inappropriate modification or loss of access could affect the organisation's intellectual property, research activities and commercial interests.

The organisation therefore needs appropriate safeguards to ensure that only authorised individuals can access the document, changes are properly controlled and the information remains available when needed.

---

## 3. 🎯 Assessment Objectives

The objectives of this assessment are to:

- Evaluate the confidentiality risks associated with storing and sharing sensitive research information.
- Identify potential threats to the accuracy and integrity of the research document.
- Assess availability risks that could interrupt access to critical research information.
- Recommend security controls to address identified risks.
- Identify evidence that could demonstrate whether the recommended controls have been implemented.
- Establish considerations for validating control design and operating effectiveness.

---

## 4. 🔒 Confidentiality Assessment

Confidentiality ensures that sensitive information is accessible only to individuals who have been authorised to view it.

For the company, the research document contains confidential information about the ingredients required for medication experimentation. Unauthorised disclosure could expose intellectual property, compromise research activities and create a competitive disadvantage.

### Key Risk Considerations

The assessment considers the following questions:

- Who is authorised to access the research document?
- Are access permissions assigned according to job responsibilities?
- Can individuals outside the research team access the document?
- Do former employees or third-party users retain access after their responsibilities end?
- Is multi-factor authentication required for access?
- Is the document encrypted when stored and transmitted?
- Can users download, copy or share the document externally?
- Are access activities recorded and monitored?

### Potential Risks

| Risk | Potential Business Impact |
|---|---|
| Unauthorised access | Sensitive research information may be accessed by individuals without legitimate business need. |
| External disclosure | Confidential research details may be shared with competitors or unauthorised parties. |
| Excessive access privileges | Employees may have access beyond what is required for their roles. |
| Inadequate access removal | Former employees or third parties may retain access to sensitive information. |
| Unmonitored file activity | Suspicious access, downloads or sharing activities may go undetected. |

### Recommended Security Controls

| Control | Purpose |
|---|---|
| Role-Based Access Control (RBAC) | Restricts access according to assigned job responsibilities. |
| Least Privilege | Ensures users receive only the permissions necessary to perform their duties. |
| Multi-Factor Authentication (MFA) | Adds an additional authentication requirement to reduce the risk of unauthorised access. |
| Encryption at Rest and in Transit | Protects research information while stored and when transmitted. |
| Data Loss Prevention (DLP) | Helps detect or prevent unauthorised sharing, copying or transfer of sensitive information. |
| Access Logging and Monitoring | Records access activities and supports the identification of suspicious behaviour. |
| Periodic Access Reviews | Helps confirm that access permissions remain appropriate as roles and responsibilities change. |
| External Sharing Restrictions | Limits the ability to share confidential research information outside approved channels. |

---

## 5. ✍️ Integrity Assessment

Integrity ensures that information remains accurate, complete and protected against unauthorised or inappropriate modification.

For the company, the research document must remain reliable throughout the medication development process. Unauthorised or accidental changes to research information could affect the accuracy of the documented ingredients and compromise the reliability of the information used by the research team.

### Key Risk Considerations

The assessment considers the following questions:

- Who is authorised to modify the research document?
- Are users assigned separate read-only and editing permissions?
- Can changes be made without appropriate authorisation?
- Is version history maintained?
- Can changes be attributed to individual users?
- Are significant changes reviewed or approved?
- Can the organisation restore an earlier version if information is incorrectly modified or deleted?
- Are sensitive changes subject to additional review?

### Potential Risks

| Risk | Potential Business Impact |
|---|---|
| Unauthorised modification | Research information may be changed by individuals without appropriate permission. |
| Accidental modification | Important research details may be altered or removed unintentionally. |
| Lack of change tracking | The organisation may be unable to identify who changed information or when the change occurred. |
| Inadequate version control | Previous versions may be unavailable when incorrect changes need to be reversed. |
| Unapproved changes | Significant modifications may be made without appropriate review or authorisation. |

### Recommended Security Controls

| Control | Purpose |
|---|---|
| Restricted Editing Permissions | Limits document modification rights to authorised personnel. |
| Read-Only Access | Allows users to view information without changing its contents. |
| Version History | Maintains previous document versions and supports recovery from inappropriate changes. |
| Change Logging | Records document modifications and helps establish accountability. |
| Approval Workflows | Requires appropriate review and authorisation for significant changes. |
| Separation of Duties | Reduces the risk of one individual having excessive control over sensitive activities. |
| Versioned Backups | Provides recoverable copies of the document if information is altered or lost. |
| Integrity Monitoring | Helps identify unexpected or unauthorised changes to sensitive information. |

---

## 6. 🔄 Availability Assessment

Availability ensures that information and systems remain accessible to authorised users when required.

For the company, the research team needs reliable access to the medication development document to support ongoing experimentation and research activities.

An outage, accidental deletion, ransomware incident or storage failure could prevent authorised personnel from accessing critical research information and disrupt the development process.

### Key Risk Considerations

The assessment considers the following questions:

- Where is the research document stored?
- Is it held in a centralised location or on an individual user's device?
- What happens if the storage platform becomes unavailable?
- Are regular backups maintained?
- How frequently is the document backed up?
- Can the organisation recover the document following accidental deletion?
- What safeguards exist against ransomware or other disruptive incidents?
- Are disaster recovery and business continuity procedures established?
- How quickly can access to the document be restored?
- Is there a single point of failure that could prevent access?

### Potential Risks

| Risk | Potential Business Impact |
|---|---|
| System or storage outage | Research personnel may be unable to access the document. |
| Accidental deletion | Critical research information may become unavailable. |
| Ransomware | The document may be encrypted or otherwise inaccessible. |
| Backup failure | The organisation may be unable to recover the document after data loss. |
| Lack of recovery procedures | Restoration may be delayed, extending research disruption. |
| Single point of failure | Failure of one storage component or service may interrupt access. |

### Recommended Security Controls

| Control | Purpose |
|---|---|
| Regular Backups | Maintains recoverable copies of the research document. |
| Versioned Backups | Supports recovery of earlier versions and helps protect against accidental or malicious changes. |
| Redundant Storage | Reduces dependence on a single storage component or location. |
| Disaster Recovery Procedures | Establishes how critical information and services will be restored following disruption. |
| Business Continuity Planning | Helps maintain essential business activities during an incident. |
| Backup Restoration Testing | Validates whether backed-up information can be successfully recovered. |
| Availability Monitoring | Helps identify service interruptions and storage availability issues. |
| Recovery Time and Recovery Point Objectives | Establishes acceptable restoration timeframes and data loss tolerances. |

---

## 7. 📊 CIA Risk Assessment Summary

The following table summarises the key information security risks and recommended controls identified across the three dimensions of the CIA Triad.

| CIA Dimension | Key Risk | Potential Impact | Recommended Controls |
|---|---|---|---|
| Confidentiality | Unauthorised access or disclosure of sensitive research information. | Intellectual property exposure, competitive disadvantage and reputational damage. | RBAC, least privilege, MFA, encryption, DLP, access logging and periodic access reviews. |
| Integrity | Unauthorised or accidental modification of research information. | Inaccurate research records, unreliable information and potential disruption to research activities. | Restricted editing, version history, change logging, approval workflows and separation of duties. |
| Availability | Loss of access to the research document due to outages, deletion or ransomware. | Research interruption, delayed activities and potential loss of critical information. | Regular backups, redundant storage, disaster recovery, business continuity and recovery testing. |

---

## 8. 🧭 GRC Risk Assessment Approach

This assessment follows a structured approach to connecting information assets, risks, controls and evidence.

The process can be summarised as:

**Asset → Risk → Impact → Control → Evidence → Validation**

| Assessment Stage | Application to the Company |
|---|---|
| Asset Identification | Identify the confidential pharmaceutical research document as an information asset requiring protection. |
| Risk Identification | Consider potential unauthorised disclosure, inappropriate modification and loss of availability. |
| Impact Assessment | Evaluate potential consequences for intellectual property, research activities, business operations and commercial interests. |
| Control Recommendations | Identify safeguards that could reduce the likelihood or impact of the risks. |
| Evidence Requirements | Determine what documentation or system records would demonstrate control implementation. |
| Control Validation | Establish how control design and operating effectiveness could be assessed. |

This approach helps ensure that security recommendations are connected to identifiable risks and that evidence requirements are considered as part of the wider GRC process.

---

## 9. 🧾 Evidence Requirements and Control Validation

Identifying a security control is only one part of an effective GRC assessment. An organisation should also be able to demonstrate that relevant controls have been appropriately designed, implemented and are operating as intended.

The following evidence could be requested to support validation of the recommended controls.

| CIA Dimension | Control Area | Potential Evidence |
|---|---|---|
| Confidentiality | Access Management | User access lists, role assignments and access permission records. |
| Confidentiality | Access Reviews | Completed access review records and evidence of remediation. |
| Confidentiality | Authentication | MFA configuration and authentication policy records. |
| Confidentiality | Encryption | Encryption configuration and relevant security settings. |
| Confidentiality | Monitoring and DLP | Access logs, DLP configurations, alerts and investigation records. |
| Integrity | Change Management | Document version history, change logs and modification records. |
| Integrity | Approval Processes | Documented approval workflows and evidence of authorised changes. |
| Integrity | Access Restrictions | Read-only and editing permission records. |
| Availability | Backup Management | Backup schedules, backup logs and backup completion records. |
| Availability | Recovery | Backup restoration test results and recovery records. |
| Availability | Business Continuity | Business continuity and disaster recovery documentation. |

### Control Validation Considerations

When assessing the controls, the organisation should consider:

- **Control design:** Is the control appropriately designed to address the identified risk?
- **Implementation:** Has the control been implemented in the relevant system or business process?
- **Operating effectiveness:** Is there evidence that the control operates consistently and as intended?
- **Remediation:** Are identified weaknesses documented, assigned to appropriate owners and tracked through to resolution?

For example, the existence of an access control policy does not, by itself, demonstrate that access permissions are appropriately restricted. Access records and review evidence would be needed to assess how the control is implemented and maintained.

Similarly, the existence of a backup schedule does not establish that recovery is effective. Restoration records and test results would provide stronger evidence of the organisation's ability to recover information.

---

## 10. ✅ Key Assessment Observations

The assessment highlights several considerations for protecting sensitive research information:

1. **Access must reflect business need.** Access to confidential research information should be limited to authorised individuals with legitimate responsibilities.

2. **Access and modification rights should be managed separately.** Individuals who need to view research information may not necessarily require permission to modify it.

3. **Accountability requires traceability.** Access logs, change records and version history can help establish who accessed or modified information and when.

4. **Sensitive information requires protection beyond basic access restrictions.** Encryption, monitoring and data loss prevention can provide additional safeguards against unauthorised disclosure.

5. **Recovery capability should be demonstrable.** Backup processes should be supported by restoration testing and documented recovery procedures.

6. **Evidence is essential to control assurance.** Policies and documented procedures should be supported by records demonstrating how controls are implemented and maintained.

---

## 11. 💡 Practitioner notes

This assessment demonstrates how I apply the CIA Triad to evaluate information security risks affecting sensitive business information.

I assessed the potential consequences of unauthorised disclosure, inappropriate modification and loss of availability, and identified security controls to address each area.

The assessment also demonstrates how I connect information security principles to practical GRC activities, including risk identification, control recommendations, evidence requirements and control validation.

---

## 12. 📎 Assessment Basis and Scope

This assessment examines a defined scenario involving the protection of highly confidential pharmaceutical research information.

The risk analysis, assessment questions, recommended security controls, evidence requirements and control validation considerations represent my documented assessment work.

Scenario-based assessment; control recommendations have not been tested against a live environment.

---

## 13. 🧰 Frameworks and Concepts

- CIA Triad (Confidentiality, Integrity, Availability)
- ISO/IEC 27001:2022 Annex A (access control, cryptography, logging, backup)
- NIST Cybersecurity Framework 2.0
- Role-Based Access Control (RBAC) and Least Privilege
- Data Loss Prevention (DLP)
- Business Continuity and Disaster Recovery (RTO / RPO)
- Evidence Requirements and Control Validation

---

**Project:** CIA Triad Risk Assessment | Pharmaceutical Research Document  
**Assessment Focus:** Confidentiality, Integrity and Availability  
**Domain:** Cybersecurity | Information Security | GRC
