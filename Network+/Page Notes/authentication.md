========================
Wireless Authentication
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 2.3: Wireless Devices and Technologies
Pages 45–50
0 1

-----------------------------------
AUTHENTICATION
-----------------------------------

Authentication is:
- the process of verifying identity

In wireless networking:
- authentication determines whether a device or user is allowed to join the network

-----------------------------------
CORE PURPOSE
-----------------------------------

Wireless authentication helps:
- prevent unauthorized access
- control who connects to WiFi
- protect internal resources
- enforce security policies

-----------------------------------
AUTHENTICATION VS ENCRYPTION
-----------------------------------

Very important exam distinction:

Authentication:
- verifies identity

Encryption:
- protects confidentiality of data

-----------------------------------
WHY AUTHENTICATION MATTERS
-----------------------------------

Without authentication:
- unauthorized users may access the network
- attackers may gain LAN access
- internal systems become exposed

-----------------------------------
COMMON AUTHENTICATION METHODS
-----------------------------------

The guide focuses on:
- PSK
- Enterprise authentication
- RADIUS

Very common related exam concepts:
- 802.1X
- captive portals

-----------------------------------
PSK
-----------------------------------

PSK =
Pre-Shared Key

-----------------------------------
PSK PURPOSE
-----------------------------------

PSK uses:
- a shared wireless password/passphrase

All authorized users:
- use the same password

-----------------------------------
PSK CHARACTERISTICS
-----------------------------------

- simple setup
- common in homes
- common in small offices
- low administrative overhead

-----------------------------------
PSK ADVANTAGES
-----------------------------------

Advantages:
- easy configuration
- inexpensive deployment
- no authentication server required

-----------------------------------
PSK DISADVANTAGES
-----------------------------------

Disadvantages:
- all users share the same key
- weak accountability
- difficult credential rotation
- compromised password affects all users

-----------------------------------
PSK EXAM IDEA
-----------------------------------

PSK is best associated with:
- home WiFi
- small office WiFi
- shared passwords

-----------------------------------
ENTERPRISE AUTHENTICATION
-----------------------------------

Enterprise authentication uses:
- centralized authentication systems
- individual user credentials

-----------------------------------
ENTERPRISE AUTHENTICATION PURPOSE
-----------------------------------

Enterprise authentication improves:
- access control
- accountability
- centralized management
- security

-----------------------------------
RADIUS
-----------------------------------

RADIUS =
Remote Authentication Dial-In User Service

-----------------------------------
RADIUS PURPOSE
-----------------------------------

RADIUS provides:
- centralized authentication
- centralized authorization
- centralized accounting

-----------------------------------
RADIUS CHARACTERISTICS
-----------------------------------

RADIUS:
- validates user credentials
- supports enterprise WiFi
- manages centralized access control

-----------------------------------
AAA
-----------------------------------

{{{
Additional Context:
RADIUS commonly supports AAA:
- Authentication
- Authorization
- Accounting

Source:
Cisco AAA Overview
https://www.cisco.com/
}}}

-----------------------------------
802.1X
-----------------------------------

{{{
Additional Context:
802.1X is the common framework used for enterprise wireless authentication.

Source:
Cisco 802.1X Authentication Overview
https://www.cisco.com/
}}}

-----------------------------------
802.1X PURPOSE
-----------------------------------

802.1X provides:
- port-based access control
- enterprise authentication framework

-----------------------------------
802.1X COMPONENTS
-----------------------------------

Important 802.1X roles:

Supplicant:
- client requesting access

Authenticator:
- AP/switch controlling access

Authentication server:
- usually RADIUS

-----------------------------------
802.1X EXAM IDEA
-----------------------------------

If a question asks:
"What authentication framework commonly works with enterprise wireless and RADIUS?"

Answer:
802.1X

-----------------------------------
PERSONAL VS ENTERPRISE MODE
-----------------------------------

Personal mode:
- PSK/shared password

Enterprise mode:
- centralized individual authentication

-----------------------------------
WPA/WPA2/WPA3 RELATIONSHIP
-----------------------------------

Wireless authentication commonly operates alongside:
- WPA
- WPA2
- WPA3

-----------------------------------
WPA PERSONAL
-----------------------------------

WPA/WPA2/WPA3 Personal:
- use PSK authentication

-----------------------------------
WPA ENTERPRISE
-----------------------------------

WPA/WPA2/WPA3 Enterprise:
- use RADIUS/802.1X authentication

-----------------------------------
OPEN AUTHENTICATION
-----------------------------------

Open authentication:
- allows clients to connect without credentials

-----------------------------------
OPEN NETWORK RISKS
-----------------------------------

Open networks:
- allow unauthorized access more easily
- often lack encryption
- increase exposure risks

-----------------------------------
CAPTIVE PORTALS
-----------------------------------

Guest networks commonly use:
- captive portals

-----------------------------------
CAPTIVE PORTAL PURPOSE
-----------------------------------

Captive portals may require:
- login
- agreement acceptance
- payment
before:
- granting network access

-----------------------------------
CERTIFICATE AUTHENTICATION
-----------------------------------

{{{
Additional Context:
Enterprise wireless deployments may use digital certificates for authentication.

Source:
Cisco Enterprise Wireless Security Guide
https://www.cisco.com/
}}}

-----------------------------------
MULTIFACTOR AUTHENTICATION
-----------------------------------

