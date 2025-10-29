# Fundamentals of Computer Security

## Identification, Authentication, and Authorization

| Concept | Description | Example |
|----------|--------------|----------|
| *Identification* | Claiming an identity | Typing username |
| *Authentication* | Proving identity | Entering password / fingerprint |
| *Authorization* | Granting access | Accessing certain files after login |

---

## Key Principle:
*“Authentication verifies who you are. Authorization decides what you can do.”*


##  Authentication Methods

- Knowledge-based: Passwords, PINs
- Possession-based: smart cards, OTP tokens
- inherence-based: Biometrics (Fingerprint face ID)
- Multifactor Authentication (MFA): combination of 2 or more above
- single sign-on (sso): One-time login across multiple systems (e.g., Google or Microsoft SSO)

# Authorization Models
- DAC (Descretionary Access Control): Owner decided who can access (Windows permissions).
- MAC (Mandatory Access Control): Access based on classification levels (military systems).
- RBAC (Role-Based Access Control): Permissions assigned to roles (Admin,Manager,User).
- ABAC (Attribute-Based Access System): Access based on condition (time,location,user type).

Example:

An "HR Manager" role can view employee data, while "Employee" role can only view their own profil

Best Practices

strong, unique unique passwords.

Apply MFA wherever possible.

Review role-based permissions regularly.

Log all authentication and access events.
-
