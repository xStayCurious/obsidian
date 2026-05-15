========================
FHRP — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Page 29
0

-----------------------------------
FHRP
-----------------------------------

FHRP =
First Hop Redundancy Protocol

-----------------------------------
CORE PURPOSE
-----------------------------------

FHRPs provide:
- default gateway redundancy

-----------------------------------
WHY FHRP EXISTS
-----------------------------------

Without FHRP:
- failure of a default gateway router
can:
- interrupt network connectivity

-----------------------------------
DEFAULT GATEWAY
-----------------------------------

The default gateway:
- is the router used by hosts
to reach:
- external networks

-----------------------------------
FHRP GOAL
-----------------------------------

FHRPs ensure:
- continuous gateway availability
if:
- a router fails

-----------------------------------
HOW FHRP WORKS
-----------------------------------

Multiple routers:
- cooperate
to present:
- one virtual default gateway

-----------------------------------
VIRTUAL IP ADDRESS
-----------------------------------

Hosts use:
- a virtual IP address
as:
- their default gateway

-----------------------------------
ACTIVE AND STANDBY ROUTERS
-----------------------------------

Typically:
- one router is active
- another router is standby

-----------------------------------
FAILOVER
-----------------------------------

If the active router fails:
- the standby router takes over

-----------------------------------
REDUNDANCY
-----------------------------------

FHRPs improve:
- network reliability
- availability
- fault tolerance

-----------------------------------
HSRP
-----------------------------------

HSRP =
Hot Standby Router Protocol

-----------------------------------
HSRP CHARACTERISTICS
-----------------------------------

- Cisco proprietary
- Provides gateway redundancy
- Uses active/standby routers

-----------------------------------
HSRP OPERATION
-----------------------------------

One router:
- actively forwards traffic

Another router:
- waits as standby

-----------------------------------
VRRP
-----------------------------------

VRRP =
Virtual Router Redundancy Protocol

-----------------------------------
VRRP CHARACTERISTICS
-----------------------------------

- Open standard
- Similar purpose to HSRP
- Provides gateway redundancy

-----------------------------------
VRRP BENEFIT
-----------------------------------

VRRP supports:
- multi-vendor interoperability

-----------------------------------
GLBP
-----------------------------------

GLBP =
Gateway Load Balancing Protocol

-----------------------------------
GLBP CHARACTERISTICS
-----------------------------------

- Cisco proprietary
- Provides redundancy
- Provides load balancing

-----------------------------------
GLBP BENEFITS
-----------------------------------

GLBP:
- distributes traffic across multiple routers
while:
- maintaining redundancy

-----------------------------------
LOAD BALANCING
-----------------------------------

GLBP supports:
- load balancing between gateways

-----------------------------------
VIRTUAL GATEWAY CONCEPT
-----------------------------------

FHRPs create:
- a virtual gateway
shared by:
- multiple routers

-----------------------------------
TRANSPARENCY TO HOSTS
-----------------------------------

Hosts are generally unaware:
- which physical router is active

Hosts communicate with:
- the virtual gateway

-----------------------------------
HIGH AVAILABILITY
-----------------------------------

FHRPs support:
- high availability networking

-----------------------------------
SINGLE POINT OF FAILURE
-----------------------------------

FHRPs help eliminate:
- default gateway single points of failure

-----------------------------------
FAILOVER BENEFIT
-----------------------------------

If one router fails:
- connectivity can continue automatically

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A network requires default gateway redundancy."

Answer:
FHRP

-----------------------------------

Scenario:
"A standby router automatically takes over after gateway failure."

Answer:
HSRP or VRRP

-----------------------------------

Scenario:
"A company wants gateway redundancy across multiple vendors."

Answer:
VRRP

-----------------------------------

Scenario:
"A protocol provides gateway redundancy and load balancing."

Answer:
GLBP

-----------------------------------

Scenario:
"A network uses a virtual default gateway shared between routers."

Answer:
FHRP

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking FHRP replaces routing protocols.

Wrong.

FHRP:
- provides gateway redundancy
not:
- route learning

-----------------------------------

Trap:
Confusing HSRP and VRRP.

HSRP:
- Cisco proprietary

VRRP:
- open standard

-----------------------------------

Trap:
Thinking GLBP only provides failover.

Wrong.

GLBP provides:
- failover
and:
- load balancing

-----------------------------------

Trap:
Thinking hosts communicate directly with multiple gateways.

Wrong.

Hosts typically use:
- one virtual gateway address

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

FHRP =
Gateway redundancy

HSRP =
Hot standby

VRRP =
Vendor-neutral redundancy

GLBP =
Gateway load balancing

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does FHRP stand for?

A:
First Hop Redundancy Protocol.

-----------------------------------

Q:
What is the purpose of FHRP?

A:
Provide default gateway redundancy.

-----------------------------------

Q:
What problem does FHRP solve?

A:
Default gateway single point of failure.

-----------------------------------

Q:
What do hosts use in an FHRP environment?

A:
A virtual default gateway IP address.

-----------------------------------

Q:
What does HSRP stand for?

A:
Hot Standby Router Protocol.

-----------------------------------

Q:
Is HSRP proprietary or open standard?

A:
Cisco proprietary.

-----------------------------------

Q:
What does VRRP stand for?

A:
Virtual Router Redundancy Protocol.

-----------------------------------

Q:
Is VRRP proprietary or open standard?

A:
Open standard.

-----------------------------------

Q:
What does GLBP provide in addition to redundancy?

A:
Load balancing.

-----------------------------------

Q:
What happens if the active gateway router fails in an FHRP setup?

A:
A standby router takes over automatically.