========================
Deception Technologies
Honeypots and Honeynets
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.2: Security Concepts
Pages 66–68


-----------------------------------
DECEPTION TECHNOLOGIES
-----------------------------------

Deception technologies are:
- systems/resources intentionally designed to attract attackers

-----------------------------------
CORE PURPOSE
-----------------------------------

Deception technologies help:
- detect attackers
- monitor malicious activity
- gather intelligence
- distract attackers
- delay intrusions

-----------------------------------
WHY DECEPTION TECHNOLOGIES EXIST
-----------------------------------

Attackers commonly probe networks for:
- vulnerable systems
- exposed services
- weak configurations

Deception systems intentionally appear:
- valuable
or:
- vulnerable

-----------------------------------
MAIN EXAM TOPICS
-----------------------------------

Important topics:
- honeypots
- honeynets

===================================
HONEYPOTS
===================================

-----------------------------------
HONEYPOT
-----------------------------------

A honeypot is:
- a decoy system/resource intended to attract attackers

-----------------------------------
HONEYPOT PURPOSE
-----------------------------------

Honeypots help:
- detect attacks
- observe attacker behavior
- gather threat intelligence

-----------------------------------
WHY HONEYPOTS WORK
-----------------------------------

Legitimate users should generally:
- never access honeypots

Therefore:
- activity targeting honeypots is suspicious

-----------------------------------
COMMON HONEYPOT CHARACTERISTICS
-----------------------------------

Honeypots may appear to be:
- servers
- databases
- applications
- IoT devices
- vulnerable systems

-----------------------------------
DECOY SYSTEMS
-----------------------------------

Honeypots are intentionally:
- decoys

-----------------------------------
MONITORING
-----------------------------------

Honeypots commonly:
- log activity extensively

-----------------------------------
ACTIVITY EXAMPLES
-----------------------------------

Examples:
- scans
- login attempts
- malware activity
- exploit attempts
- reconnaissance

-----------------------------------
THREAT INTELLIGENCE
-----------------------------------

Honeypots help gather:
- attacker tactics
- malware behavior
- intrusion techniques

-----------------------------------
EARLY DETECTION
-----------------------------------

Honeypots may provide:
- early warning of attacks

-----------------------------------
DISTRACTION
-----------------------------------

Honeypots may:
- distract attackers from production systems

-----------------------------------
LOW-INTERACTION HONEYPOTS
-----------------------------------

{{{
Additional Context:
Low-interaction honeypots simulate limited services/applications.

Source:
SANS Honeypot Concepts
https://www.sans.org/
}}}

-----------------------------------
LOW-INTERACTION PURPOSE
-----------------------------------

Low-interaction honeypots:
- reduce risk
- simplify deployment

-----------------------------------
HIGH-INTERACTION HONEYPOTS
-----------------------------------

{{{
Additional Context:
High-interaction honeypots simulate full operating environments.

Source:
SANS Honeypot Concepts
https://www.sans.org/
}}}

-----------------------------------
HIGH-INTERACTION PURPOSE
-----------------------------------

High-interaction honeypots:
- provide deeper attacker visibility

-----------------------------------
HIGH-INTERACTION RISKS
-----------------------------------

High-interaction honeypots may:
- increase risk if compromised

-----------------------------------
PRODUCTION RISKS
-----------------------------------

Poorly isolated honeypots may:
- become attack launch points

-----------------------------------
ISOLATION
-----------------------------------

Honeypots should commonly be:
- isolated
- monitored carefully

-----------------------------------
LOGGING
-----------------------------------

Honeypots heavily rely on:
- logging
- monitoring
- packet capture

-----------------------------------
FORENSICS
-----------------------------------

Honeypots may support:
- forensic investigations

-----------------------------------
FALSE POSITIVES
-----------------------------------

Honeypots often produce:
- low false-positive rates

-----------------------------------
WHY LOW FALSE POSITIVES MATTER
-----------------------------------

Legitimate users should not:
- normally interact with honeypots

===================================
HONEYNETS
===================================

-----------------------------------
HONEYNET
-----------------------------------

A honeynet is:
- a network of multiple honeypots

-----------------------------------
HONEynet PURPOSE
-----------------------------------

Honeynets simulate:
- realistic network environments

-----------------------------------
WHY HONEYNETS EXIST
-----------------------------------

Attackers often target:
- multiple systems
- network relationships
- lateral movement opportunities

-----------------------------------
HONEYNET CHARACTERISTICS
-----------------------------------

A honeynet may include:
- multiple decoy hosts
- fake services
- simulated infrastructure
- realistic traffic

-----------------------------------
LATERAL MOVEMENT
-----------------------------------

Honeynets may help analyze:
- attacker lateral movement

-----------------------------------
LATERAL MOVEMENT PURPOSE
-----------------------------------

Attackers often attempt to:
- pivot between systems

-----------------------------------
THREAT RESEARCH
-----------------------------------

Honeynets are commonly used for:
- advanced threat research

-----------------------------------
ADVANCED VISIBILITY
-----------------------------------

Honeynets provide:
- broader attack visibility than single honeypots

-----------------------------------
COMPLEXITY
-----------------------------------

Honeynets are generally:
- more complex than honeypots

-----------------------------------
MANAGEMENT REQUIREMENTS
-----------------------------------

