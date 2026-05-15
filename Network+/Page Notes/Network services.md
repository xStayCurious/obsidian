========================
Network Services
DHCP, SLAAC, DNS,
NTP, PTP, and NTS
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 3 — Network Operations
Section 3.2: Network Services
Pages 57–59
0

-----------------------------------
NETWORK SERVICES
-----------------------------------

Network services provide:
- core communication functions
- addressing
- time synchronization
- name resolution
- automation support

-----------------------------------
WHY NETWORK SERVICES MATTER
-----------------------------------

Without network services:
- communication becomes difficult
- scalability decreases
- administration becomes complex
- automation becomes harder

-----------------------------------
MAIN EXAM TOPICS
-----------------------------------

The guide specifically includes:
- DHCP
- SLAAC
- DNS
- NTP
- PTP
- NTS

===================================
DHCP
===================================

-----------------------------------
DHCP
-----------------------------------

DHCP =
Dynamic Host Configuration Protocol

-----------------------------------
DHCP PURPOSE
-----------------------------------

DHCP automatically assigns:
- IP addresses
- subnet masks
- default gateways
- DNS server addresses

-----------------------------------
WHY DHCP EXISTS
-----------------------------------

DHCP eliminates:
- manual addressing configuration

-----------------------------------
DORA
-----------------------------------

DHCP process:
- Discover
- Offer
- Request
- Acknowledge

-----------------------------------
DORA EXAM FACT
-----------------------------------

Important sequence:
Discover →
Offer →
Request →
Acknowledge

-----------------------------------
LEASES
-----------------------------------

DHCP addresses are commonly:
- leased temporarily

-----------------------------------
SCOPES
-----------------------------------

A scope is:
- a range of assignable IP addresses

-----------------------------------
RESERVATIONS
-----------------------------------

Reservations assign:
- consistent IP addresses
to:
- specific devices

-----------------------------------
APIPA
-----------------------------------

APIPA range:
169.254.0.0/16

-----------------------------------
APIPA EXAM IDEA
-----------------------------------

169.254.x.x commonly indicates:
- DHCP failure

-----------------------------------
DHCP RELAY
-----------------------------------

DHCP relay forwards:
- DHCP traffic between subnets

-----------------------------------
IMPORTANT DHCP FACTS
-----------------------------------

- DHCP automates addressing
- DHCP leases addresses
- DHCP relay supports centralized DHCP
- DHCP broadcasts normally do not cross routers

===================================
SLAAC
===================================

-----------------------------------
SLAAC
-----------------------------------

SLAAC =
Stateless Address Autoconfiguration

-----------------------------------
SLAAC PURPOSE
-----------------------------------

SLAAC allows IPv6 devices to:
- automatically configure IPv6 addresses

-----------------------------------
STATELESS
-----------------------------------

Stateless means:
- no centralized server tracks assignments

-----------------------------------
ROUTER ADVERTISEMENTS
-----------------------------------

SLAAC relies on:
- router advertisements (RAs)

-----------------------------------
RA PURPOSE
-----------------------------------

RAs provide:
- network prefix information
- gateway information

-----------------------------------
HOW SLAAC WORKS
-----------------------------------

The host:
- receives the prefix
- generates its own IPv6 address

-----------------------------------
SLAAC VS DHCP
-----------------------------------

DHCP:
- centralized assignment

SLAAC:
- self-generated IPv6 addressing

-----------------------------------
DHCPv6
-----------------------------------

{{{
Additional Context:
IPv6 environments may also use:
- DHCPv6

Source:
RFC 8415 DHCP for IPv6
https://datatracker.ietf.org/
}}}

-----------------------------------
IMPORTANT SLAAC FACTS
-----------------------------------

- SLAAC is IPv6 autoconfiguration
- Uses router advertisements
- Stateless automatic addressing
- Common in IPv6 deployments

===================================
DNS
===================================

-----------------------------------
DNS
-----------------------------------

DNS =
Domain Name System

-----------------------------------
DNS PURPOSE
-----------------------------------

DNS resolves:
- hostnames
to:
- IP addresses

-----------------------------------
WHY DNS EXISTS
-----------------------------------

Humans prefer:
- names

Networks communicate using:
- IP addresses

-----------------------------------
DNS EXAMPLE
-----------------------------------

Example:
google.com →
142.x.x.x

-----------------------------------
DNS QUERIES
-----------------------------------

DNS clients send:
- queries

DNS servers return:
- IP address responses

-----------------------------------
COMMON DNS RECORDS
-----------------------------------

Important DNS records:
- A
- AAAA
- MX
- CNAME
- PTR

-----------------------------------
A RECORD
-----------------------------------

A records map:
- hostnames
to:
- IPv4 addresses

-----------------------------------
AAAA RECORD
-----------------------------------

AAAA records map:
- hostnames
to:
- IPv6 addresses

-----------------------------------
MX RECORD
-----------------------------------

MX records identify:
- mail servers

-----------------------------------
CNAME RECORD
-----------------------------------

CNAME records create:
- aliases for hostnames

-----------------------------------
PTR RECORD
-----------------------------------

PTR records support:
- reverse lookups

-----------------------------------
DNS CACHE
-----------------------------------

DNS caching improves:
- performance
- efficiency

-----------------------------------
DNS SECURITY RISKS
-----------------------------------

DNS attacks may include:
- spoofing
- poisoning
- tunneling

-----------------------------------
IMPORTANT DNS FACTS
-----------------------------------

- DNS resolves names to IPs
- A = IPv4
- AAAA = IPv6
- MX = mail server
- PTR = reverse lookup

===================================
NTP
===================================

