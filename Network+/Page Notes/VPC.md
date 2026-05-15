========================
VPC — Network+ Review
========================

Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 1.3: Cloud Concepts and Connectivity Options
Pages 9–10
0

-----------------------------------
VPC DEFINITION
-----------------------------------

VPC =
Virtual Private Cloud

A VPC is:
- an isolated network space within a public cloud
- designed to provide segmentation, control, and security
similar to a private data center

-----------------------------------
CORE PURPOSE
-----------------------------------

A VPC allows organizations to:
- run cloud resources in an isolated virtual network
- control networking configurations
- securely separate cloud resources

-----------------------------------
VPC CHARACTERISTICS
-----------------------------------

A VPC allows users to define:
- IP address ranges
- subnets
- route tables
- network gateways

-----------------------------------
SIMPLE MENTAL MODEL
-----------------------------------

A VPC is essentially:
- your own private network
inside:
- a public cloud provider

-----------------------------------
VPC GOALS
-----------------------------------

VPCs provide:
- segmentation
- isolation
- security
- network control
- cloud resource organization

-----------------------------------
VPC COMPONENTS
-----------------------------------

Common VPC components include:
- subnets
- route tables
- gateways
- security groups
- security lists

-----------------------------------
SUBNETS
-----------------------------------

Subnets divide a VPC into smaller network segments.

Subnets help:
- organize resources
- improve security
- separate workloads

-----------------------------------
ROUTE TABLES
-----------------------------------

Route tables determine:
- how traffic moves within the VPC
- where traffic is forwarded

-----------------------------------
NETWORK GATEWAYS
-----------------------------------

Gateways allow communication between:
- VPC resources
and:
- external networks

-----------------------------------
INTERNET GATEWAY
-----------------------------------

An internet gateway:
- connects the VPC to the internet
- enables internet access for cloud resources

-----------------------------------
NAT GATEWAY
-----------------------------------

A NAT gateway:
- allows outbound internet access
- prevents inbound internet connections
- hides private IP addresses

-----------------------------------
NAT GATEWAY PURPOSE
-----------------------------------

Used for systems that:
- need updates
- require internet access
- should not be publicly reachable

-----------------------------------
NETWORK SECURITY GROUPS
-----------------------------------

Network Security Groups:
- control inbound traffic
- control outbound traffic
- act like a virtual firewall

Rules can specify:
- ports
- protocols
- source IPs
- destination IPs

-----------------------------------
NETWORK SECURITY LISTS
-----------------------------------

Network Security Lists:
- manage traffic at subnet level
- provide traffic filtering
- help secure cloud traffic

-----------------------------------
VPC SECURITY
-----------------------------------

VPC security is achieved through:
- segmentation
- traffic filtering
- routing controls
- gateways
- access policies

-----------------------------------
PRIVATE CLOUD-LIKE CONTROL
-----------------------------------

A VPC allows organizations to manage cloud networking similarly to:
- on-premises private networks

-----------------------------------
VPC ISOLATION
-----------------------------------

VPCs isolate cloud resources from:
- other customers
- other virtual networks

-----------------------------------
WHY VPCS MATTER
-----------------------------------

VPCs help organizations:
- securely deploy cloud applications
- separate workloads
- enforce security controls
- manage cloud networking

-----------------------------------
CLOUD CONNECTIVITY
-----------------------------------

VPCs can connect to:
- the internet
- on-premises networks
- VPNs
- other cloud networks

-----------------------------------
VPN CONNECTIVITY
-----------------------------------

VPNs can securely connect:
- remote users
- branch offices
- private networks
to:
- the VPC

-----------------------------------
PRIVATE-DIRECT CONNECTIONS
-----------------------------------

Private-direct connections:
- bypass the public internet
- provide secure and reliable cloud access
- improve performance

-----------------------------------
DEPLOYMENT MODELS
-----------------------------------

Public Cloud:
- shared cloud services over the internet

Private Cloud:
- dedicated cloud resources for one organization

Hybrid Cloud:
- combination of public and private cloud

-----------------------------------
SERVICE MODELS RELATED TO VPCS
-----------------------------------

SaaS:
Software as a Service

IaaS:
Infrastructure as a Service

PaaS:
Platform as a Service

-----------------------------------
SCALABILITY
-----------------------------------

Scalability means:
- handling increased workloads
- expanding resources efficiently

-----------------------------------
ELASTICITY
-----------------------------------

Elasticity means:
- automatically scaling resources
up or down
as demand changes

-----------------------------------
MULTITENANCY
-----------------------------------

Multitenancy means:
- multiple customers share cloud infrastructure
while:
- keeping data isolated

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company wants isolated cloud networking with custom subnets and routing."

Answer:
VPC

-----------------------------------

Scenario:
"Cloud resources need internet access."

Answer:
Internet Gateway

-----------------------------------

Scenario:
"Private instances need outbound internet access but should not accept inbound connections."

Answer:
NAT Gateway

-----------------------------------

Scenario:
"A company wants to control inbound and outbound traffic to cloud resources."

Answer:
Network Security Groups

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking a VPC is physical hardware.

Wrong.

A VPC is:
- virtualized cloud networking

-----------------------------------

Trap:
Confusing Internet Gateway and NAT Gateway.

Internet Gateway:
- allows internet connectivity

NAT Gateway:
- allows outbound access while hiding private IPs

-----------------------------------

Trap:
Thinking VPC means fully private cloud infrastructure.

Wrong.

A VPC exists:
- inside a public cloud provider

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

VPC =
Your own isolated network inside the cloud.

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does VPC stand for?

A:
Virtual Private Cloud.

-----------------------------------

Q:
What is a VPC?

A:
An isolated network space within a public cloud.

-----------------------------------

Q:
What can users define inside a VPC?

A:
IP ranges, subnets, route tables, and gateways.

-----------------------------------

Q:
What does an Internet Gateway do?

A:
Connects the VPC to the internet.

-----------------------------------

Q:
What does a NAT Gateway do?

A:
Allows outbound internet access while hiding private IP addresses.

-----------------------------------

Q:
What controls inbound and outbound traffic in a VPC?

A:
Network Security Groups.

-----------------------------------

Q:
What is the purpose of subnets in a VPC?

A:
Segmentation and organization of cloud resources.

-----------------------------------

Q:
What is elasticity?

A:
Automatically scaling resources up or down based on demand.

-----------------------------------

Q:
What is scalability?

A:
The ability to handle increasing workloads efficiently.

-----------------------------------

Q:
What is multitenancy?

A:
Multiple customers sharing cloud infrastructure while keeping data isolated.