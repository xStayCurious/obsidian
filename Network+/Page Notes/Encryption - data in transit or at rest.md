========================
Encryption
Data in Transit vs Data at Rest
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
ENCRYPTION
-----------------------------------

Encryption is:
- converting readable data into unreadable ciphertext

-----------------------------------
CORE PURPOSE
-----------------------------------

Encryption helps protect:
- confidentiality
- sensitive information
- communications
- stored data

-----------------------------------
WHY ENCRYPTION EXISTS
-----------------------------------

Without encryption:
- attackers may read intercepted/stolen data

-----------------------------------
PLAINTEXT
-----------------------------------

Plaintext is:
- readable original data

-----------------------------------
CIPHERTEXT
-----------------------------------

Ciphertext is:
- encrypted unreadable data

-----------------------------------
DECRYPTION
-----------------------------------

Decryption converts:
- ciphertext
back into:
- readable plaintext

-----------------------------------
KEYS
-----------------------------------

Encryption commonly uses:
- cryptographic keys

-----------------------------------
KEY PURPOSE
-----------------------------------

Keys help:
- encrypt
- decrypt
- protect data

-----------------------------------
MAIN EXAM TOPICS
-----------------------------------

Important Network+ concepts:
- data in transit
- data at rest

===================================
DATA IN TRANSIT
===================================

-----------------------------------
DATA IN TRANSIT
-----------------------------------

Data in transit is:
- data actively moving across a network

-----------------------------------
EXAMPLES
-----------------------------------

Examples:
- web traffic
- email traffic
- VPN traffic
- SSH sessions
- file transfers

-----------------------------------
WHY DATA IN TRANSIT NEEDS PROTECTION
-----------------------------------

Attackers may:
- intercept communications
- sniff packets
- perform man-in-the-middle attacks

-----------------------------------
ENCRYPTION PURPOSE
-----------------------------------

Transit encryption protects:
- network communications

-----------------------------------
COMMON TRANSIT ENCRYPTION PROTOCOLS
-----------------------------------

Examples:
- HTTPS
- TLS
- SSH
- IPsec
- VPNs

-----------------------------------
HTTPS
-----------------------------------

HTTPS:
- encrypts web traffic

-----------------------------------
TLS
-----------------------------------

TLS =
Transport Layer Security

-----------------------------------
TLS PURPOSE
-----------------------------------

TLS secures:
- network communications
- web sessions
- email traffic
- APIs

-----------------------------------
SSH
-----------------------------------

SSH provides:
- encrypted remote management access

-----------------------------------
VPN
-----------------------------------

VPNs create:
- encrypted tunnels across untrusted networks

-----------------------------------
IPSEC
-----------------------------------

{{{
Additional Context:
IPsec is commonly used to secure VPN communications.

Source:
RFC 4301 IPsec Architecture
https://datatracker.ietf.org/
}}}

-----------------------------------
MAN-IN-THE-MIDDLE ATTACKS
-----------------------------------

Transit encryption helps reduce risk from:
- MITM attacks

-----------------------------------
PACKET SNIFFING
-----------------------------------

Encryption protects against:
- readable packet interception

-----------------------------------
PUBLIC WIFI RISKS
-----------------------------------

Unencrypted traffic on public WiFi may be:
- intercepted by attackers

-----------------------------------
CERTIFICATES
-----------------------------------

Certificates help:
- verify identities
- establish encrypted sessions

-----------------------------------
CERTIFICATE AUTHORITIES
-----------------------------------

{{{
Additional Context:
Certificate Authorities (CAs) issue trusted digital certificates.

Source:
DigiCert Certificate Basics
https://www.digicert.com/
}}}

-----------------------------------
PORTS AND ENCRYPTION
-----------------------------------

{{{
Additional Context:
Common encrypted protocols:
- HTTPS = TCP 443
- SSH = TCP 22

Source:
IANA Service Registry
https://www.iana.org/
}}}

===================================
DATA AT REST
===================================

-----------------------------------
DATA AT REST
-----------------------------------

Data at rest is:
- stored data not actively moving across networks

-----------------------------------
EXAMPLES
-----------------------------------

Examples:
- files on hard drives
- databases
- backups
- USB drives
- cloud storage

-----------------------------------
WHY DATA AT REST NEEDS PROTECTION
-----------------------------------

If storage devices are:
- stolen
- accessed improperly
- compromised

unencrypted data may be exposed

-----------------------------------
DATA AT REST ENCRYPTION PURPOSE
-----------------------------------

Encryption protects:
- stored information

-----------------------------------
COMMON DATA AT REST TARGETS
-----------------------------------

Examples:
- laptops
- servers
- mobile devices
- backup systems
- cloud storage

-----------------------------------
FULL-DISK ENCRYPTION
-----------------------------------

Full-disk encryption encrypts:
- entire storage devices

-----------------------------------
WHY FULL-DISK ENCRYPTION MATTERS
-----------------------------------

If a device is stolen:
- attackers cannot easily read stored data

-----------------------------------
FILE-LEVEL ENCRYPTION
-----------------------------------

File-level encryption protects:
- individual files/folders

-----------------------------------
DATABASE ENCRYPTION
-----------------------------------

Databases may encrypt:
- stored records
- sensitive fields

