========================
Wireless Channels
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 2.3: Wireless Devices and Technologies
Pages 45–50
0 1

-----------------------------------
WIRELESS CHANNELS
-----------------------------------

Wireless channels are:
- subdivisions of wireless frequency bands

Channels allow:
- multiple wireless devices and networks
to communicate simultaneously
without all using the exact same frequency space.

-----------------------------------
CORE PURPOSE
-----------------------------------

Channels help:
- organize wireless communication
- reduce interference
- improve wireless performance
- separate nearby wireless traffic

-----------------------------------
WHY CHANNELS MATTER
-----------------------------------

Wireless communication uses:
- shared radio frequencies

If too many devices or APs use overlapping frequencies:
- interference increases
- retransmissions increase
- latency increases
- throughput decreases
- reliability decreases

-----------------------------------
CHANNELS AND FREQUENCY BANDS
-----------------------------------

Wireless channels exist inside:
- 2.4 GHz
- 5 GHz
- 6 GHz

Each frequency band contains:
- multiple possible channels

-----------------------------------
2.4 GHz CHANNELS
-----------------------------------

2.4 GHz:
- has fewer channels
- has more overlap
- is more congested

-----------------------------------
2.4 GHz OVERLAP
-----------------------------------

In 2.4 GHz:
- many channels overlap with neighboring channels

This overlap can create:
- adjacent-channel interference

-----------------------------------
NON-OVERLAPPING CHANNELS
-----------------------------------

The most important Network+ fact:

In the United States, the commonly used non-overlapping 2.4 GHz channels are:
- 1
- 6
- 11

-----------------------------------
WHY 1, 6, AND 11 ARE IMPORTANT
-----------------------------------

Channels 1, 6, and 11:
- do not overlap each other significantly

Using these channels:
- reduces interference
- improves AP coexistence
- improves stability

-----------------------------------
EXAM SCENARIO
-----------------------------------

Scenario:
Three nearby APs must minimize interference in 2.4 GHz.

Best answer:
Configure:
- AP1 = channel 1
- AP2 = channel 6
- AP3 = channel 11

-----------------------------------
CHANNEL INTERFERENCE
-----------------------------------

Two major interference types:

1. Co-channel interference
2. Adjacent-channel interference

-----------------------------------
CO-CHANNEL INTERFERENCE
-----------------------------------

Co-channel interference occurs when:
- nearby APs use the same channel

-----------------------------------
CO-CHANNEL EFFECTS
-----------------------------------

Devices:
- must share airtime
- compete for transmission opportunities

This reduces:
- overall performance

-----------------------------------
ADJACENT-CHANNEL INTERFERENCE
-----------------------------------

Adjacent-channel interference occurs when:
- overlapping channels interfere with each other

This is usually:
- worse than co-channel interference

-----------------------------------
WHY ADJACENT INTERFERENCE IS BAD
-----------------------------------

Overlapping channels:
- corrupt wireless communication
- increase retransmissions
- degrade throughput severely

-----------------------------------
CHANNEL WIDTH
-----------------------------------

Channel width refers to:
- how much frequency space a channel occupies

The guide references:
- 40 MHz
- 80 MHz

-----------------------------------
WIDER CHANNELS
-----------------------------------

Wider channels provide:
- higher throughput potential
- more bandwidth

-----------------------------------
WIDER CHANNEL TRADEOFF
-----------------------------------

Wider channels also:
- consume more spectrum
- increase interference risk
- reduce the number of usable channels

-----------------------------------
NARROWER CHANNELS
-----------------------------------

Narrower channels:
- reduce interference risk
- improve coexistence in dense environments

But:
- provide lower throughput

-----------------------------------
EXAM LOGIC FOR CHANNEL WIDTH
-----------------------------------

Dense environment:
- narrower channels may perform better

Clean RF environment:
- wider channels may improve throughput

-----------------------------------
5 GHz CHANNELS
-----------------------------------

5 GHz:
- offers many more channels than 2.4 GHz
- experiences less congestion
- supports higher throughput

-----------------------------------
WHY 5 GHz IS EASIER TO SCALE
-----------------------------------

Because 5 GHz has:
- more non-overlapping channels

it supports:
- more nearby APs with less interference

-----------------------------------
DFS CHANNELS
-----------------------------------

DFS =
Dynamic Frequency Selection

-----------------------------------
DFS PURPOSE
-----------------------------------

DFS channels help avoid interference with:
- radar systems

-----------------------------------
DFS OPERATION
-----------------------------------

If radar is detected:
- the AP must move to another channel

-----------------------------------
802.11h
-----------------------------------

The guide associates 802.11h with:
- DFS
- TPC
- regulatory compliance

-----------------------------------
TPC
-----------------------------------

TPC =
Transmit Power Control

-----------------------------------
TPC PURPOSE
-----------------------------------

TPC adjusts wireless power levels to:
- reduce interference
- comply with regulations
- improve RF efficiency

-----------------------------------
6 GHz CHANNELS
-----------------------------------

6 GHz provides:
- additional spectrum
- more available channels
- reduced congestion
- lower latency potential

