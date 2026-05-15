========================
MAC Flooding
CAM Table Overflow Attack
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.2: Common Network Attacks
Pages 66–68


-----------------------------------
MAC FLOODING
-----------------------------------

MAC flooding is:
- an attack that overwhelms a switch's MAC address table

-----------------------------------
CAM TABLE
-----------------------------------

CAM =
Content Addressable Memory

-----------------------------------
CAM TABLE PURPOSE
-----------------------------------

Switches use CAM/MAC tables to:
- map MAC addresses to switch ports

-----------------------------------
WHY CAM TABLES EXIST
-----------------------------------

CAM tables allow switches to:
- forward traffic efficiently

-----------------------------------
SWITCH LEARNING
-----------------------------------

Switches learn:
- source MAC addresses
and associate them with:
- specific ports

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

MAC flooding targets:
- switch CAM tables

-----------------------------------
ATTACKER GOAL
-----------------------------------

Attackers attempt to:
- overflow the CAM table with fake MAC addresses

-----------------------------------
HOW MAC FLOODING WORKS
-----------------------------------

Typical process:

1. Attacker sends many frames
2. Frames contain fake/spoofed MAC addresses
3. Switch CAM table fills up
4. Switch cannot learn legitimate addresses properly
5. Switch may begin flooding traffic

-----------------------------------
TRAFFIC FLOODING
-----------------------------------

When CAM tables overflow:
- switches may forward traffic out many ports

-----------------------------------
FAIL-OPEN BEHAVIOR
-----------------------------------

A switch may behave more like:
- a hub

-----------------------------------
HUB-LIKE BEHAVIOR
-----------------------------------

Instead of intelligent forwarding:
- traffic may broadcast broadly

-----------------------------------
SECURITY RISKS
-----------------------------------

MAC flooding may allow attackers to:
- sniff traffic
- intercept communications
- observe sensitive data

-----------------------------------
PACKET SNIFFING
-----------------------------------

Attackers may capture:
- network traffic
- credentials
- sensitive communications

-----------------------------------
CONFIDENTIALITY IMPACT
-----------------------------------

MAC flooding primarily threatens:
- confidentiality

-----------------------------------
CIA TRIAD
-----------------------------------

CIA =
- Confidentiality
- Integrity
- Availability

-----------------------------------
CONFIDENTIALITY
-----------------------------------

Confidentiality protects:
- sensitive information from unauthorized access

-----------------------------------
SWITCH VS HUB
-----------------------------------

Switches:
- intelligently forward traffic

Hubs:
- broadcast traffic broadly

-----------------------------------
WHY SWITCHES ARE MORE SECURE
-----------------------------------

Switches reduce:
- unnecessary traffic exposure

-----------------------------------
WHY MAC FLOODING MATTERS
-----------------------------------

MAC flooding attempts to:
- defeat switch isolation advantages

-----------------------------------
SPOOFED MAC ADDRESSES
-----------------------------------

Attackers commonly use:
- fake MAC addresses

-----------------------------------
MAC SPOOFING
-----------------------------------

MAC spoofing falsifies:
- hardware MAC addresses

-----------------------------------
AUTOMATED TOOLS
-----------------------------------

Attackers may use:
- automated flooding tools

-----------------------------------
INSIDER THREATS
-----------------------------------

MAC flooding commonly requires:
- local network access

-----------------------------------
LOCAL NETWORK ATTACK
-----------------------------------

This attack usually occurs:
- inside LAN environments

-----------------------------------
SWITCH RESOURCE LIMITS
-----------------------------------

Switch CAM tables have:
- finite size/capacity

-----------------------------------
HIGH TRAFFIC EFFECTS
-----------------------------------

Overflow conditions may:
- degrade performance
- disrupt switching behavior

-----------------------------------
PORT SECURITY
-----------------------------------

Port security helps mitigate:
- MAC flooding attacks

-----------------------------------
PORT SECURITY PURPOSE
-----------------------------------

Port security limits:
- MAC addresses allowed per port

-----------------------------------
COMMON PORT SECURITY CONTROLS
-----------------------------------

Examples:
- MAC address limits
- sticky MAC learning
- shutdown on violation

-----------------------------------
STICKY MAC
-----------------------------------

{{{
Additional Context:
Sticky MAC allows switches to dynamically learn/store approved MAC addresses.

Source:
Cisco Port Security Documentation
https://www.cisco.com/
}}}

-----------------------------------
VIOLATION ACTIONS
-----------------------------------

Switches may:
- drop traffic
- alert administrators
- disable ports

