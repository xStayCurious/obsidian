========================
Wireless Access Points (APs)
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 2.3: Wireless Devices and Technologies
Pages 45–50
0 1

-----------------------------------
ACCESS POINT (AP)
-----------------------------------

An access point (AP):
- provides wireless connectivity
to:
- client devices

-----------------------------------
CORE PURPOSE
-----------------------------------

Access points allow:
- wireless devices
to communicate with:
- wired networks

-----------------------------------
HOW APS WORK
-----------------------------------

An AP acts as:
- a bridge between wireless and wired communication

Wireless clients connect to:
- the AP

The AP then forwards traffic to:
- the wired LAN/network infrastructure

-----------------------------------
AP EXAM IDEA
-----------------------------------

The most important AP concept:

AP =
wireless bridge into the wired network

-----------------------------------
COMMON AP FUNCTIONS
-----------------------------------

Access points commonly:
- broadcast SSIDs
- manage wireless associations
- authenticate wireless users
- encrypt wireless traffic
- relay traffic to wired networks

-----------------------------------
WIRELESS CLIENTS
-----------------------------------

Common wireless clients:
- laptops
- phones
- tablets
- printers
- IoT devices

-----------------------------------
INFRASTRUCTURE MODE
-----------------------------------

Most modern wireless networking uses:
- infrastructure mode

-----------------------------------
INFRASTRUCTURE MODE MEANING
-----------------------------------

In infrastructure mode:
- wireless clients communicate through an AP

instead of:
- directly with each other

-----------------------------------
AP VS AD HOC
-----------------------------------

Infrastructure mode:
- uses APs

Ad hoc mode:
- direct client-to-client communication
- no AP required

-----------------------------------
SSID BROADCASTING
-----------------------------------

APs commonly broadcast:
- SSIDs

-----------------------------------
SSID PURPOSE
-----------------------------------

SSID =
Service Set Identifier

Purpose:
- identify the wireless network name

-----------------------------------
MULTIPLE SSIDS
-----------------------------------

One AP may broadcast:
- multiple SSIDs

Examples:
- employee WiFi
- guest WiFi
- IoT WiFi

-----------------------------------
SSID/VLAN MAPPING
-----------------------------------

Different SSIDs commonly map to:
- different VLANs
- different security policies
- different access permissions

-----------------------------------
BSSID
-----------------------------------

BSSID =
Basic Service Set Identifier

-----------------------------------
BSSID PURPOSE
-----------------------------------

The BSSID uniquely identifies:
- a specific AP radio

-----------------------------------
ROAMING
-----------------------------------

Enterprise AP deployments commonly support:
- wireless roaming

-----------------------------------
ROAMING PURPOSE
-----------------------------------

Roaming allows:
- clients to move between APs
while:
- remaining connected to the same network

-----------------------------------
ESS
-----------------------------------

ESS =
Extended Service Set

-----------------------------------
ESS PURPOSE
-----------------------------------

Multiple APs may share:
- the same SSID

to create:
- seamless wireless coverage

-----------------------------------
CHANNELS
-----------------------------------

APs operate on:
- wireless channels

-----------------------------------
CHANNEL PURPOSE
-----------------------------------

Channels help:
- organize RF communication
- reduce interference

-----------------------------------
2.4 GHz CHANNEL FACT
-----------------------------------

Important exam fact:
The common non-overlapping 2.4 GHz channels are:
- 1
- 6
- 11

-----------------------------------
CHANNEL PLANNING
-----------------------------------

Proper AP channel planning helps:
- reduce interference
- improve roaming
- improve performance

-----------------------------------
CHANNEL WIDTH
-----------------------------------

APs may use different channel widths such as:
- 20 MHz
- 40 MHz
- 80 MHz

-----------------------------------
CHANNEL WIDTH TRADEOFF
-----------------------------------

Wider channels:
- higher throughput
but:
- greater interference risk

-----------------------------------
FREQUENCY OPTIONS
-----------------------------------

APs may operate on:
- 2.4 GHz
- 5 GHz
- 6 GHz

-----------------------------------
2.4 GHz CHARACTERISTICS
-----------------------------------

2.4 GHz:
- longer range
- more interference

-----------------------------------
5 GHz CHARACTERISTICS
-----------------------------------

5 GHz:
- higher throughput
- shorter range
- more channels

-----------------------------------
6 GHz CHARACTERISTICS
-----------------------------------

6 GHz:
- cleaner spectrum
- higher capacity
- modern WiFi 6E support

-----------------------------------
BAND STEERING
-----------------------------------

Band steering:
- moves capable devices
toward:
- 5 GHz or 6 GHz

-----------------------------------
WHY BAND STEERING EXISTS
-----------------------------------

Band steering helps:
- reduce 2.4 GHz congestion
- improve wireless performance

-----------------------------------
ENCRYPTION
-----------------------------------

