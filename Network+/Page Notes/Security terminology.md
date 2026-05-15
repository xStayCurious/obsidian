========================
Security Terminology
Risk, Vulnerability,
Exploit, Threat,
and CIA Triad
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
SECURITY TERMINOLOGY
-----------------------------------

Security terminology provides:
- foundational cybersecurity concepts

-----------------------------------
WHY THESE TERMS MATTER
-----------------------------------

Network+ heavily tests:
- conceptual understanding
- relationship between threats and defenses

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

Many exam questions focus on:
- distinguishing similar security terms

===================================
RISK
===================================

-----------------------------------
RISK
-----------------------------------

Risk is:
- the potential for loss/damage when a threat exploits a vulnerability

-----------------------------------
CORE PURPOSE
-----------------------------------

Risk helps organizations evaluate:
- security exposure
- likelihood of harm
- potential impact

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

Risk commonly depends on:
- threats
- vulnerabilities
- impact
- likelihood

-----------------------------------
RISK FORMULA IDEA
-----------------------------------

{{{
Additional Context:
Risk is commonly thought of as:

Risk =
Likelihood × Impact

Source:
NIST Risk Management Concepts
https://csrc.nist.gov/
}}}

-----------------------------------
LIKELIHOOD
-----------------------------------

Likelihood means:
- probability an event may occur

-----------------------------------
IMPACT
-----------------------------------

Impact means:
- severity of damage/loss

-----------------------------------
RISK EXAMPLES
-----------------------------------

Examples:
- ransomware risk
- insider threat risk
- data breach risk
- hardware failure risk

-----------------------------------
HIGH RISK
-----------------------------------

High risk commonly involves:
- likely threats
and/or:
- severe impact

-----------------------------------
RISK MANAGEMENT
-----------------------------------

Risk management involves:
- identifying
- evaluating
- reducing risk

-----------------------------------
RISK MITIGATION
-----------------------------------

Mitigation reduces:
- likelihood
or:
- impact

-----------------------------------
COMMON MITIGATION METHODS
-----------------------------------

Examples:
- patching
- MFA
- firewalls
- segmentation
- backups

-----------------------------------
RISK ACCEPTANCE
-----------------------------------

{{{
Additional Context:
Organizations may choose to:
- accept
- transfer
- mitigate
- avoid risk

Source:
NIST Risk Management Framework
https://csrc.nist.gov/
}}}

===================================
VULNERABILITY
===================================

-----------------------------------
VULNERABILITY
-----------------------------------

A vulnerability is:
- a weakness that may be exploited

-----------------------------------
CORE PURPOSE
-----------------------------------

Vulnerabilities create:
- opportunities for attackers

-----------------------------------
COMMON VULNERABILITY EXAMPLES
-----------------------------------

Examples:
- weak passwords
- unpatched systems
- open ports
- insecure configurations
- outdated software

-----------------------------------
SOFTWARE VULNERABILITIES
-----------------------------------

Software flaws may create:
- exploitable weaknesses

-----------------------------------
MISCONFIGURATIONS
-----------------------------------

Improper configurations commonly create:
- vulnerabilities

-----------------------------------
ZERO-DAY
-----------------------------------

{{{
Additional Context:
A zero-day vulnerability is unknown to the vendor/public before discovery or patch availability.

Source:
CISA Vulnerability Guidance
https://www.cisa.gov/
}}}

-----------------------------------
PATCHING
-----------------------------------

Patching helps:
- remediate vulnerabilities

-----------------------------------
VULNERABILITY SCANNING
-----------------------------------

Organizations commonly perform:
- vulnerability scans

-----------------------------------
SCANNING PURPOSE
-----------------------------------

Scanning helps identify:
- weaknesses needing remediation

-----------------------------------
COMMON VULNERABILITY SOURCES
-----------------------------------

Examples:
- outdated firmware
- default credentials
- weak encryption
- exposed services

===================================
EXPLOIT
===================================

-----------------------------------
EXPLOIT
-----------------------------------

An exploit is:
- code/technique used to take advantage of a vulnerability

-----------------------------------
CORE PURPOSE
-----------------------------------

Exploits allow attackers to:
- gain unauthorized access
- execute malicious actions
- compromise systems

-----------------------------------
RELATIONSHIP TO VULNERABILITIES
-----------------------------------

