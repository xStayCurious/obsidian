========================
Baseline Metrics
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 3 — Network Operations
Section 3.2: Monitoring and Performance
Pages 57–59
0

-----------------------------------
BASELINE METRICS
-----------------------------------

Baseline metrics are:
- measurements representing normal network/system performance

-----------------------------------
CORE PURPOSE
-----------------------------------

Baselines help administrators:
- identify abnormal behavior
- troubleshoot problems
- monitor performance trends
- detect anomalies
- support capacity planning

-----------------------------------
WHY BASELINES MATTER
-----------------------------------

Without baselines:
- it is difficult to determine what is "normal"

-----------------------------------
BASELINE EXAMPLE
-----------------------------------

Example:
If a network normally uses:
- 30% bandwidth

but suddenly reaches:
- 95%

administrators can recognize:
- abnormal activity or congestion

-----------------------------------
NORMAL OPERATING CONDITIONS
-----------------------------------

Baselines represent:
- expected operational behavior during normal conditions

-----------------------------------
WHAT BASELINES MEASURE
-----------------------------------

Common baseline metrics:
- bandwidth utilization
- latency
- CPU usage
- memory usage
- uptime
- packet loss
- interface errors
- throughput
- response times

-----------------------------------
BANDWIDTH UTILIZATION
-----------------------------------

Bandwidth utilization measures:
- how much network capacity is being used

-----------------------------------
WHY BANDWIDTH BASELINES MATTER
-----------------------------------

High bandwidth usage may indicate:
- congestion
- large transfers
- malware activity
- abnormal traffic spikes

-----------------------------------
LATENCY
-----------------------------------

Latency measures:
- communication delay

-----------------------------------
LATENCY BASELINE PURPOSE
-----------------------------------

Latency baselines help identify:
- slow connections
- routing issues
- WAN problems
- congestion

-----------------------------------
CPU USAGE
-----------------------------------

CPU usage measures:
- processor utilization on devices/systems

-----------------------------------
HIGH CPU RISKS
-----------------------------------

Excessive CPU usage may cause:
- slow performance
- instability
- dropped packets
- degraded services

-----------------------------------
MEMORY USAGE
-----------------------------------

Memory usage measures:
- RAM consumption

-----------------------------------
HIGH MEMORY RISKS
-----------------------------------

Excessive memory use may lead to:
- crashes
- instability
- poor performance

-----------------------------------
PACKET LOSS
-----------------------------------

Packet loss occurs when:
- packets fail to reach their destination

-----------------------------------
PACKET LOSS EFFECTS
-----------------------------------

Packet loss may cause:
- poor VoIP quality
- slow applications
- retransmissions
- unstable communication

-----------------------------------
THROUGHPUT
-----------------------------------

Throughput measures:
- actual successful data transfer rates

-----------------------------------
THROUGHPUT VS BANDWIDTH
-----------------------------------

Bandwidth:
- theoretical maximum capacity

Throughput:
- actual achieved transfer rate

-----------------------------------
ERROR RATES
-----------------------------------

Baseline monitoring may track:
- CRC errors
- interface errors
- dropped packets

-----------------------------------
UPTIME
-----------------------------------

Uptime measures:
- how long systems remain operational

-----------------------------------
UPTIME BASELINES
-----------------------------------

Unexpected uptime changes may indicate:
- crashes
- reboots
- outages

-----------------------------------
TREND ANALYSIS
-----------------------------------

Baselines support:
- trend analysis

-----------------------------------
TREND ANALYSIS PURPOSE
-----------------------------------

Trend analysis helps identify:
- gradual degradation
- capacity issues
- recurring problems
- long-term growth

-----------------------------------
CAPACITY PLANNING
-----------------------------------

Baseline metrics help:
- predict future resource needs

-----------------------------------
CAPACITY EXAMPLE
-----------------------------------

Example:
Bandwidth usage increases steadily every month.

Administrators may determine:
- WAN upgrades are needed soon

-----------------------------------
ANOMALY DETECTION
-----------------------------------

Baselines help identify:
- abnormal events

-----------------------------------
ANOMALY EXAMPLES
-----------------------------------

Examples:
- sudden traffic spikes
- unusual outbound traffic
- high CPU utilization
- abnormal latency

-----------------------------------
SECURITY MONITORING
-----------------------------------

Baselines may help detect:
- malware activity
- DDoS attacks
- unauthorized transfers
- compromised systems

-----------------------------------
DDoS DETECTION
-----------------------------------

{{{
Additional Context:
Baseline traffic analysis is commonly used to identify volumetric DDoS attacks.

Source:
Cisco DDoS Detection Concepts
https://www.cisco.com/
}}}

-----------------------------------
MONITORING TOOLS
-----------------------------------

