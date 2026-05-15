========================
NAS vs SAN — Deep Review
========================

-----------------------------------
CORE DEFINITIONS
-----------------------------------

NAS = Network Attached Storage
SAN = Storage Area Network

NAS:
- File-level storage over a network
- Users/systems access shared files/folders

SAN:
- Block-level storage network
- Servers access raw storage as though it were a local disk

-----------------------------------
SIMPLE MENTAL MODEL
-----------------------------------

NAS:
"Here are files."

SAN:
"Here is a hard drive."

-----------------------------------
KEY DIFFERENCE
-----------------------------------

NAS = File Storage
SAN = Block Storage

This is THE biggest conceptual distinction.

-----------------------------------
FILE-LEVEL STORAGE (NAS)
-----------------------------------

With NAS:
- The NAS manages the filesystem
- The client accesses files/folders

Example:
\\NAS\Movies\Movie.mp4

Protocols:
- SMB
- NFS
- AFP

The client:
- does NOT manage the disk structure itself
- simply accesses files

-----------------------------------
BLOCK-LEVEL STORAGE (SAN)
-----------------------------------

With SAN:
- The storage provides raw blocks
- The client/server builds the filesystem

To the server:
- it appears like a locally attached drive

Example:
- Windows sees "Disk 2"
- Linux sees /dev/sdb

The server itself:
- formats the disk
- creates NTFS/ext4/etc
- manages partitions

-----------------------------------
COMMON NAS PROTOCOLS
-----------------------------------

SMB (Windows)
Port:
- TCP 445

NFS (Linux/Unix)
Port:
- TCP/UDP 2049

AFP (Older Apple)
Mostly obsolete now.

-----------------------------------
COMMON SAN PROTOCOLS
-----------------------------------

iSCSI
Port:
- TCP 3260

Fibre Channel
Very high-speed enterprise storage fabric.

FCoE
(Fibre Channel over Ethernet)

-----------------------------------
WHAT IS iSCSI?
-----------------------------------

iSCSI =
SCSI commands over IP/Ethernet.

It allows:
- block storage over standard networks

Very important exam concept.

-----------------------------------
NAS USE CASES
-----------------------------------

Home:
- Plex
- photo backups
- family files

Small Business:
- shared office documents
- centralized backups

Enterprise:
- department shares
- collaborative storage

-----------------------------------
SAN USE CASES
-----------------------------------

Enterprise virtualization
Databases
High-performance applications
VMware clusters
Hyper-V clusters

Why?
Because SANs:
- are faster
- have lower latency
- scale better for enterprise workloads

-----------------------------------
PERFORMANCE DIFFERENCES
-----------------------------------

NAS:
- usually slower
- Ethernet-based
- more overhead

SAN:
- usually faster
- optimized for storage traffic
- lower latency

-----------------------------------
WHY SANS ARE FASTER
-----------------------------------

SANs often use:
- dedicated storage networks
- Fibre Channel
- specialized HBAs
- low-latency switching

Instead of:
- general LAN traffic

-----------------------------------
DEDICATED STORAGE NETWORK
-----------------------------------

A SAN often exists on its OWN network.

Example:

Production LAN:
- user traffic
- internet
- printers

Separate SAN:
- storage-only traffic

Benefits:
- less congestion
- better performance
- predictable latency

-----------------------------------
NAS APPLIANCES
-----------------------------------

Examples:
- Synology
- QNAP
- TrueNAS

They are:
- storage-focused servers

-----------------------------------
SAN INFRASTRUCTURE
-----------------------------------

SANs commonly require:
- Fibre Channel switches
- HBAs
- enterprise arrays
- zoning
- LUN management

Much more complex.

-----------------------------------
WHAT IS A LUN?
-----------------------------------

LUN =
Logical Unit Number

Essentially:
- a block storage allocation presented to a server

Think:
"virtual disk presented by SAN"

-----------------------------------
MULTIPLE SERVERS ACCESSING SAN
-----------------------------------

Very important.

Multiple servers may access:
- shared SAN storage

This enables:
- clustering
- failover
- virtualization migration

-----------------------------------
VMWARE + SAN
-----------------------------------

Very common enterprise architecture.

Example:
Multiple VMware hosts use shared SAN storage.

Benefits:
- live migration
- high availability
- failover clustering

-----------------------------------
RAID IN NAS AND SAN
-----------------------------------

Both commonly use RAID.

RAID provides:
- redundancy
- fault tolerance
- performance

-----------------------------------
IMPORTANT RAID REMINDER
-----------------------------------

RAID IS NOT BACKUP.

RAID protects against:
- drive failure

RAID does NOT protect against:
- ransomware
- deletion
- corruption
- fire
- theft

-----------------------------------
COMMON RAID LEVELS
-----------------------------------

RAID 0
- striping
- no redundancy
- fastest
- dangerous

RAID 1
- mirroring
- redundancy
- simple

RAID 5
- parity
- survives 1 drive failure

