========================
Network Topologies and Architectures
Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.6: Network Topologies, Architectures, and Types
Pages 23–24
0

-----------------------------------
NETWORK TOPOLOGIES
-----------------------------------

Network topology describes:
- how devices are connected
- how communication paths are organized
within a network

-----------------------------------
MESH TOPOLOGY
-----------------------------------

Mesh topology:
- devices connect to multiple other devices

-----------------------------------
MESH CHARACTERISTICS
-----------------------------------

- High redundancy
- Multiple communication paths
- Fault tolerant
- Reliable connectivity

-----------------------------------
MESH BENEFITS
-----------------------------------

If one connection fails:
- traffic can take another path

-----------------------------------
MESH DISADVANTAGES
-----------------------------------

- Complex design
- Higher cost
- More cabling and configuration

-----------------------------------
FULL MESH
-----------------------------------

{{{
Additional Context:
In a full mesh topology, every device connects directly to every other device.

Source:
Cisco Networking Academy
https://www.netacad.com/
}}}

-----------------------------------
PARTIAL MESH
-----------------------------------

{{{
Additional Context:
In a partial mesh topology, only some devices have multiple interconnections.

Source:
Cisco Networking Academy
https://www.netacad.com/
}}}

-----------------------------------
HYBRID TOPOLOGY
-----------------------------------

Hybrid topology:
- combines multiple topology types
within the same network

-----------------------------------
HYBRID CHARACTERISTICS
-----------------------------------

- Flexible
- Scalable
- Combines advantages of different topologies

-----------------------------------
HYBRID USE CASES
-----------------------------------

Organizations use hybrid topologies to:
- meet different networking requirements
- improve scalability
- optimize network design

-----------------------------------
STAR TOPOLOGY
-----------------------------------

Star topology:
- all devices connect to a central device

-----------------------------------
STAR CHARACTERISTICS
-----------------------------------

- Centralized connectivity
- Easy to manage
- Easy to troubleshoot
- Common modern LAN design

-----------------------------------
CENTRAL DEVICE
-----------------------------------

The central device is commonly:
- a switch

-----------------------------------
STAR BENEFITS
-----------------------------------

- Failure of one endpoint does not affect others
- Simplified troubleshooting
- Easy expansion

-----------------------------------
STAR DISADVANTAGES
-----------------------------------

- Central device becomes critical point of failure

-----------------------------------
HUB-AND-SPOKE TOPOLOGY
-----------------------------------

Hub-and-spoke topology:
- uses a central hub location
connected to:
- branch/spoke locations

-----------------------------------
HUB-AND-SPOKE CHARACTERISTICS
-----------------------------------

- Centralized communication
- Simplified management
- Common in WAN environments

-----------------------------------
HUB-AND-SPOKE USE CASES
-----------------------------------

Used in:
- branch office networks
- WAN connectivity
- centralized enterprise networking

-----------------------------------
SPINE-AND-LEAF ARCHITECTURE
-----------------------------------

Spine-and-leaf:
- modern data center architecture

-----------------------------------
SPINE-AND-LEAF CHARACTERISTICS
-----------------------------------

- Every leaf switch connects to every spine switch
- High-speed east-west traffic support
- Low latency
- High scalability

-----------------------------------
SPINE SWITCHES
-----------------------------------

Spine switches:
- form the network backbone/core

-----------------------------------
LEAF SWITCHES
-----------------------------------

Leaf switches:
- connect endpoint devices and servers

-----------------------------------
SPINE-AND-LEAF BENEFITS
-----------------------------------

- Predictable latency
- High bandwidth
- Improved scalability
- Efficient data center traffic flow

-----------------------------------
POINT-TO-POINT TOPOLOGY
-----------------------------------

Point-to-point topology:
- direct connection between two devices

-----------------------------------
POINT-TO-POINT CHARACTERISTICS
-----------------------------------

- Simple design
- Dedicated connection
- Common in WAN links

-----------------------------------
POINT-TO-POINT USE CASES
-----------------------------------

Used for:
- direct router connections
- leased lines
- dedicated communication paths

-----------------------------------
THREE-TIER ARCHITECTURE
-----------------------------------

Three-tier architecture includes:
- core layer
- distribution layer
- access layer