Exploits target:
- vulnerabilities

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

Vulnerability =
Weakness

Exploit =
Method/tool attacking the weakness

-----------------------------------
EXPLOIT EXAMPLES
-----------------------------------

Examples:
- malware exploiting software flaws
- privilege escalation attacks
- remote code execution attacks

-----------------------------------
AUTOMATED EXPLOITS
-----------------------------------

Attackers commonly use:
- exploit kits
- automated malware
- scanning tools

-----------------------------------
REMOTE CODE EXECUTION
-----------------------------------

{{{
Additional Context:
RCE =
Remote Code Execution

RCE vulnerabilities may allow attackers to run code remotely.

Source:
CISA Vulnerability Catalog
https://www.cisa.gov/
}}}

-----------------------------------
PRIVILEGE ESCALATION
-----------------------------------

{{{
Additional Context:
Privilege escalation exploits attempt to gain higher permissions.

Source:
MITRE ATT&CK Framework
https://attack.mitre.org/
}}}

-----------------------------------
PATCHING AND EXPLOITS
-----------------------------------

Patching helps reduce:
- exploitability

-----------------------------------
EXPLOIT MITIGATION
-----------------------------------

Mitigation examples:
- patch management
- IPS
- segmentation
- least privilege

===================================
THREAT
===================================

-----------------------------------
THREAT
-----------------------------------

A threat is:
- anything capable of causing harm

-----------------------------------
CORE PURPOSE
-----------------------------------

Threats represent:
- potential danger to systems/assets

-----------------------------------
THREAT ACTORS
-----------------------------------

Threat actors are:
- individuals/groups causing threats

-----------------------------------
COMMON THREAT ACTORS
-----------------------------------

Examples:
- hackers
- insiders
- nation-state groups
- cybercriminals
- malware authors

-----------------------------------
THREAT EXAMPLES
-----------------------------------

Examples:
- malware
- phishing
- ransomware
- DDoS attacks
- insider abuse

-----------------------------------
NATURAL THREATS
-----------------------------------

Threats may also include:
- floods
- fires
- earthquakes

-----------------------------------
INSIDER THREATS
-----------------------------------

Insider threats originate from:
- authorized/internal users

-----------------------------------
MALWARE
-----------------------------------

Malware is:
- malicious software

-----------------------------------
SOCIAL ENGINEERING
-----------------------------------

{{{
Additional Context:
Social engineering manipulates people into revealing information or performing actions.

Source:
CISA Social Engineering Guidance
https://www.cisa.gov/
}}}

-----------------------------------
PHISHING
-----------------------------------

Phishing attempts:
- steal credentials/information

-----------------------------------
RANSOMWARE
-----------------------------------

Ransomware encrypts:
- victim data/systems

-----------------------------------
THREAT VS VULNERABILITY
-----------------------------------

Threat =
Potential danger

Vulnerability =
Weakness

-----------------------------------
THREAT VS RISK
-----------------------------------

Threat =
Potential harmful event/actor

Risk =
Potential impact if threat succeeds

===================================
CIA TRIAD
===================================

-----------------------------------
CIA TRIAD
-----------------------------------

CIA Triad =
- Confidentiality
- Integrity
- Availability

-----------------------------------
CORE PURPOSE
-----------------------------------

The CIA triad represents:
- foundational information security principles

-----------------------------------
IMPORTANT EXAM IDEA
-----------------------------------

The CIA triad is one of the MOST important security concepts on Network+.

===================================
CONFIDENTIALITY
===================================

-----------------------------------
CONFIDENTIALITY
-----------------------------------

Confidentiality protects:
- sensitive information from unauthorized access

-----------------------------------
CONFIDENTIALITY GOAL
-----------------------------------

Only authorized users should:
- access protected data

-----------------------------------
CONFIDENTIALITY EXAMPLES
-----------------------------------

Examples:
- encryption
- permissions
- MFA
- access controls

-----------------------------------
CONFIDENTIALITY VIOLATIONS
-----------------------------------

Examples:
- data leaks
- unauthorized viewing
- credential theft

===================================
INTEGRITY
===================================

-----------------------------------
INTEGRITY
-----------------------------------

Integrity ensures:
- data remains accurate/unmodified

-----------------------------------
INTEGRITY GOAL
-----------------------------------

Data should not be:
- improperly altered
- tampered with

