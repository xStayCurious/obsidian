========================
DHCP
Network Services
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 3 — Network Operations
Section 3.2: Network Services
Pages 57–59
0

-----------------------------------
DHCP
-----------------------------------

DHCP =
Dynamic Host Configuration Protocol

-----------------------------------
CORE PURPOSE
-----------------------------------

DHCP automatically provides:
- IP addresses
- subnet masks
- default gateways
- DNS server information

to:
- client devices

-----------------------------------
WHY DHCP EXISTS
-----------------------------------

Without DHCP:
- devices require manual IP configuration

Manual configuration:
- takes time
- scales poorly
- increases mistakes
- creates addressing conflicts

-----------------------------------
AUTOMATIC CONFIGURATION
-----------------------------------

DHCP automates:
- network addressing/configuration

-----------------------------------
COMMON DHCP CLIENTS
-----------------------------------

Examples:
- laptops
- desktops
- phones
- printers
- IoT devices
- tablets

-----------------------------------
DHCP SERVER
-----------------------------------

The DHCP server:
- manages address assignments

-----------------------------------
DHCP SERVER FUNCTIONS
-----------------------------------

The DHCP server:
- assigns IP addresses
- tracks leases
- distributes network settings
- prevents duplicate addressing

-----------------------------------
LEASES
-----------------------------------

A lease is:
- a temporary IP address assignment

-----------------------------------
LEASE PURPOSE
-----------------------------------

Leases allow:
- address reuse
- dynamic allocation
- efficient address management

-----------------------------------
LEASE TIME
-----------------------------------

Lease time defines:
- how long a client may use an IP address

-----------------------------------
SHORT LEASES
-----------------------------------

Short leases are useful for:
- guest WiFi
- public hotspots
- highly dynamic environments

-----------------------------------
LONG LEASES
-----------------------------------

Long leases:
- reduce renewal traffic
- reduce DHCP overhead

-----------------------------------
DHCP PROCESS
-----------------------------------

The DHCP process is commonly called:
- DORA

-----------------------------------
DORA
-----------------------------------

DORA =
- Discover
- Offer
- Request
- Acknowledge

-----------------------------------
DISCOVER
-----------------------------------

Discover:
- client broadcasts searching for DHCP servers

-----------------------------------
OFFER
-----------------------------------

Offer:
- DHCP server offers network configuration information

-----------------------------------
REQUEST
-----------------------------------

Request:
- client requests the offered configuration

-----------------------------------
ACKNOWLEDGE
-----------------------------------

Acknowledge:
- DHCP server confirms the lease assignment

-----------------------------------
IMPORTANT EXAM FACT
-----------------------------------

Very important:
DORA sequence order:

Discover →
Offer →
Request →
Acknowledge

-----------------------------------
DHCP SCOPES
-----------------------------------

A scope is:
- a range of assignable IP addresses

-----------------------------------
SCOPE PURPOSE
-----------------------------------

Scopes define:
- what addresses DHCP may assign

-----------------------------------
SCOPE EXAMPLE
-----------------------------------

Example:
192.168.1.100–192.168.1.200

-----------------------------------
EXCLUSIONS
-----------------------------------

Exclusions are:
- addresses DHCP should NOT assign

-----------------------------------
WHY EXCLUSIONS EXIST
-----------------------------------

Exclusions reserve addresses for:
- servers
- printers
- routers
- static devices

-----------------------------------
RESERVATIONS
-----------------------------------

Reservations assign:
- a consistent IP address
to:
- a specific device

-----------------------------------
HOW RESERVATIONS WORK
-----------------------------------

Reservations commonly map:
- MAC addresses
to:
- specific IP addresses

-----------------------------------
WHY RESERVATIONS MATTER
-----------------------------------

Reservations combine:
- centralized DHCP management
with:
- predictable addressing

-----------------------------------
STATIC VS DHCP
-----------------------------------

Static addressing:
- manually configured

DHCP:
- automatically assigned

-----------------------------------
STATIC ADDRESSING USE CASES
-----------------------------------

Static addressing commonly used for:
- servers
- infrastructure devices
- firewalls
- printers
- network appliances

-----------------------------------
DHCP OPTIONS
-----------------------------------

DHCP may distribute:
- DNS server addresses
- default gateways
- domain names
- NTP server addresses

-----------------------------------
DEFAULT GATEWAY
-----------------------------------

The default gateway:
- allows communication outside the local subnet

-----------------------------------
DNS SETTINGS
-----------------------------------

DHCP commonly provides:
- DNS server information automatically

-----------------------------------
APIPA
-----------------------------------

APIPA =
Automatic Private IP Addressing

-----------------------------------
APIPA PURPOSE
-----------------------------------

If DHCP fails:
- Windows systems may self-assign APIPA addresses

-----------------------------------
APIPA RANGE
-----------------------------------

APIPA range:
169.254.0.0/16

-----------------------------------
APIPA EXAM IDEA
-----------------------------------

If a host has:
169.254.x.x

Likely issue:
- DHCP failure

-----------------------------------
DHCP RELAY
-----------------------------------

DHCP relay forwards:
- DHCP traffic between subnets

-----------------------------------
WHY DHCP RELAY EXISTS
-----------------------------------

DHCP broadcasts normally do NOT cross routers.

DHCP relay allows:
- centralized DHCP servers
for:
- multiple subnets

-----------------------------------
IP HELPER
-----------------------------------

{{{
Additional Context:
Cisco devices commonly use:
- ip helper-address

to configure DHCP relay functionality.

Source:
Cisco DHCP Relay Documentation
https://www.cisco.com/
}}}

-----------------------------------
DHCP STARVATION
-----------------------------------

