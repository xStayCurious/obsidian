========================
Traffic Types — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.4: Common Ports, Protocols, and Services
Pages 19–20
0

-----------------------------------
TRAFFIC TYPES
-----------------------------------

Traffic types describe:
- how data is transmitted
- who receives the data
- how communication occurs across a network

The guide covers:
- Unicast
- Multicast
- Anycast
- Broadcast

-----------------------------------
UNICAST
-----------------------------------

Unicast is:
- one-to-one communication

Data is sent:
- from one source
to:
- one specific destination

-----------------------------------
UNICAST CHARACTERISTICS
-----------------------------------

- Uses a unique IP address
- Most common form of communication
- Direct communication between devices

-----------------------------------
UNICAST USE CASES
-----------------------------------

Used for:
- web browsing
- email
- file transfers

-----------------------------------
UNICAST EXAMPLE
-----------------------------------

One computer accessing:
- one web server

-----------------------------------
MULTICAST
-----------------------------------

Multicast is:
- one-to-many communication

Data is sent:
- from one or more sources
to:
- multiple destinations simultaneously

-----------------------------------
MULTICAST CHARACTERISTICS
-----------------------------------

- Uses multicast group addresses
- Efficient for delivering the same data to many recipients
- Reduces bandwidth usage compared to sending separate copies

-----------------------------------
MULTICAST USE CASES
-----------------------------------

Used for:
- streaming video
- streaming audio
- multimedia distribution

-----------------------------------
MULTICAST BENEFITS
-----------------------------------

Multicast improves efficiency by:
- reducing duplicate transmissions
- lowering bandwidth consumption

-----------------------------------
ANYCAST
-----------------------------------

Anycast is:
- one-to-nearest/best communication

Data is sent to:
- the nearest or best destination
from:
- multiple possible destinations sharing the same address

-----------------------------------
ANYCAST CHARACTERISTICS
-----------------------------------

- Uses routing protocols to determine best destination
- Improves performance
- Improves availability

-----------------------------------
ANYCAST USE CASES
-----------------------------------

Used in:
- DNS services
- CDNs (Content Delivery Networks)

-----------------------------------
ANYCAST BENEFITS
-----------------------------------

Anycast:
- improves network performance
- directs users to the closest server
- improves service availability

-----------------------------------
BROADCAST
-----------------------------------

Broadcast is:
- one-to-all communication

Data is sent:
- from one sender
to:
- all devices on a network segment

-----------------------------------
BROADCAST CHARACTERISTICS
-----------------------------------

- All devices receive the message
- Common in IPv4 networks
- Used for network discovery and requests

-----------------------------------
BROADCAST USE CASES
-----------------------------------

Example:
A device requesting an IP address via DHCP.

-----------------------------------
IPV4 BROADCAST
-----------------------------------

In IPv4:
- broadcast addresses send traffic to all devices on a LAN

-----------------------------------
IPV6 DIFFERENCE
-----------------------------------

The guide states:
- broadcast is NOT supported in IPv6

Instead:
- IPv6 uses multicast for similar purposes

-----------------------------------
TRAFFIC TYPE COMPARISON
-----------------------------------

Unicast:
- one-to-one

Multicast:
- one-to-many

Anycast:
- one-to-nearest

Broadcast:
- one-to-all

-----------------------------------
SIMPLE MENTAL MODEL
-----------------------------------

Unicast:
One person receives the message.

Multicast:
A selected group receives the message.

Anycast:
The closest available receiver gets the message.

Broadcast:
Everyone receives the message.

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A user accesses a website."

Answer:
Unicast

-----------------------------------

Scenario:
"A company streams video to multiple users simultaneously."

Answer:
Multicast

-----------------------------------

Scenario:
"A DNS request is routed to the nearest available server."

Answer:
Anycast

-----------------------------------

Scenario:
"A DHCP request is sent to all devices on a subnet."

Answer:
Broadcast

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking multicast means all devices receive the traffic.

Wrong.

Multicast:
- only selected group members receive traffic

-----------------------------------

Trap:
Thinking IPv6 supports broadcast.

Wrong.

IPv6:
- uses multicast instead

-----------------------------------

Trap:
Confusing Anycast and Multicast.

Anycast:
- one best destination

Multicast:
- multiple destinations simultaneously

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Unicast:
One-to-one

Multicast:
One-to-many

Anycast:
One-to-nearest

Broadcast:
One-to-all

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is unicast communication?

A:
One-to-one communication.

-----------------------------------

Q:
What is multicast communication?

A:
One-to-many communication using multicast group addresses.

-----------------------------------

Q:
What is anycast communication?

A:
Traffic sent to the nearest or best destination.

-----------------------------------

Q:
What is broadcast communication?

A:
One-to-all communication on a network segment.

-----------------------------------

Q:
What traffic type is most common for normal internet use?

A:
Unicast.

-----------------------------------

Q:
What traffic type is efficient for streaming media to multiple users?

A:
Multicast.

-----------------------------------

Q:
What traffic type is commonly used with DNS and CDNs?

A:
Anycast.

-----------------------------------

Q:
What traffic type is used by DHCP requests in IPv4?

A:
Broadcast.

-----------------------------------

Q:
Does IPv6 support broadcast?

A:
No. IPv6 uses multicast instead.

-----------------------------------

Q:
What is a key benefit of multicast?

A:
Reduced bandwidth usage.