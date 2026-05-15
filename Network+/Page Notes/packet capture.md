========================
Packet Capture
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 3 — Network Operations
Section 3.2: Monitoring and Performance
Pages 57–59
0

-----------------------------------
PACKET CAPTURE
-----------------------------------

Packet capture refers to:
- collecting and analyzing network packets

-----------------------------------
CORE PURPOSE
-----------------------------------

Packet capture helps administrators:
- troubleshoot network problems
- analyze traffic
- investigate security incidents
- inspect protocols
- diagnose performance issues

-----------------------------------
WHY PACKET CAPTURE EXISTS
-----------------------------------

Network traffic problems are often difficult to diagnose using only:
- logs
- alerts
- summaries

Packet captures provide:
- detailed visibility into actual traffic

-----------------------------------
PACKETS
-----------------------------------

A packet is:
- a unit of network data transmitted across a network

-----------------------------------
WHAT PACKET CAPTURE SHOWS
-----------------------------------

Packet captures may reveal:
- source IP addresses
- destination IP addresses
- protocols
- ports
- flags
- payload data
- packet timing
- retransmissions
- errors

-----------------------------------
IMPORTANT DISTINCTION
-----------------------------------

Packet captures analyze:
- full packets

including:
- packet contents/payloads

-----------------------------------
WHY THIS MATTERS
-----------------------------------

Unlike flow data:
- packet captures provide deep inspection capability

-----------------------------------
PACKET CAPTURE USE CASES
-----------------------------------

Common uses:
- troubleshooting latency
- troubleshooting connectivity
- diagnosing packet loss
- analyzing protocols
- detecting malicious traffic
- validating configurations

-----------------------------------
PROTOCOL ANALYSIS
-----------------------------------

Packet captures help analyze:
- TCP
- UDP
- DNS
- DHCP
- HTTP
- HTTPS
- ICMP
- ARP

-----------------------------------
TCP ANALYSIS
-----------------------------------

Packet captures may show:
- SYN packets
- ACK packets
- retransmissions
- resets
- failed handshakes

-----------------------------------
DNS ANALYSIS
-----------------------------------

Packet captures can reveal:
- DNS queries
- DNS responses
- failed lookups
- slow resolutions

-----------------------------------
DHCP ANALYSIS
-----------------------------------

Packet captures can show:
- DHCP Discover
- DHCP Offer
- DHCP Request
- DHCP Acknowledge

-----------------------------------
ICMP ANALYSIS
-----------------------------------

Packet captures can show:
- ping requests/replies
- unreachable messages
- TTL exceeded messages

-----------------------------------
PACKET CAPTURE TOOLS
-----------------------------------

{{{
Additional Context:
Common packet capture tools:
- Wireshark
- tcpdump
- tshark

Source:
Wireshark Documentation
https://www.wireshark.org/
}}}

-----------------------------------
WIRESHARK
-----------------------------------

{{{
Additional Context:
Wireshark is one of the most common graphical packet analysis tools.

Source:
Wireshark Documentation
https://www.wireshark.org/
}}}

-----------------------------------
TCPDUMP
-----------------------------------

{{{
Additional Context:
tcpdump is a common command-line packet capture utility used on Linux/Unix systems.

Source:
tcpdump Documentation
https://www.tcpdump.org/
}}}

-----------------------------------
PROMISCUOUS MODE
-----------------------------------

{{{
Additional Context:
Packet capture interfaces commonly use promiscuous mode to capture all visible traffic.

Source:
Wireshark Capture Concepts
https://www.wireshark.org/
}}}

-----------------------------------
PROMISCUOUS MODE PURPOSE
-----------------------------------

Promiscuous mode allows:
- network interfaces to capture traffic not specifically addressed to themselves

-----------------------------------
SPAN PORTS
-----------------------------------

{{{
Additional Context:
Switches commonly use SPAN/mirror ports for packet capture.

SPAN =
Switched Port Analyzer

Source:
Cisco SPAN Documentation
https://www.cisco.com/
}}}

-----------------------------------
SPAN PORT PURPOSE
-----------------------------------

SPAN ports copy traffic from:
- one/multiple switch ports
to:
- a monitoring device

-----------------------------------
TAPS
-----------------------------------

{{{
Additional Context:
Network TAPs (Test Access Points) passively copy traffic for monitoring/analysis.

Source:
Gigamon TAP Concepts
https://www.gigamon.com/
}}}

-----------------------------------
FILTERING
-----------------------------------

Packet capture tools commonly support:
- filters

-----------------------------------
FILTER PURPOSE
-----------------------------------

Filters help:
- isolate relevant traffic
- reduce noise
- simplify troubleshooting

-----------------------------------
FILTER EXAMPLES
-----------------------------------

Examples:
- only TCP traffic
- only DNS traffic
- traffic from one IP
- traffic on one port

-----------------------------------
PAYLOAD INSPECTION
-----------------------------------

Packet captures may inspect:
- packet payloads

-----------------------------------
PAYLOAD RISKS
-----------------------------------

Payload inspection may expose:
- usernames
- passwords
- sensitive data

especially if:
- traffic is unencrypted

-----------------------------------
ENCRYPTED TRAFFIC
-----------------------------------

Encrypted traffic limits visibility into:
- payload contents

-----------------------------------
HTTPS TRAFFIC
-----------------------------------