{{{
Additional Context:
Some enterprise wireless deployments integrate MFA for stronger identity verification.

Source:
Microsoft Entra Wireless Authentication Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
AUTHENTICATION FAILURES
-----------------------------------

Common authentication problems:
- wrong PSK
- expired credentials
- RADIUS failures
- certificate problems
- unsupported encryption settings

-----------------------------------
ROGUE ACCESS POINTS
-----------------------------------

{{{
Additional Context:
Rogue APs may attempt to trick users into authenticating to fake wireless networks.

Source:
Cisco Wireless Threat Defense
https://www.cisco.com/
}}}

-----------------------------------
EVIL TWIN ATTACKS
-----------------------------------

{{{
Additional Context:
An evil twin attack uses a fake AP impersonating a legitimate SSID to capture credentials.

Source:
Wi-Fi Alliance Security Documentation
https://www.wi-fi.org/
}}}

-----------------------------------
MUTUAL AUTHENTICATION
-----------------------------------

{{{
Additional Context:
Enterprise authentication may support mutual authentication, where both the client and server verify each other.

Source:
Cisco EAP Authentication Guide
https://www.cisco.com/
}}}

-----------------------------------
EAP
-----------------------------------

{{{
Additional Context:
EAP =
Extensible Authentication Protocol

Used heavily with 802.1X enterprise authentication.

Source:
RFC 3748
https://datatracker.ietf.org/doc/html/rfc3748
}}}

-----------------------------------
COMMON EAP TYPES
-----------------------------------

{{{
Additional Context:
Common EAP methods include:
- PEAP
- EAP-TLS
- EAP-TTLS

Source:
Cisco EAP Authentication Methods
https://www.cisco.com/
}}}

-----------------------------------
EAP-TLS
-----------------------------------

{{{
Additional Context:
EAP-TLS uses certificate-based mutual authentication and is considered highly secure.

Source:
Cisco EAP-TLS Documentation
https://www.cisco.com/
}}}

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Authentication verifies identity
- Encryption protects confidentiality
- PSK = shared password
- Enterprise mode = individual credentials
- RADIUS provides centralized authentication
- 802.1X commonly works with RADIUS
- WPA Personal uses PSK
- WPA Enterprise uses RADIUS/802.1X
- Open authentication provides little security
- Captive portals commonly appear on guest networks

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A home wireless network uses one shared WiFi password."

Answer:
PSK

-----------------------------------

Scenario:
"A company wants centralized wireless authentication."

Answer:
RADIUS

-----------------------------------

Scenario:
"A company wants individual employee WiFi credentials."

Answer:
Enterprise authentication

-----------------------------------

Scenario:
"A wireless deployment uses 802.1X."

Answer:
Enterprise authentication framework

-----------------------------------

Scenario:
"A guest network requires acceptance of terms before access."

Answer:
Captive portal

-----------------------------------

Scenario:
"A wireless client provides a username/password to a RADIUS-backed network."

Answer:
Enterprise authentication

-----------------------------------

Scenario:
"A company wants the simplest wireless authentication setup."

Answer:
PSK

-----------------------------------

Scenario:
"A fake AP attempts to steal user credentials."

Answer:
Evil twin attack

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing authentication and encryption.

Authentication:
- verifies identity

Encryption:
- protects confidentiality

-----------------------------------

Trap:
Thinking PSK gives each user unique credentials.

Wrong.

PSK:
- shared password for all users

-----------------------------------

Trap:
Thinking enterprise authentication uses PSK only.

Wrong.

Enterprise mode commonly uses:
- RADIUS
- 802.1X

-----------------------------------

Trap:
Thinking open authentication is secure.

Wrong.

Open authentication:
- provides minimal/no access control

-----------------------------------

Trap:
Thinking RADIUS only works for wireless.

Wrong.

RADIUS can authenticate:
- VPNs
- wired access
- wireless access
- network devices

-----------------------------------

Trap:
Thinking captive portals themselves encrypt traffic.

Wrong.

Captive portals:
- control access
They do not inherently encrypt traffic.

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Authentication =
Verify identity

Encryption =
Protect data

PSK =
Shared password

Enterprise =
RADIUS + 802.1X

RADIUS =
Centralized authentication

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is authentication?

A:
The process of verifying identity.

-----------------------------------

Q:
What does authentication protect against?

A:
Unauthorized network access.

-----------------------------------

Q:
What does PSK stand for?

A:
Pre-Shared Key.

-----------------------------------

Q:
What is PSK authentication?

A:
Authentication using a shared wireless password.

-----------------------------------

Q:
What type of environments commonly use PSK?

A:
Home and small office networks.

-----------------------------------

Q:
What is the major weakness of PSK?

A:
All users share the same password.

-----------------------------------

Q:
What does RADIUS stand for?

A:
Remote Authentication Dial-In User Service.

-----------------------------------

Q:
What does RADIUS provide?

A:
Centralized authentication, authorization, and accounting.

-----------------------------------

Q:
What is 802.1X?

A:
A framework for enterprise authentication.

-----------------------------------

Q:
What type of authentication commonly uses 802.1X and RADIUS?

A:
Enterprise wireless authentication.

-----------------------------------

Q:
What is the difference between authentication and encryption?

A:
Authentication verifies identity; encryption protects data confidentiality.

-----------------------------------

Q:
What is an evil twin attack?

A:
A fake AP impersonating a legitimate wireless network.

-----------------------------------

Q:
What is open authentication?

A:
Authentication allowing connection without credentials.

-----------------------------------

Q:
What is a captive portal?

A:
A login or agreement page shown before granting network access.