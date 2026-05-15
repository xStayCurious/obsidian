========================
Authorization,
Least Privilege,
RBAC, and Geofencing
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
AUTHORIZATION
-----------------------------------

Authorization determines:
- what actions/resources a user is allowed to access

-----------------------------------
CORE PURPOSE
-----------------------------------

Authorization controls:
- permissions
- resource access
- allowed actions

-----------------------------------
AUTHENTICATION VS AUTHORIZATION
-----------------------------------

Authentication:
- verifies identity

Authorization:
- determines permissions

-----------------------------------
AUTHORIZATION QUESTION
-----------------------------------

Authorization answers:
"What are you allowed to do?"

-----------------------------------
WHY AUTHORIZATION EXISTS
-----------------------------------

Not every authenticated user should:
- access all systems
- modify all data
- perform all actions

-----------------------------------
PERMISSIONS
-----------------------------------

Authorization commonly controls:
- read access
- write access
- execute access
- administrative privileges

-----------------------------------
ACCESS CONTROL
-----------------------------------

Authorization is a major part of:
- access control

-----------------------------------
ACCESS CONTROL PURPOSE
-----------------------------------

Access controls help:
- protect resources
- reduce misuse
- limit damage
- enforce security policies

-----------------------------------
COMMON AUTHORIZATION EXAMPLES
-----------------------------------

Examples:
- help desk resets passwords only
- HR accesses employee records
- admins configure routers
- guests access limited resources

-----------------------------------
CENTRALIZED AUTHORIZATION
-----------------------------------

Authorization may be centrally managed through:
- IAM
- Active Directory
- LDAP
- cloud identity systems

-----------------------------------
IAM
-----------------------------------

IAM =
Identity and Access Management

-----------------------------------
AAA
-----------------------------------

Authorization is part of:
- AAA

-----------------------------------
AAA
-----------------------------------

AAA =
- Authentication
- Authorization
- Accounting

===================================
LEAST PRIVILEGE
===================================

-----------------------------------
LEAST PRIVILEGE
-----------------------------------

Least privilege means:
- users receive only minimum necessary permissions

-----------------------------------
CORE PURPOSE
-----------------------------------

Least privilege reduces:
- attack surface
- accidental damage
- insider threats
- privilege abuse

-----------------------------------
WHY LEAST PRIVILEGE EXISTS
-----------------------------------

Excessive permissions increase:
- security risks
- potential damage from compromise

-----------------------------------
EXAMPLE
-----------------------------------

Example:
A receptionist should NOT:
- administer firewalls
- modify servers
- access financial databases

-----------------------------------
ADMINISTRATIVE ACCOUNTS
-----------------------------------

Administrative accounts should:
- be limited carefully

-----------------------------------
PRIVILEGED ACCOUNT RISKS
-----------------------------------

Compromised privileged accounts may:
- expose critical systems
- allow widespread damage

-----------------------------------
JUST-ENOUGH ACCESS
-----------------------------------

Least privilege emphasizes:
- only necessary access

-----------------------------------
TEMPORARY PRIVILEGES
-----------------------------------

{{{
Additional Context:
Organizations may grant temporary elevated privileges only when needed.

Source:
Microsoft Privileged Access Guidance
https://learn.microsoft.com/
}}}

-----------------------------------
ZERO TRUST
-----------------------------------

Least privilege strongly aligns with:
- Zero Trust security

-----------------------------------
ZERO TRUST
-----------------------------------

{{{
Additional Context:
Zero Trust emphasizes:
- least privilege
- continuous verification

Source:
NIST Zero Trust Architecture
https://csrc.nist.gov/
}}}

-----------------------------------
SEGMENTATION
-----------------------------------

Least privilege may also involve:
- network segmentation
- restricted resource visibility

-----------------------------------
COMMON LEAST PRIVILEGE USES
-----------------------------------

Examples:
- restricted admin rights
- limited application permissions
- restricted file access
- limited cloud privileges

-----------------------------------
LEAST PRIVILEGE BENEFITS
-----------------------------------

Benefits:
- reduced lateral movement
- smaller attack surface
- improved security posture

===================================
ROLE-BASED ACCESS CONTROL
===================================

-----------------------------------
RBAC
-----------------------------------

RBAC =
Role-Based Access Control

-----------------------------------
RBAC PURPOSE
-----------------------------------

RBAC assigns permissions based on:
- organizational roles

-----------------------------------
WHY RBAC EXISTS
-----------------------------------

Managing permissions individually for every user:
- does not scale well

-----------------------------------
HOW RBAC WORKS
-----------------------------------

Users are assigned:
- roles

Roles contain:
- permissions

-----------------------------------
ROLE EXAMPLES
-----------------------------------

Examples:
- Help Desk
- Network Administrator
- HR Manager
- Finance User

-----------------------------------
RBAC ADVANTAGES
-----------------------------------

Advantages:
- simplified administration
- scalability
- consistency
- easier auditing

-----------------------------------
RBAC EXAMPLE
-----------------------------------

Example:
Help Desk role:
- password reset permissions

Network Admin role:
- router/switch management

-----------------------------------
DYNAMIC MANAGEMENT
-----------------------------------

Changing a user's role may:
- automatically change permissions

-----------------------------------
GROUPS
-----------------------------------

RBAC commonly uses:
- groups

-----------------------------------
ACTIVE DIRECTORY
-----------------------------------