-----------------------------------
DISABLE UNUSED PORTS
-----------------------------------

Unused ports should commonly be:
- disabled

-----------------------------------
NETWORK ACCESS CONTROL
-----------------------------------

{{{
Additional Context:
NAC solutions may help restrict unauthorized devices.

Source:
Cisco NAC Documentation
https://www.cisco.com/
}}}

-----------------------------------
MONITORING
-----------------------------------

Monitoring may identify:
- abnormal MAC address activity

-----------------------------------
IDS/IPS
-----------------------------------

IDS/IPS systems may detect:
- suspicious flooding behavior

-----------------------------------
SEGMENTATION
-----------------------------------

Segmentation may help:
- contain attack impact

-----------------------------------
SWITCH HARDENING
-----------------------------------

Switch hardening commonly includes:
- port security
- disabling unused ports
- monitoring

-----------------------------------
LAYER 2 ATTACK
-----------------------------------

MAC flooding is primarily:
- a Layer 2 attack

-----------------------------------
OSI MODEL
-----------------------------------

Layer 2 =
Data Link layer

-----------------------------------
ETHERNET
-----------------------------------

Ethernet switching operates at:
- Layer 2

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- MAC flooding targets CAM tables
- CAM tables map MAC addresses to ports
- Overflowed switches may behave like hubs
- MAC flooding threatens confidentiality
- MAC flooding is a Layer 2 attack
- Port security helps mitigate attacks
- Attackers use spoofed MAC addresses
- Port security may limit MAC addresses per port

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"An attacker overwhelms a switch with fake MAC addresses."

Answer:
MAC flooding

-----------------------------------

Scenario:
"A switch begins forwarding traffic broadly after table overflow."

Answer:
CAM table overflow/MAC flooding

-----------------------------------

Scenario:
"An attack attempts to sniff switched traffic."

Answer:
MAC flooding

-----------------------------------

Scenario:
"A switch security feature limits MAC addresses per port."

Answer:
Port security

-----------------------------------

Scenario:
"A Layer 2 attack targets Ethernet switching behavior."

Answer:
MAC flooding

-----------------------------------

Scenario:
"A switch acts more like a hub unexpectedly."

Answer:
CAM table overflow

-----------------------------------

Scenario:
"A network admin enables sticky MAC learning."

Answer:
Port security mitigation

-----------------------------------

Scenario:
"A company disables unused switch ports to reduce attack surface."

Answer:
Switch hardening/mitigation

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing MAC flooding and broadcast storms.

MAC flooding:
- CAM table overflow attack

Broadcast storm:
- excessive broadcast traffic

-----------------------------------

Trap:
Thinking switches normally broadcast all traffic.

Wrong.

Switches normally:
- intelligently forward traffic

-----------------------------------

Trap:
Thinking MAC flooding directly targets routers.

Wrong.

MAC flooding targets:
- switches/CAM tables

-----------------------------------

Trap:
Confusing MAC spoofing and MAC flooding.

MAC spoofing:
- falsified MAC addresses

MAC flooding:
- overwhelming CAM tables

-----------------------------------

Trap:
Thinking MAC flooding is primarily a Layer 3 attack.

Wrong.

It is primarily:
- Layer 2

-----------------------------------

Trap:
Thinking port security only blocks physical access.

Wrong.

Port security also controls:
- MAC address behavior

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

MAC flooding =
Overflow switch memory

CAM table =
MAC-to-port map

Overflow =
Hub-like behavior

Port security =
Main mitigation

Layer 2 =
Ethernet switching

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is MAC flooding?

A:
An attack that overwhelms a switch CAM table.

-----------------------------------

Q:
What does a CAM table store?

A:
MAC address to port mappings.

-----------------------------------

Q:
What may happen when a CAM table overflows?

A:
The switch may behave like a hub.

-----------------------------------

Q:
What security objective does MAC flooding primarily threaten?

A:
Confidentiality.

-----------------------------------

Q:
What type of attack is MAC flooding?

A:
A Layer 2 attack.

-----------------------------------

Q:
What security feature helps mitigate MAC flooding?

A:
Port security.

-----------------------------------

Q:
What does port security commonly limit?

A:
The number of MAC addresses per port.

-----------------------------------

Q:
What technique commonly supports MAC flooding attacks?

A:
MAC spoofing.

-----------------------------------

Q:
Why are switches normally more secure than hubs?

A:
They intelligently forward traffic only where needed.

-----------------------------------

Q:
What OSI layer is associated with Ethernet switching?

A:
Layer 2.