-----------------------------------
6 GHz ADVANTAGE
-----------------------------------

The major advantage of 6 GHz:
- much cleaner RF space
- fewer legacy devices
- less interference

-----------------------------------
BAND STEERING
-----------------------------------

Band steering:
- encourages capable devices
to use:
- 5 GHz
or:
- 6 GHz

instead of:
- congested 2.4 GHz

-----------------------------------
AUTOMATIC CHANNEL SELECTION
-----------------------------------

Many APs:
- automatically choose channels
based on:
- detected interference
- neighboring AP activity

-----------------------------------
CHANNEL PLANNING
-----------------------------------

Good wireless channel planning:
- reduces interference
- improves roaming
- improves throughput
- improves client stability

-----------------------------------
POOR CHANNEL PLANNING
-----------------------------------

Poor channel planning can cause:
- dropped connections
- slow wireless speeds
- retransmissions
- unstable roaming
- poor VoIP quality

-----------------------------------
HIGH-DENSITY ENVIRONMENTS
-----------------------------------

High-density wireless environments include:
- stadiums
- schools
- airports
- offices
- apartment complexes

These environments require:
- careful channel planning

-----------------------------------
WIRELESS ROAMING
-----------------------------------

Improper channel planning can negatively affect:
- roaming performance

Clients may:
- stay connected to weak APs
- fail to roam efficiently

-----------------------------------
EXAM-RELEVANT CHANNEL FACTS
-----------------------------------

Very important exam facts:

- 2.4 GHz has more interference
- 5 GHz has more channels
- 1, 6, and 11 are non-overlapping in 2.4 GHz
- wider channels increase throughput potential
- wider channels also increase interference risk
- DFS protects radar systems
- 802.11h relates to DFS and TPC
- 6 GHz supports cleaner spectrum and higher capacity

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A wireless deployment suffers from heavy 2.4 GHz interference."

Best answer:
Use channels 1, 6, and 11 properly
or move clients to 5 GHz.

-----------------------------------

Scenario:
"A stadium WiFi deployment requires many APs near each other."

Best answer:
Careful channel planning with more non-overlapping channels.

-----------------------------------

Scenario:
"An AP automatically changes channels after detecting radar."

Answer:
DFS.

-----------------------------------

Scenario:
"A company wants to move dual-band clients away from congested 2.4 GHz."

Answer:
Band steering.

-----------------------------------

Scenario:
"A clean RF environment needs maximum throughput."

Answer:
Use wider channels.

-----------------------------------

Scenario:
"A dense office environment suffers interference from wide channels."

Answer:
Use narrower channel widths.

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking wider channels are always better.

Wrong.

Wider channels:
- increase throughput
but:
- increase interference risk

-----------------------------------

Trap:
Thinking all 2.4 GHz channels are independent.

Wrong.

Most overlap heavily.

-----------------------------------

Trap:
Thinking co-channel interference is always worse than adjacent-channel interference.

Wrong.

Adjacent-channel interference is often more damaging.

-----------------------------------

Trap:
Thinking 5 GHz always has better range.

Wrong.

5 GHz:
- usually has shorter range than 2.4 GHz

-----------------------------------

Trap:
Thinking DFS is primarily for improving speed.

Wrong.

DFS exists primarily to:
- avoid radar interference

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

1 / 6 / 11 =
2.4 GHz non-overlapping channels

2.4 GHz =
More range
More interference

5 GHz =
More channels
Higher throughput

6 GHz =
Cleaner spectrum

DFS =
Radar avoidance

TPC =
Power adjustment

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What are wireless channels?

A:
Subdivisions of wireless frequency bands used for communication.

-----------------------------------

Q:
Why are wireless channels important?

A:
They reduce interference and organize wireless communication.

-----------------------------------

Q:
Which 2.4 GHz channels are commonly non-overlapping in the US?

A:
1, 6, and 11.

-----------------------------------

Q:
What is co-channel interference?

A:
Interference from nearby APs using the same channel.

-----------------------------------

Q:
What is adjacent-channel interference?

A:
Interference caused by overlapping channels.

-----------------------------------

Q:
What is channel width?

A:
The amount of frequency spectrum a channel occupies.

-----------------------------------

Q:
What is the tradeoff of wider channels?

A:
Higher throughput but greater interference risk.

-----------------------------------

Q:
Why does 5 GHz scale better than 2.4 GHz?

A:
It has more non-overlapping channels.

-----------------------------------

Q:
What does DFS stand for?

A:
Dynamic Frequency Selection.

-----------------------------------

Q:
What is the purpose of DFS?

A:
Avoid interference with radar systems.

-----------------------------------

Q:
What does TPC stand for?

A:
Transmit Power Control.

-----------------------------------

Q:
What is the purpose of TPC?

A:
Adjust transmit power to reduce interference and meet regulations.

-----------------------------------

Q:
What is band steering?

A:
Moving capable clients to 5 GHz or 6 GHz bands.

-----------------------------------

Q:
What major advantage does 6 GHz provide?

A:
Cleaner spectrum and greater capacity.