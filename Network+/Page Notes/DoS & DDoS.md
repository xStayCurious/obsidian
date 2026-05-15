========================
DoS and DDoS
Denial-of-Service Attacks
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.2: Common Attacks
Pages 66–68


-----------------------------------
DoS
-----------------------------------

DoS =
Denial-of-Service

-----------------------------------
DDoS
-----------------------------------

DDoS =
Distributed Denial-of-Service

-----------------------------------
CORE PURPOSE
-----------------------------------

DoS/DDoS attacks attempt to:
- overwhelm systems/services
- disrupt operations
- prevent legitimate access

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

DoS/DDoS attacks primarily target:
- availability

-----------------------------------
CIA TRIAD
-----------------------------------

Availability is part of:
- CIA triad

-----------------------------------
CIA TRIAD
-----------------------------------

CIA =
- Confidentiality
- Integrity
- Availability

-----------------------------------
AVAILABILITY
-----------------------------------

Availability ensures:
- systems/services remain accessible

-----------------------------------
WHY DoS ATTACKS EXIST
-----------------------------------

Attackers may attempt to:
- disrupt businesses
- extort organizations
- damage reputation
- distract defenders

-----------------------------------
DoS
-----------------------------------

A DoS attack generally originates from:
- a single source/system

-----------------------------------
DDoS
-----------------------------------

A DDoS attack originates from:
- many distributed systems simultaneously

-----------------------------------
IMPORTANT EXAM DIFFERENCE
-----------------------------------

DoS:
- single attacking source

DDoS:
- multiple distributed attacking sources

-----------------------------------
BOTNETS
-----------------------------------

DDoS attacks commonly use:
- botnets

-----------------------------------
BOTNET
-----------------------------------

A botnet is:
- a network of compromised devices

-----------------------------------
COMMON BOTNET DEVICES
-----------------------------------

Examples:
- infected PCs
- IoT devices
- servers
- routers

-----------------------------------
IoT RISKS
-----------------------------------

{{{
Additional Context:
Weakly secured IoT devices are commonly recruited into botnets.

Source:
CISA IoT Security Guidance
https://www.cisa.gov/
}}}

-----------------------------------
TRAFFIC FLOODING
-----------------------------------

DoS/DDoS attacks commonly overwhelm:
- bandwidth
- servers
- applications
- network devices

-----------------------------------
RESOURCE EXHAUSTION
-----------------------------------

Attackers attempt to exhaust:
- CPU
- memory
- sessions
- bandwidth
- processing resources

-----------------------------------
COMMON TARGETS
-----------------------------------

Examples:
- websites
- DNS servers
- gaming platforms
- APIs
- cloud services

-----------------------------------
SERVICE OUTAGES
-----------------------------------

Successful attacks may cause:
- downtime
- slow performance
- inaccessible services

-----------------------------------
COMMON ATTACK TYPES
-----------------------------------

Examples:
- SYN flood
- UDP flood
- ICMP flood
- amplification attacks

-----------------------------------
SYN FLOOD
-----------------------------------

{{{
Additional Context:
SYN floods abuse TCP connection establishment to exhaust server resources.

Source:
Cloudflare Learning Center
https://www.cloudflare.com/
}}}

-----------------------------------
TCP THREE-WAY HANDSHAKE
-----------------------------------

{{{
Additional Context:
TCP uses:
- SYN
- SYN-ACK
- ACK

for connection establishment.

Source:
RFC 793 TCP Specification
https://datatracker.ietf.org/
}}}

-----------------------------------
UDP FLOOD
-----------------------------------

UDP floods overwhelm targets using:
- large volumes of UDP traffic

-----------------------------------
ICMP FLOOD
-----------------------------------

ICMP floods commonly use:
- excessive ping traffic

-----------------------------------
AMPLIFICATION ATTACKS
-----------------------------------

Amplification attacks leverage:
- intermediary services to magnify traffic volume

-----------------------------------
DNS AMPLIFICATION
-----------------------------------

{{{
Additional Context:
DNS amplification abuses open DNS resolvers to amplify traffic.

Source:
CISA DDoS Guidance
https://www.cisa.gov/
}}}

-----------------------------------
NTP AMPLIFICATION
-----------------------------------

{{{
Additional Context:
Misconfigured NTP servers may also be abused for amplification attacks.

Source:
US-CERT DDoS Guidance
https://www.cisa.gov/
}}}

-----------------------------------
REFLECTION ATTACKS
-----------------------------------

Reflection attacks spoof:
- victim source addresses

-----------------------------------
SPOOFING
-----------------------------------

Spoofing falsifies:
- source information

-----------------------------------
APPLICATION-LAYER ATTACKS
-----------------------------------

Some DDoS attacks target:
- applications/services directly

-----------------------------------
LAYER 7 ATTACKS
-----------------------------------

{{{
Additional Context:
Layer 7 attacks target application-layer resources such as HTTP services.

Source:
Cloudflare DDoS Learning Center
https://www.cloudflare.com/
}}}

-----------------------------------
VOLUMETRIC ATTACKS
-----------------------------------

Volumetric attacks focus on:
- consuming bandwidth

-----------------------------------
ASYMMETRIC ATTACKS
-----------------------------------

{{{
Additional Context:
Some attacks send small requests that force large responses/workloads.

Source:
Cloudflare Security Documentation
https://www.cloudflare.com/
}}}

-----------------------------------
DDoS DETECTION
-----------------------------------

Indicators may include:
- unusual traffic spikes
- degraded performance
- service outages