APs commonly support:
- WPA2
- WPA3

-----------------------------------
AUTHENTICATION
-----------------------------------

APs may support:
- PSK authentication
- enterprise authentication
- captive portals

-----------------------------------
PSK
-----------------------------------

PSK =
Pre-Shared Key

-----------------------------------
ENTERPRISE AUTHENTICATION
-----------------------------------

Enterprise authentication commonly uses:
- RADIUS
- 802.1X

-----------------------------------
CAPTIVE PORTALS
-----------------------------------

Guest wireless networks may use:
- captive portals

-----------------------------------
CAPTIVE PORTAL PURPOSE
-----------------------------------

Captive portals may require:
- login
- agreement acceptance
- payment
before:
- network access is granted

-----------------------------------
ANTENNAS
-----------------------------------

APs use antennas to:
- transmit RF signals
- receive RF signals

-----------------------------------
OMNIDIRECTIONAL ANTENNAS
-----------------------------------

Most indoor APs commonly use:
- omnidirectional antennas

-----------------------------------
DIRECTIONAL ANTENNAS
-----------------------------------

Some AP deployments use:
- directional antennas

especially for:
- outdoor links
- point-to-point communication

-----------------------------------
MIMO
-----------------------------------

{{{
Additional Context:
MIMO =
Multiple Input Multiple Output

Uses multiple antennas simultaneously to improve throughput and reliability.

Source:
Cisco WiFi Technologies Overview
https://www.cisco.com/
}}}

-----------------------------------
MU-MIMO
-----------------------------------

{{{
Additional Context:
MU-MIMO allows simultaneous communication with multiple wireless clients.

Source:
Cisco Wireless Design Guide
https://www.cisco.com/
}}}

-----------------------------------
BEAMFORMING
-----------------------------------

{{{
Additional Context:
Beamforming focuses wireless energy toward clients dynamically.

Source:
Cisco Beamforming Overview
https://www.cisco.com/
}}}

-----------------------------------
AUTONOMOUS ACCESS POINTS
-----------------------------------

The guide discusses:
- autonomous APs

-----------------------------------
AUTONOMOUS AP CHARACTERISTICS
-----------------------------------

Autonomous APs:
- operate independently
- manage their own configuration
- handle local wireless operations

-----------------------------------
AUTONOMOUS AP FUNCTIONS
-----------------------------------

The guide states autonomous APs may manage:
- SSIDs
- security protocols
- DHCP services

-----------------------------------
AUTONOMOUS AP USE CASES
-----------------------------------

Best for:
- small networks
- simple deployments
- remote locations

-----------------------------------
AUTONOMOUS AP ADVANTAGES
-----------------------------------

Advantages:
- simple deployment
- no controller required
- independent operation

-----------------------------------
AUTONOMOUS AP DISADVANTAGES
-----------------------------------

Disadvantages:
- harder to scale
- harder centralized management
- inconsistent large-scale administration

-----------------------------------
LIGHTWEIGHT ACCESS POINTS
-----------------------------------

The guide also discusses:
- lightweight APs

-----------------------------------
LIGHTWEIGHT AP CHARACTERISTICS
-----------------------------------

Lightweight APs:
- depend on centralized controllers
- offload management/control functions
- simplify large deployments

-----------------------------------
WIRELESS LAN CONTROLLER (WLC)
-----------------------------------

WLC =
Wireless LAN Controller

-----------------------------------
WLC PURPOSE
-----------------------------------

WLCs:
- centrally manage APs
- centralize configuration
- centralize security policies
- simplify large WLAN deployments

-----------------------------------
LIGHTWEIGHT AP ADVANTAGES
-----------------------------------

Advantages:
- centralized management
- scalability
- consistent policy enforcement
- simplified administration

-----------------------------------
LIGHTWEIGHT AP DISADVANTAGES
-----------------------------------

Disadvantages:
- controller dependency
- greater infrastructure complexity
- potential controller failure concerns

-----------------------------------
AUTONOMOUS VS LIGHTWEIGHT
-----------------------------------

Autonomous AP:
- standalone
- independently managed

Lightweight AP:
- centrally managed by WLC

-----------------------------------
POWER OVER ETHERNET (PoE)
-----------------------------------

{{{
Additional Context:
Many APs use PoE for both:
- electrical power
and:
- network connectivity

Source:
Cisco PoE Deployment Guide
https://www.cisco.com/
}}}

-----------------------------------
POE BENEFITS
-----------------------------------

PoE helps:
- simplify AP installation
- reduce electrical wiring needs
- improve placement flexibility

-----------------------------------
AP PLACEMENT
-----------------------------------

Proper AP placement affects:
- signal quality
- roaming
- interference
- dead zones

-----------------------------------
POOR AP PLACEMENT
-----------------------------------

