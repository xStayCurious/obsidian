========================
Network Segmentation
IoT, IIoT, SCADA,
ICS, OT, Guest,
and BYOD Networks
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.2: Network Segmentation
Pages 66–68


-----------------------------------
NETWORK SEGMENTATION
-----------------------------------

Network segmentation divides:
- networks into smaller isolated sections

-----------------------------------
CORE PURPOSE
-----------------------------------

Segmentation helps:
- improve security
- reduce attack surface
- contain threats
- improve performance
- separate trust levels

-----------------------------------
WHY SEGMENTATION EXISTS
-----------------------------------

Not all devices/systems should:
- communicate freely
- share the same trust level
- access sensitive resources

-----------------------------------
SEGMENTATION BENEFITS
-----------------------------------

Benefits:
- reduced lateral movement
- improved monitoring
- easier access control
- isolation of vulnerable devices

-----------------------------------
LATERAL MOVEMENT
-----------------------------------

Lateral movement occurs when attackers:
- pivot between systems/networks

-----------------------------------
COMMON SEGMENTATION METHODS
-----------------------------------

Examples:
- VLANs
- subnets
- firewalls
- ACLs
- air gaps

-----------------------------------
TRUST ZONES
-----------------------------------

Segmentation commonly creates:
- trust boundaries/zones

-----------------------------------
HIGH-YIELD EXAM IDEA
-----------------------------------

Very important concept:
High-risk or less-trusted devices are commonly:
- isolated from critical systems

===================================
IoT
===================================

-----------------------------------
IoT
-----------------------------------

IoT =
Internet of Things

-----------------------------------
IoT PURPOSE
-----------------------------------

IoT includes:
- Internet-connected smart devices

-----------------------------------
COMMON IoT DEVICES
-----------------------------------

Examples:
- smart TVs
- cameras
- thermostats
- smart bulbs
- voice assistants
- smart appliances

-----------------------------------
IoT SECURITY RISKS
-----------------------------------

IoT devices commonly have:
- weak security
- poor patching
- default passwords
- limited monitoring

-----------------------------------
WHY IoT SHOULD BE SEGMENTED
-----------------------------------

Compromised IoT devices may:
- become attack entry points
- join botnets
- threaten production systems

-----------------------------------
COMMON IoT SEGMENTATION
-----------------------------------

IoT devices are commonly isolated using:
- VLANs
- guest networks
- dedicated subnets

-----------------------------------
BOTNET RISKS
-----------------------------------

{{{
Additional Context:
Compromised IoT devices are commonly used in botnets.

Source:
CISA IoT Security Guidance
https://www.cisa.gov/
}}}

-----------------------------------
DEFAULT PASSWORD RISKS
-----------------------------------

IoT devices frequently suffer from:
- insecure default credentials

===================================
IIoT
===================================

-----------------------------------
IIoT
-----------------------------------

IIoT =
Industrial Internet of Things

-----------------------------------
IIoT PURPOSE
-----------------------------------

IIoT refers to:
- industrial smart/connected devices

-----------------------------------
COMMON IIoT DEVICES
-----------------------------------

Examples:
- industrial sensors
- robotics
- manufacturing systems
- smart industrial controllers

-----------------------------------
IIoT ENVIRONMENTS
-----------------------------------

IIoT is commonly found in:
- factories
- utilities
- manufacturing plants
- industrial operations

-----------------------------------
IIoT SECURITY RISKS
-----------------------------------

Compromised IIoT systems may:
- disrupt industrial operations
- impact safety
- damage infrastructure

-----------------------------------
WHY IIoT SEGMENTATION MATTERS
-----------------------------------

Industrial environments often require:
- strict isolation
- operational reliability
- safety protections

-----------------------------------
IIoT VS IoT
-----------------------------------

IoT:
- consumer/general smart devices

IIoT:
- industrial operational devices

===================================
SCADA
===================================

-----------------------------------
SCADA
-----------------------------------

SCADA =
Supervisory Control and Data Acquisition

-----------------------------------
SCADA PURPOSE
-----------------------------------

SCADA systems monitor/control:
- industrial infrastructure

-----------------------------------
COMMON SCADA ENVIRONMENTS
-----------------------------------

Examples:
- power grids
- water systems
- pipelines
- utilities
- manufacturing

-----------------------------------
SCADA FUNCTIONS
-----------------------------------

SCADA systems commonly:
- collect telemetry
- monitor equipment
- control industrial processes

