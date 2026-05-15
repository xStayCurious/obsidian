========================
Subinterfaces — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Page 29
0

-----------------------------------
SUBINTERFACES
-----------------------------------

Subinterfaces:
- are logical subdivisions
of:
- a physical network interface

-----------------------------------
CORE PURPOSE
-----------------------------------

Subinterfaces allow:
- multiple logical networks
to use:
- one physical interface

-----------------------------------
LOGICAL INTERFACES
-----------------------------------

A subinterface:
- behaves like a separate interface
even though:
- it shares physical hardware

-----------------------------------
WHY SUBINTERFACES EXIST
-----------------------------------

Subinterfaces help:
- reduce physical interface requirements
- support VLAN routing
- improve network flexibility

-----------------------------------
ROUTER-ON-A-STICK
-----------------------------------

{{{
Additional Context:
Subinterfaces are commonly used in "router-on-a-stick" configurations where one router interface handles traffic for multiple VLANs.

Source:
Cisco Inter-VLAN Routing Documentation
https://www.cisco.com/
}}}

-----------------------------------
VLAN RELATIONSHIP
-----------------------------------

Subinterfaces are commonly associated with:
- VLANs

-----------------------------------
INTER-VLAN ROUTING
-----------------------------------

Subinterfaces allow routers to:
- route traffic between VLANs

-----------------------------------
802.1Q TAGGING
-----------------------------------

{{{
Additional Context:
Subinterfaces commonly use IEEE 802.1Q tagging to identify VLAN traffic.

Source:
Cisco VLAN Tagging Overview
https://www.cisco.com/
}}}

-----------------------------------
PHYSICAL VS LOGICAL
-----------------------------------

Physical Interface:
- actual hardware port

Subinterface:
- logical partition of that port

-----------------------------------
IP ADDRESSING
-----------------------------------

Each subinterface may have:
- its own IP address
- its own VLAN association

-----------------------------------
TRAFFIC SEPARATION
-----------------------------------

Subinterfaces help:
- separate network traffic logically

-----------------------------------
MULTIPLE NETWORKS
-----------------------------------

One physical router interface can support:
- multiple networks
through:
- multiple subinterfaces

-----------------------------------
CONFIGURATION STYLE
-----------------------------------

{{{
Additional Context:
Cisco devices commonly name subinterfaces using formats such as:
GigabitEthernet0/0.10

where:
- .10 represents the subinterface number/VLAN association.

Source:
Cisco Inter-VLAN Routing Documentation
https://www.cisco.com/
}}}

-----------------------------------
ADVANTAGES
-----------------------------------

- Efficient hardware usage
- Reduced interface requirements
- VLAN support
- Flexible routing design

-----------------------------------
DISADVANTAGES
-----------------------------------

{{{
Additional Context:
Using many subinterfaces on one physical link can create bandwidth bottlenecks because all VLAN traffic shares the same physical connection.

Source:
Cisco Router-on-a-Stick Overview
https://www.cisco.com/
}}}

-----------------------------------
TRUNK LINKS
-----------------------------------

{{{
Additional Context:
Subinterfaces are commonly used over trunk links carrying multiple VLANs between switches and routers.

Source:
Cisco VLAN Trunking Overview
https://www.cisco.com/
}}}

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A router uses one physical interface to route between multiple VLANs."

Answer:
Subinterfaces

-----------------------------------

Scenario:
"A network needs logical separation using one physical router port."

Answer:
Subinterfaces

-----------------------------------

Scenario:
"A router-on-a-stick configuration is implemented."

Answer:
Subinterfaces

-----------------------------------

Scenario:
"One interface handles traffic for multiple VLANs."

Answer:
Subinterfaces with 802.1Q tagging

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking subinterfaces are separate physical ports.

Wrong.

Subinterfaces:
- are logical interfaces

-----------------------------------

Trap:
Thinking each VLAN always requires a separate physical router interface.

Wrong.

Subinterfaces:
- allow multiple VLANs on one interface

-----------------------------------

Trap:
Ignoring VLAN tagging.

Subinterfaces commonly rely on:
- 802.1Q tagging

-----------------------------------

Trap:
Thinking subinterfaces increase physical bandwidth.

Wrong.

All subinterfaces:
- share the same physical interface bandwidth

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Subinterface =
Multiple logical interfaces on one physical port.

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is a subinterface?

A:
A logical subdivision of a physical interface.

-----------------------------------

Q:
Why are subinterfaces used?

A:
To support multiple logical networks on one physical interface.

-----------------------------------

Q:
What networking feature commonly uses subinterfaces?

A:
VLAN routing.

-----------------------------------

Q:
What is router-on-a-stick?

A:
Using subinterfaces on one router interface to route between VLANs.

-----------------------------------

Q:
Do subinterfaces use separate physical ports?

A:
No.

-----------------------------------

Q:
Can each subinterface have its own IP address?

A:
Yes.

-----------------------------------

Q:
What tagging standard is commonly used with subinterfaces?

A:
802.1Q.

-----------------------------------

Q:
What major advantage do subinterfaces provide?

A:
Efficient hardware utilization.

-----------------------------------

Q:
What major limitation do subinterfaces have?

A:
They share the same physical bandwidth.

-----------------------------------

Q:
What type of interface is a subinterface?

A:
Logical interface.