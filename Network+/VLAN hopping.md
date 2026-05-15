========================
VLAN Hopping
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.2: Common Network Attacks
Pages 66–68


-----------------------------------
VLAN HOPPING
-----------------------------------

VLAN hopping is:
- an attack that allows traffic to access unauthorized VLANs

-----------------------------------
CORE PURPOSE
-----------------------------------

Attackers attempt to:
- bypass VLAN segmentation
- access restricted networks
- move laterally between VLANs

-----------------------------------
WHY VLAN HOPPING MATTERS
-----------------------------------

VLANs are commonly used for:
- segmentation
- isolation
- security boundaries

If attackers bypass VLAN separation:
- segmentation protections weaken

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

VLAN hopping attacks target:
- VLAN isolation/segmentation

-----------------------------------
SEGMENTATION
-----------------------------------

Segmentation divides:
- networks into isolated sections

-----------------------------------
WHY SEGMENTATION EXISTS
-----------------------------------

Segmentation helps:
- reduce attack surface
- contain threats
- separate trust levels

-----------------------------------
VLAN
-----------------------------------

VLAN =
Virtual Local Area Network

-----------------------------------
VLAN PURPOSE
-----------------------------------

VLANs logically separate:
- broadcast domains/devices

-----------------------------------
COMMON VLAN USE CASES
-----------------------------------

Examples:
- guest networks
- VoIP VLANs
- management VLANs
- server VLANs
- user VLANs

-----------------------------------
ATTACKER GOAL
-----------------------------------

An attacker may attempt to:
- send traffic into unauthorized VLANs

-----------------------------------
COMMON VLAN HOPPING METHODS
-----------------------------------

Two major concepts:
- switch spoofing
- double tagging

===================================
SWITCH SPOOFING
===================================

-----------------------------------
SWITCH SPOOFING
-----------------------------------

Switch spoofing occurs when:
- an attacker pretends to be a switch

-----------------------------------
TRUNKING
-----------------------------------

Trunk links carry:
- traffic for multiple VLANs

-----------------------------------
TRUNK PURPOSE
-----------------------------------

Trunks commonly connect:
- switches
- virtualization hosts
- infrastructure devices

-----------------------------------
DTP
-----------------------------------

{{{
Additional Context:
DTP =
Dynamic Trunking Protocol

Cisco switches may negotiate trunking automatically using DTP.

Source:
Cisco VLAN Security Documentation
https://www.cisco.com/
}}}

-----------------------------------
SWITCH SPOOFING PURPOSE
-----------------------------------

If a port incorrectly becomes a trunk:
- attacker traffic may access multiple VLANs

-----------------------------------
AUTO-TRUNK RISKS
-----------------------------------

Automatic trunk negotiation may create:
- security risks

-----------------------------------
MITIGATION
-----------------------------------

Common mitigations:
- disable DTP
- disable auto trunking
- configure ports manually

-----------------------------------
ACCESS PORTS
-----------------------------------

User-facing ports should commonly be:
- access ports

-----------------------------------
ACCESS PORT
-----------------------------------

Access ports carry:
- one VLAN only

===================================
DOUBLE TAGGING
===================================

-----------------------------------
DOUBLE TAGGING
-----------------------------------

Double tagging uses:
- two VLAN tags in frames

-----------------------------------
TAGGING
-----------------------------------

VLAN tagging identifies:
- VLAN membership

-----------------------------------
802.1Q
-----------------------------------

{{{
Additional Context:
802.1Q is the standard VLAN tagging protocol.

Source:
IEEE 802.1Q VLAN Standard
https://standards.ieee.org/
}}}

-----------------------------------
HOW DOUBLE TAGGING WORKS
-----------------------------------

Typical process:

1. Attacker sends frame with two VLAN tags
2. First switch removes outer tag
3. Remaining tag forwards traffic into another VLAN

-----------------------------------
NATIVE VLAN
-----------------------------------

Double-tagging attacks commonly involve:
- native VLANs

-----------------------------------
NATIVE VLAN
-----------------------------------

The native VLAN carries:
- untagged traffic on trunk links

-----------------------------------
WHY NATIVE VLANS MATTER
-----------------------------------

Improper native VLAN configuration may:
- increase VLAN hopping risk

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

Native VLAN misconfiguration is heavily associated with:
- VLAN hopping risk

-----------------------------------
DOUBLE-TAGGING LIMITATIONS
-----------------------------------

Double tagging commonly only works:
- under certain trunk/native VLAN conditions

===================================
MITIGATION
===================================

-----------------------------------
COMMON MITIGATIONS
-----------------------------------

Mitigations include:
- disable unused ports
- disable DTP
- manually configure trunking
- change native VLANs
- avoid VLAN 1 usage
- use access ports appropriately

-----------------------------------
DISABLE DTP
-----------------------------------

Disabling DTP helps prevent:
- unauthorized trunk negotiation

-----------------------------------
MANUAL TRUNK CONFIGURATION
-----------------------------------

Administrators should commonly:
- statically configure trunks

