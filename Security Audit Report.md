# Controls and compliance checklist 

- To complete the controls assessment checklist, refer to the information provided in the scope, goals, and risk assessment report. For more details about each control, including the type and purpose, refer to the control categories document. 
- Then, select “yes” or “no” to answer the question: Does Botium Toys currently have this control in place?  

## Controls assessment checklist 

| Control | Status |
|---|---|
| Least Privilege | No |
| Disaster Recovery Plans | No |
| Password Policies | Yes |
| Separation of Duties | No |
| Firewall | Yes |
| Intrusion Detection System (IDS) | No |
| Backups | No |
| Antivirus Software | Yes |
| Legacy-System Monitoring/Maintenance | Yes |
| Encryption | No |
| Password Management System | No |
| Locks | Yes |
| CCTV Surveillance | Yes |
| Fire Detection/Prevention | Yes |

## PCI DSS Compliance Assessment

| PCI DSS Practice | Status |
| ------------------------------------ | ----- |
| Only authorized users have access to customer credit-card information | No |
| Credit-card information is handled in a secure environment | No |
| Data encryption procedures are implemented | No |
| Secure password management policies are adopted | No |

## Explanation 

- The controls and compliance checklist was completed using the Botium Toys Scope, Goals, and Risk Assessment Report. The following explanations describe the reason for each Yes or No finding.

  - ### Controls Assessment:

    - **Least Privilege**
      - Botium Toys has not implemented least privilege. All employees currently have access to internally stored data, which may include customer PII/SPII and cardholder data.
    - **Disaster Recovery Plans**
      - Botium Toys does not currently have disaster recovery plans. This creates a risk that the organization may have difficulty restoring normal operations after a major disruption or security incident.
    - **Password Policies**
      - Botium Toys has a password policy in place. However, the policy has weak requirements and does not meet current minimum password complexity requirements.
    - **Separation of Duties**
      - Separation of duties has not been implemented. This means responsibilities have not been divided among employees to help prevent unauthorized actions or misuse of access.
    - **Firewall**
      - Botium Toys has a firewall that blocks network traffic based on an appropriately defined set of security rules.
    - **Intrusion Detection System (IDS)**
      - Botium Toys has not installed an intrusion detection system. Therefore, the organization does not currently have this additional control for detecting suspicious network activity.
    - **Backups**
      - Botium Toys does not have backups of critical data. This could make it difficult to recover important information after data loss or a security incident.
    - **Antivirus Software**
      - Antivirus software is installed and regularly monitored by the IT department.
    - **Legacy-System Monitoring/Maintenance**
      - Legacy systems are monitored and maintained by the IT department. However, there is no regular schedule for these activities and intervention methods are unclear.
    - **Encryption**
      - Encryption is not currently used to protect customers' credit-card information that is accepted, processed, transmitted, and stored in the company's internal database.
    - **Password Management System**
      - Botium Toys does not have a centralized password management system that enforces the password policy's minimum requirements.
    - **Locks**
      - The physical location has sufficient locks protecting the main offices, storefront, and warehouse.
    - **CCTV Surveillance**
      - The physical location has up-to-date closed-circuit television (CCTV) surveillance.
    - **Fire Detection/Prevention**
      - The physical location has functioning fire detection and prevention systems.
        
  - ### PCI DSS Compliance Assessment:

    - **Only authorized users have access to customer credit-card information**
      - All employees have access to internally stored data and may be able to access cardholder data. Therefore, access to credit-card information is not properly restricted.
    - **Credit-card information is handled in a secure environment**
      - Credit-card information is stored internally, but the report states that encryption is not currently used to protect the information.
    - **Data encryption procedures are implemented**
      - Botium Toys does not currently use encryption to protect customers' credit-card information.
    - **Secure password management policies are adopted**
      - Although Botium Toys has a password policy, its requirements are nominal and do not meet current minimum password complexity requirements. The company also does not have a centralized password management system.

## Recommendations

Based on the controls and PCI DSS compliance assessment, the following recommendations should be implemented to improve Botium Toys' overall security posture.

### 1. Implement Least Privilege

* Restrict employee access to only the systems and data required for their job responsibilities.
* Limit access to sensitive information such as customer PII/SPII and cardholder data.
* Regularly review user permissions and remove unnecessary access.

### 2. Implement Separation of Duties

* Divide sensitive responsibilities among multiple employees.
* Prevent a single employee from having complete control over sensitive processes.
* Reduce the risk of unauthorized actions and misuse of access.

### 3. Strengthen Password Policies

* Update the existing password policy with stronger security requirements.
* Require appropriate password length and complexity.
* Ensure the policy follows current security best practices.

### 4. Implement a Password Management System

* Implement a centralized password management system.
* Enforce the organization's password requirements.
* Provide a secure process for password recovery and resets.

### 5. Implement Encryption

* Encrypt sensitive customer information, especially credit-card data.
* Protect sensitive information while it is stored and transmitted.
* Use encryption to improve the confidentiality of sensitive data.

### 6. Implement an Intrusion Detection System (IDS)

* Deploy an IDS to monitor network activity for suspicious behavior.
* Configure alerts for potentially malicious network activity.
* Integrate IDS alerts with existing security monitoring tools when appropriate.

### 7. Create Disaster Recovery Plans

* Develop documented disaster recovery procedures.
* Identify critical systems and data that need to be restored after an incident.
* Define responsibilities and recovery procedures for IT personnel.
* Regularly review and test the disaster recovery plan.

### 8. Implement Regular Backups

* Create regular backups of critical business data.
* Protect backups from unauthorized access.
* Test backups regularly to verify that data can be successfully restored.

### 9. Establish a Legacy-System Maintenance Schedule

* Create a regular schedule for monitoring and maintaining legacy systems.
* Document procedures for responding to problems with legacy systems.
* Identify systems that are approaching or have reached end-of-life.

### 10. Strengthen PCI DSS Compliance

* Restrict access to customer credit-card information to authorized personnel.
* Protect cardholder data using appropriate security controls.
* Implement encryption for sensitive cardholder information.
* Strengthen password and access-management practices.

### 11. Maintain Physical Security Controls

* Continue maintaining existing locks, CCTV surveillance, and fire detection/prevention systems.
* Regularly inspect and test physical security controls.
* Document maintenance activities to ensure the controls remain effective.