-----------------------------------
SCADA SECURITY RISKS
-----------------------------------

Compromised SCADA systems may:
- disrupt critical infrastructure
- create physical damage
- threaten safety

-----------------------------------
WHY SCADA SEGMENTATION MATTERS
-----------------------------------

SCADA systems should generally be:
- highly isolated
- tightly controlled

-----------------------------------
AIR GAPS
-----------------------------------

{{{
Additional Context:
Some critical SCADA systems use air gaps for isolation.

Source:
CISA ICS Security Guidance
https://www.cisa.gov/
}}}

-----------------------------------
AIR GAP
-----------------------------------

Air gaps isolate systems by:
- physically separating them from networks

===================================
ICS
===================================

-----------------------------------
ICS
-----------------------------------

ICS =
Industrial Control Systems

-----------------------------------
ICS PURPOSE
-----------------------------------

ICS manage/control:
- industrial operations/processes

-----------------------------------
ICS COMPONENTS
-----------------------------------

ICS may include:
- PLCs
- SCADA systems
- sensors
- industrial controllers

-----------------------------------
PLC
-----------------------------------

{{{
Additional Context:
PLC =
Programmable Logic Controller

PLCs commonly automate industrial processes.

Source:
CISA ICS Security Guidance
https://www.cisa.gov/
}}}

-----------------------------------
ICS SECURITY PRIORITIES
-----------------------------------

ICS environments prioritize:
- safety
- reliability
- uptime
- operational continuity

-----------------------------------
ICS VS IT
-----------------------------------

Traditional IT focuses heavily on:
- confidentiality

ICS/OT environments heavily prioritize:
- availability
- safety

-----------------------------------
LEGACY SYSTEM RISKS
-----------------------------------

ICS environments commonly contain:
- legacy systems
- outdated operating systems

-----------------------------------
PATCHING RISKS
-----------------------------------

Industrial systems may:
- patch slowly
due to:
- operational risk concerns

===================================
OT
===================================

-----------------------------------
OT
-----------------------------------

OT =
Operational Technology

-----------------------------------
OT PURPOSE
-----------------------------------

OT includes:
- hardware/software managing physical operations

-----------------------------------
COMMON OT ENVIRONMENTS
-----------------------------------

Examples:
- manufacturing
- utilities
- transportation
- industrial facilities

-----------------------------------
OT VS IT
-----------------------------------

IT:
- information/data systems

OT:
- physical operational systems

-----------------------------------
OT SECURITY PRIORITIES
-----------------------------------

OT environments heavily prioritize:
- uptime
- safety
- operational continuity

-----------------------------------
OT SEGMENTATION
-----------------------------------

OT systems are commonly:
- isolated from enterprise IT networks

-----------------------------------
WHY OT SEGMENTATION MATTERS
-----------------------------------

Compromise of OT may:
- disrupt physical operations
- threaten safety
- damage infrastructure

-----------------------------------
CONVERGENCE
-----------------------------------

{{{
Additional Context:
Modern organizations increasingly integrate IT and OT systems, increasing security complexity.

Source:
NIST OT Security Guidance
https://csrc.nist.gov/
}}}

===================================
GUEST NETWORKS
===================================

-----------------------------------
GUEST NETWORK
-----------------------------------

Guest networks provide:
- isolated network access for visitors

-----------------------------------
CORE PURPOSE
-----------------------------------

Guest networks separate:
- untrusted users/devices
from:
- internal resources

-----------------------------------
WHY GUEST NETWORKS EXIST
-----------------------------------

Visitors should generally NOT access:
- production systems
- internal servers
- sensitive resources

-----------------------------------
COMMON GUEST NETWORK FEATURES
-----------------------------------

Examples:
- Internet-only access
- bandwidth restrictions
- client isolation

-----------------------------------
CLIENT ISOLATION
-----------------------------------

Client isolation prevents:
- guest devices from communicating directly

-----------------------------------
GUEST NETWORK SECURITY BENEFITS
-----------------------------------

Guest segmentation reduces:
- internal exposure
- malware spread
- unauthorized access

-----------------------------------
COMMON DEPLOYMENTS
-----------------------------------

Examples:
- hotels
- offices
- cafes
- enterprise WiFi

===================================
BYOD
===================================

-----------------------------------
BYOD
-----------------------------------

BYOD =
Bring Your Own Device

-----------------------------------
BYOD PURPOSE
-----------------------------------

BYOD allows employees to:
- use personal devices for work

