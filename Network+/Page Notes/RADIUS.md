========================
RADIUS
Remote Authentication
Dial-In User Service
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
RADIUS
-----------------------------------

RADIUS =
Remote Authentication Dial-In User Service

-----------------------------------
CORE PURPOSE
-----------------------------------

RADIUS provides:
- centralized authentication
- authorization
- accounting

-----------------------------------
AAA
-----------------------------------

RADIUS is heavily associated with:
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
AUTHORIZATION
-----------------------------------

Authorization determines:
- permissions/access rights

-----------------------------------
ACCOUNTING
-----------------------------------

Accounting tracks:
- user activity
- session usage
- connection details

-----------------------------------
WHY RADIUS EXISTS
-----------------------------------

Without centralized authentication:
- devices may require separate local accounts

This creates:
- management complexity
- inconsistent security
- scalability problems

-----------------------------------
CENTRALIZED AUTHENTICATION
-----------------------------------

RADIUS centralizes:
- user authentication management

-----------------------------------
COMMON RADIUS USE CASES
-----------------------------------

Examples:
- WiFi authentication
- VPN authentication
- network access control
- remote access services

-----------------------------------
WIRELESS NETWORKS
-----------------------------------

RADIUS is heavily used in:
- enterprise wireless environments

-----------------------------------
802.1X
-----------------------------------

{{{
Additional Context:
RADIUS commonly works with:
- 802.1X authentication

Source:
Cisco 802.1X Authentication Guide
https://www.cisco.com/
}}}

-----------------------------------
802.1X PURPOSE
-----------------------------------

802.1X provides:
- port-based network access control

-----------------------------------
HOW RADIUS WORKS
-----------------------------------

Typical process:
1. User attempts connection
2. Network device forwards credentials
3. RADIUS server validates credentials
4. Access is approved or denied

-----------------------------------
AUTHENTICATOR
-----------------------------------

The network device forwarding credentials is often called:
- the authenticator

-----------------------------------
AUTHENTICATOR EXAMPLES
-----------------------------------

Examples:
- wireless AP
- switch
- VPN concentrator

-----------------------------------
RADIUS SERVER
-----------------------------------

The RADIUS server:
- validates credentials
- applies policies
- returns authorization decisions

-----------------------------------
DIRECTORY SERVICES
-----------------------------------

RADIUS commonly integrates with:
- Active Directory
- LDAP
- identity systems

-----------------------------------
LDAP
-----------------------------------

LDAP =
Lightweight Directory Access Protocol

-----------------------------------
LDAP PURPOSE
-----------------------------------

LDAP supports:
- centralized directory/authentication services

-----------------------------------
WIRELESS AUTHENTICATION
-----------------------------------

Enterprise WiFi commonly uses:
- WPA2-Enterprise
- WPA3-Enterprise

with:
- RADIUS authentication

-----------------------------------
ENTERPRISE VS PSK
-----------------------------------

WPA2/WPA3 Personal:
- shared password (PSK)

WPA2/WPA3 Enterprise:
- centralized authentication via RADIUS

-----------------------------------
WHY ENTERPRISE AUTHENTICATION MATTERS
-----------------------------------

Enterprise authentication improves:
- accountability
- scalability
- credential management
- access control

-----------------------------------
ACCOUNTING FEATURES
-----------------------------------

RADIUS accounting may log:
- login times
- session duration
- bandwidth usage
- connection events

-----------------------------------
WHY ACCOUNTING MATTERS
-----------------------------------

Accounting supports:
- auditing
- monitoring
- investigations
- billing/reporting

-----------------------------------
RADIUS PORTS
-----------------------------------

{{{
Additional Context:
Common RADIUS ports:
- UDP 1812 = authentication
- UDP 1813 = accounting

Older implementations:
- UDP 1645/1646

Source:
IANA Service Registry
https://www.iana.org/
}}}

-----------------------------------
SHARED SECRET
-----------------------------------

RADIUS commonly uses:
- shared secrets

-----------------------------------
SHARED SECRET PURPOSE
-----------------------------------

Shared secrets help secure:
- communication between devices and RADIUS servers

-----------------------------------
ENCRYPTION
-----------------------------------

RADIUS encrypts:
- passwords during transmission

-----------------------------------
IMPORTANT SECURITY NOTE
-----------------------------------

Traditional RADIUS does NOT fully encrypt:
- all traffic contents

-----------------------------------
RADIUS VS TACACS+
-----------------------------------

RADIUS:
- commonly used for network access authentication

TACACS+:
- commonly used for device administration

-----------------------------------
RADIUS VS TACACS+ SECURITY
-----------------------------------

{{{
Additional Context:
TACACS+ encrypts the full packet body, while traditional RADIUS encrypts mainly passwords.

Source:
Cisco TACACS+ Documentation
https://www.cisco.com/
}}}

-----------------------------------
FAILOVER
-----------------------------------