-----------------------------------
UNUSED PORTS
-----------------------------------

Unused switch ports should commonly be:
- disabled

-----------------------------------
NATIVE VLAN BEST PRACTICES
-----------------------------------

Common best practices:
- avoid default VLAN 1
- use unused native VLAN IDs

-----------------------------------
PORT SECURITY
-----------------------------------

{{{
Additional Context:
Port security may help limit unauthorized device access.

Source:
Cisco Port Security Documentation
https://www.cisco.com/
}}}

-----------------------------------
ACLs
-----------------------------------

ACLs may help:
- restrict inter-VLAN communication

-----------------------------------
MONITORING
-----------------------------------

Monitoring/logging may help detect:
- suspicious VLAN activity

-----------------------------------
SEGMENTATION SECURITY
-----------------------------------

Proper VLAN security strengthens:
- segmentation effectiveness

-----------------------------------
LATERAL MOVEMENT
-----------------------------------

Successful VLAN hopping may enable:
- lateral movement

-----------------------------------
LATERAL MOVEMENT PURPOSE
-----------------------------------

Attackers pivot:
- between systems/networks

-----------------------------------
MANAGEMENT VLAN RISKS
-----------------------------------

Compromised management VLANs may:
- expose infrastructure administration

-----------------------------------
VOICE VLAN RISKS
-----------------------------------

{{{
Additional Context:
Voice VLANs may also require secure segmentation.

Source:
Cisco Voice VLAN Documentation
https://www.cisco.com/
}}}

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- VLAN hopping bypasses VLAN segmentation
- Switch spoofing attempts unauthorized trunking
- Double tagging abuses VLAN tags/native VLANs
- DTP may create trunking risks
- Access ports carry one VLAN
- Trunk ports carry multiple VLANs
- Native VLAN misconfiguration increases risk
- Disabling DTP helps mitigate attacks
- Avoid using default VLAN 1 when possible

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"An attacker gains access to unauthorized VLAN traffic."

Answer:
VLAN hopping

-----------------------------------

Scenario:
"A malicious device negotiates a trunk connection."

Answer:
Switch spoofing

-----------------------------------

Scenario:
"An attack abuses multiple VLAN tags in Ethernet frames."

Answer:
Double tagging

-----------------------------------

Scenario:
"A switch port dynamically becomes a trunk unexpectedly."

Answer:
DTP/security misconfiguration

-----------------------------------

Scenario:
"A network administrator disables automatic trunk negotiation."

Answer:
Mitigation against VLAN hopping

-----------------------------------

Scenario:
"A port should only carry one VLAN for endpoint devices."

Answer:
Access port

-----------------------------------

Scenario:
"A link carries traffic for multiple VLANs."

Answer:
Trunk link

-----------------------------------

Scenario:
"A company changes native VLAN settings to improve security."

Answer:
VLAN hopping mitigation

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing access ports and trunk ports.

Access port:
- single VLAN

Trunk port:
- multiple VLANs

-----------------------------------

Trap:
Thinking VLANs provide perfect security automatically.

Wrong.

Misconfiguration may allow:
- VLAN hopping attacks

-----------------------------------

Trap:
Thinking DTP is always desirable.

Wrong.

Automatic trunk negotiation may:
- increase attack surface

-----------------------------------

Trap:
Confusing switch spoofing and double tagging.

Switch spoofing:
- fake trunk negotiation

Double tagging:
- multiple VLAN tags/native VLAN abuse

-----------------------------------

Trap:
Thinking VLAN 1 is always safe to use.

Wrong.

Default/native VLAN configurations may:
- increase security risk

-----------------------------------

Trap:
Thinking VLAN hopping directly breaks encryption.

Wrong.

VLAN hopping primarily:
- bypasses segmentation/isolation

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

VLAN hopping =
Bypass segmentation

Switch spoofing =
Fake trunk

Double tagging =
Two VLAN tags

Access port =
One VLAN

Trunk =
Many VLANs

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is VLAN hopping?

A:
An attack that bypasses VLAN segmentation.

-----------------------------------

Q:
What is switch spoofing?

A:
Pretending to be a switch to negotiate trunk access.

-----------------------------------

Q:
What is double tagging?

A:
An attack using multiple VLAN tags to cross VLAN boundaries.

-----------------------------------

Q:
What protocol is commonly associated with trunk negotiation?

A:
DTP.

-----------------------------------

Q:
What is an access port?

A:
A switch port carrying one VLAN.

-----------------------------------

Q:
What is a trunk port?

A:
A port carrying traffic for multiple VLANs.

-----------------------------------

Q:
What protocol commonly handles VLAN tagging?

A:
802.1Q.

-----------------------------------

Q:
Why can native VLANs increase VLAN hopping risk?

A:
Improper native VLAN handling may enable double-tagging attacks.

-----------------------------------

Q:
What is a common mitigation for VLAN hopping?

A:
Disable DTP/manual trunk configuration.

-----------------------------------

Q:
What security concept do VLAN hopping attacks primarily undermine?

A:
Segmentation/isolation.