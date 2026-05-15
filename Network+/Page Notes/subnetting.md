========================
Subnetting, VLSM, and CIDR
Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.7: IPv4 Addressing
Pages 27–28
0

-----------------------------------
SUBNETTING
-----------------------------------

Subnetting:
- divides a larger network
into:
- smaller subnetworks

-----------------------------------
CORE PURPOSE
-----------------------------------

Subnetting helps:
- improve network organization
- improve efficiency
- reduce broadcast domains
- improve address utilization

-----------------------------------
WHY SUBNETTING MATTERS
-----------------------------------

Subnetting allows organizations to:
- separate departments
- improve performance
- simplify management
- conserve IP addresses

-----------------------------------
SUBNET MASK
-----------------------------------

A subnet mask:
- identifies the network portion
and:
- the host portion
of an IP address

-----------------------------------
COMMON SUBNET MASKS
-----------------------------------

255.0.0.0
255.255.0.0
255.255.255.0

-----------------------------------
CIDR
-----------------------------------

CIDR =
Classless Inter-Domain Routing

-----------------------------------
CIDR PURPOSE
-----------------------------------

CIDR:
- replaces classful addressing
- improves address allocation efficiency
- supports flexible subnetting

-----------------------------------
CIDR NOTATION
-----------------------------------

CIDR uses:
- slash notation

Example:
192.168.1.0/24

-----------------------------------
CIDR PREFIX
-----------------------------------

The number after the slash:
- identifies network bits

Example:
/24 =
24 network bits

-----------------------------------
CIDR BENEFITS
-----------------------------------

CIDR:
- reduces wasted IP addresses
- supports route aggregation
- allows flexible subnet sizes

-----------------------------------
ROUTE AGGREGATION
-----------------------------------

{{{
Additional Context:
Route aggregation (route summarization) combines multiple networks into one summarized route to reduce routing table size.

Source:
Cisco Route Summarization Overview
https://www.cisco.com/
}}}

-----------------------------------
CLASSLESS ADDRESSING
-----------------------------------

CIDR is:
- classless addressing

Meaning:
- subnet sizes are flexible
- not restricted to Class A/B/C boundaries

-----------------------------------
VLSM
-----------------------------------

VLSM =
Variable Length Subnet Masking

-----------------------------------
VLSM PURPOSE
-----------------------------------

VLSM allows:
- different subnet masks
within:
- the same network

-----------------------------------
WHY VLSM EXISTS
-----------------------------------

VLSM improves:
- IP address efficiency
- subnet flexibility

-----------------------------------
VLSM EXAMPLE
-----------------------------------

One subnet may use:
/24

Another may use:
/27

within the same organization.

-----------------------------------
VLSM BENEFITS
-----------------------------------

VLSM helps:
- reduce wasted addresses
- create subnet sizes based on need
- support efficient network design

-----------------------------------
FIXED-LENGTH VS VARIABLE-LENGTH
-----------------------------------

Fixed-length subnetting:
- all subnets same size

VLSM:
- subnets may have different sizes

-----------------------------------
NETWORK BITS AND HOST BITS
-----------------------------------

Subnetting divides addresses into:
- network bits
- host bits

-----------------------------------
MORE NETWORK BITS
-----------------------------------

More network bits:
- create more subnets
- reduce hosts per subnet

-----------------------------------
MORE HOST BITS
-----------------------------------

More host bits:
- allow more hosts
- reduce number of subnets

-----------------------------------
BROADCAST DOMAIN REDUCTION
-----------------------------------

Subnetting reduces:
- broadcast domain size

This can improve:
- performance
- traffic management

-----------------------------------
PRIVATE ADDRESSING AND SUBNETTING
-----------------------------------

Organizations commonly subnet:
- RFC1918 private address ranges

-----------------------------------
COMMON PREFIXES
-----------------------------------

/8
- large network

/16
- medium network

/24
- common LAN subnet

-----------------------------------
SMALLER SUBNETS
-----------------------------------

Larger prefix numbers:
- create smaller subnets

Example:
/27 smaller than /24

-----------------------------------
LARGER SUBNETS
-----------------------------------

Smaller prefix numbers:
- create larger subnets

Example:
/16 larger than /24

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company wants to divide a network into smaller broadcast domains."

Answer:
Subnetting

-----------------------------------

Scenario:
"A company uses flexible subnet sizes to conserve addresses."

Answer:
VLSM

-----------------------------------

Scenario:
"A network uses slash notation like /24."

Answer:
CIDR notation

-----------------------------------

Scenario:
"A company wants classless addressing and route aggregation."

Answer:
CIDR

-----------------------------------

Scenario:
"A company creates subnets of different sizes within the same network."

Answer:
VLSM

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking CIDR and VLSM are identical.

Wrong.

CIDR:
- classless routing/addressing

VLSM:
- different subnet sizes within a network

-----------------------------------

Trap:
Thinking larger prefix numbers mean larger networks.

Wrong.

/30:
- much smaller than /24

-----------------------------------

Trap:
Thinking subnetting increases broadcast traffic.

Wrong.

Subnetting:
- reduces broadcast domains

-----------------------------------

Trap:
Confusing subnet mask and IP address.

Subnet mask:
- identifies network vs host portions

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

CIDR =
Slash notation/classless routing

VLSM =
Different subnet sizes

More network bits =
More subnets

More host bits =
More hosts

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is subnetting?

A:
Dividing a larger network into smaller subnetworks.

-----------------------------------

Q:
What is the purpose of subnetting?

A:
Improve organization, efficiency, and reduce broadcast domains.

-----------------------------------

Q:
What does CIDR stand for?

A:
Classless Inter-Domain Routing.

-----------------------------------

Q:
What does CIDR use?

A:
Slash notation.

-----------------------------------

Q:
What does /24 mean?

A:
24 bits are used for the network portion.

-----------------------------------

Q:
What does VLSM stand for?

A:
Variable Length Subnet Masking.

-----------------------------------

Q:
What is the purpose of VLSM?

A:
Allow different subnet sizes within the same network.

-----------------------------------

Q:
What happens when more bits are allocated to the network portion?

A:
More subnets and fewer hosts per subnet.

-----------------------------------

Q:
What does subnetting reduce?

A:
Broadcast domain size.

-----------------------------------

Q:
Which addressing method replaced classful addressing?

A:
CIDR.

-----------------------------------

Q:
What is route aggregation?

A:
Combining multiple routes into a summarized route.

-----------------------------------

Q:
What is a common subnet for LANs?

A:
/24.