-----------------------------------
NTP
-----------------------------------

NTP =
Network Time Protocol

-----------------------------------
NTP PURPOSE
-----------------------------------

NTP synchronizes:
- system clocks across networks

-----------------------------------
WHY TIME SYNCHRONIZATION MATTERS
-----------------------------------

Accurate time is important for:
- logging
- authentication
- troubleshooting
- event correlation
- security investigations

-----------------------------------
NTP STRATUM
-----------------------------------

{{{
Additional Context:
NTP uses strata to define clock hierarchy levels.

Source:
NTP Documentation
https://www.ntp.org/
}}}

-----------------------------------
LOWER STRATUM
-----------------------------------

Lower stratum values:
- are closer to authoritative time sources

-----------------------------------
NTP SECURITY RISKS
-----------------------------------

Improper time synchronization may affect:
- Kerberos authentication
- logging accuracy
- forensic investigations

-----------------------------------
IMPORTANT NTP FACTS
-----------------------------------

- NTP synchronizes clocks
- Accurate time supports security/logging
- Time synchronization is critical for event correlation

===================================
PTP
===================================

-----------------------------------
PTP
-----------------------------------

PTP =
Precision Time Protocol

-----------------------------------
PTP PURPOSE
-----------------------------------

PTP provides:
- highly accurate time synchronization

-----------------------------------
WHY PTP EXISTS
-----------------------------------

Some environments require:
- extremely precise timing

-----------------------------------
PTP USE CASES
-----------------------------------

Examples:
- financial trading
- telecommunications
- industrial systems
- scientific environments

-----------------------------------
PTP VS NTP
-----------------------------------

NTP:
- general time synchronization

PTP:
- high-precision synchronization

-----------------------------------
IMPORTANT PTP FACTS
-----------------------------------

- PTP provides more precise synchronization than NTP
- Used in specialized high-precision environments

===================================
NTS
===================================

-----------------------------------
NTS
-----------------------------------

NTS =
Network Time Security

-----------------------------------
NTS PURPOSE
-----------------------------------

NTS secures:
- NTP communications

-----------------------------------
WHY NTS EXISTS
-----------------------------------

Attackers may attempt to:
- manipulate time synchronization

-----------------------------------
NTS FUNCTIONS
-----------------------------------

NTS helps provide:
- authentication
- integrity protection
- secure time synchronization

-----------------------------------
WHY SECURE TIME MATTERS
-----------------------------------

Incorrect system time may affect:
- authentication
- logs
- certificates
- investigations

-----------------------------------
IMPORTANT NTS FACTS
-----------------------------------

- NTS secures NTP
- Protects time synchronization integrity
- Helps prevent time-based attacks

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- DHCP automates IP addressing
- SLAAC provides stateless IPv6 addressing
- DNS resolves names to IPs
- NTP synchronizes clocks
- PTP provides high-precision timing
- NTS secures NTP communications
- A records = IPv4
- AAAA records = IPv6
- APIPA = DHCP failure indicator

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A laptop automatically receives an IP address."

Answer:
DHCP

-----------------------------------

Scenario:
"A host self-generates an IPv6 address using router advertisements."

Answer:
SLAAC

-----------------------------------

Scenario:
"A system resolves hostnames to IP addresses."

Answer:
DNS

-----------------------------------

Scenario:
"A network synchronizes timestamps across systems."

Answer:
NTP

-----------------------------------

Scenario:
"A telecommunications environment requires extremely precise timing."

Answer:
PTP

-----------------------------------

Scenario:
"A company secures time synchronization traffic."

Answer:
NTS

-----------------------------------

Scenario:
"A host receives a 169.254.x.x address."

Answer:
DHCP failure/APIPA

-----------------------------------

Scenario:
"A DNS record maps a hostname to an IPv6 address."

Answer:
AAAA record

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing DHCP and SLAAC.

DHCP:
- centralized addressing

SLAAC:
- self-generated IPv6 addressing

-----------------------------------

Trap:
Confusing DNS A and AAAA records.

A:
- IPv4

AAAA:
- IPv6

-----------------------------------

Trap:
Thinking NTP and PTP are identical.

NTP:
- general synchronization

PTP:
- extremely precise synchronization

-----------------------------------

Trap:
Thinking NTS replaces NTP.

Wrong.

NTS:
- secures NTP

-----------------------------------

Trap:
Thinking APIPA is normal DHCP behavior.

Wrong.

APIPA commonly indicates:
- DHCP failure

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

DHCP =
Automatic addressing

SLAAC =
IPv6 self-addressing

DNS =
Name resolution

NTP =
Time synchronization

PTP =
Precision timing

NTS =
Secure NTP

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does DHCP stand for?

A:
Dynamic Host Configuration Protocol.

-----------------------------------

Q:
What does SLAAC stand for?

A:
Stateless Address Autoconfiguration.

-----------------------------------

Q:
What is the purpose of DNS?

A:
Resolve hostnames to IP addresses.

-----------------------------------

Q:
What does NTP stand for?

A:
Network Time Protocol.

-----------------------------------

Q:
What does PTP stand for?

A:
Precision Time Protocol.

-----------------------------------

Q:
What does NTS stand for?

A:
Network Time Security.

-----------------------------------

Q:
What does SLAAC use for IPv6 configuration?

A:
Router advertisements.

-----------------------------------

Q:
What DNS record maps names to IPv6 addresses?

A:
AAAA record.

-----------------------------------

Q:
What does APIPA usually indicate?

A:
DHCP failure.

-----------------------------------

Q:
What is the purpose of NTS?

A:
Secure NTP communications.