-----------------------------------
BACKUP ENCRYPTION
-----------------------------------

Backups should commonly be:
- encrypted

-----------------------------------
WHY BACKUP ENCRYPTION MATTERS
-----------------------------------

Backups often contain:
- sensitive information
- entire system data

-----------------------------------
CLOUD STORAGE ENCRYPTION
-----------------------------------

Cloud providers commonly support:
- encryption at rest

-----------------------------------
KEY MANAGEMENT
-----------------------------------

Key management is:
- critical for encryption security

-----------------------------------
WHY KEY MANAGEMENT MATTERS
-----------------------------------

If encryption keys are:
- lost
or:
- stolen

data may become:
- inaccessible
or:
- compromised

-----------------------------------
SYMMETRIC ENCRYPTION
-----------------------------------

Symmetric encryption uses:
- the same key for encryption/decryption

-----------------------------------
SYMMETRIC ADVANTAGES
-----------------------------------

Advantages:
- fast
- efficient

-----------------------------------
ASYMMETRIC ENCRYPTION
-----------------------------------

Asymmetric encryption uses:
- public/private key pairs

-----------------------------------
ASYMMETRIC PURPOSE
-----------------------------------

Often used for:
- authentication
- key exchange
- certificates

-----------------------------------
AES
-----------------------------------

{{{
Additional Context:
AES =
Advanced Encryption Standard

AES is a very common symmetric encryption algorithm.

Source:
NIST AES Standard
https://csrc.nist.gov/
}}}

-----------------------------------
RSA
-----------------------------------

{{{
Additional Context:
RSA is a common asymmetric encryption algorithm.

Source:
RSA Laboratories Documentation
}}}

-----------------------------------
HASHING VS ENCRYPTION
-----------------------------------

Encryption:
- reversible with keys

Hashing:
- one-way transformation

-----------------------------------
COMPLIANCE
-----------------------------------

Encryption commonly supports:
- compliance requirements
- privacy regulations
- data protection laws

-----------------------------------
PERFORMANCE IMPACT
-----------------------------------

Encryption may:
- increase CPU usage
- slightly affect performance

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Encryption protects confidentiality
- Data in transit = moving data
- Data at rest = stored data
- HTTPS/TLS secure communications
- VPNs encrypt remote connectivity
- Full-disk encryption protects devices
- SSH provides encrypted management
- Symmetric encryption uses one key
- Asymmetric encryption uses key pairs
- Certificates support secure communications

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company encrypts laptop hard drives."

Answer:
Data at rest encryption

-----------------------------------

Scenario:
"A website uses HTTPS."

Answer:
Data in transit encryption

-----------------------------------

Scenario:
"A VPN encrypts remote employee traffic."

Answer:
Data in transit encryption

-----------------------------------

Scenario:
"A stolen backup drive remains unreadable."

Answer:
Data at rest encryption

-----------------------------------

Scenario:
"A company protects management traffic using SSH."

Answer:
Transit encryption

-----------------------------------

Scenario:
"A protocol secures web communications."

Answer:
TLS/HTTPS

-----------------------------------

Scenario:
"A company encrypts cloud-stored customer data."

Answer:
Encryption at rest

-----------------------------------

Scenario:
"Attackers intercept unreadable encrypted packets."

Answer:
Transit encryption protection

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing data at rest and data in transit.

Transit:
- moving across networks

At rest:
- stored data

-----------------------------------

Trap:
Thinking encryption prevents data theft entirely.

Wrong.

Encryption primarily protects:
- confidentiality/readability

-----------------------------------

Trap:
Thinking hashing and encryption are identical.

Wrong.

Encryption:
- reversible

Hashing:
- one-way

-----------------------------------

Trap:
Thinking HTTPS only authenticates websites.

Wrong.

HTTPS also:
- encrypts traffic

-----------------------------------

Trap:
Thinking VPNs guarantee anonymity.

Wrong.

VPNs primarily:
- encrypt communications

-----------------------------------

Trap:
Thinking encryption removes need for access controls.

Wrong.

Encryption complements:
- authentication
- authorization
- access control

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Transit =
Moving data

At rest =
Stored data

TLS/HTTPS =
Encrypted web traffic

SSH =
Encrypted management

VPN =
Encrypted tunnel

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is encryption?

A:
Converting readable data into unreadable ciphertext.

-----------------------------------

Q:
What is data in transit?

A:
Data actively moving across a network.

-----------------------------------

Q:
What is data at rest?

A:
Stored data not actively moving across networks.

-----------------------------------

Q:
What protocol commonly secures web traffic?

A:
HTTPS/TLS.

-----------------------------------

Q:
What does SSH provide?

A:
Encrypted remote management access.

-----------------------------------

Q:
What does a VPN provide?

A:
Encrypted remote connectivity.

-----------------------------------

Q:
What is full-disk encryption?

A:
Encrypting an entire storage device.

-----------------------------------

Q:
What is symmetric encryption?

A:
Encryption using the same key for encryption/decryption.

-----------------------------------

Q:
What is asymmetric encryption?

A:
Encryption using public/private key pairs.

-----------------------------------

Q:
What is the difference between hashing and encryption?

A:
Encryption is reversible; hashing is one-way.