========================
IPv4 Addressing — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.7: IPv4 Addressing
Pages 25–27
0

-----------------------------------
IPV4 ADDRESSING
-----------------------------------

IPv4 addressing:
- identifies devices on a network
- enables communication between systems

IPv4 addresses are:
- 32-bit addresses
- written in dotted-decimal notation

Example:
192.168.1.10

-----------------------------------
PUBLIC IP ADDRESSES
-----------------------------------

Public IP addresses:
- are routable on the internet
- are globally unique
- are assigned by ISPs or providers

-----------------------------------
PUBLIC IP PURPOSE
-----------------------------------

Public IPs allow:
- communication across the internet

-----------------------------------
PRIVATE IP ADDRESSES
-----------------------------------

Private IP addresses:
- are used within internal networks
- are NOT routable on the public internet

-----------------------------------
PRIVATE IP PURPOSE
-----------------------------------

Private IPs are used for:
- home networks
- internal enterprise networks
- internal communication

-----------------------------------
RFC1918
-----------------------------------

RFC1918 defines:
- private IPv4 address ranges

-----------------------------------
PRIVATE ADDRESS RANGES
-----------------------------------

Class A private range:
10.0.0.0 – 10.255.255.255

Class B private range:
172.16.0.0 – 172.31.255.255

Class C private range:
192.168.0.0 – 192.168.255.255

-----------------------------------
WHY PRIVATE IPS EXIST
-----------------------------------

Private addressing helps:
- conserve public IPv4 addresses
- support internal networking
- improve address management

-----------------------------------
NAT RELATIONSHIP
-----------------------------------

Private IP addresses commonly use:
- NAT (Network Address Translation)

to access:
- the public internet

-----------------------------------
APIPA
-----------------------------------

APIPA =
Automatic Private IP Addressing

-----------------------------------
APIPA PURPOSE
-----------------------------------

APIPA automatically assigns:
- an IP address
when:
- a DHCP server is unavailable

-----------------------------------
APIPA RANGE
-----------------------------------

169.254.0.0 – 169.254.255.255

-----------------------------------
APIPA CHARACTERISTICS
-----------------------------------

- Self-assigned address
- Local communication only
- Non-routable

-----------------------------------
APIPA USE CASE
-----------------------------------

If a device cannot contact DHCP:
- it may assign itself an APIPA address

-----------------------------------
LOOPBACK ADDRESS
-----------------------------------

Loopback addresses:
- allow a device to communicate with itself

-----------------------------------
LOOPBACK RANGE
-----------------------------------

127.0.0.0/8

-----------------------------------
COMMON LOOPBACK ADDRESS
-----------------------------------

127.0.0.1

-----------------------------------
LOOPBACK PURPOSE
-----------------------------------

Loopback is used for:
- testing
- troubleshooting
- local network stack verification

-----------------------------------
ADDRESS CLASSES
-----------------------------------

IPv4 historically used:
- Class A
- Class B
- Class C
- Class D
- Class E

-----------------------------------
CLASS A
-----------------------------------

Class A:
- designed for very large networks

Range:
1.0.0.0 – 126.255.255.255

Default subnet mask:
255.0.0.0

-----------------------------------
CLASS A CHARACTERISTICS
-----------------------------------

- Large number of hosts
- Few networks

-----------------------------------
CLASS B
-----------------------------------

Class B:
- designed for medium-to-large networks

Range:
128.0.0.0 – 191.255.255.255

Default subnet mask:
255.255.0.0

-----------------------------------
CLASS B CHARACTERISTICS
-----------------------------------

- Balanced network/host capacity

-----------------------------------
CLASS C
-----------------------------------

Class C:
- designed for smaller networks

Range:
192.0.0.0 – 223.255.255.255

Default subnet mask:
255.255.255.0

-----------------------------------
CLASS C CHARACTERISTICS
-----------------------------------

- Many networks
- Fewer hosts per network

-----------------------------------
CLASS D
-----------------------------------

Class D:
- used for multicast traffic

Range:
224.0.0.0 – 239.255.255.255

-----------------------------------
CLASS D PURPOSE
-----------------------------------

Used for:
- multicast communication

-----------------------------------
CLASS E
-----------------------------------

Class E:
- reserved for experimental purposes

Range:
240.0.0.0 – 255.255.255.255

-----------------------------------
CLASSFUL ADDRESSING
-----------------------------------

{{{
Additional Context:
Modern networks primarily use CIDR instead of classful addressing, but address classes are still important for Network+ exam knowledge.

Source:
RFC 4632 — CIDR Address Strategy
https://datatracker.ietf.org/doc/html/rfc4632
}}}

-----------------------------------
MULTICAST
-----------------------------------

Class D addresses are used for:
- multicast traffic

Example:
One sender transmitting to multiple receivers.

-----------------------------------
EXPERIMENTAL RANGE
-----------------------------------

Class E addresses are:
- reserved
- experimental
- generally not used for normal hosts

-----------------------------------
PRIVATE VS PUBLIC COMPARISON
-----------------------------------

Public:
- internet routable
- globally unique

Private:
- internal use only
- non-routable on internet

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A device self-assigns an address because DHCP is unavailable."

Answer:
APIPA

-----------------------------------

Scenario:
"A company needs internal non-routable addressing."

Answer:
RFC1918 private addressing

-----------------------------------

Scenario:
"A technician tests the local TCP/IP stack."

Answer:
Loopback address

-----------------------------------

Scenario:
"A multicast application uses IPv4 addressing."

Answer:
Class D

-----------------------------------

Scenario:
"An organization uses 192.168.x.x internally."

Answer:
Private Class C addressing

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking APIPA provides internet access.

Wrong.

APIPA:
- only supports local communication

-----------------------------------

Trap:
Confusing loopback and APIPA.

Loopback:
127.x.x.x

APIPA:
169.254.x.x

-----------------------------------

Trap:
Thinking Class D is for normal hosts.

Wrong.

Class D:
- multicast only

-----------------------------------

Trap:
Thinking private IPs are internet-routable.

Wrong.

Private IPs:
- require NAT for internet access

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Private:
10.x.x.x
172.16–31.x.x
192.168.x.x

APIPA:
169.254.x.x

Loopback:
127.0.0.1

Class D:
Multicast

Class E:
Experimental

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is the purpose of IPv4 addressing?

A:
To identify devices and enable communication on networks.

-----------------------------------

Q:
What is a public IP address?

A:
A globally routable internet address.

-----------------------------------

Q:
What is a private IP address?

A:
An internal non-routable IP address.

-----------------------------------

Q:
What RFC defines private IPv4 addressing?

A:
RFC1918.

-----------------------------------

Q:
What are the RFC1918 private ranges?

A:
10.x.x.x, 172.16–31.x.x, and 192.168.x.x.

-----------------------------------

Q:
What is APIPA?

A:
Automatic Private IP Addressing used when DHCP is unavailable.

-----------------------------------

Q:
What APIPA range is used?

A:
169.254.0.0/16.

-----------------------------------

Q:
What is the loopback address commonly used?

A:
127.0.0.1.

-----------------------------------

Q:
What is the purpose of loopback?

A:
Testing and local TCP/IP communication.

-----------------------------------

Q:
What is Class D used for?

A:
Multicast traffic.

-----------------------------------

Q:
What is Class E used for?

A:
Experimental purposes.

-----------------------------------

Q:
What is the default subnet mask for Class A?

A:
255.0.0.0.

-----------------------------------

Q:
What is the default subnet mask for Class B?

A:
255.255.0.0.

-----------------------------------

Q:
What is the default subnet mask for Class C?

A:
255.255.255.0.