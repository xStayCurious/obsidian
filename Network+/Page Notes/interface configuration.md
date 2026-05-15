========================
Interface Configuration
Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Pages 28–29
0

-----------------------------------
INTERFACE CONFIGURATION
-----------------------------------

Interface configuration:
- involves assigning settings
to:
- network interfaces

-----------------------------------
CORE PURPOSE
-----------------------------------

Interface configuration allows devices to:
- communicate on networks
- send and receive traffic
- participate in routing and switching

-----------------------------------
NETWORK INTERFACE
-----------------------------------

A network interface:
- is a connection point
between:
- a device
and:
- a network

-----------------------------------
INTERFACE TYPES
-----------------------------------

Interfaces may include:
- physical interfaces
- logical interfaces
- subinterfaces

-----------------------------------
PHYSICAL INTERFACE
-----------------------------------

A physical interface:
- corresponds to actual hardware ports

-----------------------------------
LOGICAL INTERFACE
-----------------------------------

A logical interface:
- is software-defined
- not tied directly to separate hardware

-----------------------------------
SUBINTERFACES
-----------------------------------

Subinterfaces:
- are logical subdivisions
of:
- a physical interface

-----------------------------------
COMMON INTERFACE SETTINGS
-----------------------------------

Interfaces may be configured with:
- IP addresses
- subnet masks
- VLAN assignments
- speed settings
- duplex settings

-----------------------------------
IP ADDRESS CONFIGURATION
-----------------------------------

Interfaces commonly require:
- an IP address
- a subnet mask

for:
- network communication

-----------------------------------
SUBNET MASK
-----------------------------------

The subnet mask identifies:
- network portion
and:
- host portion
of an IP address

-----------------------------------
INTERFACE STATUS
-----------------------------------

Interfaces may be:
- enabled
or:
- disabled

-----------------------------------
ADMINISTRATIVE STATE
-----------------------------------

{{{
Additional Context:
Interfaces may have an administrative state:
- up
or:
- down

An interface configured as "shutdown" is administratively down.

Source:
Cisco Interface Configuration Guide
https://www.cisco.com/
}}}

-----------------------------------
LINK STATE
-----------------------------------

{{{
Additional Context:
An interface may also have an operational/link state indicating whether a physical connection is active.

Source:
Cisco Interface Status Documentation
https://www.cisco.com/
}}}

-----------------------------------
SPEED SETTINGS
-----------------------------------

Interfaces may be configured for:
- specific speeds

Examples:
- 100 Mbps
- 1 Gbps
- 10 Gbps

-----------------------------------
DUPLEX SETTINGS
-----------------------------------

Interfaces may use:
- half duplex
or:
- full duplex

-----------------------------------
HALF DUPLEX
-----------------------------------

Half duplex:
- devices transmit OR receive
one at a time

-----------------------------------
FULL DUPLEX
-----------------------------------

Full duplex:
- devices transmit AND receive
simultaneously

-----------------------------------
DUPLEX MISMATCH
-----------------------------------

{{{
Additional Context:
A duplex mismatch can cause:
- collisions
- poor performance
- connectivity issues

Source:
Cisco Duplex Mismatch Overview
https://www.cisco.com/
}}}

-----------------------------------
VLAN CONFIGURATION
-----------------------------------

Interfaces may be assigned to:
- VLANs

-----------------------------------
ACCESS PORT CONFIGURATION
-----------------------------------

{{{
Additional Context:
Access ports are assigned to one VLAN.

Source:
Cisco VLAN Overview
https://www.cisco.com/
}}}

-----------------------------------
TRUNK CONFIGURATION
-----------------------------------

{{{
Additional Context:
Trunk interfaces carry multiple VLANs using VLAN tagging.

Source:
Cisco VLAN Trunking Overview
https://www.cisco.com/
}}}

-----------------------------------
ROUTED VS SWITCHED PORTS
-----------------------------------

{{{
Additional Context:
Some interfaces function as:
- Layer 2 switched ports
while others function as:
- Layer 3 routed ports

Source:
Cisco Switching Concepts
https://www.cisco.com/
}}}

-----------------------------------
INTERFACE ERRORS
-----------------------------------

{{{
Additional Context:
Common interface problems include:
- speed mismatches
- duplex mismatches
- cabling problems
- incorrect VLAN assignment

Source:
Cisco Interface Troubleshooting Guide
https://www.cisco.com/
}}}

-----------------------------------
INTERFACE IDENTIFIERS
-----------------------------------

{{{
Additional Context:
Interfaces are commonly identified using names such as:
GigabitEthernet0/1
FastEthernet0/0

Source:
Cisco Interface Naming Conventions
https://www.cisco.com/
}}}

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A network interface needs an IP address and subnet mask."

Answer:
Interface configuration

-----------------------------------

Scenario:
"A switch port is assigned to VLAN 20."

Answer:
Interface/VLAN configuration

-----------------------------------

Scenario:
"A network experiences poor performance due to duplex mismatch."

Answer:
Incorrect interface configuration

-----------------------------------

Scenario:
"A trunk interface carries multiple VLANs."

Answer:
Trunk configuration

-----------------------------------

Scenario:
"An interface is administratively disabled."

Answer:
Interface shutdown/down state

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking interfaces only require IP addresses.

Wrong.

Interfaces may also require:
- VLAN settings
- speed
- duplex
- operational configuration

-----------------------------------

Trap:
Confusing half duplex and full duplex.

Half duplex:
- one direction at a time

Full duplex:
- simultaneous communication

-----------------------------------

Trap:
Thinking subinterfaces are physical ports.

Wrong.

Subinterfaces:
- are logical interfaces

-----------------------------------

Trap:
Ignoring duplex mismatches.

Duplex mismatches:
- commonly cause performance problems

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Interface configuration =
Settings that allow network communication.

Full duplex =
Send and receive simultaneously.

Access port =
One VLAN

Trunk port =
Multiple VLANs

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is interface configuration?

A:
Assigning settings to network interfaces for communication.

-----------------------------------

Q:
What settings are commonly configured on interfaces?

A:
IP address, subnet mask, VLAN, speed, and duplex.

-----------------------------------

Q:
What is a physical interface?

A:
A hardware network connection port.

-----------------------------------

Q:
What is a logical interface?

A:
A software-defined interface.

-----------------------------------

Q:
What is full duplex?

A:
Simultaneous sending and receiving of data.

-----------------------------------

Q:
What is half duplex?

A:
Communication in only one direction at a time.

-----------------------------------

Q:
What can a duplex mismatch cause?

A:
Performance and connectivity problems.

-----------------------------------

Q:
What type of port carries one VLAN?

A:
Access port.

-----------------------------------

Q:
What type of port carries multiple VLANs?

A:
Trunk port.

-----------------------------------

Q:
What does a subnet mask identify?

A:
The network and host portions of an IP address.