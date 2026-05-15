========================
LDAP
Lightweight Directory
Access Protocol
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
LDAP
-----------------------------------

LDAP =
Lightweight Directory Access Protocol

-----------------------------------
CORE PURPOSE
-----------------------------------

LDAP provides:
- centralized directory services
- authentication support
- user/account lookup services

-----------------------------------
WHY LDAP EXISTS
-----------------------------------

Large organizations require:
- centralized user management
- centralized authentication
- scalable identity services

Without centralized directories:
- each system may require separate account databases

-----------------------------------
DIRECTORY SERVICES
-----------------------------------

Directory services store:
- identity information
- user accounts
- groups
- permissions
- organizational data

-----------------------------------
DIRECTORY EXAMPLES
-----------------------------------

Examples:
- usernames
- passwords
- email addresses
- department information
- phone numbers
- group memberships

-----------------------------------
CENTRALIZATION
-----------------------------------

LDAP centralizes:
- identity information

-----------------------------------
WHY CENTRALIZATION MATTERS
-----------------------------------

Centralization improves:
- scalability
- consistency
- administration
- authentication management

-----------------------------------
LDAP FUNCTIONS
-----------------------------------

LDAP commonly supports:
- authentication
- directory searches
- account lookups
- access management

-----------------------------------
AUTHENTICATION
-----------------------------------

LDAP commonly helps verify:
- usernames/passwords

-----------------------------------
DIRECTORY LOOKUPS
-----------------------------------

LDAP may allow systems to:
- search for users/groups
- retrieve account information

-----------------------------------
COMMON LDAP USE CASES
-----------------------------------

Examples:
- enterprise login systems
- email directories
- VPN authentication
- WiFi authentication
- application authentication

-----------------------------------
ACTIVE DIRECTORY
-----------------------------------

