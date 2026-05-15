========================
SNMP
Simple Network Management Protocol
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 3 — Network Operations
Section 3.2: Monitoring and Performance
Pages 57–59
0

-----------------------------------
SNMP
-----------------------------------

SNMP =
Simple Network Management Protocol

-----------------------------------
CORE PURPOSE
-----------------------------------

SNMP is used to:
- monitor
- manage
- gather information from
network devices

-----------------------------------
WHY SNMP EXISTS
-----------------------------------

Large networks contain many devices:
- routers
- switches
- firewalls
- servers
- APs
- printers

SNMP allows centralized systems to:
- monitor device health
- gather statistics
- detect failures
- automate alerts

-----------------------------------
SNMP FUNCTIONS
-----------------------------------

SNMP can:
- collect device information
- monitor performance
- monitor interface status
- track bandwidth usage
- generate alerts

-----------------------------------
COMMON DEVICES USING SNMP
-----------------------------------

Examples:
- routers
- switches
- UPS systems
- printers
- APs
- servers
- IoT devices

-----------------------------------
SNMP COMPONENTS
-----------------------------------

The major SNMP components:
- SNMP manager
- SNMP agent
- MIB

-----------------------------------
SNMP MANAGER
-----------------------------------

The SNMP manager is:
- the centralized monitoring system

-----------------------------------
SNMP MANAGER PURPOSE
-----------------------------------

The manager:
- requests information
- receives alerts
- monitors devices

-----------------------------------
SNMP AGENT
-----------------------------------

The SNMP agent is:
- software running on the monitored device

-----------------------------------
SNMP AGENT PURPOSE
-----------------------------------

The agent:
- collects local device information
- responds to manager requests
- sends notifications/traps

-----------------------------------
MIB
-----------------------------------

MIB =
Management Information Base

-----------------------------------
MIB PURPOSE
-----------------------------------

The MIB is:
- a structured database of monitored device information

-----------------------------------
WHAT THE MIB CONTAINS
-----------------------------------

Examples:
- interface statistics
- CPU usage
- memory usage
- uptime
- device status

-----------------------------------
OIDs
-----------------------------------

{{{
Additional Context:
MIB objects are identified using:
- OIDs (Object Identifiers)

Source:
RFC 1157 SNMP
https://datatracker.ietf.org/
}}}

-----------------------------------
SNMP OPERATIONS
-----------------------------------

Important SNMP operations:
- GET
- SET
- TRAP

-----------------------------------
GET
-----------------------------------

GET requests:
- retrieve information from a device

-----------------------------------
GET EXAMPLE
-----------------------------------

Example:
A monitoring server asks a router:
- current CPU usage
- interface statistics
- uptime

-----------------------------------
SET
-----------------------------------

SET operations:
- modify device settings remotely

-----------------------------------
SET RISKS
-----------------------------------

SET operations may:
- create security risks if improperly secured

-----------------------------------
TRAP
-----------------------------------

TRAP messages:
- are alerts sent from devices to the manager

-----------------------------------
TRAP PURPOSE
-----------------------------------

TRAPs notify administrators about:
- failures
- outages
- threshold violations
- interface problems

-----------------------------------
TRAP EXAMPLE
-----------------------------------

Example:
A switch interface goes down.

The SNMP agent:
- sends a trap to the monitoring server

-----------------------------------
POLLING
-----------------------------------

Polling refers to:
- the manager regularly requesting information from devices

-----------------------------------
POLLING PURPOSE
-----------------------------------

Polling helps:
- continuously monitor network health

-----------------------------------
SNMP VERSIONS
-----------------------------------

Important SNMP versions:
- SNMPv1
- SNMPv2c
- SNMPv3

-----------------------------------
SNMPv1
-----------------------------------

SNMPv1:
- original version
- limited security

-----------------------------------
SNMPv2c
-----------------------------------

SNMPv2c:
- improved performance/features
- still weak security

-----------------------------------
SNMPv3
-----------------------------------

SNMPv3:
- secure version of SNMP

-----------------------------------
SNMPv3 FEATURES
-----------------------------------

SNMPv3 supports:
- authentication
- encryption
- integrity protection

-----------------------------------
IMPORTANT EXAM FACT
-----------------------------------

Very important:
SNMPv3 is preferred because it provides:
- security

-----------------------------------
COMMUNITY STRINGS
-----------------------------------

SNMPv1/v2c commonly use:
- community strings

-----------------------------------
COMMUNITY STRING PURPOSE
-----------------------------------

Community strings act somewhat like:
- passwords for SNMP access

-----------------------------------
COMMON COMMUNITY STRINGS
-----------------------------------

Default examples:
- public
- private

-----------------------------------
SECURITY RISKS
-----------------------------------

Weak/default community strings may allow:
- unauthorized monitoring
- unauthorized configuration changes

-----------------------------------
READ-ONLY VS READ-WRITE
-----------------------------------

Read-only:
- monitoring only

Read-write:
- allows configuration changes

-----------------------------------
READ-WRITE RISKS
-----------------------------------

