# CIA Triad Risk Assessment | OsCorp Research Document

## 1. Executive Summary

This assessment evaluates the security risks associated with a highly confidential pharmaceutical research document at OsCorp, a fictional organisation developing a new medication.

The assessment applies the Confidentiality, Integrity and Availability (CIA) Triad to identify potential information security risks, evaluate their business implications and recommend appropriate security controls.

The review considers how sensitive research information could be exposed to unauthorised individuals, modified incorrectly or maliciously, or become unavailable to authorised researchers.

The assessment also identifies evidence requirements and control validation considerations to support the evaluation of security safeguards.

## 2. Business Context

OsCorp is in the early stages of developing a highly confidential new medication. The research project is led by Chief Scientist Harry Osborn.

Key research information, including ingredients required for experimentation, is maintained in a Microsoft Word document.

Given the sensitivity and commercial value of this information, unauthorised disclosure, modification or loss could affect research activities, intellectual property, business operations and competitive advantage.

The assessment therefore considers the security requirements necessary to protect the document throughout its use and storage.

## 3. Assessment Objectives

The assessment focuses on three fundamental information security objectives:

- **Confidentiality:** Ensuring that sensitive research information is accessible only to authorised individuals.
- **Integrity:** Maintaining the accuracy, completeness and reliability of the research information.
- **Availability:** Ensuring that authorised researchers can access the document when required.

## 4. Confidentiality Assessment

### Assessment Objective

Evaluate how access to the confidential research document is managed and identify safeguards that can prevent unauthorised access or disclosure.

### Assessment Considerations

- Identify individuals and roles with access to the document.
- Determine whether access is limited to personnel with a legitimate business need.
- Review access permissions and privilege levels.
- Consider whether former employees or unauthorised third parties retain access.
- Assess the use of Multi-Factor Authentication (MFA).
- Determine whether the document is encrypted at rest and during transmission.
- Review restrictions on downloading, copying and external sharing.
- Evaluate access logging and monitoring capabilities.

### Potential Risk Exposure

- Unauthorised access to sensitive research information.
- Disclosure of confidential intellectual property.
- Exposure of commercially sensitive information to external parties.
- Unauthorised distribution or sharing of research documents.

### Recommended Security Controls

| Control | Security Objective |
|---|---|
| Role-Based Access Control (RBAC) | Restrict access based on defined user roles. |
| Least Privilege | Ensure users receive only the permissions required for their responsibilities. |
| Multi-Factor Authentication (MFA) | Strengthen authentication and reduce the risk of unauthorised account access. |
| Encryption | Protect research information at rest and in transit. |
| Data Loss Prevention (DLP) | Detect or restrict unauthorised movement of sensitive information. |
| Access Logging and Monitoring | Provide visibility into access and document-related activities. |
| External Sharing Restrictions | Limit unauthorised distribution of research information. |
| Periodic Access Reviews | Identify and remove unnecessary or inappropriate access. |

## 5. Integrity Assessment

### Assessment Objective

Evaluate the safeguards required to protect the research document from unauthorised, accidental or malicious modification.

### Assessment Considerations

- Identify individuals authorised to modify the document.
- Determine whether read and edit permissions are appropriately separated.
- Review restrictions on editing sensitive research information.
- Establish whether document version history is maintained.
- Determine whether changes can be attributed to individual users.
- Assess whether formal review and approval processes exist.
- Consider independent review of sensitive changes.
- Determine whether previous document versions can be restored.

### Potential Risk Exposure

- Unauthorised modification of research information.
- Accidental changes to experimental ingredients or research details.
- Incorrect or unreliable research information.
- Loss of data accuracy and trustworthiness.

### Recommended Security Controls

| Control | Security Objective |
|---|---|
| Restricted Edit Permissions | Limit modification rights to authorised personnel. |
| Version History | Maintain records of previous document versions. |
| Change Logging | Record who made changes and when they occurred. |
| Approval Workflows | Ensure sensitive changes are reviewed and authorised. |
| Document Integrity Monitoring | Identify unexpected or unauthorised modifications. |
| Digital Signatures, Where Appropriate | Support document authenticity and integrity verification. |
| Versioned Backups | Preserve recoverable copies of the document. |
| Separation of Duties | Reduce the risk of inappropriate changes being made and approved by the same individual. |

## 6. Availability Assessment

### Assessment Objective

Evaluate the safeguards required to ensure that authorised researchers can access the document when needed and recover it following disruption.

### Assessment Considerations

- Identify where the research document is stored.
- Assess the potential impact of storage or system outages.
- Determine whether regular backups are maintained.
- Review backup frequency and retention arrangements.
- Establish whether accidentally deleted documents can be recovered.
- Consider the impact of ransomware or other disruptive incidents.
- Review disaster recovery arrangements.
- Determine expected recovery requirements.
- Identify potential single points of failure.

