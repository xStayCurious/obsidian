========================
Static vs Dynamic Routing
Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Pages 28–29
0

-----------------------------------
ROUTING
-----------------------------------

Routing:
- determines the path traffic takes
between:
- networks

Routers use:
- routing tables
to:
- forward packets

-----------------------------------
STATIC ROUTING
-----------------------------------

Static routing:
- manually configured routes
created by:
- network administrators

-----------------------------------
STATIC ROUTE CHARACTERISTICS
-----------------------------------

- Manually configured
- Fixed paths
- No automatic updates
- Low overhead

-----------------------------------
STATIC ROUTE BENEFITS
-----------------------------------

- Simplicity
- Predictable routing
- Low resource usage
- Increased control

-----------------------------------
STATIC ROUTE DISADVANTAGES
-----------------------------------

- Manual management required
- Poor scalability
- No automatic adaptation to failures

-----------------------------------
STATIC ROUTE USE CASES
-----------------------------------

Used in:
- small networks
- simple topologies
- stub networks

-----------------------------------
STUB NETWORK
-----------------------------------

{{{
Additional Context:
A stub network is a network with only one path to external networks.

Source:
Cisco Networking Academy
https://www.netacad.com/
}}}

-----------------------------------
STATIC ROUTE FAILURE BEHAVIOR
-----------------------------------

If a link fails:
- static routes do not automatically adjust

Administrator intervention may be required.

-----------------------------------
DYNAMIC ROUTING
-----------------------------------

Dynamic routing:
- automatically learns routes
using:
- routing protocols

-----------------------------------
DYNAMIC ROUTE CHARACTERISTICS
-----------------------------------

- Automatic route discovery
- Automatic route updates
- Adaptive path selection
- Better scalability

-----------------------------------
DYNAMIC ROUTING BENEFITS
-----------------------------------

- Automatically adapts to changes
- Better for large networks
- Reduces manual configuration

-----------------------------------
DYNAMIC ROUTING DISADVANTAGES
-----------------------------------

- More resource usage
- Greater complexity
- Routing protocol overhead

-----------------------------------
ROUTING PROTOCOLS
-----------------------------------

Dynamic routing uses:
- routing protocols

-----------------------------------
COMMON DYNAMIC ROUTING PROTOCOLS
-----------------------------------

The guide lists:
- RIP
- OSPF
- BGP

-----------------------------------
RIP
-----------------------------------

RIP =
Routing Information Protocol

-----------------------------------
RIP CHARACTERISTICS
-----------------------------------

- Distance-vector routing protocol
- Uses hop count
- Simple configuration

-----------------------------------
RIP METRIC
-----------------------------------

RIP uses:
- hop count

to determine:
- best route

-----------------------------------
RIP LIMITATION
-----------------------------------

Maximum hop count:
- 15 hops

-----------------------------------
RIP DISADVANTAGES
-----------------------------------

- Slow convergence
- Limited scalability

-----------------------------------
CONVERGENCE
-----------------------------------

Convergence:
- process of routers updating and agreeing on routing information

-----------------------------------
OSPF
-----------------------------------

OSPF =
Open Shortest Path First

-----------------------------------
OSPF CHARACTERISTICS
-----------------------------------

- Link-state routing protocol
- Faster convergence
- Scalable
- Efficient routing

-----------------------------------
OSPF BENEFITS
-----------------------------------

- Better performance than RIP
- Supports large enterprise networks
- Faster adaptation to changes

-----------------------------------
OSPF METRIC
-----------------------------------

{{{
Additional Context:
OSPF uses "cost" as its routing metric, commonly based on bandwidth.

Source:
Cisco OSPF Overview
https://www.cisco.com/
}}}

-----------------------------------
BGP
-----------------------------------

BGP =
Border Gateway Protocol

-----------------------------------
BGP PURPOSE
-----------------------------------

BGP is used:
- between autonomous systems
- on the internet

-----------------------------------
AUTONOMOUS SYSTEM (AS)
-----------------------------------

{{{
Additional Context:
An autonomous system is a network or group of networks under a single administrative control.

Source:
Cloudflare Learning Center
https://www.cloudflare.com/learning/
}}}

-----------------------------------
BGP CHARACTERISTICS
-----------------------------------

- Path-vector routing protocol
- Internet-scale routing
- Policy-based routing

-----------------------------------
BGP USE CASES
-----------------------------------

Used by:
- ISPs
- large organizations
- internet backbone networks

-----------------------------------
DISTANCE-VECTOR VS LINK-STATE
-----------------------------------

RIP:
- distance-vector

OSPF:
- link-state

-----------------------------------
DISTANCE-VECTOR CHARACTERISTICS
-----------------------------------

Distance-vector protocols:
- share routing information with neighbors
- simpler design
- slower convergence

-----------------------------------
LINK-STATE CHARACTERISTICS
-----------------------------------

Link-state protocols:
- build a topology map
- converge faster
- scale better

-----------------------------------
ROUTING TABLES
-----------------------------------

Routers maintain:
- routing tables

These tables determine:
- where packets are forwarded

-----------------------------------
DEFAULT ROUTE
-----------------------------------

{{{
Additional Context:
A default route is used when no specific route exists for a destination network.

Source:
Cisco Networking Academy
https://www.netacad.com/
}}}

-----------------------------------
STATIC VS DYNAMIC COMPARISON
-----------------------------------

Static Routing:
- manual
- predictable
- low overhead
- poor scalability

Dynamic Routing:
- automatic
- adaptive
- scalable
- higher overhead

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A small network needs simple predictable routing with minimal overhead."

Answer:
Static routing

-----------------------------------

Scenario:
"A large enterprise network needs automatic route adaptation."

Answer:
Dynamic routing

-----------------------------------

Scenario:
"A routing protocol uses hop count."

Answer:
RIP

-----------------------------------

Scenario:
"A routing protocol is commonly used inside large enterprise networks."

Answer:
OSPF

-----------------------------------

Scenario:
"A routing protocol is used between ISPs on the internet."

Answer:
BGP

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking static routing automatically adapts to failures.

Wrong.

Static routes:
- require manual changes

-----------------------------------

Trap:
Confusing RIP and OSPF.

RIP:
- distance-vector
- hop count

OSPF:
- link-state
- faster convergence

-----------------------------------

Trap:
Thinking BGP is typically used for small LANs.

Wrong.

BGP:
- internet-scale routing

-----------------------------------

Trap:
Thinking dynamic routing has no overhead.

Wrong.

Dynamic routing:
- consumes bandwidth and processing resources

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Static =
Manual routes

Dynamic =
Automatic routes

RIP =
Hop count

OSPF =
Fast enterprise routing

BGP =
Internet routing

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is routing?

A:
The process of determining packet paths between networks.

-----------------------------------

Q:
What is static routing?

A:
Manually configured routing.

-----------------------------------

Q:
What is dynamic routing?

A:
Routing that automatically learns and updates routes.

-----------------------------------

Q:
What routing protocol uses hop count?

A:
RIP.

-----------------------------------

Q:
What type of routing protocol is RIP?

A:
Distance-vector.

-----------------------------------

Q:
What type of routing protocol is OSPF?

A:
Link-state.

-----------------------------------

Q:
What routing protocol is commonly used on the internet?

A:
BGP.

-----------------------------------

Q:
What is convergence?

A:
Routers updating and agreeing on routing information.

-----------------------------------

Q:
What is a major advantage of dynamic routing?

A:
Automatic adaptation to network changes.

-----------------------------------

Q:
What is a major advantage of static routing?

A:
Low overhead and predictable routing.