Read-write SNMP access increases:
- security risk

-----------------------------------
PORTS
-----------------------------------

{{{
Additional Context:
SNMP commonly uses:
- UDP 161 for queries
- UDP 162 for traps

Source:
IANA Service Name Registry
https://www.iana.org/
}}}

-----------------------------------
MONITORING METRICS
-----------------------------------

SNMP commonly monitors:
- bandwidth utilization
- interface errors
- CPU usage
- memory usage
- uptime
- temperature
- device availability

-----------------------------------
NETWORK MANAGEMENT SYSTEMS
-----------------------------------

{{{
Additional Context:
Examples of network monitoring platforms using SNMP:
- SolarWinds
- PRTG
- Zabbix
- Nagios

Source:
Vendor Documentation
}}}

-----------------------------------
THRESHOLDS
-----------------------------------

Monitoring systems may use:
- thresholds

-----------------------------------
THRESHOLD PURPOSE
-----------------------------------

Thresholds trigger alerts when:
- values exceed acceptable limits

-----------------------------------
EXAMPLE THRESHOLDS
-----------------------------------

Examples:
- high CPU usage
- interface down
- excessive bandwidth usage
- temperature warnings

-----------------------------------
SNMP SECURITY BEST PRACTICES
-----------------------------------

{{{
Additional Context:
Common best practices:
- use SNMPv3
- disable unused SNMP versions
- avoid default community strings
- restrict SNMP access with ACLs

Source:
Cisco SNMP Security Guide
https://www.cisco.com/
}}}

-----------------------------------
SNMP VS SYSLOG
-----------------------------------

SNMP:
- monitoring and alerts

Syslog:
- centralized logging

-----------------------------------
SNMP VS NETFLOW
-----------------------------------

SNMP:
- general device monitoring

NetFlow:
- traffic flow analysis

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- SNMP = Simple Network Management Protocol
- Used for monitoring/managing devices
- Manager monitors devices
- Agent runs on monitored device
- MIB stores monitored information
- GET retrieves information
- SET changes information
- TRAP sends alerts
- SNMPv3 is secure
- SNMPv1/v2c use community strings
- UDP 161 = SNMP queries
- UDP 162 = SNMP traps

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A monitoring server checks switch interface utilization."

Answer:
SNMP GET request

-----------------------------------

Scenario:
"A router automatically alerts administrators about an interface failure."

Answer:
SNMP trap

-----------------------------------

Scenario:
"A company wants encrypted SNMP communication."

Answer:
SNMPv3

-----------------------------------

Scenario:
"A network device runs software responding to monitoring requests."

Answer:
SNMP agent

-----------------------------------

Scenario:
"A centralized monitoring platform polls many devices."

Answer:
SNMP manager

-----------------------------------

Scenario:
"A company stores device statistics in a structured database."

Answer:
MIB

-----------------------------------

Scenario:
"A technician sees default SNMP community string 'public'."

Answer:
Security risk

-----------------------------------

Scenario:
"A monitoring system changes remote device settings."

Answer:
SNMP SET operation

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking SNMPv2c is secure.

Wrong.

SNMPv2c:
- has weak security

-----------------------------------

Trap:
Confusing manager and agent.

Manager:
- monitoring system

Agent:
- software on monitored device

-----------------------------------

Trap:
Thinking traps are requested by the manager.

Wrong.

Traps:
- are initiated by devices

-----------------------------------

Trap:
Thinking MIB is the monitoring software itself.

Wrong.

MIB:
- structured information database

-----------------------------------

Trap:
Thinking SNMP only monitors routers.

Wrong.

SNMP monitors many device types.

-----------------------------------

Trap:
Thinking SNMP and syslog are identical.

Wrong.

SNMP:
- monitoring/management

Syslog:
- logging

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

SNMP =
Monitoring

Manager =
Central monitor

Agent =
Runs on device

MIB =
Device information database

Trap =
Automatic alert

v3 =
Secure

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does SNMP stand for?

A:
Simple Network Management Protocol.

-----------------------------------

Q:
What is SNMP used for?

A:
Monitoring and managing network devices.

-----------------------------------

Q:
What is an SNMP manager?

A:
The centralized monitoring system.

-----------------------------------

Q:
What is an SNMP agent?

A:
Software running on the monitored device.

-----------------------------------

Q:
What does MIB stand for?

A:
Management Information Base.

-----------------------------------

Q:
What does a GET request do in SNMP?

A:
Retrieves device information.

-----------------------------------

Q:
What does a SET request do in SNMP?

A:
Changes device settings remotely.

-----------------------------------

Q:
What is an SNMP trap?

A:
An alert sent from a device to the manager.

-----------------------------------

Q:
Which SNMP version is most secure?

A:
SNMPv3.

-----------------------------------

Q:
What are SNMP community strings?

A:
Password-like values used in SNMPv1/v2c.

-----------------------------------

Q:
What UDP port does SNMP commonly use for queries?

A:
UDP 161.

-----------------------------------

Q:
What UDP port does SNMP commonly use for traps?

A:
UDP 162.