### Potential Risk Exposure

- Loss of access to critical research information.
- Accidental deletion or corruption of the document.
- Storage or system outages.
- Ransomware-related disruption.
- Reduced research productivity.
- Delays to research and development activities.

### Recommended Security Controls

| Control | Security Objective |
|---|---|
| Regular Backups | Maintain recoverable copies of research information. |
| Versioned Backups | Support recovery of earlier document versions. |
| Disaster Recovery Procedures | Establish recovery arrangements following significant disruption. |
| Business Continuity Planning | Support continuation of critical research activities. |
| Redundant Storage | Reduce dependence on a single storage location or system. |
| Recovery Testing | Validate that backups can be successfully restored. |
| Availability Monitoring | Identify storage or system availability issues. |

## 7. CIA Risk Assessment Summary

| Security Principle | Key Assessment Question | Potential Risk | Recommended Controls |
|---|---|---|---|
| Confidentiality | Who should have access to the document? | Unauthorised disclosure of research information | MFA, RBAC, least privilege, encryption and DLP |
| Integrity | Can the information be modified without appropriate authorisation? | Incorrect or malicious changes to research information | Restricted editing, version history, change logging and approval workflows |
| Availability | Can authorised researchers access the document when required? | Document becomes unavailable or cannot be recovered | Backups, redundancy, disaster recovery and recovery testing |

## 8. GRC Risk Assessment Approach

The assessment follows a structured risk and control approach:

**Asset → Risk → Impact → Control → Evidence → Testing**

### 8.1 Asset Identification

The primary asset assessed is the highly confidential pharmaceutical research document containing information required for experimentation.

### 8.2 Risk Identification

The assessment identifies three primary risk scenarios:

- Confidential research information could be disclosed to unauthorised individuals.
- Research information could be modified incorrectly or maliciously.
- The document could be lost, corrupted or become unavailable when required.

### 8.3 Business Impact Assessment

Potential business consequences include:

- Loss of intellectual property.
- Disruption to research and development activities.
- Financial losses.
- Competitive disadvantage.
- Regulatory or legal consequences.
- Potential research or safety implications.

### 8.4 Control Selection

Security controls were identified based on the information security objective they are intended to protect.

The recommendations address access management, authentication, encryption, data protection, change management, monitoring, backup and recovery.

### 8.5 Evidence Requirements and Control Validation

Control documentation alone does not establish operating effectiveness. Appropriate evidence is required to assess whether controls have been implemented and are functioning as intended.

Evidence requirements include:

| Control Area | Evidence Required |
|---|---|
| Access Management | Current user access lists and permission records |
| Access Reviews | Completed access review records and remediation evidence |
| Authentication | MFA configuration and authentication policies |
| Security Monitoring | Access logs and monitoring records |
| Document Integrity | Version history and change records |
| Backup Management | Backup schedules and backup records |
| Recovery | Documented recovery test results |

### Control Validation Questions

The following questions would guide evidence collection and control testing:

- Can the organisation provide the current access list for the research document?
- Is there evidence that access permissions are reviewed periodically?
- Can the organisation demonstrate that MFA is enabled for authorised users?
- Are access and document-related activities logged and monitored?
- Can changes to the document be attributed to individual users?
- Are backups maintained in accordance with defined requirements?
- Can the organisation demonstrate that a backup can be successfully restored?

## 9. Assessment Observations

The assessment highlights several important security considerations for protecting sensitive pharmaceutical research information.

**Confidentiality:** Access to the research document should be restricted according to business need, with appropriate authentication, encryption and monitoring safeguards.

**Integrity:** Document modification should be controlled through restricted editing permissions, version history, change logging and appropriate approval processes.

**Availability:** Backup, recovery and continuity arrangements should support access to research information during system disruption or accidental data loss.

The recommended controls provide a basis for evaluating the organisation's security arrangements. Actual control effectiveness would require review of implementation evidence and appropriate testing.

## 10. GRC Capabilities Demonstrated

- CIA Triad Assessment
- Information Security Risk Identification
- Confidentiality, Integrity and Availability Analysis
- Security Control Identification and Recommendations
- Access Management
- Role-Based Access Control
- Least Privilege
- Multi-Factor Authentication
- Encryption and Data Protection
- Data Loss Prevention
- Change Management and Version Control
- Backup and Recovery
- Disaster Recovery and Business Continuity
- Evidence Requirements
- Control Validation and Testing
- Risk and Control Analysis

## 11. Tools and Technologies

- Microsoft Word
- GitHub
- Markdown

## 12. Project Context

This is a simulated security assessment based on a fictional pharmaceutical research scenario. It was developed to demonstrate the application of information security principles, risk identification, security control recommendations and evidence-based control validation.

The assessment identifies potential risks and recommended safeguards. It does not represent a live organisational security audit or independently verified control assessment.