{{{
Additional Context:
Microsoft Active Directory heavily uses LDAP for directory access.

Source:
Microsoft Active Directory Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
ACTIVE DIRECTORY PURPOSE
-----------------------------------

Active Directory provides:
- centralized identity management
for:
- Windows environments

-----------------------------------
RADIUS INTEGRATION
-----------------------------------

RADIUS commonly integrates with:
- LDAP directories

-----------------------------------
WHY RADIUS USES LDAP
-----------------------------------

RADIUS may validate:
- credentials stored in LDAP directories

-----------------------------------
VPN AUTHENTICATION
-----------------------------------

VPN systems may authenticate users using:
- LDAP directories

-----------------------------------
SSO
-----------------------------------

LDAP may support:
- Single Sign-On environments

-----------------------------------
GROUPS
-----------------------------------

LDAP directories commonly organize:
- users into groups

-----------------------------------
GROUP PURPOSE
-----------------------------------

Groups simplify:
- permission management
- access control

-----------------------------------
HIERARCHICAL STRUCTURE
-----------------------------------

LDAP directories commonly use:
- hierarchical structures

-----------------------------------
TREE STRUCTURE
-----------------------------------

Directories are often structured like:
- trees

-----------------------------------
ORGANIZATIONAL UNITS
-----------------------------------

{{{
Additional Context:
Directories commonly organize accounts into:
- Organizational Units (OUs)

Source:
Microsoft AD Organizational Units Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
DISTINGUISHED NAMES
-----------------------------------

{{{
Additional Context:
LDAP objects commonly use:
- Distinguished Names (DNs)

Source:
RFC 4514 LDAP Distinguished Names
https://datatracker.ietf.org/
}}}

-----------------------------------
SCHEMA
-----------------------------------

{{{
Additional Context:
LDAP schemas define:
- object types
- attributes
- directory structure rules

Source:
RFC 4512 LDAP Models
https://datatracker.ietf.org/
}}}

-----------------------------------
LDAP QUERIES
-----------------------------------

LDAP allows:
- querying directory information

-----------------------------------
QUERY EXAMPLES
-----------------------------------

Examples:
- find username
- retrieve group membership
- locate email address
- verify credentials

-----------------------------------
SECURE LDAP
-----------------------------------

Secure LDAP commonly uses:
- LDAPS

-----------------------------------
LDAPS
-----------------------------------

LDAPS =
LDAP over SSL/TLS

-----------------------------------
WHY LDAPS MATTERS
-----------------------------------

Standard LDAP traffic may otherwise expose:
- credentials
- directory information

-----------------------------------
LDAP PORTS
-----------------------------------

{{{
Additional Context:
Common LDAP ports:
- TCP/UDP 389 = LDAP
- TCP 636 = LDAPS

Source:
IANA Service Registry
https://www.iana.org/
}}}

-----------------------------------
AUTHORIZATION
-----------------------------------

LDAP directories may support:
- role/group-based authorization

-----------------------------------
RBAC
-----------------------------------

RBAC =
Role-Based Access Control

-----------------------------------
RBAC PURPOSE
-----------------------------------

RBAC assigns permissions based on:
- user roles/groups

-----------------------------------
REPLICATION
-----------------------------------

{{{
Additional Context:
LDAP directory servers commonly replicate information for redundancy/high availability.

Source:
OpenLDAP Documentation
https://www.openldap.org/
}}}

-----------------------------------
REDUNDANCY
-----------------------------------

Multiple LDAP servers may improve:
- reliability
- scalability
- fault tolerance

-----------------------------------
IAM
-----------------------------------

LDAP is heavily associated with:
- IAM

-----------------------------------
IAM
-----------------------------------

IAM =
Identity and Access Management

-----------------------------------
LOGGING
-----------------------------------

LDAP systems may log:
- authentication attempts
- directory queries
- access events

-----------------------------------
SECURITY RISKS
-----------------------------------

Improper LDAP security may expose:
- credentials
- directory information
- organizational data

-----------------------------------
COMMON SECURITY PRACTICES
-----------------------------------

{{{
Additional Context:
Common LDAP security practices:
- use LDAPS
- enforce MFA
- limit permissions
- monitor access

Source:
Microsoft LDAP Security Guidance
https://learn.microsoft.com/
}}}

-----------------------------------
LDAP VS RADIUS
-----------------------------------

LDAP:
- directory services

RADIUS:
- AAA authentication service

-----------------------------------
LDAP VS ACTIVE DIRECTORY
-----------------------------------

LDAP:
- protocol

Active Directory:
- Microsoft directory service implementation

-----------------------------------
LDAP VS TACACS+
-----------------------------------

LDAP:
- centralized directory access

TACACS+:
- administrative AAA service

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- LDAP = Lightweight Directory Access Protocol
- LDAP provides centralized directory services
- LDAP supports authentication/lookups
- Active Directory heavily uses LDAP
- LDAPS = secure LDAP
- LDAP commonly uses TCP/UDP 389
- LDAPS commonly uses TCP 636
- LDAP commonly integrates with RADIUS
- LDAP supports centralized identity management

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company centrally stores employee account information."

Answer:
LDAP directory service

-----------------------------------

Scenario:
"A VPN appliance validates credentials against a directory."

Answer:
LDAP integration

-----------------------------------

Scenario:
"A secure directory service encrypts authentication traffic."

Answer:
LDAPS

-----------------------------------

Scenario:
"A Windows domain centrally manages users/groups."

Answer:
Active Directory using LDAP

-----------------------------------

Scenario:
"A wireless authentication server checks user credentials against a directory."

Answer:
LDAP/RADIUS integration

-----------------------------------

Scenario:
"A company organizes users into groups for access control."

Answer:
LDAP directory groups/RBAC

-----------------------------------

Scenario:
"A centralized protocol retrieves user account information."

Answer:
LDAP

-----------------------------------

Scenario:
"A company uses TCP 636 for encrypted directory communication."

Answer:
LDAPS

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking LDAP is a database itself.

Wrong.

LDAP:
- protocol for directory access

-----------------------------------

Trap:
Confusing LDAP and Active Directory.

LDAP:
- protocol

Active Directory:
- Microsoft directory service

-----------------------------------

Trap:
Thinking LDAP automatically encrypts traffic.

Wrong.

Standard LDAP may be unencrypted.

LDAPS provides encryption.

-----------------------------------

Trap:
Confusing LDAP and RADIUS.

LDAP:
- directory service

RADIUS:
- AAA authentication service

-----------------------------------

Trap:
Thinking LDAP only stores usernames/passwords.

Wrong.

LDAP directories may store:
- groups
- emails
- departments
- permissions
- organizational information

-----------------------------------

Trap:
Thinking LDAPS and LDAP use the same default ports.

Wrong.

LDAP:
- 389

LDAPS:
- 636

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

LDAP =
Directory access

AD =
Directory service

LDAPS =
Secure LDAP

389 =
LDAP

636 =
LDAPS

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does LDAP stand for?

A:
Lightweight Directory Access Protocol.

-----------------------------------

Q:
What is the purpose of LDAP?

A:
Provide centralized directory services and authentication support.

-----------------------------------

Q:
What does LDAP commonly store?

A:
User accounts, groups, and directory information.

-----------------------------------

Q:
What is LDAPS?

A:
LDAP secured with SSL/TLS.

-----------------------------------

Q:
What ports commonly support LDAP and LDAPS?

A:
389 for LDAP, 636 for LDAPS.

-----------------------------------

Q:
What Microsoft service heavily uses LDAP?

A:
Active Directory.

-----------------------------------

Q:
What is the difference between LDAP and Active Directory?

A:
LDAP is a protocol; Active Directory is a directory service.

-----------------------------------

Q:
Why is centralized identity management important?

A:
Improves scalability and simplifies administration.

-----------------------------------

Q:
What is a common integration between RADIUS and LDAP?

A:
RADIUS validates credentials stored in LDAP directories.

-----------------------------------

Q:
Why is LDAPS preferred over standard LDAP?

A:
LDAPS encrypts authentication traffic.