========================
IAM
Identity and Access Management
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
IAM
-----------------------------------

IAM =
Identity and Access Management

-----------------------------------
CORE PURPOSE
-----------------------------------

IAM controls:
- who can access resources
- what they can access
- what actions they can perform

-----------------------------------
WHY IAM EXISTS
-----------------------------------

Organizations must:
- verify identities
- control permissions
- protect sensitive systems/data
- reduce unauthorized access

-----------------------------------
IAM FUNCTIONS
-----------------------------------

IAM commonly manages:
- authentication
- authorization
- account management
- permissions
- identity lifecycle

-----------------------------------
AAA
-----------------------------------

IAM heavily relates to:
- AAA

-----------------------------------
AAA
-----------------------------------

AAA =
- Authentication
- Authorization
- Accounting

-----------------------------------
AUTHENTICATION
-----------------------------------

Authentication verifies:
- identity

-----------------------------------
AUTHENTICATION QUESTION
-----------------------------------

Authentication answers:
"Who are you?"

-----------------------------------
AUTHORIZATION
-----------------------------------

Authorization determines:
- permissions/access rights

-----------------------------------
AUTHORIZATION QUESTION
-----------------------------------

Authorization answers:
"What are you allowed to do?"

-----------------------------------
ACCOUNTING
-----------------------------------

Accounting tracks:
- activity
- resource usage
- login events

-----------------------------------
ACCOUNTING PURPOSE
-----------------------------------

Accounting supports:
- auditing
- monitoring
- investigations

-----------------------------------
IDENTITIES
-----------------------------------

An identity represents:
- a user
- device
- service
- application

-----------------------------------
ACCOUNT MANAGEMENT
-----------------------------------

IAM commonly manages:
- user accounts
- permissions
- lifecycle states

-----------------------------------
ACCOUNT LIFECYCLE
-----------------------------------

Identity lifecycle stages may include:
- creation
- modification
- disabling
- deletion

-----------------------------------
WHY LIFECYCLE MANAGEMENT MATTERS
-----------------------------------

Unused accounts may create:
- security risks

-----------------------------------
LEAST PRIVILEGE
-----------------------------------

Least privilege means:
- providing only minimum necessary permissions

-----------------------------------
WHY LEAST PRIVILEGE MATTERS
-----------------------------------

Least privilege helps reduce:
- accidental damage
- insider threats
- attack surface

-----------------------------------
ROLE-BASED ACCESS CONTROL
-----------------------------------

RBAC =
Role-Based Access Control

-----------------------------------
RBAC PURPOSE
-----------------------------------

RBAC assigns permissions based on:
- organizational roles

-----------------------------------
RBAC EXAMPLE
-----------------------------------

Example:
Help desk staff:
- password reset permissions

Network admins:
- router configuration permissions

-----------------------------------
PRIVILEGED ACCOUNTS
-----------------------------------

Privileged accounts have:
- elevated permissions

-----------------------------------
PRIVILEGED ACCOUNT RISKS
-----------------------------------

Compromised privileged accounts may:
- expose critical systems
- cause severe damage

-----------------------------------
MFA
-----------------------------------

MFA =
Multifactor Authentication

-----------------------------------
MFA PURPOSE
-----------------------------------

MFA increases security by requiring:
- multiple authentication factors

-----------------------------------
AUTHENTICATION FACTORS
-----------------------------------

Common factor categories:
- something you know
- something you have
- something you are

-----------------------------------
SOMETHING YOU KNOW
-----------------------------------

Examples:
- passwords
- PINs

-----------------------------------
SOMETHING YOU HAVE
-----------------------------------

Examples:
- smart cards
- phones
- security tokens

-----------------------------------
SOMETHING YOU ARE
-----------------------------------

Examples:
- fingerprints
- facial recognition
- iris scans

-----------------------------------
MFA BENEFITS
-----------------------------------

MFA reduces risk from:
- stolen passwords
- credential compromise

-----------------------------------
SSO
-----------------------------------

SSO =
Single Sign-On

-----------------------------------
SSO PURPOSE
-----------------------------------

SSO allows users to:
- authenticate once
and:
- access multiple systems

-----------------------------------
SSO BENEFITS
-----------------------------------

Benefits:
- improved convenience
- reduced password fatigue
- simplified identity management

-----------------------------------
SSO RISKS
-----------------------------------

Compromised SSO credentials may:
- affect many systems simultaneously

-----------------------------------
FEDERATION
-----------------------------------

{{{
Additional Context:
Federation allows identity sharing across organizations/domains.

Source:
Microsoft Identity Federation Concepts
https://learn.microsoft.com/
}}}

-----------------------------------
DIRECTORY SERVICES
-----------------------------------

IAM commonly integrates with:
- directory services

-----------------------------------
ACTIVE DIRECTORY
-----------------------------------

