========================
Route Selection
Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.8: Routing Technologies
Pages 28–29
0

-----------------------------------
ROUTE SELECTION
-----------------------------------

Route selection is:
- the process routers use
to determine:
- the best path for forwarding packets

-----------------------------------
CORE PURPOSE
-----------------------------------

Routers must determine:
- which route to use
when:
- multiple routes exist

-----------------------------------
ROUTING TABLE
-----------------------------------

Routers use:
- routing tables

to:
- store route information
- determine forwarding decisions

-----------------------------------
BEST PATH SELECTION
-----------------------------------

Routers select:
- the best available route
based on:
- routing information
- metrics
- administrative distance

-----------------------------------
METRICS
-----------------------------------

Metrics are:
- values used to evaluate routes

-----------------------------------
METRIC PURPOSE
-----------------------------------

Metrics help routers determine:
- preferred paths

-----------------------------------
COMMON METRICS
-----------------------------------

The guide references:
- hop count

{{{
Additional Context:
Different routing protocols use different metrics such as:
- hop count
- bandwidth
- delay
- cost

Source:
Cisco Routing Protocol Overview
https://www.cisco.com/
}}}

-----------------------------------
HOP COUNT
-----------------------------------

Hop count:
- counts the number of routers crossed
between:
- source and destination

-----------------------------------
RIP METRIC
-----------------------------------

RIP uses:
- hop count
as its routing metric

-----------------------------------
LOWER METRIC PREFERENCE
-----------------------------------

Generally:
- lower metrics are preferred

-----------------------------------
ADMINISTRATIVE DISTANCE
-----------------------------------

{{{
Additional Context:
Administrative Distance (AD) determines which routing source is trusted more when multiple routing protocols provide routes to the same destination.

Lower AD is preferred.

Source:
Cisco Administrative Distance Documentation
https://www.cisco.com/
}}}

-----------------------------------
LONGEST PREFIX MATCH
-----------------------------------

{{{
Additional Context:
Routers typically choose the route with the most specific subnet match first.

This is called:
- longest prefix match

Example:
192.168.1.0/24 is preferred over 192.168.0.0/16 for traffic destined to 192.168.1.x.

Source:
RFC 1812 — Requirements for IP Routers
https://datatracker.ietf.org/doc/html/rfc1812
}}}

-----------------------------------
STATIC VS DYNAMIC ROUTES
-----------------------------------

Routers may learn routes through:
- static routing
- dynamic routing protocols

-----------------------------------
STATIC ROUTE SELECTION
-----------------------------------

Static routes:
- are manually configured
- provide predictable routing

-----------------------------------
DYNAMIC ROUTE SELECTION
-----------------------------------

Dynamic routing protocols:
- automatically discover routes
- automatically update routes

-----------------------------------
RIP ROUTE SELECTION
-----------------------------------

RIP selects routes based on:
- lowest hop count

-----------------------------------
OSPF ROUTE SELECTION
-----------------------------------

{{{
Additional Context:
OSPF selects routes using cost, commonly based on bandwidth.

Lower cost routes are preferred.

Source:
Cisco OSPF Overview
https://www.cisco.com/
}}}

-----------------------------------
BGP ROUTE SELECTION
-----------------------------------

{{{
Additional Context:
BGP route selection uses multiple attributes and policies to determine best paths between autonomous systems.

Source:
Cisco BGP Best Path Selection
https://www.cisco.com/
}}}

-----------------------------------
DEFAULT ROUTE
-----------------------------------

{{{
Additional Context:
A default route is used when no more specific route exists for a destination.

Often represented as:
0.0.0.0/0

Source:
Cisco Networking Academy
https://www.netacad.com/
}}}

-----------------------------------
CONVERGENCE
-----------------------------------

Convergence:
- occurs when routers agree on updated routing information

-----------------------------------
WHY CONVERGENCE MATTERS
-----------------------------------

Fast convergence:
- improves network reliability
- reduces downtime

-----------------------------------
ROUTE FAILOVER
-----------------------------------

Dynamic routing protocols can:
- automatically reroute traffic
when:
- links fail

-----------------------------------
LOAD BALANCING
-----------------------------------

{{{
Additional Context:
Some routing protocols support equal-cost load balancing, allowing traffic to use multiple paths simultaneously.

Source:
Cisco Equal-Cost Multi-Path (ECMP)
https://www.cisco.com/
}}}

-----------------------------------
ROUTING DECISION PROCESS
-----------------------------------

General routing decision process:
1. Check routing table
2. Find matching routes
3. Select best route
4. Forward packet

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A router chooses the path with the fewest router hops."

Answer:
Hop count metric

-----------------------------------

Scenario:
"A routing protocol dynamically reroutes traffic after a failure."

Answer:
Dynamic routing

-----------------------------------

Scenario:
"A router uses the most specific subnet match."

Answer:
Longest prefix match

-----------------------------------

Scenario:
"A route is manually configured by an administrator."

Answer:
Static route

-----------------------------------

Scenario:
"A router uses a default path when no specific route exists."

Answer:
Default route

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking routers randomly choose paths.

Wrong.

Routers:
- use routing tables and metrics

-----------------------------------

Trap:
Thinking all routing protocols use the same metric.

Wrong.

Different protocols:
- use different metrics

-----------------------------------

Trap:
Thinking higher metrics are preferred.

Wrong.

Lower metrics are generally preferred.

-----------------------------------

Trap:
Confusing administrative distance and metrics.

Administrative distance:
- trustworthiness of route source

Metric:
- quality/preference of path

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Metric =
Best path quality

Administrative Distance =
Most trusted route source

Longest Prefix Match =
Most specific route wins

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is route selection?

A:
The process routers use to determine the best path for packets.

-----------------------------------

Q:
What do routers use to make forwarding decisions?

A:
Routing tables.

-----------------------------------

Q:
What is a routing metric?

A:
A value used to evaluate and compare routes.

-----------------------------------

Q:
What metric does RIP use?

A:
Hop count.

-----------------------------------

Q:
What is hop count?

A:
The number of routers crossed between source and destination.

-----------------------------------

Q:
What is convergence?

A:
Routers agreeing on updated routing information.

-----------------------------------

Q:
What is a default route?

A:
A route used when no more specific route exists.

-----------------------------------

Q:
What is longest prefix match?

A:
Choosing the most specific matching subnet route.

-----------------------------------

Q:
What is administrative distance?

A:
A value representing trustworthiness of a routing source.

-----------------------------------

Q:
What type of routing automatically adapts to failures?

A:
Dynamic routing.