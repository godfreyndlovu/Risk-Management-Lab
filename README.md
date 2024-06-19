# Risk Management Lab - Conducting a Security Audit and Risk Assessment Reporting

## Objective

The Risk Management Lab project aims to mitigate risks and prevent security incidents for a fictional company called Botium Toys. Conducting these risk management exercises, such as security audits and risk assessment reporting, supports overall business resilience, regulatory compliance, and heightened security awareness in an increasingly uncertain cyber landscape and fast-paced organizational environment. Security audits help ensure that security checks are performed to monitor threats, risks, or vulnerabilities that can affect an organization’s business continuity and critical assets. In this risk assessment exercise, I evaluate the security controls and regulatory compliance of Botium Toys to improve its security posture as an organization. This hands-on project helps deepen the understanding of security auditing, risk assessment, and defense-in-depth strategies.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.


## Scenario
_This scenario is based on a fictional company:_

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Botium Toys: Scope, goals, and risk assessment report

**Scope and goals of the audit**

_Scope:_ The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

_Goals_: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.

**Current assets**

Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring 


## Risk assessment

### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. 
Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department. 
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.



# OUTCOME: Risk Assessment Report

## Security Controls checklist

#### Assessing whether Botium Toys has the following critical security controls in place.


| Control                                   | Yes             | No              | Explanation                                   |
|-------------------------------------------|-----------------|-----------------|-----------------------------------------------|
| Separation of duties          |  | 🗹  | Implementing this is necessary to minimize fraud and unauthorized access to sensitive data, as the CEO currently handles both daily operations and payroll management. |
| Password policies| | 🗹 | The current minimal password requirements for employees make it easier for threat actors to gain access to secure data or other assets through employee work devices or the internal network. |
| Least Privilege         |  | 🗹 | All employees have unrestricted access to customer data; access needs to be limited to reduce the risk of data breaches. |
| Intrusion detection system (IDS)      |  | 🗹  | The IT department needs an IDS to detect potential intrusions by threat actors. |
| Antivirus Software | 🗹 | | The IT department has installed and regularly monitors antivirus software. |
| Data Recovery Plans | | 🗹 | There are no disaster recovery plans in place, which are essential for maintaining business continuity. |
| Backups | | 🗹 | The IT department needs to ensure backups of critical data are available to maintain business continuity in the event of a breach. |
| Password Management System | | 🗹 | Currently, there is no password management system; implementing one would enhance productivity for both the IT department and other employees by resolving password-related issues more efficiently. |
| Firewalls | 🗹 |  | The existing firewall is effectively blocking traffic according to a well-defined set of security rules. |
| Manual monitoring, maintenance, and intervention for legacy systems | | 🗹 | Although legacy systems are in use, there is no regular schedule for their monitoring and maintenance, and procedures for intervention are unclear, which could leave these systems vulnerable to breaches. |
| Closed-circuit television (CCTV) surveillance | 🗹 |  | CCTV is installed and operational at the store’s physical location. |
| Locks (offices, storefront, and warehouse) | 🗹 |  | The physical location, including the main offices, storefront, and warehouse, is adequately secured with locks. |
| Fire detection/prevention (fire alarm, sprinkler system, etc.) | 🗹 |  | Botium Toys’ physical location is equipped with a functioning fire detection and prevention system. |

  
  
## Compliance checklist

#### Assessing whether Botium Toys adheres to set regulatory compliance standards.

#### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice                                                                 | Yes | No  | Explanation                                                                                           |
|-------------------------------------------------------------------------------|-----|-----|-------------------------------------------------------------------------------------------------------|
| Credit card information is accepted, processed, transmitted, and stored internally in a secure environment. |     | 🗹  | Credit card information is not encrypted, and all employees have access to internal data, including customers’ credit card information. |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data.  |     | 🗹  | Encryption is not used, compromising the confidentiality of customers’ financial information.         |
| Only authorized users have access to customers’ credit card information.      |     | 🗹  | At present, all employees can access the company’s internal data.                                     |
| Adopt secure password management policies.                                    |     | 🗹  | Current password policies are minimal, and there is no password management system in place.           |

#### General Data Protection Regulation (GDPR)

| Best Practice                                                                 | Yes | No  | Explanation                                                                                           |
|-------------------------------------------------------------------------------|-----|-----|-------------------------------------------------------------------------------------------------------|
| Ensure data is properly classified and inventoried.                           |     | 🗹  | While current assets are inventoried, they are not classified.                                        |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | 🗹  |     | A plan is in place to notify E.U. customers within 72 hours in case of a data breach.                 |
| E.U. customers’ data is kept private/secured.                                 |     | 🗹  | Encryption is not used, which compromises the confidentiality of customers’ financial information.    |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | 🗹  |     | Privacy policies, procedures, and processes are established and enforced among IT team members and other employees as required. |

#### System and Organization Controls (SOC 1, SOC 2)

| Best Practice                                                                 | Yes | No  | Explanation                                                                                           |
|-------------------------------------------------------------------------------|-----|-----|-------------------------------------------------------------------------------------------------------|
| Data is available to individuals authorized to access it.                     |     | 🗹  | Data is accessible to all employees, but access needs to be restricted to authorized personnel only.  |
| Sensitive data (PII/SPII) is confidential/private.                            |     | 🗹  | Encryption is not utilized, putting the confidentiality of PII/SPII at risk.                          |
| User access policies are established.                                         |     | 🗹  | Controls for Least Privilege and Separation of Duties are lacking; all employees have access to internal data. |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated. | 🗹  |     | Measures are in place to ensure data integrity.                                                       |






 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
