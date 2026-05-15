========================
VLANs — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.6: Network Topologies, Architectures, and Types
Page 24
0

-----------------------------------
VLAN
-----------------------------------

VLAN =
Virtual Local Area Network

-----------------------------------
CORE PURPOSE
-----------------------------------

A VLAN:
- logically separates devices
within:
- the same physical network

-----------------------------------
WHY VLANS EXIST
-----------------------------------

VLANs help:
- improve segmentation
- improve security
- reduce broadcast domains
- organize networks

-----------------------------------
LOGICAL SEGMENTATION
-----------------------------------

VLANs create:
- separate logical networks

even when devices share:
- the same switches and cabling

-----------------------------------
BROADCAST DOMAINS
-----------------------------------

Each VLAN creates:
- its own broadcast domain

-----------------------------------
BROADCAST REDUCTION
-----------------------------------

VLANs reduce:
- unnecessary broadcast traffic

-----------------------------------
SECURITY BENEFITS
-----------------------------------

VLANs improve security by:
- isolating traffic
- separating departments/systems
- limiting communication exposure

-----------------------------------
COMMON VLAN USE CASES
-----------------------------------

Organizations commonly create VLANs for:
- departments
- guest networks
- voice traffic
- management traffic

-----------------------------------
EXAMPLE VLAN SEGMENTATION
-----------------------------------

VLAN 10:
Accounting

VLAN 20:
HR

VLAN 30:
Guest WiFi

-----------------------------------
PHYSICAL VS LOGICAL
-----------------------------------

Physical separation:
- separate hardware/networks

Logical separation:
- VLAN-based segmentation
using shared infrastructure

-----------------------------------
SWITCHES AND VLANS
-----------------------------------

Switches commonly:
- implement VLANs

-----------------------------------
ACCESS PORT
-----------------------------------

{{{
Additional Context:
An access port carries traffic for one VLAN only and is typically connected to end devices.

Source:
Cisco VLAN Overview
https://www.cisco.com/
}}}

-----------------------------------
TRUNK PORT
-----------------------------------

{{{
Additional Context:
A trunk port carries traffic for multiple VLANs between networking devices.

Source:
Cisco VLAN Trunking Overview
https://www.cisco.com/
}}}

-----------------------------------
802.1Q
-----------------------------------

{{{
Additional Context:
IEEE 802.1Q is the standard commonly used for VLAN tagging on trunk links.

Source:
IEEE 802.1Q Standard Overview
https://standards.ieee.org/
}}}

-----------------------------------
VLAN TAGGING
-----------------------------------

{{{
Additional Context:
VLAN tagging identifies which VLAN traffic belongs to when multiple VLANs traverse the same trunk link.

Source:
Cisco VLAN Tagging Overview
https://www.cisco.com/
}}}

-----------------------------------
INTER-VLAN COMMUNICATION
-----------------------------------

Devices in different VLANs:
- cannot communicate directly

Routing is required for:
- inter-VLAN communication

-----------------------------------
INTER-VLAN ROUTING
-----------------------------------

Routers or Layer 3 switches may provide:
- communication between VLANs

-----------------------------------
ROUTER-ON-A-STICK
-----------------------------------

{{{
Additional Context:
Router-on-a-stick uses router subinterfaces and trunking to route between VLANs using one physical interface.

Source:
Cisco Inter-VLAN Routing Documentation
https://www.cisco.com/
}}}

-----------------------------------
NATIVE VLAN
-----------------------------------

{{{
Additional Context:
The native VLAN carries untagged traffic on an 802.1Q trunk.

Source:
Cisco VLAN Trunking Documentation
https://www.cisco.com/
}}}

-----------------------------------
VOICE VLAN
-----------------------------------

{{{
Additional Context:
Voice VLANs separate VoIP traffic from data traffic to improve management and QoS handling.

Source:
Cisco Voice VLAN Overview
https://www.cisco.com/
}}}

-----------------------------------
VLAN BENEFITS
-----------------------------------

- Improved segmentation
- Better security
- Reduced broadcasts
- Easier management
- Better traffic organization

-----------------------------------
VLAN LIMITATIONS
-----------------------------------

{{{
Additional Context:
Misconfigured VLANs or trunk ports can create security risks or connectivity problems.

Source:
Cisco VLAN Security Best Practices
https://www.cisco.com/
}}}

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company wants to separate departments logically using the same switch infrastructure."

Answer:
VLANs

-----------------------------------

Scenario:
"A network needs reduced broadcast traffic."

Answer:
VLANs

-----------------------------------

Scenario:
"Traffic for multiple VLANs travels across one switch link."

Answer:
Trunk port

-----------------------------------

Scenario:
"A switch port connects to a normal workstation in one VLAN."

Answer:
Access port

-----------------------------------

Scenario:
"A company wants guest WiFi separated from internal users."

Answer:
Separate VLAN

-----------------------------------

Scenario:
"Devices in different VLANs need communication."

Answer:
Inter-VLAN routing

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking VLANs require separate physical switches.

Wrong.

VLANs:
- provide logical separation

-----------------------------------

Trap:
Thinking devices in different VLANs communicate automatically.

Wrong.

Inter-VLAN routing is required.

-----------------------------------

Trap:
Confusing access ports and trunk ports.

Access port:
- one VLAN

Trunk port:
- multiple VLANs

-----------------------------------

Trap:
Ignoring broadcast domains.

Each VLAN:
- creates a separate broadcast domain

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

VLAN =
Logical network segmentation.

Access port =
One VLAN

Trunk port =
Many VLANs

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does VLAN stand for?

A:
Virtual Local Area Network.

-----------------------------------

Q:
What is the purpose of a VLAN?

A:
Logical network segmentation.

-----------------------------------

Q:
What does each VLAN create?

A:
A separate broadcast domain.

-----------------------------------

Q:
What device commonly implements VLANs?

A:
Switches.

-----------------------------------

Q:
What is an access port?

A:
A port carrying traffic for one VLAN.

-----------------------------------

Q:
What is a trunk port?

A:
A port carrying traffic for multiple VLANs.

-----------------------------------

Q:
What standard is commonly used for VLAN tagging?

A:
802.1Q.

-----------------------------------

Q:
Can devices in different VLANs communicate directly?

A:
No.

-----------------------------------

Q:
What is required for communication between VLANs?

A:
Inter-VLAN routing.

-----------------------------------

Q:
What major benefit do VLANs provide?

A:
Improved segmentation and reduced broadcast traffic.