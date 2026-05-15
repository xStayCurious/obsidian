========================
NAT — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Page 29
0

-----------------------------------
NAT
-----------------------------------

NAT =
Network Address Translation

-----------------------------------
CORE PURPOSE
-----------------------------------

NAT translates:
- private IP addresses
into:
- public IP addresses

-----------------------------------
WHY NAT EXISTS
-----------------------------------

NAT helps:
- conserve public IPv4 addresses
- allow private networks to access the internet
- hide internal addressing schemes

-----------------------------------
PRIVATE TO PUBLIC TRANSLATION
-----------------------------------

Devices inside a network commonly use:
- private IP addresses

NAT allows those devices to communicate with:
- public internet resources

-----------------------------------
PRIVATE ADDRESSING
-----------------------------------

Private IP ranges include:
- 10.0.0.0/8
- 172.16.0.0 – 172.31.255.255
- 192.168.0.0/16

-----------------------------------
PUBLIC ADDRESSING
-----------------------------------

Public IP addresses:
- are routable on the internet
- are globally unique

-----------------------------------
HOW NAT WORKS
-----------------------------------

NAT changes:
- source or destination IP information
as traffic passes through:
- a router or firewall

-----------------------------------
NAT DEVICE
-----------------------------------

NAT is commonly performed by:
- routers
- firewalls

-----------------------------------
OUTBOUND INTERNET ACCESS
-----------------------------------

NAT allows:
- internal private devices
to:
- access external internet resources

-----------------------------------
ADDRESS CONSERVATION
-----------------------------------

One major purpose of NAT is:
- conserving public IPv4 addresses

-----------------------------------
HIDING INTERNAL NETWORKS
-----------------------------------

NAT helps hide:
- internal IP addressing structures

from:
- external networks

-----------------------------------
STATIC NAT
-----------------------------------

Static NAT:
- maps one private IP
to:
- one public IP

-----------------------------------
STATIC NAT CHARACTERISTICS
-----------------------------------

- Permanent mapping
- One-to-one translation

-----------------------------------
STATIC NAT USE CASES
-----------------------------------

Used when:
- an internal device requires consistent public access

-----------------------------------
DYNAMIC NAT
-----------------------------------

Dynamic NAT:
- maps private IPs
to:
- available public IPs from a pool

-----------------------------------
DYNAMIC NAT CHARACTERISTICS
-----------------------------------

- Temporary mapping
- Uses address pools

-----------------------------------
PAT
-----------------------------------

PAT =
Port Address Translation

Also called:
- NAT overload

-----------------------------------
PAT PURPOSE
-----------------------------------

PAT allows:
- many private devices
to share:
- one public IP address

-----------------------------------
PAT CHARACTERISTICS
-----------------------------------

PAT differentiates sessions using:
- port numbers

-----------------------------------
PAT BENEFITS
-----------------------------------

PAT:
- greatly conserves public IP addresses
- is commonly used in home and enterprise networks

-----------------------------------
MOST COMMON NAT TYPE
-----------------------------------

{{{
Additional Context:
PAT (NAT overload) is the most commonly deployed NAT implementation in modern networks.

Source:
Cisco NAT Overview
https://www.cisco.com/
}}}

-----------------------------------
NAT AND SECURITY
-----------------------------------

NAT provides:
- some obscurity of internal addresses

However:
- NAT itself is not a firewall

-----------------------------------
NAT LIMITATIONS
-----------------------------------

NAT:
- does not replace proper security controls
- does not inherently filter malicious traffic

-----------------------------------
PORT FORWARDING
-----------------------------------

{{{
Additional Context:
Port forwarding allows external traffic on specific ports to be directed to internal devices behind NAT.

Source:
Cisco Port Forwarding Documentation
https://www.cisco.com/
}}}

-----------------------------------
NAT TABLE
-----------------------------------

{{{
Additional Context:
NAT devices maintain translation tables mapping private addresses and ports to public addresses and ports.

Source:
Cisco NAT Overview
https://www.cisco.com/
}}}

-----------------------------------
IPV4 RELATIONSHIP
-----------------------------------

NAT became important because:
- IPv4 address space is limited

-----------------------------------
IPV6 RELATIONSHIP
-----------------------------------

{{{
Additional Context:
IPv6 was designed to reduce reliance on NAT because of its vastly larger address space.

Source:
RFC 8200 — Internet Protocol Version 6 (IPv6)
https://datatracker.ietf.org/doc/html/rfc8200
}}}

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A home router allows many devices to share one public IP."

Answer:
PAT/NAT overload

-----------------------------------

Scenario:
"A company permanently maps one server to one public IP."

Answer:
Static NAT

-----------------------------------

Scenario:
"A router translates private IPs for internet access."

Answer:
NAT

-----------------------------------

Scenario:
"A company uses temporary public address assignments from a pool."

Answer:
Dynamic NAT

-----------------------------------

Scenario:
"A network wants to conserve public IPv4 addresses."

Answer:
NAT/PAT

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking NAT is a firewall.

Wrong.

NAT:
- performs address translation

-----------------------------------

Trap:
Confusing static NAT and dynamic NAT.

Static NAT:
- permanent one-to-one mapping

Dynamic NAT:
- temporary mappings from a pool

-----------------------------------

Trap:
Thinking PAT and NAT are completely different.

Wrong.

PAT:
- is a type of NAT

-----------------------------------

Trap:
Thinking NAT encrypts traffic.

Wrong.

NAT:
- does not provide encryption

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

NAT =
Private-to-public translation

Static NAT =
One-to-one

Dynamic NAT =
Pool-based translation

PAT =
Many-to-one using ports

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does NAT stand for?

A:
Network Address Translation.

-----------------------------------

Q:
What is the purpose of NAT?

A:
Translate private IP addresses to public IP addresses.

-----------------------------------

Q:
Why is NAT important?

A:
It conserves public IPv4 addresses.

-----------------------------------

Q:
What is static NAT?

A:
A permanent one-to-one IP mapping.

-----------------------------------

Q:
What is dynamic NAT?

A:
Temporary translation using a pool of public addresses.

-----------------------------------

Q:
What is PAT?

A:
Port Address Translation allowing many devices to share one public IP.

-----------------------------------

Q:
What does PAT use to differentiate sessions?

A:
Port numbers.

-----------------------------------

Q:
What device commonly performs NAT?

A:
Routers or firewalls.

-----------------------------------

Q:
Does NAT provide encryption?

A:
No.

-----------------------------------

Q:
What is another name for PAT?

A:
NAT overload.