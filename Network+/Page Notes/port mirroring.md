========================
Port Mirroring
SPAN
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 3 — Network Operations
Section 3.2: Monitoring and Performance
Pages 57–59
0

-----------------------------------
PORT MIRRORING
-----------------------------------

Port mirroring is:
- copying network traffic from one port to another port for monitoring/analysis

-----------------------------------
CORE PURPOSE
-----------------------------------

Port mirroring allows administrators to:
- analyze traffic
- troubleshoot problems
- monitor activity
- inspect packets
- perform security analysis

-----------------------------------
WHY PORT MIRRORING EXISTS
-----------------------------------

Switches normally forward traffic only to:
- intended destinations

This means:
- monitoring systems may not naturally see all traffic

Port mirroring solves this by:
- copying traffic to a monitoring interface

-----------------------------------
SPAN
-----------------------------------

SPAN =
Switched Port Analyzer

-----------------------------------
SPAN PURPOSE
-----------------------------------

SPAN is Cisco terminology for:
- port mirroring

-----------------------------------
HOW PORT MIRRORING WORKS
-----------------------------------

A switch:
- copies traffic from source ports/VLANs
to:
- a destination monitoring port

-----------------------------------
SOURCE PORT
-----------------------------------

The source port is:
- the interface being monitored

-----------------------------------
DESTINATION PORT
-----------------------------------

The destination port is:
- the interface receiving mirrored traffic

-----------------------------------
DESTINATION DEVICE
-----------------------------------

The destination device may be:
- a laptop
- packet capture system
- IDS
- IPS
- monitoring appliance

-----------------------------------
TRAFFIC TYPES
-----------------------------------

Port mirroring may copy:
- inbound traffic
- outbound traffic
- both directions

-----------------------------------
PACKET CAPTURE
-----------------------------------

Port mirroring is commonly used with:
- packet capture tools

-----------------------------------
COMMON TOOLS
-----------------------------------

{{{
Additional Context:
Common packet analysis tools:
- Wireshark
- tcpdump
- tshark

Source:
Wireshark Documentation
https://www.wireshark.org/
}}}

-----------------------------------
WHY PORT MIRRORING IS IMPORTANT
-----------------------------------

Without port mirroring:
- switched traffic may not be visible to monitoring systems

-----------------------------------
SWITCHED NETWORKS
-----------------------------------

Modern Ethernet switches:
- isolate traffic between ports

-----------------------------------
WHY THIS MATTERS
-----------------------------------

Unlike hubs:
- switches do not normally broadcast all traffic to every device

-----------------------------------
HUB VS SWITCH
-----------------------------------

Hub:
- sends traffic everywhere

Switch:
- forwards traffic intelligently

-----------------------------------
MONITORING USE CASES
-----------------------------------

Port mirroring commonly supports:
- troubleshooting
- intrusion detection
- packet analysis
- protocol analysis
- performance monitoring

-----------------------------------
SECURITY MONITORING
-----------------------------------

Security devices commonly use mirrored traffic for:
- threat detection
- anomaly analysis
- IDS monitoring

-----------------------------------
IDS
-----------------------------------

IDS =
Intrusion Detection System

-----------------------------------
IDS PURPOSE
-----------------------------------

IDS devices monitor:
- mirrored traffic
for:
- suspicious activity

-----------------------------------
IPS
-----------------------------------

IPS =
Intrusion Prevention System

-----------------------------------
IPS PURPOSE
-----------------------------------

IPS systems may:
- inspect traffic
- block malicious activity

-----------------------------------
FULL PACKET VISIBILITY
-----------------------------------

Port mirroring supports:
- full packet analysis

-----------------------------------
FLOW DATA VS PORT MIRRORING
-----------------------------------

Flow data:
- summarized metadata

Port mirroring:
- enables full packet inspection

-----------------------------------
SPAN CONFIGURATION
-----------------------------------

SPAN configurations commonly specify:
- source interfaces
- destination interfaces
- traffic direction

-----------------------------------
LOCAL SPAN
-----------------------------------

{{{
Additional Context:
Local SPAN mirrors traffic within the same switch.

Source:
Cisco SPAN Documentation
https://www.cisco.com/
}}}

-----------------------------------
REMOTE SPAN
-----------------------------------

{{{
Additional Context:
RSPAN =
Remote SPAN

RSPAN allows mirrored traffic to traverse switches remotely.

Source:
Cisco RSPAN Documentation
https://www.cisco.com/
}}}

-----------------------------------
ERSPAN
-----------------------------------

{{{
Additional Context:
ERSPAN =
Encapsulated Remote SPAN

ERSPAN transports mirrored traffic across IP networks.

Source:
Cisco ERSPAN Documentation
https://www.cisco.com/
}}}

-----------------------------------
VLAN MIRRORING
-----------------------------------

Some switches may mirror:
- entire VLAN traffic

-----------------------------------
WHY VLAN MIRRORING MATTERS
-----------------------------------

This allows visibility into:
- multiple devices simultaneously

-----------------------------------
PERFORMANCE IMPACT
-----------------------------------

