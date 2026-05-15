========================
Disaster Recovery
RPO, RTO, MTTR, MTBF,
Cold/Warm/Hot Sites,
Active-Active/Passive,
and Testing
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 3 — Network Operations
Section 3.3: Business Continuity and Disaster Recovery
Pages 59–61


-----------------------------------
DISASTER RECOVERY (DR)
-----------------------------------

Disaster recovery refers to:
- restoring systems and operations after major disruptions

-----------------------------------
CORE PURPOSE
-----------------------------------

Disaster recovery helps organizations:
- restore services
- reduce downtime
- protect data
- maintain operations
- recover from failures/disasters

-----------------------------------
WHY DISASTER RECOVERY EXISTS
-----------------------------------

Organizations may experience:
- hardware failures
- cyberattacks
- natural disasters
- power outages
- fires
- floods
- ransomware
- human error

-----------------------------------
BUSINESS CONTINUITY VS DR
-----------------------------------

Business continuity:
- maintaining operations during disruptions

Disaster recovery:
- restoring systems after disruptions

-----------------------------------
MAIN EXAM TOPICS
-----------------------------------

The guide specifically covers:
- RPO
- RTO
- MTTR
- MTBF
- cold sites
- warm sites
- hot sites
- active-active
- active-passive
- testing

-----------------------------------
RPO
-----------------------------------

RPO =
Recovery Point Objective

-----------------------------------
RPO PURPOSE
-----------------------------------

RPO defines:
- maximum acceptable data loss

-----------------------------------
RPO MEANING
-----------------------------------

RPO answers:
"How much data can we afford to lose?"

-----------------------------------
RPO EXAMPLE
-----------------------------------

Example:
RPO = 1 hour

Meaning:
- up to 1 hour of data loss may be acceptable

-----------------------------------
LOW RPO
-----------------------------------

Low RPO requires:
- frequent backups
- replication
- continuous synchronization

-----------------------------------
HIGH RPO
-----------------------------------

Higher RPO:
- allows greater data loss tolerance

-----------------------------------
RTO
-----------------------------------

RTO =
Recovery Time Objective

-----------------------------------
RTO PURPOSE
-----------------------------------

RTO defines:
- maximum acceptable downtime

-----------------------------------
RTO MEANING
-----------------------------------

RTO answers:
"How quickly must systems be restored?"

-----------------------------------
RTO EXAMPLE
-----------------------------------

Example:
RTO = 2 hours

Meaning:
- services should be restored within 2 hours

-----------------------------------
LOW RTO
-----------------------------------

Low RTO requires:
- rapid recovery systems
- redundancy
- failover mechanisms

-----------------------------------
HIGH RTO
-----------------------------------

Higher RTO:
- allows longer downtime

-----------------------------------
RPO VS RTO
-----------------------------------

RPO:
- acceptable data loss

RTO:
- acceptable downtime

-----------------------------------
MTTR
-----------------------------------

MTTR =
Mean Time To Repair

-----------------------------------
MTTR PURPOSE
-----------------------------------

MTTR measures:
- average time required to repair/restore systems

-----------------------------------
LOW MTTR
-----------------------------------

Lower MTTR is better because:
- systems recover faster

-----------------------------------
HIGH MTTR RISKS
-----------------------------------

High MTTR may indicate:
- inefficient recovery
- poor documentation
- inadequate staffing
- poor planning

-----------------------------------
MTBF
-----------------------------------

MTBF =
Mean Time Between Failures

-----------------------------------
MTBF PURPOSE
-----------------------------------

MTBF measures:
- average operational time before failures occur

-----------------------------------
HIGH MTBF
-----------------------------------

High MTBF indicates:
- greater reliability

-----------------------------------
LOW MTBF
-----------------------------------

Low MTBF may indicate:
- unreliable hardware
- aging infrastructure
- poor environmental conditions

-----------------------------------
MTBF VS MTTR
-----------------------------------

MTBF:
- reliability between failures

MTTR:
- time to repair failures

-----------------------------------
DISASTER RECOVERY SITES
-----------------------------------

Recovery sites provide:
- alternate operational locations

-----------------------------------
COLD SITE
-----------------------------------