-----------------------------------
COMMON BYOD DEVICES
-----------------------------------

Examples:
- phones
- tablets
- laptops

-----------------------------------
BYOD SECURITY RISKS
-----------------------------------

Personal devices may:
- lack security controls
- contain malware
- bypass standards
- expose sensitive data

-----------------------------------
WHY BYOD SHOULD BE SEGMENTED
-----------------------------------

BYOD devices are often:
- less trusted than managed corporate devices

-----------------------------------
BYOD SECURITY CONTROLS
-----------------------------------

Examples:
- NAC
- MDM
- VLANs
- restricted access
- MFA

-----------------------------------
NAC
-----------------------------------

NAC =
Network Access Control

-----------------------------------
NAC PURPOSE
-----------------------------------

NAC validates:
- device compliance/security posture

-----------------------------------
MDM
-----------------------------------

MDM =
Mobile Device Management

-----------------------------------
MDM PURPOSE
-----------------------------------

MDM helps manage:
- mobile device security/settings

-----------------------------------
BYOD ACCESS RESTRICTIONS
-----------------------------------

BYOD devices may receive:
- limited network access

-----------------------------------
COMPLIANCE RISKS
-----------------------------------

BYOD environments may increase:
- privacy concerns
- compliance complexity

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Segmentation isolates systems/devices
- IoT devices commonly require isolation
- IIoT refers to industrial smart devices
- SCADA monitors industrial infrastructure
- ICS controls industrial operations
- OT manages physical operational systems
- Guest networks isolate visitors
- BYOD involves personal employee devices
- IoT/guest/BYOD networks are lower trust
- OT/ICS prioritize availability/safety

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company isolates smart cameras from production systems."

Answer:
IoT segmentation

-----------------------------------

Scenario:
"A utility company protects industrial control systems."

Answer:
SCADA/ICS segmentation

-----------------------------------

Scenario:
"A business separates visitor WiFi from internal systems."

Answer:
Guest network segmentation

-----------------------------------

Scenario:
"Employees use personal phones for corporate email."

Answer:
BYOD

-----------------------------------

Scenario:
"A manufacturing facility isolates robotics controllers."

Answer:
IIoT/OT segmentation

-----------------------------------

Scenario:
"A network validates device compliance before granting access."

Answer:
NAC

-----------------------------------

Scenario:
"A company manages employee smartphones remotely."

Answer:
MDM

-----------------------------------

Scenario:
"A critical industrial environment prioritizes uptime over confidentiality."

Answer:
OT/ICS environment

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing IoT and IIoT.

IoT:
- consumer/general smart devices

IIoT:
- industrial smart devices

-----------------------------------

Trap:
Confusing IT and OT.

IT:
- information systems

OT:
- operational/physical systems

-----------------------------------

Trap:
Thinking guest networks should access internal resources.

Wrong.

Guest networks are typically:
- isolated

-----------------------------------

Trap:
Thinking BYOD devices are fully trusted.

Wrong.

BYOD devices commonly represent:
- increased security risk

-----------------------------------

Trap:
Thinking ICS environments prioritize confidentiality above all else.

Wrong.

ICS/OT heavily prioritize:
- availability
- safety

-----------------------------------

Trap:
Thinking segmentation only improves performance.

Wrong.

Segmentation also improves:
- security
- containment
- monitoring

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

IoT =
Smart consumer devices

IIoT =
Industrial smart devices

SCADA =
Industrial monitoring/control

ICS =
Industrial control

OT =
Operational systems

Guest =
Visitor isolation

BYOD =
Personal work devices

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is network segmentation?

A:
Dividing networks into isolated sections.

-----------------------------------

Q:
What does IoT stand for?

A:
Internet of Things.

-----------------------------------

Q:
What does IIoT stand for?

A:
Industrial Internet of Things.

-----------------------------------

Q:
What does SCADA stand for?

A:
Supervisory Control and Data Acquisition.

-----------------------------------

Q:
What does ICS stand for?

A:
Industrial Control Systems.

-----------------------------------

Q:
What does OT stand for?

A:
Operational Technology.

-----------------------------------

Q:
What is the purpose of guest networks?

A:
Provide isolated access for visitors.

-----------------------------------

Q:
What does BYOD stand for?

A:
Bring Your Own Device.

-----------------------------------

Q:
Why are IoT devices commonly segmented?

A:
They often have weaker security and higher risk.

-----------------------------------

Q:
What security priority is especially important in OT/ICS environments?

A:
Availability and safety.