-----------------------------------
MONITORING
-----------------------------------

Detection commonly uses:
- IDS/IPS
- flow analysis
- SIEM
- monitoring tools

-----------------------------------
FLOW DATA
-----------------------------------

Flow analysis may help identify:
- abnormal traffic patterns

-----------------------------------
PACKET CAPTURE
-----------------------------------

Packet captures may help:
- investigate attacks

-----------------------------------
MITIGATION
-----------------------------------

Common mitigation methods:
- rate limiting
- firewalls
- IPS
- load balancing
- DDoS protection services

-----------------------------------
RATE LIMITING
-----------------------------------

Rate limiting restricts:
- traffic/request volume

-----------------------------------
LOAD BALANCING
-----------------------------------

Load balancing distributes:
- traffic across multiple systems

-----------------------------------
REDUNDANCY
-----------------------------------

Redundancy may improve:
- availability during attacks

-----------------------------------
CDNs
-----------------------------------

{{{
Additional Context:
CDNs =
Content Delivery Networks

CDNs commonly help absorb/distribute DDoS traffic.

Source:
Cloudflare CDN Concepts
https://www.cloudflare.com/
}}}

-----------------------------------
BLACKHOLING
-----------------------------------

{{{
Additional Context:
Blackholing drops malicious traffic by routing it to a null destination.

Source:
Cisco DDoS Mitigation Documentation
https://www.cisco.com/
}}}

-----------------------------------
SCRUBBING
-----------------------------------

{{{
Additional Context:
Traffic scrubbing filters malicious traffic before forwarding legitimate traffic.

Source:
Cloudflare DDoS Protection Concepts
https://www.cloudflare.com/
}}}

-----------------------------------
UPSTREAM PROVIDERS
-----------------------------------

Large DDoS mitigation may require:
- ISP/provider assistance

-----------------------------------
INCIDENT RESPONSE
-----------------------------------

Organizations commonly develop:
- DDoS response plans

-----------------------------------
BUSINESS IMPACT
-----------------------------------

DoS/DDoS attacks may cause:
- lost revenue
- downtime
- customer dissatisfaction
- operational disruption

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- DoS = single-source denial attack
- DDoS = distributed denial attack
- DDoS commonly uses botnets
- DoS/DDoS target availability
- SYN floods abuse TCP handshakes
- Amplification attacks magnify traffic
- IoT devices are common botnet members
- Mitigations include rate limiting/load balancing
- Monitoring helps detect unusual traffic spikes

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A website becomes unreachable due to massive distributed traffic."

Answer:
DDoS attack

-----------------------------------

Scenario:
"A single system overwhelms a server with requests."

Answer:
DoS attack

-----------------------------------

Scenario:
"Compromised IoT devices participate in coordinated attacks."

Answer:
Botnet/DDoS

-----------------------------------

Scenario:
"An attacker abuses TCP connection establishment."

Answer:
SYN flood

-----------------------------------

Scenario:
"A company uses multiple servers to absorb attack traffic."

Answer:
Load balancing/DDoS mitigation

-----------------------------------

Scenario:
"Attack traffic is magnified using open DNS servers."

Answer:
DNS amplification attack

-----------------------------------

Scenario:
"A security analyst notices huge traffic spikes and outages."

Answer:
Possible DDoS activity

-----------------------------------

Scenario:
"An attack primarily affects system accessibility."

Answer:
Availability attack/DoS

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing DoS and DDoS.

DoS:
- one source

DDoS:
- many distributed sources

-----------------------------------

Trap:
Thinking DDoS attacks primarily steal data.

Wrong.

DDoS primarily affects:
- availability

-----------------------------------

Trap:
Thinking botnets only contain PCs.

Wrong.

Botnets commonly include:
- IoT devices
- routers
- servers

-----------------------------------

Trap:
Confusing SYN flood with generic bandwidth flooding.

SYN flood:
- abuses TCP handshake resources

-----------------------------------

Trap:
Thinking firewalls alone stop all DDoS attacks.

Wrong.

Large attacks may require:
- specialized mitigation
- provider assistance

-----------------------------------

Trap:
Thinking all DDoS attacks are volumetric.

Wrong.

Some attacks target:
- applications/services (Layer 7)

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

DoS =
Single attacker

DDoS =
Many attackers

Botnet =
Compromised devices

Availability =
Primary target

SYN flood =
TCP handshake abuse

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does DoS stand for?

A:
Denial-of-Service.

-----------------------------------

Q:
What does DDoS stand for?

A:
Distributed Denial-of-Service.

-----------------------------------

Q:
What is the main difference between DoS and DDoS?

A:
DoS uses one source; DDoS uses many distributed sources.

-----------------------------------

Q:
What CIA triad component do DoS/DDoS attacks primarily target?

A:
Availability.

-----------------------------------

Q:
What is a botnet?

A:
A network of compromised devices used for attacks.

-----------------------------------

Q:
What does a SYN flood attack abuse?

A:
TCP connection establishment/handshake resources.

-----------------------------------

Q:
What is an amplification attack?

A:
An attack that magnifies traffic volume using intermediary systems.

-----------------------------------

Q:
What are common DDoS mitigation methods?

A:
Rate limiting, load balancing, filtering, and DDoS protection services.

-----------------------------------

Q:
Why are IoT devices commonly involved in botnets?

A:
They often have weak security/default credentials.

-----------------------------------

Q:
What may indicate a DDoS attack?

A:
Large traffic spikes and service outages.