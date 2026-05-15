========================
TACACS+
Terminal Access Controller
Access-Control System Plus
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
TACACS+
-----------------------------------

TACACS+ =
Terminal Access Controller
Access-Control System Plus

-----------------------------------
CORE PURPOSE
-----------------------------------

TACACS+ provides:
- centralized authentication
- authorization
- accounting

primarily for:
- administrative access management

-----------------------------------
AAA
-----------------------------------

TACACS+ is heavily associated with:
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
- permissions/actions allowed

-----------------------------------
ACCOUNTING
-----------------------------------

Accounting tracks:
- administrative activity
- commands
- session information

-----------------------------------
WHY TACACS+ EXISTS
-----------------------------------

Organizations need:
- centralized management of administrator access

Without centralized AAA:
- devices may require local accounts
- management becomes inconsistent
- auditing becomes difficult

-----------------------------------
CENTRALIZED MANAGEMENT
-----------------------------------

TACACS+ centralizes:
- administrative authentication/control

-----------------------------------
COMMON TACACS+ USE CASES
-----------------------------------

Examples:
- router administration
- switch administration
- firewall administration
- infrastructure management

-----------------------------------
DEVICE ADMINISTRATION
-----------------------------------

TACACS+ is strongly associated with:
- network device administration

-----------------------------------
CLI ACCESS
-----------------------------------

TACACS+ commonly controls:
- CLI administrative access

-----------------------------------
WHY CLI CONTROL MATTERS
-----------------------------------

Administrative commands may:
- modify infrastructure
- affect security
- impact operations

-----------------------------------
GRANULAR AUTHORIZATION
-----------------------------------

TACACS+ provides:
- very granular authorization control

-----------------------------------
GRANULAR CONTROL PURPOSE
-----------------------------------

Administrators may be:
- restricted to specific commands/actions

-----------------------------------
EXAMPLE
-----------------------------------

Example:
Junior admin:
- view configurations only

Senior admin:
- modify configurations

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

TACACS+ commonly offers:
- more granular administrative control than RADIUS

-----------------------------------
HOW TACACS+ WORKS
-----------------------------------

Typical process:

1. Administrator attempts login
2. Device forwards credentials
3. TACACS+ server validates credentials
4. Permissions are applied
5. Activity may be logged

-----------------------------------
TACACS+ SERVER
-----------------------------------

The TACACS+ server:
- validates identities
- applies authorization policies
- logs administrative activity

-----------------------------------
AUTHORIZATION CONTROL
-----------------------------------

TACACS+ may control:
- which commands users may execute

-----------------------------------
ACCOUNTING FEATURES
-----------------------------------

TACACS+ accounting may log:
- login events
- commands executed
- session duration
- configuration changes

-----------------------------------
WHY ACCOUNTING MATTERS
-----------------------------------

Accounting supports:
- auditing
- investigations
- compliance
- administrator accountability

-----------------------------------
ENCRYPTION
-----------------------------------

TACACS+ encrypts:
- the packet body

-----------------------------------
IMPORTANT SECURITY FACT
-----------------------------------

Compared to traditional RADIUS:
- TACACS+ encrypts more authentication traffic

-----------------------------------
TACACS+ VS RADIUS
-----------------------------------

TACACS+:
- administrative access management

RADIUS:
- network access authentication

-----------------------------------
RADIUS COMMON USES
-----------------------------------

RADIUS commonly supports:
- WiFi authentication
- VPN authentication
- NAC

-----------------------------------
TACACS+ COMMON USES
-----------------------------------

TACACS+ commonly supports:
- routers
- switches
- firewalls
- infrastructure administration

-----------------------------------
TRANSPORT PROTOCOL
-----------------------------------

{{{
Additional Context:
TACACS+ commonly uses:
- TCP port 49

Source:
Cisco TACACS+ Documentation
https://www.cisco.com/
}}}

-----------------------------------
TCP VS UDP
-----------------------------------

{{{
Additional Context:
Traditional RADIUS commonly uses UDP, while TACACS+ commonly uses TCP.

Source:
Cisco TACACS+ Documentation
https://www.cisco.com/
}}}

-----------------------------------
SHARED SECRET
-----------------------------------

TACACS+ commonly uses:
- shared secrets

-----------------------------------
SHARED SECRET PURPOSE
-----------------------------------

Shared secrets help secure:
- communication between devices and TACACS+ servers

-----------------------------------
REDUNDANCY
-----------------------------------

Organizations commonly deploy:
- redundant TACACS+ servers

-----------------------------------
WHY REDUNDANCY MATTERS
-----------------------------------