HTTPS packet captures still reveal:
- source/destination IPs
- ports
- metadata

But:
- payload contents remain encrypted

-----------------------------------
PERFORMANCE TROUBLESHOOTING
-----------------------------------

Packet captures help identify:
- latency
- retransmissions
- packet loss
- congestion
- malformed packets

-----------------------------------
SECURITY INVESTIGATIONS
-----------------------------------

Packet captures help investigate:
- malware traffic
- suspicious communication
- unauthorized access
- attacks
- data exfiltration

-----------------------------------
MALWARE ANALYSIS
-----------------------------------

{{{
Additional Context:
Security analysts commonly use packet captures to identify:
- command-and-control traffic
- suspicious outbound connections

Source:
SANS Packet Analysis Concepts
https://www.sans.org/
}}}

-----------------------------------
FLOW DATA VS PACKET CAPTURE
-----------------------------------

Flow data:
- summarized metadata

Packet capture:
- full detailed packet analysis

-----------------------------------
SNMP VS PACKET CAPTURE
-----------------------------------

SNMP:
- device monitoring

Packet capture:
- deep traffic inspection

-----------------------------------
NETFLOW VS PACKET CAPTURE
-----------------------------------

NetFlow:
- traffic summaries

Packet capture:
- full packet details

-----------------------------------
PCAP FILES
-----------------------------------

{{{
Additional Context:
Packet captures are commonly stored as:
- .pcap
or:
- .pcapng files

Source:
Wireshark File Format Documentation
https://www.wireshark.org/
}}}

-----------------------------------
RETENTION CONSIDERATIONS
-----------------------------------

Packet captures may require:
- large storage capacity

because:
- full packet data is resource-intensive

-----------------------------------
LEGAL/PRIVACY CONSIDERATIONS
-----------------------------------

{{{
Additional Context:
Packet captures may contain sensitive or regulated information and require proper authorization/handling.

Source:
NIST Network Monitoring Guidance
https://csrc.nist.gov/
}}}

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Packet capture analyzes full packets
- Packet captures include payload data
- Wireshark is a common packet analyzer
- Packet captures help troubleshoot protocols
- Promiscuous mode captures additional traffic
- SPAN ports mirror traffic for analysis
- Packet capture provides deeper visibility than flow data
- Encrypted traffic limits payload visibility

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A network engineer needs full packet visibility for troubleshooting."

Answer:
Packet capture

-----------------------------------

Scenario:
"A technician analyzes DNS queries and responses directly."

Answer:
Packet capture

-----------------------------------

Scenario:
"A switch mirrors traffic to a monitoring interface."

Answer:
SPAN port

-----------------------------------

Scenario:
"A network card captures traffic not addressed to itself."

Answer:
Promiscuous mode

-----------------------------------

Scenario:
"A company wants summarized traffic metadata with low overhead."

Answer:
Flow monitoring, not packet capture

-----------------------------------

Scenario:
"A security analyst investigates suspicious outbound traffic."

Answer:
Packet capture analysis

-----------------------------------

Scenario:
"A company uses Wireshark for troubleshooting."

Answer:
Packet capture/protocol analysis

-----------------------------------

Scenario:
"A network engineer wants to inspect TCP retransmissions."

Answer:
Packet capture

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking packet captures only show summaries.

Wrong.

Packet captures:
- analyze full packets

-----------------------------------

Trap:
Thinking encrypted traffic reveals readable payloads.

Wrong.

Encryption limits payload visibility.

-----------------------------------

Trap:
Thinking NetFlow and packet capture are identical.

Wrong.

NetFlow:
- summarized metadata

Packet capture:
- complete packet details

-----------------------------------

Trap:
Thinking SNMP performs packet inspection.

Wrong.

SNMP:
- monitors devices
It does not deeply inspect packets.

-----------------------------------

Trap:
Thinking SPAN ports route traffic.

Wrong.

SPAN ports:
- mirror/copy traffic for monitoring

-----------------------------------

Trap:
Thinking promiscuous mode means hacking.

Wrong.

Promiscuous mode is commonly used for:
- legitimate monitoring/troubleshooting

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Packet capture =
Full packet visibility

Wireshark =
Packet analyzer

SPAN =
Traffic mirroring

Promiscuous mode =
Capture all visible traffic

NetFlow =
Traffic summaries

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is packet capture?

A:
Collecting and analyzing network packets.

-----------------------------------

Q:
What does packet capture reveal?

A:
Protocols, IPs, ports, payloads, and packet details.

-----------------------------------

Q:
What is a common packet capture tool?

A:
Wireshark.

-----------------------------------

Q:
What is promiscuous mode?

A:
Capturing traffic not specifically addressed to the interface.

-----------------------------------

Q:
What is a SPAN port?

A:
A switch port that mirrors traffic for monitoring.

-----------------------------------

Q:
What is the difference between packet capture and flow data?

A:
Packet capture analyzes full packets; flow data summarizes metadata.

-----------------------------------

Q:
Why is packet capture useful?

A:
It provides deep visibility for troubleshooting and security analysis.

-----------------------------------

Q:
What limits visibility into packet payloads?

A:
Encryption.

-----------------------------------

Q:
What type of traffic details can packet captures show?

A:
TCP handshakes, DNS queries, retransmissions, and errors.

-----------------------------------

Q:
What file extension is commonly used for packet captures?

A:
.pcap or .pcapng.