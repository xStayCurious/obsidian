========================
PKI
Public Key Infrastructure
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
PKI
-----------------------------------

PKI =
Public Key Infrastructure

-----------------------------------
CORE PURPOSE
-----------------------------------

PKI provides:
- secure identity verification
- certificate management
- encryption support
- trust establishment

-----------------------------------
WHY PKI EXISTS
-----------------------------------

Systems communicating securely over networks must:
- verify identities
- exchange keys securely
- establish trust

PKI helps solve these problems.

-----------------------------------
PKI FUNCTIONS
-----------------------------------

PKI commonly supports:
- encryption
- authentication
- integrity
- nonrepudiation

-----------------------------------
CONFIDENTIALITY
-----------------------------------

PKI supports:
- confidential encrypted communication

-----------------------------------
AUTHENTICATION
-----------------------------------

PKI helps verify:
- identities of systems/users

-----------------------------------
INTEGRITY
-----------------------------------

PKI helps detect:
- tampering or data modification

-----------------------------------
NONREPUDIATION
-----------------------------------

Nonrepudiation helps prevent:
- denial of performed actions/signatures

-----------------------------------
ASYMMETRIC CRYPTOGRAPHY
-----------------------------------

PKI relies heavily on:
- asymmetric encryption

-----------------------------------
ASYMMETRIC ENCRYPTION
-----------------------------------

Asymmetric encryption uses:
- public keys
- private keys

-----------------------------------
PUBLIC KEY
-----------------------------------

Public keys:
- may be shared openly

-----------------------------------
PRIVATE KEY
-----------------------------------

Private keys:
- must remain secret

-----------------------------------
KEY PAIR
-----------------------------------

Public/private keys together form:
- a key pair

-----------------------------------
KEY PURPOSE
-----------------------------------

Public/private keys support:
- secure encryption
- authentication
- digital signatures

-----------------------------------
DIGITAL CERTIFICATES
-----------------------------------

PKI commonly uses:
- digital certificates

-----------------------------------
CERTIFICATE PURPOSE
-----------------------------------

Certificates help:
- verify identities
- bind public keys to identities

-----------------------------------
CERTIFICATE CONTENTS
-----------------------------------

Certificates commonly contain:
- public key
- subject name
- issuer information
- expiration dates
- digital signatures

-----------------------------------
CERTIFICATE AUTHORITIES
-----------------------------------

CA =
Certificate Authority

-----------------------------------
CA PURPOSE
-----------------------------------

Certificate Authorities:
- issue trusted certificates

-----------------------------------
WHY CAs MATTER
-----------------------------------

CAs establish:
- trust relationships

-----------------------------------
TRUST
-----------------------------------

If a system trusts a CA:
- it may trust certificates issued by that CA

-----------------------------------
ROOT CA
-----------------------------------

A Root CA is:
- a highly trusted top-level certificate authority

-----------------------------------
INTERMEDIATE CA
-----------------------------------

