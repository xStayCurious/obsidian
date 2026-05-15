========================
VIP — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Page 29
0

-----------------------------------
VIP
-----------------------------------

VIP =
Virtual IP Address

-----------------------------------
CORE PURPOSE
-----------------------------------

A VIP is:
- an IP address not tied permanently
to:
- one physical device

-----------------------------------
WHY VIPS EXIST
-----------------------------------

VIPs provide:
- redundancy
- high availability
- simplified access
- failover capability

-----------------------------------
VIRTUAL ADDRESS CONCEPT
-----------------------------------

Multiple devices may:
- share responsibility
for:
- one virtual IP address

-----------------------------------
FHRP RELATIONSHIP
-----------------------------------

FHRPs commonly use:
- VIPs

Hosts configure:
- the VIP
as:
- their default gateway

-----------------------------------
HOW VIP FAILOVER WORKS
-----------------------------------

If one router/device fails:
- another device assumes ownership
of:
- the VIP

-----------------------------------
HIGH AVAILABILITY
-----------------------------------

VIPs support:
- high availability networking

-----------------------------------
TRANSPARENCY
-----------------------------------

Hosts communicate with:
- the VIP

Hosts may not know:
- which physical device currently owns it

-----------------------------------
LOAD BALANCING
-----------------------------------

{{{
Additional Context:
VIPs are commonly used with load balancers to distribute traffic across multiple servers.

Source:
F5 Load Balancing Concepts
https://www.f5.com/
}}}

-----------------------------------
VIP IN FHRP
-----------------------------------

In FHRP environments:
- routers share a virtual gateway IP

This VIP:
- becomes the default gateway for hosts

-----------------------------------
ACTIVE DEVICE
-----------------------------------

One device typically:
- actively handles traffic
for:
- the VIP

-----------------------------------
STANDBY DEVICE
-----------------------------------

Another device may:
- remain standby
until:
- failover occurs

-----------------------------------
FAILOVER
-----------------------------------

Failover allows:
- uninterrupted connectivity
when:
- a device fails

-----------------------------------
VIP BENEFITS
-----------------------------------

- Redundancy
- High availability
- Simplified client configuration
- Seamless failover

-----------------------------------
VIRTUAL GATEWAY
-----------------------------------

A VIP often functions as:
- a virtual gateway address

-----------------------------------
SERVICE CONTINUITY
-----------------------------------

VIPs help maintain:
- service continuity
during:
- outages or failures

-----------------------------------
LOAD BALANCER VIPS
-----------------------------------

{{{
Additional Context:
Load balancers commonly expose a VIP that clients connect to, while backend servers remain hidden behind it.

Source:
NGINX Load Balancing Overview
https://docs.nginx.com/
}}}

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"Hosts use a shared virtual default gateway."

Answer:
VIP

-----------------------------------

Scenario:
"A standby router takes over a shared gateway address after failure."

Answer:
VIP with FHRP

-----------------------------------

Scenario:
"Multiple devices provide redundancy for one IP address."

Answer:
VIP

-----------------------------------

Scenario:
"A load balancer exposes one frontend IP while distributing traffic internally."

Answer:
VIP

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking a VIP always belongs to one physical device.

Wrong.

A VIP:
- may move between devices

-----------------------------------

Trap:
Confusing VIP and physical interface IPs.

VIP:
- virtual/shared

Physical IP:
- assigned directly to an interface

-----------------------------------

Trap:
Thinking VIP itself performs routing.

Wrong.

VIP:
- is an address
not:
- a routing protocol

-----------------------------------

Trap:
Thinking VIP automatically means load balancing.

Wrong.

VIPs may support:
- redundancy
or:
- load balancing
depending on implementation

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

VIP =
Shared virtual address for redundancy or availability.

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does VIP stand for?

A:
Virtual IP Address.

-----------------------------------

Q:
What is a VIP?

A:
A virtual/shared IP address not permanently tied to one device.

-----------------------------------

Q:
Why are VIPs used?

A:
For redundancy and high availability.

-----------------------------------

Q:
How are VIPs commonly used in FHRP?

A:
As a shared virtual default gateway.

-----------------------------------

Q:
What happens to a VIP during failover?

A:
Another device assumes ownership of it.

-----------------------------------

Q:
What major networking goal do VIPs support?

A:
High availability.

-----------------------------------

Q:
Do hosts communicate with the physical router or the VIP in FHRP?

A:
The VIP.

-----------------------------------

Q:
Can VIPs be used with load balancers?

A:
Yes.

-----------------------------------

Q:
Is a VIP permanently tied to one physical device?

A:
No.

-----------------------------------

Q:
What is a common use of a VIP?

A:
Providing a virtual default gateway.