{{{
Additional Context:
RBAC is commonly implemented using Active Directory groups.

Source:
Microsoft RBAC Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
RBAC VS INDIVIDUAL ASSIGNMENT
-----------------------------------

RBAC:
- permissions by role/group

Individual assignment:
- permissions per user

-----------------------------------
COMMON RBAC USE CASES
-----------------------------------

Examples:
- cloud IAM
- enterprise authentication
- file permissions
- network administration

-----------------------------------
RBAC AND LEAST PRIVILEGE
-----------------------------------

RBAC often supports:
- least privilege implementation

===================================
GEOFENCING
===================================

-----------------------------------
GEOFENCING
-----------------------------------

Geofencing restricts access based on:
- geographic location

-----------------------------------
CORE PURPOSE
-----------------------------------

Geofencing helps:
- limit unauthorized access
- enforce location-based security policies

-----------------------------------
WHY GEOFENCING EXISTS
-----------------------------------

Organizations may want to:
- restrict access from high-risk regions
- enforce regional compliance
- protect sensitive resources

-----------------------------------
HOW GEOFENCING WORKS
-----------------------------------

Systems evaluate:
- geographic source information

Examples:
- GPS data
- IP geolocation
- device location services

-----------------------------------
IP GEOLOCATION
-----------------------------------

Geofencing commonly uses:
- IP geolocation databases

-----------------------------------
COMMON GEOFENCING USE CASES
-----------------------------------

Examples:
- blocking foreign logins
- limiting app access by country
- restricting administrative access
- preventing fraud

-----------------------------------
CLOUD SECURITY
-----------------------------------

Cloud platforms commonly support:
- geofencing policies

-----------------------------------
MOBILE DEVICE MANAGEMENT
-----------------------------------

{{{
Additional Context:
MDM platforms may enforce location-based access restrictions.

Source:
Microsoft Intune Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
COMPLIANCE
-----------------------------------

Geofencing may support:
- legal/regulatory requirements

-----------------------------------
ALERTING
-----------------------------------

Geofencing systems may generate:
- alerts for suspicious logins

-----------------------------------
TRAVEL RISKS
-----------------------------------

Legitimate travel may:
- trigger geofencing restrictions

-----------------------------------
FALSE POSITIVES
-----------------------------------

Geofencing may occasionally:
- incorrectly block legitimate users

-----------------------------------
VPN EFFECTS
-----------------------------------

VPN usage may:
- alter apparent geographic location

-----------------------------------
SECURITY BENEFITS
-----------------------------------

Geofencing helps reduce:
- unauthorized foreign access
- credential abuse
- suspicious remote logins

-----------------------------------
GEOFENCING VS GEOFILTERING
-----------------------------------

{{{
Additional Context:
Some vendors distinguish:
- geofencing = location boundary enforcement
- geofiltering = traffic filtering by region

Terminology varies by platform/vendor.

Source:
Vendor Security Documentation
}}}

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Authorization determines permissions
- Least privilege minimizes permissions
- RBAC assigns permissions by role
- Geofencing restricts access by location
- Authentication verifies identity
- Authorization controls allowed actions
- Least privilege reduces attack surface
- RBAC improves scalability
- Geofencing commonly uses IP geolocation

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A user can log in but cannot modify files."

Answer:
Authorization restriction

-----------------------------------

Scenario:
"A company limits employees to only necessary permissions."

Answer:
Least privilege

-----------------------------------

Scenario:
"Permissions are assigned based on job role."

Answer:
RBAC

-----------------------------------

Scenario:
"A company blocks administrative logins from foreign countries."

Answer:
Geofencing

-----------------------------------

Scenario:
"A hospital grants nurses access only to patient records relevant to their role."

Answer:
RBAC/least privilege

-----------------------------------

Scenario:
"A company wants easier permission management for thousands of users."

Answer:
RBAC

-----------------------------------

Scenario:
"A cloud platform denies access from unauthorized regions."

Answer:
Geofencing

-----------------------------------

Scenario:
"A user is authenticated successfully but denied access to a resource."

Answer:
Authorization failure

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing authentication and authorization.

Authentication:
- verifies identity

Authorization:
- controls permissions

-----------------------------------

Trap:
Thinking least privilege means no access.

Wrong.

Least privilege means:
- only necessary access

-----------------------------------

Trap:
Thinking RBAC assigns permissions individually.

Wrong.

RBAC assigns:
- permissions by role/group

-----------------------------------

Trap:
Thinking geofencing guarantees attacker prevention.

Wrong.

VPNs/proxies may affect geolocation.

-----------------------------------

Trap:
Thinking geofencing uses only GPS.

Wrong.

It commonly uses:
- IP geolocation
- device location data

-----------------------------------

Trap:
Thinking RBAC and least privilege are unrelated.

Wrong.

RBAC commonly helps implement:
- least privilege

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Authentication =
Who are you?

Authorization =
What can you do?

Least privilege =
Minimum access

RBAC =
Permissions by role

Geofencing =
Location-based access

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does authorization determine?

A:
What actions/resources a user may access.

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
How does RBAC assign permissions?

A:
Based on organizational roles/groups.

-----------------------------------

Q:
What is geofencing?

A:
Restricting access based on geographic location.

-----------------------------------

Q:
What is the difference between authentication and authorization?

A:
Authentication verifies identity; authorization controls permissions.

-----------------------------------

Q:
Why is least privilege important?

A:
It reduces attack surface and security risk.

-----------------------------------

Q:
What is a major advantage of RBAC?

A:
Simplified scalable permission management.

-----------------------------------

Q:
What information commonly supports geofencing?

A:
IP geolocation data.

-----------------------------------

Q:
How can VPNs affect geofencing?

A:
VPNs may alter apparent geographic location.