Honeynets require:
- careful monitoring
- segmentation
- logging
- containment

-----------------------------------
SEGMENTATION
-----------------------------------

Honeynets should commonly be:
- segmented from production systems

-----------------------------------
CONTAINMENT
-----------------------------------

Containment helps prevent:
- attackers using honeynets to attack others

-----------------------------------
IDS/IPS INTEGRATION
-----------------------------------

Honeypots/honeynets may integrate with:
- IDS
- IPS
- SIEM platforms

-----------------------------------
SIEM
-----------------------------------

SIEM =
Security Information and Event Management

-----------------------------------
SIEM PURPOSE
-----------------------------------

SIEM platforms may:
- correlate honeypot alerts
- analyze attack activity

-----------------------------------
MALWARE ANALYSIS
-----------------------------------

Honeypots may help analyze:
- malware behavior

-----------------------------------
BOTNET DETECTION
-----------------------------------

{{{
Additional Context:
Honeypots are commonly used to study:
- botnets
- automated scanning
- worms

Source:
SANS Honeynet Project
https://www.honeynet.org/
}}}

-----------------------------------
CREDENTIAL HARVESTING
-----------------------------------

Honeypots may detect:
- credential attacks
- brute-force attempts

-----------------------------------
INTERNAL VS EXTERNAL HONEYPOTS
-----------------------------------

{{{
Additional Context:
Organizations may deploy:
- external honeypots (Internet-facing)
- internal honeypots (inside networks)

Source:
SANS Honeypot Deployment Concepts
https://www.sans.org/
}}}

-----------------------------------
INTERNAL HONEYPOT PURPOSE
-----------------------------------

Internal honeypots may help detect:
- insider threats
- lateral movement

-----------------------------------
ETHICAL/LEGAL CONSIDERATIONS
-----------------------------------

{{{
Additional Context:
Organizations should consider:
- privacy
- monitoring policies
- legal compliance

Source:
NIST Security Monitoring Guidance
https://csrc.nist.gov/
}}}

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Honeypots are decoy systems
- Honeynets are networks of honeypots
- Honeypots help detect attackers
- Honeypots gather threat intelligence
- Honeynets simulate realistic environments
- Honeypots commonly have low false positives
- High-interaction honeypots provide deeper visibility
- Honeypots should be isolated
- Honeypots may integrate with SIEM/IDS

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A fake vulnerable server is deployed to attract attackers."

Answer:
Honeypot

-----------------------------------

Scenario:
"A security team creates an entire decoy network."

Answer:
Honeynet

-----------------------------------

Scenario:
"A company wants early warning of malicious scanning."

Answer:
Honeypot

-----------------------------------

Scenario:
"A security analyst studies attacker lateral movement across decoy systems."

Answer:
Honeynet

-----------------------------------

Scenario:
"A decoy system records malware activity for research."

Answer:
Honeypot

-----------------------------------

Scenario:
"A security system should rarely receive legitimate traffic."

Answer:
Honeypot

-----------------------------------

Scenario:
"A company wants to analyze attacker behavior in a realistic environment."

Answer:
High-interaction honeypot/honeynet

-----------------------------------

Scenario:
"A decoy environment must be segmented from production systems."

Answer:
Honeynet/honeypot deployment

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking honeypots are production systems.

Wrong.

Honeypots are:
- decoy systems

-----------------------------------

Trap:
Thinking honeypots prevent attacks automatically.

Wrong.

Honeypots primarily:
- detect
- monitor
- analyze

-----------------------------------

Trap:
Confusing honeypots and honeynets.

Honeypot:
- single decoy system

Honeynet:
- multiple decoy systems/network

-----------------------------------

Trap:
Thinking all honeypots are safe if compromised.

Wrong.

Poorly isolated honeypots may:
- become attack platforms

-----------------------------------

Trap:
Thinking legitimate users commonly access honeypots.

Wrong.

Legitimate interaction should generally:
- be minimal/nonexistent

-----------------------------------

Trap:
Thinking high-interaction honeypots are always preferable.

Wrong.

They provide:
- greater visibility

But also:
- greater complexity/risk

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Honeypot =
Single decoy

Honeynet =
Decoy network

Low interaction =
Safer/simple

High interaction =
More realistic/riskier

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is a honeypot?

A:
A decoy system designed to attract attackers.

-----------------------------------

Q:
What is a honeynet?

A:
A network of multiple honeypots.

-----------------------------------

Q:
What is the purpose of honeypots?

A:
Detect and analyze malicious activity.

-----------------------------------

Q:
Why do honeypots commonly have low false positives?

A:
Legitimate users should rarely access them.

-----------------------------------

Q:
What is the difference between a honeypot and a honeynet?

A:
A honeypot is a single decoy system; a honeynet is a decoy network.

-----------------------------------

Q:
What is a high-interaction honeypot?

A:
A realistic honeypot simulating full environments.

-----------------------------------

Q:
Why should honeypots be isolated?

A:
To prevent compromise from affecting production systems.

-----------------------------------

Q:
What security tools commonly integrate with honeypots?

A:
SIEM, IDS, and IPS systems.

-----------------------------------

Q:
What can honeypots help analyze?

A:
Malware, scans, brute-force attacks, and attacker behavior.

-----------------------------------

Q:
What is one advantage of high-interaction honeypots?

A:
Greater attacker visibility and intelligence gathering.