Poor AP placement may cause:
- weak signal
- dropped connections
- dead zones
- roaming issues

-----------------------------------
HIGH-DENSITY DEPLOYMENTS
-----------------------------------

High-density deployments include:
- stadiums
- airports
- schools
- offices

-----------------------------------
HIGH-DENSITY CHALLENGES
-----------------------------------

High-density WLANs require:
- careful channel planning
- proper AP placement
- interference management

-----------------------------------
WIRELESS INTERFERENCE
-----------------------------------

Common interference sources:
- neighboring APs
- microwaves
- Bluetooth devices
- overlapping channels

-----------------------------------
DFS
-----------------------------------

DFS =
Dynamic Frequency Selection

-----------------------------------
DFS PURPOSE
-----------------------------------

DFS allows APs to:
- avoid interfering with radar systems

-----------------------------------
TPC
-----------------------------------

TPC =
Transmit Power Control

-----------------------------------
TPC PURPOSE
-----------------------------------

TPC adjusts wireless power levels to:
- reduce interference
- improve RF efficiency

-----------------------------------
AP TROUBLESHOOTING
-----------------------------------

Common AP problems:
- channel overlap
- weak signal
- incorrect security settings
- overloaded APs
- bad placement
- authentication failures

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- AP = wireless bridge to wired LAN
- Infrastructure mode uses APs
- Ad hoc mode does not use APs
- Autonomous APs are standalone
- Lightweight APs use WLCs
- WLCs centralize management
- APs commonly broadcast multiple SSIDs
- 1/6/11 are common non-overlapping 2.4 GHz channels
- PoE commonly powers APs
- Band steering moves clients to better frequency bands

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A wireless device connects to the wired network through a wireless device."

Answer:
Access point

-----------------------------------

Scenario:
"A company wants centralized wireless management."

Answer:
WLC with lightweight APs

-----------------------------------

Scenario:
"A small office wants a simple standalone AP."

Answer:
Autonomous AP

-----------------------------------

Scenario:
"A wireless deployment suffers from overlapping 2.4 GHz interference."

Answer:
Use channels 1, 6, and 11

-----------------------------------

Scenario:
"A wireless network wants seamless roaming across many APs."

Answer:
ESS deployment

-----------------------------------

Scenario:
"A company powers APs through Ethernet cables."

Answer:
PoE

-----------------------------------

Scenario:
"A deployment automatically moves clients from congested 2.4 GHz."

Answer:
Band steering

-----------------------------------

Scenario:
"A wireless deployment uses centralized AP configuration."

Answer:
Wireless LAN Controller

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking APs route traffic like routers.

Wrong.

APs primarily:
- bridge wireless traffic to the LAN

-----------------------------------

Trap:
Thinking lightweight APs operate fully independently.

Wrong.

Lightweight APs:
- depend on WLCs

-----------------------------------

Trap:
Thinking ad hoc networking uses APs.

Wrong.

Ad hoc:
- direct device-to-device communication

-----------------------------------

Trap:
Thinking wider channels are always better.

Wrong.

Wider channels:
- improve throughput
but:
- increase interference risk

-----------------------------------

Trap:
Thinking SSID and BSSID are the same.

Wrong.

SSID:
- network name

BSSID:
- specific AP identifier

-----------------------------------

Trap:
Thinking AP placement is unimportant.

Wrong.

Placement strongly affects:
- coverage
- interference
- roaming
- performance

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

AP =
Wireless bridge

Autonomous AP =
Standalone

Lightweight AP =
Controller-managed

WLC =
Centralized wireless management

Infrastructure mode =
Uses APs

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is an access point?

A:
A device that provides wireless connectivity to a wired network.

-----------------------------------

Q:
What is the main purpose of an AP?

A:
Bridge wireless clients to the wired LAN.

-----------------------------------

Q:
What wireless mode commonly uses APs?

A:
Infrastructure mode.

-----------------------------------

Q:
What wireless mode does NOT require APs?

A:
Ad hoc mode.

-----------------------------------

Q:
What is an autonomous AP?

A:
A standalone independently managed AP.

-----------------------------------

Q:
What is a lightweight AP?

A:
An AP managed by a Wireless LAN Controller.

-----------------------------------

Q:
What does WLC stand for?

A:
Wireless LAN Controller.

-----------------------------------

Q:
What does a WLC do?

A:
Centrally manages wireless APs.

-----------------------------------

Q:
What channels are commonly non-overlapping in 2.4 GHz?

A:
1, 6, and 11.

-----------------------------------

Q:
What does PoE provide to APs?

A:
Power and network connectivity over Ethernet.

-----------------------------------

Q:
What does band steering do?

A:
Moves capable clients to better frequency bands.

-----------------------------------

Q:
What is the difference between autonomous and lightweight APs?

A:
Autonomous APs are standalone; lightweight APs rely on WLCs.