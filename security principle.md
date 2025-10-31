# Security Principles

## Learning Objectives:
- Understand the CIA Triad and its importance.
- Explain Risk, Privacy, and Accountability.
- Relate security principles to real-world cyber incidents.

# CIA Triad
- The CIA Triad forms the foundation of information security.
- Each element ensures that information remains safe and trustworthy.

| Element            | Description                                                        | Example                                                   |
|---------------------|--------------------------------------------------------------------|----------------------------------------------------------|
| *Confidentiality* | Ensures data is accessible only to authorized users.               | Encrypting files, using passwords, access control lists. |
| *Integrity*       | Ensures data is accurate, consistent, and not tampered with.       | Using hashing, digital signatures, checksums.            |
| *Availability*    | Ensures systems and data are available when needed.                | Redundant servers, backups, DDoS protection.             |


![images](https://github.com/user-attachments/assets/0fa0c32d-f2a3-4d41-8084-3a306adca983)


# Key Concepts
- Data breaches often occur when one or more CIA principles are compromised.
- Balance is key — too much focus on one (e.g., availability) can weaken another (e.g., confidentiality).

# Examples
- *Confidentiality Violation:* Unauthorized access to customer data (e.g., Facebook–Cambridge Analytica case).
- *Integrity Violation:* Tampered medical data in hospitals leading to misdiagnosis.
- *Availability Violation:* DDoS attack on banking websites preventing service access.

## Risk
- Definition- Probability of a threat exploitingh a vulnerability to cause harm.

## Components:
- Threat - something that can cause damage.
- Vulnerability - weakmess that can be exploited.
- Impact - damage if threat is realized.


![12de29e7-4132-41ba-955f-5a67c64520d0_1920x1080](https://github.com/user-attachments/assets/9d1ad74f-6df3-461f-97ba-e5579f63efb5)


# Risk, Privacy and Accountability

## Formula:
- Risk = Threat x Vulnerability x Impact

## Examples:
- Threat - Phishing
- Vulnerability - Employee lack of awareness
- Impact - Credential theft, financial loss



![download](https://github.com/user-attachments/assets/2535e3d7-fe12-49b0-99fb-ab3abc2f17c8)


## Privacy
- Protecting personel and sensitive information of individuals.
- Governed by laws like GDPR, DPDP Act(India), HIPAA

  
![download](https://github.com/user-attachments/assets/af4d39dd-0f89-413a-915a-228a84b60baf)

# Key Practices
- Data minimization
- Informed consent
- Data anonmymization
Example: A Healthcare app must not share user helath data without consent

## Accountability
Ensuring every action in an IT system can be traced back to an individual

## Achieved through:
- Logging & through
- user access tracking
- Non-repudiation mechanisms
Example: Audit logs in firewalls to trace malicious user actions.

## Real-World Case Studies

| cases                      | Description                                                        | Violated Principles                                      |
|----------------------------|--------------------------------------------------------------------|----------------------------------------------------------|
| *Wannacry (2017)*         | Ransomware disabled hospital systems worldwide                     | availability                                            |
| *Equifax Breach (2017)*  | personal data of 143M users leaked                                 | confidentiality and integrity                            |
| *Twitter Hack (2020)*    | insider access to admin tools                                      | confidentiality and accountability                       |

## what is threat ?
in cybersecurity, a threat is any 

# Types of Threat
## Common Threat Categories

| Threat            | Description                                     | Example                 |
|-------------------|-------------------------------------------------|-------------------------|
| Malware         | Malicious software that damages or steals data  | Viruses, worms, trojans |
| Ransomware      | Encrypts files and demands payment              | WannaCry, LockBit       |
| Insider Threat  | Employees misusing access                       | Edward Snowden case     |
| Phishing        | Deceptive emails to steal credentials           | Fake Office365 login    |
| DDos            | overwhelms servers with traffic                 | mirai botnet attack     |


## Prevention Technique
- use antivirus and EDR solutions
- Train employees regularly
- Apply regular security patches
Use email filtering and rate limiting

# Threat Actors
## Types of Threat Actors

| Actor Type                 | Motivation                 | Example                    |
|----------------------------|----------------------------|----------------------------|
| script kiddies           | Fun or recognition         |Defacing websites           |
| Hackivists               | Political or Social course | Anonymous group attacks    |
| State-Sponsored Hackers  | Espionage or warfare       | APT29(Russia),APT41(China) |
| Cybercriminals           | Financial gain             | Credit card theft          |
| Insiders                 | Revenge or greed           | Data theft by employees    |