{{{
Additional Context:
Microsoft Active Directory is a common directory service used for centralized authentication/authorization.

Source:
Microsoft Active Directory Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
LDAP
-----------------------------------

LDAP =
Lightweight Directory Access Protocol

-----------------------------------
LDAP PURPOSE
-----------------------------------

LDAP supports:
- directory queries
- centralized authentication

-----------------------------------
RADIUS
-----------------------------------

RADIUS =
Remote Authentication Dial-In User Service

-----------------------------------
RADIUS PURPOSE
-----------------------------------

RADIUS provides:
- centralized AAA services

-----------------------------------
TACACS+
-----------------------------------

TACACS+ =
Terminal Access Controller Access-Control System Plus

-----------------------------------
TACACS+ PURPOSE
-----------------------------------

TACACS+ commonly manages:
- administrative device access

-----------------------------------
RADIUS VS TACACS+
-----------------------------------

RADIUS:
- commonly used for network access authentication

TACACS+:
- commonly used for device administration

-----------------------------------
ACCOUNT POLICIES
-----------------------------------

IAM commonly enforces:
- password policies
- lockout policies
- access policies

-----------------------------------
PASSWORD POLICIES
-----------------------------------

Policies may require:
- complexity
- expiration
- minimum length

-----------------------------------
ACCOUNT LOCKOUT
-----------------------------------

Lockouts help reduce:
- brute-force attacks

-----------------------------------
ACCESS REVIEWS
-----------------------------------

Organizations commonly review:
- user permissions
- privileged access
- stale accounts

-----------------------------------
ZERO TRUST
-----------------------------------

{{{
Additional Context:
Zero Trust assumes no user/device is automatically trusted.

Source:
NIST Zero Trust Architecture
https://csrc.nist.gov/
}}}

-----------------------------------
ZERO TRUST PRINCIPLES
-----------------------------------

Zero Trust emphasizes:
- continuous verification
- least privilege
- segmentation

-----------------------------------
LOGGING AND AUDITING
-----------------------------------

IAM systems commonly log:
- login attempts
- permission changes
- authentication events

-----------------------------------
WHY LOGGING MATTERS
-----------------------------------

Logging supports:
- investigations
- compliance
- anomaly detection

-----------------------------------
INSIDER THREATS
-----------------------------------

IAM helps reduce:
- insider misuse
- unauthorized access
- privilege abuse

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- IAM = Identity and Access Management
- Authentication verifies identity
- Authorization controls permissions
- Accounting tracks activity
- Least privilege minimizes permissions
- MFA requires multiple factors
- SSO allows one login for multiple systems
- RBAC assigns permissions by role
- RADIUS provides centralized AAA
- TACACS+ commonly manages admin access

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A user verifies identity with password and fingerprint."

Answer:
MFA

-----------------------------------

Scenario:
"A company assigns permissions based on job role."

Answer:
RBAC

-----------------------------------

Scenario:
"A system verifies who a user is."

Answer:
Authentication

-----------------------------------

Scenario:
"A system determines what actions a user may perform."

Answer:
Authorization

-----------------------------------

Scenario:
"A company tracks login activity for investigations."

Answer:
Accounting/logging

-----------------------------------

Scenario:
"A user logs in once and accesses multiple applications."

Answer:
SSO

-----------------------------------

Scenario:
"A company limits employees to only necessary permissions."

Answer:
Least privilege

-----------------------------------

Scenario:
"A centralized service authenticates WiFi users."

Answer:
RADIUS

-----------------------------------

Scenario:
"A company centrally manages administrative router logins."

Answer:
TACACS+

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing authentication and authorization.

Authentication:
- identity verification

Authorization:
- permission assignment

-----------------------------------

Trap:
Thinking MFA means two passwords.

Wrong.

MFA requires:
- multiple factor categories

-----------------------------------

Trap:
Thinking SSO improves security automatically.

Wrong.

SSO improves convenience but:
- increases impact if credentials are compromised

-----------------------------------

Trap:
Confusing RADIUS and TACACS+.

RADIUS:
- network access authentication

TACACS+:
- administrative access management

-----------------------------------

Trap:
Thinking least privilege restricts all productivity.

Wrong.

Least privilege:
- provides only required access

-----------------------------------

Trap:
Thinking IAM only applies to users.

Wrong.

IAM also manages:
- devices
- services
- applications

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Authentication =
Who are you?

Authorization =
What can you do?

Accounting =
What happened?

MFA =
Multiple factors

RBAC =
Permissions by role

SSO =
One login many systems

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does IAM stand for?

A:
Identity and Access Management.

-----------------------------------

Q:
What does authentication verify?

A:
Identity.

-----------------------------------

Q:
What does authorization determine?

A:
Permissions and allowed actions.

-----------------------------------

Q:
What does accounting track?

A:
User/system activity.

-----------------------------------

Q:
What does MFA stand for?

A:
Multifactor Authentication.

-----------------------------------

Q:
What is least privilege?

A:
Providing only minimum necessary permissions.

-----------------------------------

Q:
What does RBAC stand for?

A:
Role-Based Access Control.

-----------------------------------

Q:
What does SSO stand for?

A:
Single Sign-On.

-----------------------------------

Q:
What is the purpose of RADIUS?

A:
Centralized AAA/network access authentication.

-----------------------------------

Q:
What is TACACS+ commonly used for?

A:
Administrative device access management.