Baseline metrics are commonly gathered using:
- SNMP
- flow monitoring
- packet analysis
- monitoring platforms

-----------------------------------
SNMP
-----------------------------------

SNMP commonly monitors:
- CPU usage
- memory usage
- interface statistics
- uptime

-----------------------------------
FLOW DATA
-----------------------------------

Flow monitoring commonly analyzes:
- bandwidth patterns
- top talkers
- communication trends

-----------------------------------
THRESHOLDS
-----------------------------------

Monitoring systems commonly use:
- thresholds

-----------------------------------
THRESHOLD PURPOSE
-----------------------------------

Thresholds trigger alerts when:
- metrics exceed acceptable ranges

-----------------------------------
THRESHOLD EXAMPLES
-----------------------------------

Examples:
- CPU > 90%
- bandwidth > 85%
- latency spike
- packet loss increase

-----------------------------------
SEASONAL PATTERNS
-----------------------------------

{{{
Additional Context:
Some environments experience predictable traffic spikes during:
- business hours
- backups
- patch windows
- holidays

Source:
Microsoft Network Monitoring Best Practices
https://learn.microsoft.com/
}}}

-----------------------------------
BASELINE COLLECTION
-----------------------------------

Good baselines should be collected:
- over time
- during normal operations
- across varying workloads

-----------------------------------
WHY LONG-TERM COLLECTION MATTERS
-----------------------------------

Short sampling periods may:
- misrepresent normal behavior

-----------------------------------
FALSE POSITIVES
-----------------------------------

Poor baseline development may create:
- false alarms
- unnecessary troubleshooting

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- Baselines define normal performance
- Baselines help detect anomalies
- Baselines support troubleshooting
- Bandwidth utilization measures network usage
- Latency measures delay
- Throughput measures actual transfer rates
- Packet loss affects communication quality
- Thresholds trigger alerts
- Trend analysis supports capacity planning

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A network suddenly experiences abnormal traffic spikes."

Answer:
Compare against baseline metrics

-----------------------------------

Scenario:
"A company monitors average WAN latency over time."

Answer:
Baseline monitoring

-----------------------------------

Scenario:
"A network administrator predicts future bandwidth upgrades."

Answer:
Capacity planning using baselines

-----------------------------------

Scenario:
"A monitoring system alerts when CPU exceeds 90%."

Answer:
Threshold alerting

-----------------------------------

Scenario:
"A security analyst notices outbound traffic far above normal."

Answer:
Anomaly detection using baselines

-----------------------------------

Scenario:
"A VoIP deployment experiences intermittent quality problems."

Answer:
Check latency and packet loss baselines

-----------------------------------

Scenario:
"A company tracks average network throughput trends."

Answer:
Baseline metric analysis

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking bandwidth and throughput are identical.

Wrong.

Bandwidth:
- theoretical capacity

Throughput:
- actual transfer rate

-----------------------------------

Trap:
Thinking baselines only help troubleshooting.

Wrong.

Baselines also support:
- security monitoring
- capacity planning
- trend analysis

-----------------------------------

Trap:
Thinking one-time measurements create accurate baselines.

Wrong.

Baselines require:
- long-term normal data collection

-----------------------------------

Trap:
Thinking packet loss only affects downloads.

Wrong.

Packet loss affects:
- VoIP
- video
- applications
- reliability

-----------------------------------

Trap:
Thinking high CPU usage always means hardware failure.

Wrong.

High CPU may result from:
- traffic spikes
- attacks
- inefficient configurations
- heavy workloads

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

Baseline =
Normal behavior

Threshold =
Alert trigger

Bandwidth =
Maximum capacity

Throughput =
Actual speed

Latency =
Delay

Packet loss =
Missing packets

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What are baseline metrics?

A:
Measurements representing normal system/network performance.

-----------------------------------

Q:
Why are baseline metrics important?

A:
They help identify abnormal behavior and troubleshoot problems.

-----------------------------------

Q:
What does bandwidth utilization measure?

A:
How much network capacity is being used.

-----------------------------------

Q:
What does latency measure?

A:
Communication delay.

-----------------------------------

Q:
What does throughput measure?

A:
Actual successful data transfer rates.

-----------------------------------

Q:
What is packet loss?

A:
Packets failing to reach their destination.

-----------------------------------

Q:
What is the difference between bandwidth and throughput?

A:
Bandwidth is theoretical capacity; throughput is actual transfer speed.

-----------------------------------

Q:
What are thresholds used for?

A:
Trigger alerts when metrics exceed acceptable ranges.

-----------------------------------

Q:
What is trend analysis?

A:
Monitoring changes over time to identify growth or degradation.

-----------------------------------

Q:
What can baseline metrics help detect?

A:
Congestion, attacks, anomalies, and performance issues.