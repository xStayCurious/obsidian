========================
SAML
Security Assertion
Markup Language
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
SAML
-----------------------------------

SAML =
Security Assertion Markup Language

-----------------------------------
CORE PURPOSE
-----------------------------------

SAML provides:
- federated authentication
- Single Sign-On (SSO)
- identity sharing between systems

-----------------------------------
WHY SAML EXISTS
-----------------------------------

Organizations commonly use:
- multiple applications
- cloud services
- external platforms

Users should not need:
- separate credentials for every service

-----------------------------------
SINGLE SIGN-ON
-----------------------------------

SAML is heavily associated with:
- SSO

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
- access multiple systems/services

-----------------------------------
FEDERATION
-----------------------------------

SAML supports:
- federated identity management

-----------------------------------
FEDERATION PURPOSE
-----------------------------------

Federation allows:
- identity sharing across organizations/systems

-----------------------------------
IDENTITY PROVIDER
-----------------------------------

IdP =
Identity Provider

-----------------------------------
IDP PURPOSE
-----------------------------------

The Identity Provider:
- authenticates users

-----------------------------------
IDP EXAMPLES
-----------------------------------

Examples:
- Active Directory Federation Services
- Okta
- Microsoft Entra ID
- Google Identity

-----------------------------------
SERVICE PROVIDER
-----------------------------------

SP =
Service Provider

-----------------------------------
SP PURPOSE
-----------------------------------

The Service Provider:
- provides applications/services
and:
- trusts the IdP authentication

-----------------------------------
SAML AUTHENTICATION FLOW
-----------------------------------

Typical process:

1. User requests application access
2. Service Provider redirects to IdP
3. IdP authenticates user
4. IdP sends SAML assertion
5. SP grants access

-----------------------------------
ASSERTIONS
-----------------------------------

SAML commonly exchanges:
- assertions

-----------------------------------
ASSERTION PURPOSE
-----------------------------------

Assertions contain:
- authentication information
- identity data
- authorization information

-----------------------------------
XML
-----------------------------------

SAML commonly uses:
- XML

-----------------------------------
XML
-----------------------------------

XML =
Extensible Markup Language

-----------------------------------
WHY XML MATTERS
-----------------------------------

SAML assertions are commonly:
- XML-based documents

-----------------------------------
TRUST RELATIONSHIPS
-----------------------------------

SAML relies heavily on:
- trust relationships

-----------------------------------
WHY TRUST MATTERS
-----------------------------------

The Service Provider must trust:
- the Identity Provider

-----------------------------------
DIGITAL SIGNATURES
-----------------------------------

SAML commonly uses:
- digital signatures

-----------------------------------
DIGITAL SIGNATURE PURPOSE
-----------------------------------

Digital signatures help verify:
- integrity
- authenticity

-----------------------------------
PKI
-----------------------------------

SAML commonly relies on:
- PKI

-----------------------------------
PKI
-----------------------------------

PKI =
Public Key Infrastructure

-----------------------------------
ENCRYPTION
-----------------------------------

SAML may use:
- encryption
- signed assertions

-----------------------------------
CLOUD APPLICATIONS
-----------------------------------

SAML is extremely common in:
- cloud/SaaS environments

-----------------------------------
COMMON SAML USE CASES
-----------------------------------

Examples:
- Microsoft 365
- Salesforce
- Google Workspace
- enterprise web applications

-----------------------------------
WEB-BASED AUTHENTICATION
-----------------------------------

SAML is primarily associated with:
- web/browser authentication

-----------------------------------
SAML VS LDAP
-----------------------------------

LDAP:
- directory access/authentication

SAML:
- federated SSO/authentication assertions

-----------------------------------
SAML VS RADIUS
-----------------------------------

RADIUS:
- network access authentication

SAML:
- web/application SSO federation

-----------------------------------
SAML VS OAUTH
-----------------------------------

{{{
Additional Context:
OAuth primarily handles authorization/delegated access.

SAML primarily handles authentication and SSO.

Source:
OAuth 2.0 RFC 6749
https://datatracker.ietf.org/
}}}

-----------------------------------
SAML VS OPENID CONNECT
-----------------------------------

{{{
Additional Context:
OpenID Connect is a modern authentication layer built on OAuth 2.0.

Source:
OpenID Foundation Documentation
https://openid.net/
}}}

-----------------------------------
MFA INTEGRATION
-----------------------------------

SAML environments commonly integrate:
- MFA