-----------------------------------
INTEGRITY EXAMPLES
-----------------------------------

Examples:
- hashing
- digital signatures
- checksums
- version control

-----------------------------------
INTEGRITY VIOLATIONS
-----------------------------------

Examples:
- unauthorized modification
- tampering
- corrupted records

===================================
AVAILABILITY
===================================

-----------------------------------
AVAILABILITY
-----------------------------------

Availability ensures:
- systems/data remain accessible when needed

-----------------------------------
AVAILABILITY GOAL
-----------------------------------

Authorized users should:
- reliably access systems/resources

-----------------------------------
AVAILABILITY EXAMPLES
-----------------------------------

Examples:
- redundancy
- backups
- load balancing
- failover systems

-----------------------------------
AVAILABILITY VIOLATIONS
-----------------------------------

Examples:
- DDoS attacks
- outages
- ransomware downtime
- hardware failure

-----------------------------------
CIA TRIAD RELATIONSHIPS
-----------------------------------

Examples:

Encryption supports:
- confidentiality

Hashing supports:
- integrity

Redundancy supports:
- availability

-----------------------------------
BALANCING THE CIA TRIAD
-----------------------------------

Security controls may affect:
- multiple CIA principles simultaneously

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Risk = potential loss from threats exploiting vulnerabilities
- Vulnerability = weakness
- Exploit = attack method/code
- Threat = potential danger
- CIA triad = confidentiality, integrity, availability
- Encryption supports confidentiality
- Hashing supports integrity
- Redundancy supports availability
- Patching reduces vulnerabilities
- Exploits target vulnerabilities

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"An outdated server contains an unpatched weakness."

Answer:
Vulnerability

-----------------------------------

Scenario:
"Attack code targets a software flaw."

Answer:
Exploit

-----------------------------------

Scenario:
"A hacker group attempts ransomware attacks."

Answer:
Threat/threat actor

-----------------------------------

Scenario:
"A company estimates possible financial damage from attacks."

Answer:
Risk assessment

-----------------------------------

Scenario:
"A company encrypts customer records."

Answer:
Confidentiality

-----------------------------------

Scenario:
"A system uses hashing to detect file modification."

Answer:
Integrity

-----------------------------------

Scenario:
"A company deploys redundant servers to reduce downtime."

Answer:
Availability

-----------------------------------

Scenario:
"A phishing email steals credentials."

Answer:
Threat/social engineering

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Confusing threat and vulnerability.

Threat:
- potential danger

Vulnerability:
- weakness

-----------------------------------

Trap:
Confusing exploit and vulnerability.

Vulnerability:
- weakness

Exploit:
- attack method/tool

-----------------------------------

Trap:
Thinking encryption supports integrity only.

Wrong.

Encryption primarily supports:
- confidentiality

-----------------------------------

Trap:
Thinking hashing provides confidentiality.

Wrong.

Hashing primarily supports:
- integrity

-----------------------------------

Trap:
Confusing risk and threat.

Threat:
- possible harmful event/actor

Risk:
- potential impact if threat succeeds

-----------------------------------

Trap:
Thinking availability only means uptime.

Wrong.

Availability also includes:
- accessibility
- reliability
- recoverability

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Threat =
Danger

Vulnerability =
Weakness

Exploit =
Attack method

Risk =
Potential damage

CIA =
Confidentiality, Integrity, Availability

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What is a vulnerability?

A:
A weakness that may be exploited.

-----------------------------------

Q:
What is an exploit?

A:
A method/tool used to attack a vulnerability.

-----------------------------------

Q:
What is a threat?

A:
Anything capable of causing harm.

-----------------------------------

Q:
What is risk?

A:
Potential for loss when threats exploit vulnerabilities.

-----------------------------------

Q:
What does the CIA triad stand for?

A:
Confidentiality, Integrity, Availability.

-----------------------------------

Q:
What does confidentiality protect?

A:
Sensitive data from unauthorized access.

-----------------------------------

Q:
What does integrity ensure?

A:
Data accuracy and protection from unauthorized modification.

-----------------------------------

Q:
What does availability ensure?

A:
Systems/data remain accessible when needed.

-----------------------------------

Q:
What security concept does encryption primarily support?

A:
Confidentiality.

-----------------------------------

Q:
What security concept does hashing primarily support?

A:
Integrity.