Cold site:
- facility with minimal infrastructure

-----------------------------------
COLD SITE CHARACTERISTICS
-----------------------------------

Cold sites typically include:
- building space
- power
- networking capability

But may lack:
- active systems
- current data
- operational hardware

-----------------------------------
COLD SITE ADVANTAGES
-----------------------------------

Advantages:
- lowest cost

-----------------------------------
COLD SITE DISADVANTAGES
-----------------------------------

Disadvantages:
- slowest recovery
- highest setup time

-----------------------------------
WARM SITE
-----------------------------------

Warm site:
- partially prepared recovery site

-----------------------------------
WARM SITE CHARACTERISTICS
-----------------------------------

Warm sites may include:
- some hardware
- partial configurations
- partial connectivity

But:
- may still require restoration/configuration

-----------------------------------
WARM SITE ADVANTAGES
-----------------------------------

Advantages:
- moderate recovery speed
- moderate cost

-----------------------------------
WARM SITE DISADVANTAGES
-----------------------------------

Disadvantages:
- not immediately operational

-----------------------------------
HOT SITE
-----------------------------------

Hot site:
- fully operational recovery environment

-----------------------------------
HOT SITE CHARACTERISTICS
-----------------------------------

Hot sites commonly include:
- active systems
- current data
- active connectivity
- ready-to-operate infrastructure

-----------------------------------
HOT SITE ADVANTAGES
-----------------------------------

Advantages:
- fastest recovery
- minimal downtime

-----------------------------------
HOT SITE DISADVANTAGES
-----------------------------------

Disadvantages:
- highest cost

-----------------------------------
SITE SPEED COMPARISON
-----------------------------------

Recovery speed:
Hot > Warm > Cold

-----------------------------------
SITE COST COMPARISON
-----------------------------------

Cost:
Hot > Warm > Cold

-----------------------------------
ACTIVE-ACTIVE
-----------------------------------

Active-active systems:
- multiple active systems/sites operating simultaneously

-----------------------------------
ACTIVE-ACTIVE PURPOSE
-----------------------------------

Active-active designs improve:
- redundancy
- load balancing
- high availability

-----------------------------------
ACTIVE-ACTIVE ADVANTAGES
-----------------------------------

Advantages:
- fast failover
- high availability
- load sharing

-----------------------------------
ACTIVE-PASSIVE
-----------------------------------

Active-passive systems:
- primary active system
- secondary standby system

-----------------------------------
ACTIVE-PASSIVE PURPOSE
-----------------------------------

Passive systems activate:
- after primary failure

-----------------------------------
ACTIVE-PASSIVE ADVANTAGES
-----------------------------------

Advantages:
- simpler design
- lower cost than active-active

-----------------------------------
ACTIVE-PASSIVE DISADVANTAGES
-----------------------------------

Disadvantages:
- failover delay
- unused standby resources

-----------------------------------
FAILOVER
-----------------------------------

Failover refers to:
- switching operations to backup systems

-----------------------------------
REDUNDANCY
-----------------------------------

Redundancy helps:
- reduce single points of failure

-----------------------------------
BACKUPS
-----------------------------------

Disaster recovery commonly relies on:
- backups

-----------------------------------
BACKUP TYPES
-----------------------------------

{{{
Additional Context:
Common backup types:
- full
- incremental
- differential

Source:
Microsoft Backup Concepts
https://learn.microsoft.com/
}}}

-----------------------------------
REPLICATION
-----------------------------------

{{{
Additional Context:
Replication continuously copies data between systems/sites.

Source:
VMware Replication Concepts
https://docs.vmware.com/
}}}

-----------------------------------
TESTING
-----------------------------------

Testing validates:
- disaster recovery plans

-----------------------------------
WHY TESTING MATTERS
-----------------------------------

Untested recovery plans may:
- fail during real disasters

-----------------------------------
TESTING PURPOSE
-----------------------------------

Testing helps:
- identify weaknesses
- verify procedures
- improve readiness
- train personnel

-----------------------------------
COMMON TEST TYPES
-----------------------------------

{{{
Additional Context:
Common DR testing methods:
- tabletop exercises
- simulations
- failover testing
- full interruption testing

Source:
NIST Contingency Planning Guide
https://csrc.nist.gov/
}}}