-----------------------------------
WHY MFA MATTERS
-----------------------------------

MFA improves security for:
- centralized SSO systems

-----------------------------------
CENTRALIZED AUTHENTICATION BENEFITS
-----------------------------------

Benefits:
- simplified user experience
- reduced password fatigue
- centralized identity management
- easier account control

-----------------------------------
CENTRALIZED AUTHENTICATION RISKS
-----------------------------------

Risks:
- compromised IdP credentials may affect many systems

-----------------------------------
ACCOUNT PROVISIONING
-----------------------------------

{{{
Additional Context:
Federated identity systems may automate account provisioning/deprovisioning.

Source:
Microsoft Identity Federation Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
SECURITY BENEFITS
-----------------------------------

SAML may improve:
- centralized security management
- auditing
- identity consistency

-----------------------------------
LOGGING
-----------------------------------

SAML systems commonly log:
- login events
- federation activity
- authentication attempts

-----------------------------------
TIME SYNCHRONIZATION
-----------------------------------

{{{
Additional Context:
SAML assertions often rely on accurate timestamps and synchronized clocks.

Source:
OASIS SAML Documentation
https://www.oasis-open.org/
}}}

-----------------------------------
WHY TIME MATTERS
-----------------------------------

Incorrect time synchronization may:
- invalidate assertions
- break authentication

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- SAML = Security Assertion Markup Language
- SAML supports SSO
- SAML supports federated identity
- IdP authenticates users
- SP provides services/applications
- SAML commonly uses XML
- Assertions contain authentication information
- SAML commonly supports cloud applications
- SAML relies on trust relationships
- SAML commonly integrates with MFA

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A user logs in once and accesses multiple cloud applications."

Answer:
SAML/SSO

-----------------------------------

Scenario:
"A cloud application trusts an external authentication provider."

Answer:
Federated identity/SAML

-----------------------------------

Scenario:
"A system redirects users to a centralized login provider."

Answer:
Identity Provider (IdP)

-----------------------------------

Scenario:
"A web application receives authentication assertions."

Answer:
SAML assertion

-----------------------------------

Scenario:
"A company uses centralized authentication for SaaS applications."

Answer:
SAML federation

-----------------------------------

Scenario:
"A login system shares identities across organizations."

Answer:
Federation/SAML

-----------------------------------

Scenario:
"A protocol uses XML-based authentication assertions."

Answer:
SAML

-----------------------------------

Scenario:
"A company wants reduced password fatigue for employees."

Answer:
SSO/SAML

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing authentication and authorization.

SAML:
- primarily authentication/SSO

OAuth:
- authorization/delegated access

-----------------------------------

Trap:
Thinking SAML replaces LDAP.

Wrong.

LDAP:
- directory service

SAML:
- federated SSO/authentication

-----------------------------------

Trap:
Thinking SAML is mainly for network device authentication.

Wrong.

SAML is mainly associated with:
- web/cloud applications

-----------------------------------

Trap:
Confusing IdP and SP.

IdP:
- authenticates users

SP:
- provides services

-----------------------------------

Trap:
Thinking SAML eliminates need for MFA.

Wrong.

MFA is commonly integrated with SAML.

-----------------------------------

Trap:
Thinking SAML stores user accounts directly.

Wrong.

SAML primarily:
- exchanges authentication assertions

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

SAML =
Federated SSO

IdP =
Authenticates users

SP =
Provides applications

Assertion =
Authentication proof

XML =
SAML data format

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does SAML stand for?

A:
Security Assertion Markup Language.

-----------------------------------

Q:
What is the primary purpose of SAML?

A:
Federated authentication and Single Sign-On.

-----------------------------------

Q:
What does SSO stand for?

A:
Single Sign-On.

-----------------------------------

Q:
What is an Identity Provider?

A:
A system that authenticates users.

-----------------------------------

Q:
What is a Service Provider?

A:
A system/application providing services to users.

-----------------------------------

Q:
What does a SAML assertion contain?

A:
Authentication and identity information.

-----------------------------------

Q:
What data format does SAML commonly use?

A:
XML.

-----------------------------------

Q:
What is federation?

A:
Identity sharing across organizations/systems.

-----------------------------------

Q:
What is a common use case for SAML?

A:
Cloud/SaaS Single Sign-On.

-----------------------------------

Q:
What is the difference between SAML and OAuth?

A:
SAML primarily handles authentication; OAuth primarily handles authorization.