{{{
Additional Context:
DHCP starvation attacks attempt to exhaust available DHCP addresses using fake requests.

Source:
Cisco DHCP Snooping Guide
https://www.cisco.com/
}}}

-----------------------------------
DHCP SNOOPING
-----------------------------------

{{{
Additional Context:
DHCP snooping helps protect against rogue DHCP servers and DHCP attacks.

Source:
Cisco DHCP Snooping Guide
https://www.cisco.com/
}}}

-----------------------------------
ROGUE DHCP SERVER
-----------------------------------

A rogue DHCP server is:
- an unauthorized DHCP server on the network

-----------------------------------
ROGUE DHCP RISKS
-----------------------------------

Rogue DHCP servers may:
- distribute incorrect gateways
- redirect traffic
- cause outages
- support man-in-the-middle attacks

-----------------------------------
DHCP SNOOPING PURPOSE
-----------------------------------

DHCP snooping helps:
- filter unauthorized DHCP messages
- identify trusted DHCP ports

-----------------------------------
DHCP RENEWAL
-----------------------------------

Clients periodically:
- renew DHCP leases

-----------------------------------
WHY RENEWAL MATTERS
-----------------------------------

Renewal helps:
- maintain valid addressing
- prevent conflicts
- reuse addresses efficiently

-----------------------------------
DHCP EXHAUSTION
-----------------------------------

{{{
Additional Context:
If all DHCP addresses in a scope are assigned, new clients may fail to obtain IP addresses.

Source:
Microsoft DHCP Concepts
https://learn.microsoft.com/
}}}

-----------------------------------
HIGH AVAILABILITY
-----------------------------------

Organizations may deploy:
- redundant DHCP servers

-----------------------------------
WHY DHCP REDUNDANCY MATTERS
-----------------------------------

If DHCP fails:
- clients may lose addressing capability

-----------------------------------
DHCP VS DNS
-----------------------------------

DHCP:
- provides addressing configuration

DNS:
- resolves names to IP addresses

-----------------------------------
DHCP VS APIPA
-----------------------------------

DHCP:
- valid centralized addressing

APIPA:
- fallback self-assigned addressing

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- DHCP automatically assigns IP settings
- DORA = Discover, Offer, Request, Acknowledge
- DHCP leases are temporary
- Scopes define assignable addresses
- Reservations map devices to fixed IPs
- APIPA range = 169.254.0.0/16
- DHCP relay forwards DHCP across subnets
- DHCP broadcasts do not cross routers
- Rogue DHCP servers are security risks
- DHCP snooping helps prevent rogue DHCP activity

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A laptop automatically receives an IP address."

Answer:
DHCP

-----------------------------------

Scenario:
"A client broadcasts looking for a DHCP server."

Answer:
DHCP Discover

-----------------------------------

Scenario:
"A DHCP server offers an address to a client."

Answer:
DHCP Offer

-----------------------------------

Scenario:
"A host receives a 169.254.x.x address."

Answer:
DHCP failure/APIPA

-----------------------------------

Scenario:
"A network uses one centralized DHCP server for multiple subnets."

Answer:
DHCP relay

-----------------------------------

Scenario:
"A company wants printers to always receive the same IP address automatically."

Answer:
DHCP reservation

-----------------------------------

Scenario:
"An unauthorized server distributes incorrect IP settings."

Answer:
Rogue DHCP server

-----------------------------------

Scenario:
"A switch feature blocks unauthorized DHCP responses."

Answer:
DHCP snooping

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing DHCP and DNS.

DHCP:
- assigns addressing information

DNS:
- resolves names to IPs

-----------------------------------

Trap:
Forgetting DORA order.

Correct order:
Discover →
Offer →
Request →
Acknowledge

-----------------------------------

Trap:
Thinking APIPA indicates normal DHCP operation.

Wrong.

APIPA commonly indicates:
- DHCP failure

-----------------------------------

Trap:
Thinking DHCP broadcasts cross routers automatically.

Wrong.

Routers normally block broadcasts.

DHCP relay is needed.

-----------------------------------

Trap:
Thinking reservations are the same as static IPs.

Wrong.

Reservations:
- centrally managed through DHCP

Static IPs:
- manually configured on devices

-----------------------------------

Trap:
Thinking rogue DHCP servers are harmless.

Wrong.

Rogue DHCP may:
- redirect traffic
- disrupt networks
- support attacks

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

DHCP =
Automatic addressing

DORA =
Lease process

Scope =
Assignable range

Reservation =
Predictable DHCP IP

APIPA =
DHCP failed

Relay =
Cross-subnet DHCP

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does DHCP stand for?

A:
Dynamic Host Configuration Protocol.

-----------------------------------

Q:
What is the purpose of DHCP?

A:
Automatically assign network configuration settings.

-----------------------------------

Q:
What does DORA stand for?

A:
Discover, Offer, Request, Acknowledge.

-----------------------------------

Q:
What is a DHCP lease?

A:
A temporary IP address assignment.

-----------------------------------

Q:
What is a DHCP scope?

A:
A range of assignable IP addresses.

-----------------------------------

Q:
What is a DHCP reservation?

A:
A consistent DHCP-assigned IP tied to a device.

-----------------------------------

Q:
What APIPA range indicates DHCP failure?

A:
169.254.0.0/16.

-----------------------------------

Q:
Why is DHCP relay needed?

A:
DHCP broadcasts do not cross routers.

-----------------------------------

Q:
What is a rogue DHCP server?

A:
An unauthorized DHCP server on the network.

-----------------------------------

Q:
What does DHCP snooping do?

A:
Helps prevent rogue DHCP activity.