-----------------------------------
CORE LAYER
-----------------------------------

Core layer:
- high-speed backbone
- fast transport between network segments

-----------------------------------
DISTRIBUTION LAYER
-----------------------------------

Distribution layer:
- policy enforcement
- routing
- aggregation

-----------------------------------
ACCESS LAYER
-----------------------------------

Access layer:
- connects end-user devices

-----------------------------------
THREE-TIER BENEFITS
-----------------------------------

- Modular design
- Scalability
- Easier management
- Structured hierarchy

-----------------------------------
COLLAPSED CORE ARCHITECTURE
-----------------------------------

Collapsed core architecture:
- combines core and distribution layers

-----------------------------------
COLLAPSED CORE CHARACTERISTICS
-----------------------------------

- Simplified architecture
- Lower cost
- Common in smaller environments

-----------------------------------
COLLAPSED CORE BENEFITS
-----------------------------------

- Reduced complexity
- Fewer devices
- Easier management

-----------------------------------
THREE-TIER VS COLLAPSED CORE
-----------------------------------

Three-tier:
- separate core and distribution layers
- larger enterprise environments

Collapsed core:
- merged core/distribution layers
- smaller networks

-----------------------------------
TOPOLOGY COMPARISON
-----------------------------------

Mesh:
- highly redundant

Star:
- centralized switch

Hub-and-spoke:
- centralized WAN structure

Spine-and-leaf:
- scalable data center architecture

Point-to-point:
- direct connection between two devices

Three-tier:
- core/distribution/access hierarchy

Collapsed core:
- merged core/distribution design

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A network requires maximum redundancy with multiple communication paths."

Answer:
Mesh topology

-----------------------------------

Scenario:
"All devices connect to a central switch."

Answer:
Star topology

-----------------------------------

Scenario:
"A branch office network uses a central headquarters connection."

Answer:
Hub-and-spoke

-----------------------------------

Scenario:
"A modern data center requires scalable low-latency east-west traffic."

Answer:
Spine-and-leaf

-----------------------------------

Scenario:
"A dedicated WAN link directly connects two routers."

Answer:
Point-to-point

-----------------------------------

Scenario:
"A network architecture separates access, distribution, and core layers."

Answer:
Three-tier architecture

-----------------------------------

Scenario:
"A smaller organization combines core and distribution functions."

Answer:
Collapsed core architecture

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking mesh topology is simple and inexpensive.

Wrong.

Mesh:
- complex
- expensive
- highly redundant

-----------------------------------

Trap:
Thinking star topology has no single point of failure.

Wrong.

The central device:
- is critical

-----------------------------------

Trap:
Confusing spine-and-leaf with traditional three-tier architecture.

Spine-and-leaf:
- data center optimized
- flat scalable design

Three-tier:
- hierarchical enterprise model

-----------------------------------

Trap:
Thinking collapsed core means no hierarchy exists.

Wrong.

Collapsed core:
- still has hierarchy
- but combines layers

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Mesh =
Many paths

Star =
Central switch

Hub-and-spoke =
Central WAN hub

Spine-and-leaf =
Data center fabric

Point-to-point =
Direct link

Three-tier =
Core/distribution/access

Collapsed core =
Merged core/distribution

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is mesh topology?

A:
A topology with multiple interconnections between devices.

-----------------------------------

Q:
What is the major advantage of mesh topology?

A:
High redundancy and fault tolerance.

-----------------------------------

Q:
What topology connects all devices to a central switch?

A:
Star topology.

-----------------------------------

Q:
What is hub-and-spoke topology commonly used for?

A:
WAN and branch office networking.

-----------------------------------

Q:
What architecture is commonly used in modern data centers?

A:
Spine-and-leaf.

-----------------------------------

Q:
What is the purpose of spine switches?

A:
Provide high-speed backbone connectivity.

-----------------------------------

Q:
What topology provides a direct connection between two devices?

A:
Point-to-point.

-----------------------------------

Q:
What are the three layers of three-tier architecture?

A:
Core, distribution, and access.

-----------------------------------

Q:
What is collapsed core architecture?

A:
A design combining the core and distribution layers.

-----------------------------------

Q:
Why is spine-and-leaf architecture beneficial?

A:
High scalability, low latency, and efficient east-west traffic handling.