Organizations commonly deploy:
- redundant RADIUS servers

-----------------------------------
WHY REDUNDANCY MATTERS
-----------------------------------

If RADIUS fails:
- users may lose authentication capability

-----------------------------------
NAC
-----------------------------------

{{{
Additional Context:
RADIUS is commonly used with NAC:
- Network Access Control

Source:
Cisco NAC Concepts
https://www.cisco.com/
}}}

-----------------------------------
NAC PURPOSE
-----------------------------------

NAC helps:
- enforce security policies
- validate endpoint compliance
- restrict unauthorized devices

-----------------------------------
CERTIFICATE AUTHENTICATION
-----------------------------------

RADIUS may support:
- certificate-based authentication

-----------------------------------
EAP
-----------------------------------

{{{
Additional Context:
EAP =
Extensible Authentication Protocol

RADIUS commonly transports EAP authentication methods.

Source:
RFC 3748 EAP
https://datatracker.ietf.org/
}}}

-----------------------------------
EAP METHODS
-----------------------------------

{{{
Additional Context:
Common EAP methods:
- EAP-TLS
- PEAP
- EAP-TTLS

Source:
Cisco EAP Authentication Guide
https://www.cisco.com/
}}}

-----------------------------------
LOGGING
-----------------------------------

RADIUS systems commonly log:
- authentication attempts
- failures
- connection events

-----------------------------------
SECURITY BENEFITS
-----------------------------------

RADIUS helps improve:
- centralized security
- access management
- accountability

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- RADIUS = Remote Authentication Dial-In User Service
- RADIUS provides AAA services
- RADIUS centralizes authentication
- RADIUS commonly supports enterprise WiFi
- WPA2/WPA3 Enterprise commonly use RADIUS
- RADIUS commonly uses UDP 1812 and 1813
- 802.1X commonly works with RADIUS
- RADIUS commonly integrates with LDAP/AD
- TACACS+ commonly manages admin access

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company centrally authenticates enterprise WiFi users."

Answer:
RADIUS

-----------------------------------

Scenario:
"A switch forwards authentication requests to a centralized server."

Answer:
RADIUS authentication

-----------------------------------

Scenario:
"A business uses WPA2-Enterprise wireless authentication."

Answer:
RADIUS

-----------------------------------

Scenario:
"A company logs user session connection information."

Answer:
RADIUS accounting

-----------------------------------

Scenario:
"A network uses centralized AAA services."

Answer:
RADIUS

-----------------------------------

Scenario:
"A VPN appliance validates users against a central authentication server."

Answer:
RADIUS

-----------------------------------

Scenario:
"A company uses port-based authentication for wired/wireless access."

Answer:
802.1X with RADIUS

-----------------------------------

Scenario:
"A company uses shared passwords for WiFi instead of individual accounts."

Answer:
WPA2 Personal/PSK, not RADIUS enterprise authentication

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing RADIUS and TACACS+.

RADIUS:
- network access authentication

TACACS+:
- device administration

-----------------------------------

Trap:
Thinking WPA2 Personal uses RADIUS.

Wrong.

WPA2 Personal:
- PSK/shared password

WPA2 Enterprise:
- RADIUS

-----------------------------------

Trap:
Thinking RADIUS only authenticates dial-up users.

Wrong.

Modern RADIUS commonly supports:
- WiFi
- VPNs
- NAC
- enterprise access control

-----------------------------------

Trap:
Thinking RADIUS fully encrypts all traffic contents.

Wrong.

Traditional RADIUS mainly encrypts:
- passwords

-----------------------------------

Trap:
Thinking accounting means billing only.

Wrong.

Accounting also tracks:
- session activity
- login times
- auditing information

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

RADIUS =
Centralized AAA

802.1X =
Port-based access control

Enterprise WiFi =
RADIUS

Authentication =
Identity verification

Accounting =
Session tracking

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does RADIUS stand for?

A:
Remote Authentication Dial-In User Service.

-----------------------------------

Q:
What services does RADIUS provide?

A:
AAA services.

-----------------------------------

Q:
What does AAA stand for?

A:
Authentication, Authorization, Accounting.

-----------------------------------

Q:
What is a common use of RADIUS?

A:
Enterprise WiFi authentication.

-----------------------------------

Q:
What type of wireless security commonly uses RADIUS?

A:
WPA2/WPA3 Enterprise.

-----------------------------------

Q:
What protocol commonly works with RADIUS for port-based access control?

A:
802.1X.

-----------------------------------

Q:
What ports commonly support RADIUS?

A:
UDP 1812 and UDP 1813.

-----------------------------------

Q:
What does RADIUS accounting track?

A:
Session activity and connection information.

-----------------------------------

Q:
What is the difference between RADIUS and TACACS+?

A:
RADIUS commonly manages network access authentication; TACACS+ commonly manages administrative access.

-----------------------------------

Q:
What is the purpose of centralized authentication?

A:
Simplify management and improve security consistency.