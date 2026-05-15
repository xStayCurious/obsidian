========================
Network Security Groups — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.3: Cloud Concepts and Connectivity Options
Page 10
0

-----------------------------------
NETWORK SECURITY GROUPS (NSGs)
-----------------------------------

Network Security Groups are used to:
- control inbound traffic
- control outbound traffic
to cloud resources within a VPC.

-----------------------------------
CORE PURPOSE
-----------------------------------

NSGs act as:
- a virtual firewall
for cloud resources.

-----------------------------------
WHAT NSGS CONTROL
-----------------------------------

NSGs control traffic based on:
- ports
- protocols
- source IP addresses
- destination IP addresses

-----------------------------------
TRAFFIC FILTERING
-----------------------------------

NSGs can:
- allow traffic
or
- deny traffic

based on configured rules.

-----------------------------------
SIMPLE MENTAL MODEL
-----------------------------------

NSG =
Cloud-based firewall rules for cloud resources.

-----------------------------------
WHERE NSGS ARE USED
-----------------------------------

NSGs are used:
- within a VPC
- to secure cloud resources
- to manage network traffic

-----------------------------------
NSG PURPOSES
-----------------------------------

NSGs help:
- secure cloud environments
- restrict unauthorized access
- enforce network security policies
- manage protocol and port access

-----------------------------------
NSG RULES
-----------------------------------

NSG rules may specify:
- allowed ports
- denied ports
- allowed protocols
- source addresses
- destination addresses

-----------------------------------
PROTOCOL CONTROL
-----------------------------------

NSGs can filter traffic by protocol, such as:
- TCP
- UDP

-----------------------------------
PORT CONTROL
-----------------------------------

NSGs can allow or deny specific ports.

Examples:
- allow HTTPS on port 443
- block Telnet on port 23

-----------------------------------
SOURCE/DESTINATION FILTERING
-----------------------------------

NSGs can restrict traffic based on:
- source IP address
- destination IP address

-----------------------------------
SECURITY BENEFITS
-----------------------------------

NSGs help:
- reduce attack surfaces
- limit unnecessary access
- improve cloud security
- isolate workloads

-----------------------------------
VPC RELATIONSHIP
-----------------------------------

NSGs operate:
- within a Virtual Private Cloud (VPC)

They help secure:
- instances
- workloads
- cloud resources

-----------------------------------
VIRTUAL FIREWALL CONCEPT
-----------------------------------

The guide specifically describes NSGs as:
- acting like a virtual firewall

This means:
- they filter and control traffic
similar to traditional firewalls.

-----------------------------------
GRANULAR CONTROL
-----------------------------------

The guide notes NSGs provide control based on:
- ports
- protocols
- source/destination IPs

{{{
Additional Context:
NSGs are generally considered more granular than subnet-wide filtering because rules can often be applied directly to cloud resources or interfaces instead of only entire subnets.

Source:
Microsoft Azure Documentation
https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview
}}}

-----------------------------------
NSGS VS NETWORK SECURITY LISTS
-----------------------------------

The guide states:

NSGs:
- control inbound/outbound traffic
- act as virtual firewalls

Network Security Lists:
- manage and secure traffic
- provide stateful or stateless filtering
- operate at subnet level

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company wants to restrict inbound cloud traffic to only HTTPS."

Answer:
Use Network Security Group rules.

-----------------------------------

Scenario:
"A company needs a virtual firewall for cloud resources."

Answer:
Network Security Groups.

-----------------------------------

Scenario:
"A company wants to allow only specific protocols and ports."

Answer:
Network Security Groups.

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking NSGs are physical firewalls.

Wrong.

NSGs are:
- virtual cloud security controls.

-----------------------------------

Trap:
Thinking NSGs only filter inbound traffic.

Wrong.

NSGs control:
- inbound
and
- outbound traffic.

-----------------------------------

Trap:
Thinking NSGs are unrelated to VPCs.

Wrong.

NSGs are used:
- within VPC environments.

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

NSG =
Cloud virtual firewall.

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is a Network Security Group?

A:
A virtual firewall used to control inbound and outbound cloud traffic.

-----------------------------------

Q:
What does an NSG control?

A:
Ports, protocols, source IPs, and destination IPs.

-----------------------------------

Q:
Where are NSGs commonly used?

A:
Within a VPC.

-----------------------------------

Q:
What is the main purpose of an NSG?

A:
To secure cloud resources by filtering traffic.

-----------------------------------

Q:
Can NSGs control both inbound and outbound traffic?

A:
Yes.

-----------------------------------

Q:
What do NSGs act like?

A:
A virtual firewall.

-----------------------------------

Q:
What types of filtering can NSGs perform?

A:
Port, protocol, source, and destination filtering.

-----------------------------------

Q:
Why are NSGs important?

A:
They help secure cloud resources and reduce unauthorized access.

-----------------------------------

Q:
What is an example of an NSG rule?

A:
Allow HTTPS traffic on port 443.

-----------------------------------

Q:
What cloud concept are NSGs commonly associated with?

A:
Virtual Private Clouds (VPCs).