{{{
Additional Context:
Intermediate CAs help separate and protect root CA operations.

Source:
Microsoft PKI Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
CERTIFICATE CHAIN
-----------------------------------

Certificates may form:
- chains of trust

-----------------------------------
CHAIN OF TRUST
-----------------------------------

Trust flows from:
- trusted root CAs
through:
- intermediate CAs
to:
- endpoint certificates

-----------------------------------
CSR
-----------------------------------

CSR =
Certificate Signing Request

-----------------------------------
CSR PURPOSE
-----------------------------------

A CSR requests:
- certificate issuance from a CA

-----------------------------------
DIGITAL SIGNATURES
-----------------------------------

Digital signatures help verify:
- integrity
- authenticity

-----------------------------------
DIGITAL SIGNATURE PURPOSE
-----------------------------------

Digital signatures help confirm:
- data was not altered
- sender authenticity

-----------------------------------
HASHING
-----------------------------------

PKI commonly uses:
- hashing algorithms

-----------------------------------
HASH PURPOSE
-----------------------------------

Hashes help verify:
- data integrity

-----------------------------------
CERTIFICATE EXPIRATION
-----------------------------------

Certificates commonly contain:
- expiration dates

-----------------------------------
WHY EXPIRATION MATTERS
-----------------------------------

Expired certificates may:
- become invalid/untrusted

-----------------------------------
CERTIFICATE REVOCATION
-----------------------------------

Revocation invalidates:
- compromised or untrusted certificates

-----------------------------------
WHY REVOCATION EXISTS
-----------------------------------

Certificates may require revocation if:
- keys are compromised
- certificates were issued improperly

-----------------------------------
CRL
-----------------------------------

CRL =
Certificate Revocation List

-----------------------------------
CRL PURPOSE
-----------------------------------

CRLs list:
- revoked certificates

-----------------------------------
OCSP
-----------------------------------

OCSP =
Online Certificate Status Protocol

-----------------------------------
OCSP PURPOSE
-----------------------------------

OCSP allows:
- real-time certificate validity checking

-----------------------------------
TLS/HTTPS
-----------------------------------

PKI is heavily used in:
- TLS
- HTTPS

-----------------------------------
HTTPS CERTIFICATES
-----------------------------------

HTTPS websites commonly use:
- digital certificates

-----------------------------------
WHY HTTPS USES PKI
-----------------------------------

PKI helps browsers:
- verify website identities
- establish encrypted sessions

-----------------------------------
SSH AND PKI
-----------------------------------

{{{
Additional Context:
SSH commonly uses asymmetric cryptography and key pairs.

Source:
OpenSSH Documentation
https://www.openssh.com/
}}}

-----------------------------------
VPN AND PKI
-----------------------------------

VPNs may use PKI for:
- authentication
- certificate-based trust

-----------------------------------
EMAIL SECURITY
-----------------------------------

PKI may secure:
- email communications
- digital signatures

-----------------------------------
SMART CARDS
-----------------------------------

{{{
Additional Context:
Smart cards commonly store certificates and private keys securely.

Source:
NIST Smart Card Guidance
https://csrc.nist.gov/
}}}

-----------------------------------
SELF-SIGNED CERTIFICATES
-----------------------------------

Self-signed certificates are:
- signed by their own issuer

-----------------------------------
SELF-SIGNED RISKS
-----------------------------------

Browsers/systems may:
- not trust self-signed certificates automatically

-----------------------------------
COMMON PKI USE CASES
-----------------------------------

Examples:
- HTTPS websites
- VPN authentication
- email encryption
- wireless authentication
- digital signatures

-----------------------------------
WIRELESS SECURITY
-----------------------------------

{{{
Additional Context:
Enterprise WPA2/WPA3 environments may use certificates through 802.1X/EAP authentication.

Source:
Cisco Enterprise Wireless Security Guide
https://www.cisco.com/
}}}

-----------------------------------
PRIVATE KEY SECURITY
-----------------------------------

Private keys must remain:
- protected

-----------------------------------
WHY PRIVATE KEY SECURITY MATTERS
-----------------------------------

Compromised private keys may:
- compromise trust
- allow impersonation
- weaken encryption

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- PKI = Public Key Infrastructure
- PKI supports trust and certificate management
- Asymmetric encryption uses public/private keys
- Certificates bind identities to public keys
- CAs issue trusted certificates
- HTTPS heavily relies on PKI
- CRL lists revoked certificates
- OCSP checks certificate validity
- Digital signatures verify integrity/authenticity

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A browser validates a secure website certificate."

Answer:
PKI/Certificate Authority

-----------------------------------

Scenario:
"A company verifies identities using digital certificates."

Answer:
PKI

-----------------------------------

Scenario:
"A protocol checks whether certificates were revoked."

Answer:
OCSP or CRL

-----------------------------------

Scenario:
"A system uses public/private key pairs."

Answer:
Asymmetric cryptography

-----------------------------------

Scenario:
"A company issues trusted certificates internally."

Answer:
Certificate Authority

-----------------------------------

Scenario:
"A certificate request is submitted to a CA."

Answer:
CSR

-----------------------------------

Scenario:
"A website certificate expires."

Answer:
Certificate validity issue

-----------------------------------

Scenario:
"A VPN authenticates devices using certificates."

Answer:
PKI/certificate authentication

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing symmetric and asymmetric encryption.

Symmetric:
- same key

Asymmetric:
- public/private key pair

-----------------------------------

Trap:
Thinking certificates themselves encrypt data.

Wrong.

Certificates primarily:
- verify identity
- distribute public keys

-----------------------------------

Trap:
Thinking self-signed certificates are automatically trusted.

Wrong.

Trust usually requires:
- trusted CA validation

-----------------------------------

Trap:
Confusing CRL and OCSP.

CRL:
- downloaded revocation list

OCSP:
- real-time status checking

-----------------------------------

Trap:
Thinking public keys must remain secret.

Wrong.

Private keys must remain secret.

-----------------------------------

Trap:
Thinking PKI only supports HTTPS.

Wrong.

PKI also supports:
- VPNs
- email security
- wireless authentication
- digital signatures

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

PKI =
Trust infrastructure

CA =
Issues trust

Certificate =
Identity verification

Public key =
Shared openly

Private key =
Secret

OCSP =
Real-time validation

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does PKI stand for?

A:
Public Key Infrastructure.

-----------------------------------

Q:
What is the purpose of PKI?

A:
Provide trust, certificate management, and secure identity verification.

-----------------------------------

Q:
What type of cryptography does PKI commonly use?

A:
Asymmetric cryptography.

-----------------------------------

Q:
What is a Certificate Authority?

A:
A trusted entity that issues digital certificates.

-----------------------------------

Q:
What does a digital certificate contain?

A:
Identity information and a public key.

-----------------------------------

Q:
What is a CSR?

A:
Certificate Signing Request.

-----------------------------------

Q:
What is the purpose of a digital signature?

A:
Verify integrity and authenticity.

-----------------------------------

Q:
What does CRL stand for?

A:
Certificate Revocation List.

-----------------------------------

Q:
What does OCSP do?

A:
Checks certificate validity in real time.

-----------------------------------

Q:
What must remain secret in asymmetric cryptography?

A:
The private key.