-----------------------------------
TABLETOP EXERCISES
-----------------------------------

{{{
Additional Context:
Tabletop exercises discuss simulated disaster scenarios without actual failover.

Source:
NIST Contingency Planning Guide
https://csrc.nist.gov/
}}}

-----------------------------------
FAILOVER TESTING
-----------------------------------

Failover testing validates:
- backup systems
- redundancy
- recovery procedures

-----------------------------------
DOCUMENTATION
-----------------------------------

Disaster recovery plans should document:
- recovery procedures
- contacts
- priorities
- restoration steps
- communication plans

-----------------------------------
PRIORITIZATION
-----------------------------------

Critical systems are commonly restored:
- first

-----------------------------------
MISSION-CRITICAL SYSTEMS
-----------------------------------

Examples:
- authentication systems
- DNS
- firewalls
- core applications
- databases

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- RPO = acceptable data loss
- RTO = acceptable downtime
- MTTR = average repair time
- MTBF = reliability between failures
- Hot sites recover fastest
- Cold sites recover slowest
- Active-active uses multiple active systems
- Active-passive uses standby systems
- Testing validates recovery plans
- Redundancy reduces downtime

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A company can only tolerate 15 minutes of lost data."

Answer:
RPO

-----------------------------------

Scenario:
"A business requires systems restored within 1 hour."

Answer:
RTO

-----------------------------------

Scenario:
"A metric measures average repair time after failures."

Answer:
MTTR

-----------------------------------

Scenario:
"A metric measures reliability between failures."

Answer:
MTBF

-----------------------------------

Scenario:
"A fully operational backup data center is immediately available."

Answer:
Hot site

-----------------------------------

Scenario:
"A recovery facility contains only power and networking capability."

Answer:
Cold site

-----------------------------------

Scenario:
"A standby server activates after the primary fails."

Answer:
Active-passive

-----------------------------------

Scenario:
"Two data centers operate simultaneously for redundancy."

Answer:
Active-active

-----------------------------------

Scenario:
"A company simulates disaster scenarios to verify procedures."

Answer:
Disaster recovery testing

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing RPO and RTO.

RPO:
- acceptable data loss

RTO:
- acceptable downtime

-----------------------------------

Trap:
Confusing MTBF and MTTR.

MTBF:
- reliability before failure

MTTR:
- repair/recovery time

-----------------------------------

Trap:
Thinking cold sites recover quickly.

Wrong.

Cold sites:
- recover slowest

-----------------------------------

Trap:
Thinking hot sites are inexpensive.

Wrong.

Hot sites:
- highest cost

-----------------------------------

Trap:
Thinking active-passive systems both actively serve workloads simultaneously.

Wrong.

Only the active system normally handles workloads.

-----------------------------------

Trap:
Thinking backups alone guarantee disaster recovery.

Wrong.

Recovery procedures must also:
- be tested
- be documented
- support restoration

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

RPO =
Data loss tolerance

RTO =
Downtime tolerance

MTTR =
Repair time

MTBF =
Reliability

Hot site =
Ready now

Cold site =
Empty building

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does RPO stand for?

A:
Recovery Point Objective.

-----------------------------------

Q:
What does RPO measure?

A:
Maximum acceptable data loss.

-----------------------------------

Q:
What does RTO stand for?

A:
Recovery Time Objective.

-----------------------------------

Q:
What does RTO measure?

A:
Maximum acceptable downtime.

-----------------------------------

Q:
What does MTTR stand for?

A:
Mean Time To Repair.

-----------------------------------

Q:
What does MTBF stand for?

A:
Mean Time Between Failures.

-----------------------------------

Q:
Which recovery site restores operations fastest?

A:
Hot site.

-----------------------------------

Q:
Which recovery site is least prepared?

A:
Cold site.

-----------------------------------

Q:
What is an active-active design?

A:
Multiple active systems operating simultaneously.

-----------------------------------

Q:
What is an active-passive design?

A:
Primary active system with standby backup system.

-----------------------------------

Q:
Why is disaster recovery testing important?

A:
To verify recovery plans and procedures work properly.