Port mirroring may:
- increase switch load
- increase bandwidth usage
- impact performance if overused

-----------------------------------
OVERSUBSCRIPTION
-----------------------------------

{{{
Additional Context:
Oversubscription may occur when mirrored traffic exceeds destination port capacity.

Source:
Cisco SPAN Best Practices
https://www.cisco.com/
}}}

-----------------------------------
PROMISCUOUS MODE
-----------------------------------

Monitoring systems commonly use:
- promiscuous mode

-----------------------------------
PROMISCUOUS MODE PURPOSE
-----------------------------------

Promiscuous mode allows:
- capturing traffic not specifically addressed to the monitoring device

-----------------------------------
TAPS
-----------------------------------

{{{
Additional Context:
Network TAPs provide dedicated passive traffic monitoring.

Source:
Gigamon TAP Concepts
https://www.gigamon.com/
}}}

-----------------------------------
TAP VS SPAN
-----------------------------------

TAP:
- dedicated hardware monitoring device

SPAN:
- switch-based traffic mirroring

-----------------------------------
FILTERING
-----------------------------------

Packet analysis tools commonly use:
- filters

-----------------------------------
FILTER PURPOSE
-----------------------------------

Filters help:
- isolate relevant traffic
- reduce noise
- simplify troubleshooting

-----------------------------------
COMMON TROUBLESHOOTING USES
-----------------------------------

Port mirroring may help diagnose:
- packet loss
- retransmissions
- DNS failures
- DHCP issues
- latency
- protocol errors

-----------------------------------
SECURITY INVESTIGATION USES
-----------------------------------

Mirrored traffic may help identify:
- malware communication
- unauthorized traffic
- suspicious activity
- attack attempts

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Port mirroring copies traffic for monitoring
- SPAN = Switched Port Analyzer
- Source port = monitored interface
- Destination port = monitoring interface
- Port mirroring supports packet capture
- Switches normally isolate traffic
- IDS/IPS commonly use mirrored traffic
- Promiscuous mode captures additional traffic
- Port mirroring enables full packet analysis

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A switch copies traffic to a monitoring laptop."

Answer:
Port mirroring/SPAN

-----------------------------------

Scenario:
"A security appliance inspects mirrored switch traffic."

Answer:
SPAN/port mirroring

-----------------------------------

Scenario:
"A network engineer captures packets from a specific switch port."

Answer:
Port mirroring

-----------------------------------

Scenario:
"A monitoring interface receives copied traffic from another interface."

Answer:
Destination SPAN port

-----------------------------------

Scenario:
"A switch interface being monitored for troubleshooting."

Answer:
Source SPAN port

-----------------------------------

Scenario:
"A company wants full packet visibility on switched traffic."

Answer:
Port mirroring

-----------------------------------

Scenario:
"A security analyst uses Wireshark to inspect mirrored packets."

Answer:
SPAN + packet capture

-----------------------------------

Scenario:
"A network monitoring device receives traffic not originally addressed to it."

Answer:
Promiscuous mode

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking switches naturally expose all traffic to all devices.

Wrong.

Switches:
- isolate traffic intelligently

-----------------------------------

Trap:
Thinking port mirroring modifies traffic.

Wrong.

Port mirroring:
- copies traffic only

-----------------------------------

Trap:
Thinking SPAN and packet capture are identical.

Wrong.

SPAN:
- copies traffic

Packet capture:
- analyzes copied packets

-----------------------------------

Trap:
Thinking flow monitoring and port mirroring are identical.

Wrong.

Flow monitoring:
- summarized metadata

Port mirroring:
- full packet visibility

-----------------------------------

Trap:
Thinking destination SPAN ports generate mirrored traffic.

Wrong.

Source ports:
- generate mirrored traffic

Destination ports:
- receive mirrored traffic

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

SPAN =
Port mirroring

Source port =
Monitored traffic

Destination port =
Receives copied traffic

Port mirroring =
Full packet visibility

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is port mirroring?

A:
Copying network traffic to another port for monitoring.

-----------------------------------

Q:
What does SPAN stand for?

A:
Switched Port Analyzer.

-----------------------------------

Q:
What is the purpose of port mirroring?

A:
Traffic monitoring and packet analysis.

-----------------------------------

Q:
What is a source port in SPAN?

A:
The monitored interface.

-----------------------------------

Q:
What is a destination port in SPAN?

A:
The interface receiving mirrored traffic.

-----------------------------------

Q:
Why is port mirroring useful on switches?

A:
Switches normally isolate traffic between ports.

-----------------------------------

Q:
What tools commonly analyze mirrored traffic?

A:
Wireshark and tcpdump.

-----------------------------------

Q:
What security devices commonly use mirrored traffic?

A:
IDS and IPS systems.

-----------------------------------

Q:
What is the difference between flow data and port mirroring?

A:
Flow data summarizes metadata; port mirroring enables full packet inspection.

-----------------------------------

Q:
What does promiscuous mode allow?

A:
Capturing traffic not specifically addressed to the monitoring device.