RAID 6
- dual parity
- survives 2 failures

RAID 10
- mirror + stripe
- fast and redundant

-----------------------------------
THIN PROVISIONING
-----------------------------------

Common SAN concept.

Storage is:
- allocated logically
before physically consuming space.

Example:
Present:
- 10TB logical storage

Even though:
- only 2TB physically used currently

-----------------------------------
SNAPSHOTS
-----------------------------------

Common in enterprise storage.

Snapshots:
- point-in-time copies

Useful for:
- rollback
- ransomware recovery
- accidental deletion

-----------------------------------
NAS SECURITY CONCERNS
-----------------------------------

Weak passwords
Exposed SMB shares
Internet exposure
Ransomware

Very common attack target.

-----------------------------------
SAN SECURITY CONCERNS
-----------------------------------

Unauthorized LUN access
Poor zoning
Misconfigured initiators
Data exposure between servers

-----------------------------------
WHAT IS ZONING?
-----------------------------------

Fibre Channel zoning:
controls which devices can communicate.

Similar conceptually to:
- VLAN segmentation

-----------------------------------
INITIATOR VS TARGET
-----------------------------------

Important SAN terms.

Initiator:
- client/server requesting storage

Target:
- storage device providing storage

Example:
Server --> initiator
SAN array --> target

-----------------------------------
NAS AUTHENTICATION
-----------------------------------

May integrate with:
- Active Directory
- LDAP
- local accounts

Permissions:
- share permissions
- file permissions

-----------------------------------
SAN AUTHENTICATION
-----------------------------------

Often uses:
- IQNs (iSCSI Qualified Names)
- CHAP authentication
- Fibre Channel WWNs

-----------------------------------
WHAT IS CHAP?
-----------------------------------

CHAP =
Challenge Handshake Authentication Protocol

Used commonly with:
- iSCSI authentication

-----------------------------------
WHAT IS A HBA?
-----------------------------------

HBA =
Host Bus Adapter

Specialized SAN network card.

Commonly:
- Fibre Channel adapter

-----------------------------------
FIBRE CHANNEL
-----------------------------------

Enterprise storage protocol.

Advantages:
- very fast
- low latency
- reliable

Disadvantages:
- expensive
- specialized hardware

-----------------------------------
FCoE
-----------------------------------

Fibre Channel over Ethernet

Allows:
- Fibre Channel traffic over Ethernet

Attempts to combine:
- LAN + SAN infrastructure

-----------------------------------
DAS VS NAS VS SAN
-----------------------------------

DAS = Direct Attached Storage

Examples:
- internal HDD
- USB drive

Comparison:

DAS:
directly connected

NAS:
file storage over network

SAN:
block storage network

-----------------------------------
EXAM SCENARIO EXAMPLES
-----------------------------------

Scenario:
"Users need shared folders."

Answer:
NAS

-----------------------------------

Scenario:
"Virtualization cluster needs shared high-speed storage."

Answer:
SAN

-----------------------------------

Scenario:
"Storage appears as local disk to server."

Answer:
SAN

-----------------------------------

Scenario:
"Windows shared files over TCP 445."

Answer:
NAS/SMB

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking SAN = "bigger NAS"

Wrong.

Core difference:
- file vs block storage

-----------------------------------

Trap:
Thinking RAID = backup

Wrong.

-----------------------------------

Trap:
Confusing NAS protocols and SAN protocols

NAS:
- SMB
- NFS

SAN:
- iSCSI
- Fibre Channel

-----------------------------------

Trap:
Thinking SAN is always internet/cloud based

Wrong.

Many SANs are:
- entirely internal enterprise networks

-----------------------------------
COMPARISON TABLE
-----------------------------------

NAS
- File-level
- SMB/NFS
- Easier
- Cheaper
- Shared folders
- Home/business common

SAN
- Block-level
- iSCSI/Fibre Channel
- More complex
- More expensive
- Enterprise/datacenter common
- Appears as local disks

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

NAS:
Network files.

SAN:
Storage blocks.

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What type of storage does NAS provide?

A:
File-level storage.

-----------------------------------

Q:
What type of storage does SAN provide?

A:
Block-level storage.

-----------------------------------

Q:
Which NAS protocol is most associated with Windows?

A:
SMB.

-----------------------------------

Q:
Which SAN protocol runs over IP networks?

A:
iSCSI.

-----------------------------------

Q:
What port does iSCSI use?

A:
TCP 3260.

-----------------------------------

Q:
What is a LUN?

A:
Logical storage allocation presented by a SAN.

-----------------------------------

Q:
What device commonly connects servers to Fibre Channel SANs?

A:
HBA.

-----------------------------------

Q:
Which is generally more complex: NAS or SAN?

A:
SAN.

-----------------------------------

Q:
Which is commonly used for virtualization clusters?

A:
SAN.

-----------------------------------

Q:
What is the biggest conceptual difference between NAS and SAN?

A:
NAS provides files; SAN provides raw blocks.