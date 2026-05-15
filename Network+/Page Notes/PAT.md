========================
PAT — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Page 29
0

-----------------------------------
PAT
-----------------------------------

PAT =
Port Address Translation

Also called:
- NAT overload

-----------------------------------
CORE PURPOSE
-----------------------------------

PAT allows:
- multiple private devices
to share:
- a single public IP address

-----------------------------------
WHY PAT EXISTS
-----------------------------------

PAT helps:
- conserve public IPv4 addresses
- support internet access for many devices
- reduce public IP usage

-----------------------------------
HOW PAT WORKS
-----------------------------------

PAT translates:
- private IP addresses
and:
- port numbers

into:
- one public IP address
with unique ports

-----------------------------------
PORT DIFFERENTIATION
-----------------------------------

PAT uses:
- port numbers

to keep track of:
- multiple simultaneous sessions

-----------------------------------
SIMPLE MENTAL MODEL
-----------------------------------

Many internal devices:
- share one public IP

PAT keeps sessions separate using:
- unique port numbers

-----------------------------------
PAT PROCESS
-----------------------------------

Example:

Internal device:
192.168.1.10:5000

May become:
203.0.113.5:30001

-----------------------------------

Another device:
192.168.1.11:5000

May become:
203.0.113.5:30002

-----------------------------------
PUBLIC IP SHARING
-----------------------------------

PAT allows:
- many internal hosts
to appear externally as:
- one public address

-----------------------------------
PAT BENEFITS
-----------------------------------

- Conserves IPv4 addresses
- Supports many users
- Common in home/enterprise networks
- Efficient internet access

-----------------------------------
PAT AND HOME NETWORKS
-----------------------------------

Home routers commonly use:
- PAT/NAT overload

to allow:
- multiple home devices
to share:
- one ISP-assigned public IP

-----------------------------------
PAT VS STATIC NAT
-----------------------------------

PAT:
- many-to-one translation

Static NAT:
- one-to-one translation

-----------------------------------
PAT VS DYNAMIC NAT
-----------------------------------

PAT:
- one public IP shared by many devices

Dynamic NAT:
- uses a pool of public IP addresses

-----------------------------------
PAT AND PORTS
-----------------------------------

PAT relies heavily on:
- TCP/UDP port numbers

-----------------------------------
TCP/UDP PORTS
-----------------------------------

Ports help:
- identify sessions
- separate traffic streams
- direct traffic properly

-----------------------------------
NAT TABLE
-----------------------------------

{{{
Additional Context:
PAT devices maintain translation tables that map internal IP addresses and ports to external IP addresses and ports.

Source:
Cisco NAT Overview
https://www.cisco.com/
}}}

-----------------------------------
RETURN TRAFFIC
-----------------------------------

When return traffic arrives:
- PAT uses the port mapping table
to determine:
- which internal device should receive the traffic

-----------------------------------
PAT LIMITATIONS
-----------------------------------

PAT:
- does not encrypt traffic
- does not replace firewalls
- depends on available ports

-----------------------------------
PAT AND SECURITY
-----------------------------------

PAT provides:
- some obscurity of internal IP addresses

However:
- PAT itself is not a security solution

-----------------------------------
MOST COMMON NAT IMPLEMENTATION
-----------------------------------

{{{
Additional Context:
PAT (NAT overload) is the most common NAT implementation in modern networks.

Source:
Cisco NAT Overview
https://www.cisco.com/
}}}

-----------------------------------
PAT USE CASES
-----------------------------------

Used in:
- home routers
- enterprise edge routers
- internet access gateways

-----------------------------------
IPV4 RELATIONSHIP
-----------------------------------

PAT became critical because:
- IPv4 address space is limited

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A home router allows many devices to share one public IP."

Answer:
PAT

-----------------------------------

Scenario:
"A router distinguishes sessions using port numbers."

Answer:
PAT

-----------------------------------

Scenario:
"A company wants to conserve public IPv4 addresses while supporting many internal hosts."

Answer:
PAT

-----------------------------------

Scenario:
"Many internal devices appear externally as one public IP."

Answer:
PAT

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking PAT and NAT are unrelated.

Wrong.

PAT:
- is a type of NAT

-----------------------------------

Trap:
Thinking PAT uses multiple public IPs by default.

Wrong.

PAT commonly uses:
- one shared public IP

-----------------------------------

Trap:
Thinking PAT provides encryption.

Wrong.

PAT:
- only performs address/port translation

-----------------------------------

Trap:
Confusing PAT and static NAT.

PAT:
- many-to-one

Static NAT:
- one-to-one

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

PAT =
Many devices
One public IP
Different ports

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does PAT stand for?

A:
Port Address Translation.

-----------------------------------

Q:
What is another name for PAT?

A:
NAT overload.

-----------------------------------

Q:
What is the purpose of PAT?

A:
Allow many private devices to share one public IP address.

-----------------------------------

Q:
How does PAT differentiate sessions?

A:
Using port numbers.

-----------------------------------

Q:
What type of NAT is PAT?

A:
Many-to-one NAT.

-----------------------------------

Q:
Why is PAT important?

A:
It conserves public IPv4 addresses.

-----------------------------------

Q:
What device commonly performs PAT?

A:
Routers.

-----------------------------------

Q:
Does PAT encrypt traffic?

A:
No.

-----------------------------------

Q:
What is the difference between PAT and static NAT?

A:
PAT is many-to-one; static NAT is one-to-one.

-----------------------------------

Q:
What common network device uses PAT?

A:
Home internet routers.