If TACACS+ fails:
- administrative authentication may fail

-----------------------------------
LOCAL FALLBACK
-----------------------------------

Devices may support:
- local fallback accounts

-----------------------------------
WHY LOCAL FALLBACK MATTERS
-----------------------------------

Fallback accounts help administrators:
- recover access during AAA outages

-----------------------------------
LDAP/AD INTEGRATION
-----------------------------------

{{{
Additional Context:
TACACS+ servers may integrate with:
- LDAP
- Active Directory

Source:
Cisco Identity Services Engine Documentation
https://www.cisco.com/
}}}

-----------------------------------
MFA
-----------------------------------

{{{
Additional Context:
Administrative AAA systems may integrate MFA for stronger security.

Source:
Cisco Secure Access Documentation
https://www.cisco.com/
}}}

-----------------------------------
COMMAND AUTHORIZATION
-----------------------------------

TACACS+ may authorize:
- individual commands

-----------------------------------
WHY COMMAND AUTHORIZATION MATTERS
-----------------------------------

This improves:
- least privilege
- administrative control
- auditing

-----------------------------------
SECURITY BENEFITS
-----------------------------------

TACACS+ helps improve:
- centralized administration
- auditing
- accountability
- administrator security

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- TACACS+ provides AAA services
- TACACS+ commonly manages admin access
- TACACS+ commonly controls network devices
- TACACS+ provides granular authorization
- TACACS+ encrypts packet bodies
- TACACS+ commonly uses TCP 49
- TACACS+ accounting tracks commands/actions
- RADIUS commonly manages network access authentication
- TACACS+ is commonly used for CLI administration

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company centrally manages router administrator logins."

Answer:
TACACS+

-----------------------------------

Scenario:
"A network administrator's commands are individually authorized."

Answer:
TACACS+

-----------------------------------

Scenario:
"A company tracks every command executed on switches."

Answer:
TACACS+ accounting

-----------------------------------

Scenario:
"A centralized AAA server controls firewall administration."

Answer:
TACACS+

-----------------------------------

Scenario:
"A protocol encrypts the full packet body for admin AAA."

Answer:
TACACS+

-----------------------------------

Scenario:
"A company centrally authenticates enterprise WiFi users."

Answer:
RADIUS, not TACACS+

-----------------------------------

Scenario:
"A protocol commonly uses TCP port 49."

Answer:
TACACS+

-----------------------------------

Scenario:
"A network uses centralized command authorization for administrators."

Answer:
TACACS+

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing TACACS+ and RADIUS.

TACACS+:
- administrative access

RADIUS:
- network access authentication

-----------------------------------

Trap:
Thinking TACACS+ is mainly for WiFi authentication.

Wrong.

RADIUS commonly handles:
- enterprise WiFi authentication

-----------------------------------

Trap:
Thinking TACACS+ only authenticates users.

Wrong.

TACACS+ also provides:
- authorization
- accounting

-----------------------------------

Trap:
Thinking TACACS+ and RADIUS encrypt the same amount of traffic.

Wrong.

TACACS+ encrypts:
- the packet body

Traditional RADIUS mainly encrypts:
- passwords

-----------------------------------

Trap:
Thinking authorization and authentication are identical.

Authentication:
- verifies identity

Authorization:
- determines allowed actions

-----------------------------------

Trap:
Thinking TACACS+ eliminates need for local fallback access.

Wrong.

Organizations commonly maintain:
- emergency local accounts

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

TACACS+ =
Admin AAA

RADIUS =
User/network AAA

TCP 49 =
TACACS+

Granular command control =
TACACS+

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does TACACS+ stand for?

A:
Terminal Access Controller Access-Control System Plus.

-----------------------------------

Q:
What services does TACACS+ provide?

A:
AAA services.

-----------------------------------

Q:
What does AAA stand for?

A:
Authentication, Authorization, Accounting.

-----------------------------------

Q:
What is TACACS+ primarily used for?

A:
Administrative access management.

-----------------------------------

Q:
What type of control is TACACS+ known for?

A:
Granular command authorization.

-----------------------------------

Q:
What port does TACACS+ commonly use?

A:
TCP 49.

-----------------------------------

Q:
What does TACACS+ accounting track?

A:
Administrative commands and session activity.

-----------------------------------

Q:
What is the primary difference between TACACS+ and RADIUS?

A:
TACACS+ commonly manages admin access; RADIUS commonly manages network access authentication.

-----------------------------------

Q:
Why is TACACS+ considered secure?

A:
It encrypts the packet body.

-----------------------------------

Q:
Why are local fallback accounts important?

A:
They allow emergency access during AAA outages.