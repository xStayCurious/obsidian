========================
SSID, BSSID, and ESSID
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Section 2.3: Wireless Devices and Technologies
Pages 45–50
0 1

-----------------------------------
SSID
-----------------------------------

SSID =
Service Set Identifier

-----------------------------------
CORE PURPOSE
-----------------------------------

An SSID identifies:
- a wireless network

It is essentially:
- the WiFi network name

-----------------------------------
WHAT USERS SEE
-----------------------------------

When users scan for WiFi networks:
- they see SSIDs

Examples:
- HomeWiFi
- CoffeeShopGuest
- CompanySecure
- Apartment-5G

-----------------------------------
WHY SSIDS EXIST
-----------------------------------

SSIDs allow:
- users to identify networks
- clients to connect to the correct WLAN
- administrators to organize wireless access

-----------------------------------
SSID CHARACTERISTICS
-----------------------------------

The SSID:
- is configured on an access point
- can be broadcast publicly
- may be shared by multiple APs
- helps clients discover networks

-----------------------------------
SSID BROADCAST
-----------------------------------

Wireless APs commonly:
- broadcast SSIDs

Broadcasting allows:
- devices to easily discover networks

-----------------------------------
HIDDEN SSIDS
-----------------------------------

Some networks disable:
- SSID broadcast

This creates:
- a hidden SSID network

-----------------------------------
HIDDEN SSID EXAM IDEA
-----------------------------------

A hidden SSID:
- is not openly advertised
but:
- can still often be discovered

-----------------------------------
IMPORTANT SECURITY FACT
-----------------------------------

Hiding an SSID:
- is NOT strong security

It may:
- reduce casual visibility
but:
- does not meaningfully secure the network

-----------------------------------
SSID LENGTH
-----------------------------------

{{{
Additional Context:
IEEE 802.11 SSIDs can be up to 32 characters long.

Source:
IEEE 802.11 Standard
https://standards.ieee.org/
}}}

-----------------------------------
CASE SENSITIVITY
-----------------------------------

{{{
Additional Context:
SSIDs are case-sensitive.

Source:
Cisco Wireless Configuration Guide
https://www.cisco.com/
}}}

-----------------------------------
MULTIPLE SSIDS
-----------------------------------

One AP may broadcast:
- multiple SSIDs

-----------------------------------
WHY MULTIPLE SSIDS ARE USED
-----------------------------------

Organizations commonly separate:
- employee traffic
- guest traffic
- IoT traffic
- management traffic

using:
- different SSIDs

-----------------------------------
EXAMPLE MULTI-SSID DESIGN
-----------------------------------

CompanySecure
- employee devices

CompanyGuest
- visitors

CompanyIoT
- cameras/sensors

-----------------------------------
SSID AND VLANS
-----------------------------------

SSIDs are commonly mapped to:
- VLANs

-----------------------------------
SSID/VLAN RELATIONSHIP
-----------------------------------

Different SSIDs may place users into:
- different VLANs
- different security policies
- different access levels

-----------------------------------
EXAM SCENARIO
-----------------------------------

Scenario:
A company wants guests isolated from internal users.

Common solution:
- separate guest SSID
- separate guest VLAN

-----------------------------------
BSSID
-----------------------------------

BSSID =
Basic Service Set Identifier

-----------------------------------
BSSID PURPOSE
-----------------------------------

A BSSID uniquely identifies:
- a specific access point radio

-----------------------------------
BSSID CHARACTERISTICS
-----------------------------------

The BSSID is usually:
- the MAC address of the AP radio

-----------------------------------
WHY BSSIDS MATTER
-----------------------------------

Many APs may broadcast:
- the same SSID

But:
- each AP still has a unique BSSID

-----------------------------------
SSID VS BSSID
-----------------------------------

SSID:
- wireless network name

BSSID:
- specific AP/radio identifier

-----------------------------------
ROAMING
-----------------------------------

Wireless clients use BSSID information when:
- roaming between APs

-----------------------------------
ROAMING PURPOSE
-----------------------------------

Roaming allows:
- clients to move between APs
while:
- remaining connected to the same wireless network

-----------------------------------
ESSID
-----------------------------------

ESSID =
Extended Service Set Identifier

-----------------------------------
ESSID PURPOSE
-----------------------------------

The guide describes ESSID as:
- a shared wireless network name
across:
- interconnected APs

-----------------------------------
WHY ESSID EXISTS
-----------------------------------

ESSIDs allow:
- larger wireless deployments
- seamless roaming
- broader wireless coverage

-----------------------------------
ESSID EXAM IDEA
-----------------------------------

Multiple APs using the same wireless network name:
- are part of an ESS/ESSID deployment

-----------------------------------
ESS
-----------------------------------

ESS =
Extended Service Set

-----------------------------------
ESS CHARACTERISTICS
-----------------------------------

An ESS consists of:
- multiple APs
- connected together
- sharing the same SSID/ESSID

-----------------------------------
WHY ESS MATTERS
-----------------------------------

ESS deployments:
- improve wireless coverage
- support roaming
- reduce dead zones

-----------------------------------
WIRELESS CLIENT ASSOCIATION
-----------------------------------

Wireless clients:
- associate to APs using SSIDs/BSSIDs

-----------------------------------
ASSOCIATION PROCESS
-----------------------------------

General wireless process:
1. Client scans for SSIDs
2. Client selects network
3. Authentication occurs
4. Association occurs
5. Client joins WLAN

-----------------------------------
OPEN NETWORKS
-----------------------------------

Open wireless networks:
- may still use SSIDs
but:
- do not require authentication

-----------------------------------
SECURE NETWORKS
-----------------------------------

Secure wireless networks:
- use SSIDs plus authentication/encryption

Examples:
- WPA2
- WPA3

-----------------------------------
COMMON SSID NAMING PRACTICES
-----------------------------------

Organizations commonly use:
- descriptive names
- department names
- guest labels
- location labels

-----------------------------------
BAD SSID PRACTICES
-----------------------------------

{{{
Additional Context:
Avoid exposing sensitive information in SSIDs such as:
- company security details
- device types
- physical locations
- administrator names

Source:
Cisco Wireless Security Best Practices
https://www.cisco.com/
}}}

-----------------------------------
GUEST SSIDS
-----------------------------------

Guest SSIDs commonly:
- isolate guest users
- limit internal access
- use captive portals

-----------------------------------
CAPTIVE PORTALS
-----------------------------------

Captive portals may:
- require login
- require agreement acceptance
- require payment
before:
- granting network access

-----------------------------------
WIRELESS SURVEYS
-----------------------------------

{{{
Additional Context:
Wireless surveys commonly analyze:
- SSIDs
- BSSIDs
- channels
- signal strength
- roaming behavior

Source:
Ekahau Wireless Survey Concepts
https://www.ekahau.com/
}}}

-----------------------------------
COMMON NETWORK+ EXAM FACTS
-----------------------------------

Very important exam facts:

- SSID = network name
- BSSID = AP/radio MAC identifier
- ESSID = shared SSID across multiple APs
- Hidden SSID is NOT strong security
- Multiple SSIDs may map to different VLANs
- Roaming relies on multiple APs sharing the same ESSID

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A wireless client sees several available WiFi names."

Answer:
SSIDs

-----------------------------------

Scenario:
"A technician needs to identify the exact AP a client is connected to."

Answer:
BSSID

-----------------------------------

Scenario:
"A company wants seamless roaming across multiple APs."

Answer:
ESS/ESSID

-----------------------------------

Scenario:
"A company creates separate employee and guest wireless networks."

Answer:
Multiple SSIDs

-----------------------------------

Scenario:
"A company hides the wireless network name."

Answer:
Hidden SSID

-----------------------------------

Scenario:
"A company wants guest traffic separated from internal traffic."

Answer:
Guest SSID mapped to separate VLAN/network

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking SSID and BSSID are the same.

Wrong.

SSID:
- network name

BSSID:
- AP/radio identifier

-----------------------------------

Trap:
Thinking hidden SSIDs provide strong security.

Wrong.

Hidden SSIDs:
- are easily discoverable with wireless tools

-----------------------------------

Trap:
Thinking one AP can only broadcast one SSID.

Wrong.

APs commonly broadcast:
- multiple SSIDs

-----------------------------------

Trap:
Thinking ESSID identifies one AP.

Wrong.

ESSID:
- shared network identity across multiple APs

-----------------------------------

Trap:
Thinking SSIDs provide encryption.

Wrong.

SSIDs:
- identify networks
Encryption/authentication provide security.

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

SSID =
Network name

BSSID =
Specific AP MAC

ESSID =
Shared network across many APs

Hidden SSID =
Obscurity, not security

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does SSID stand for?

A:
Service Set Identifier.

-----------------------------------

Q:
What is an SSID?

A:
The wireless network name.

-----------------------------------

Q:
What does BSSID stand for?

A:
Basic Service Set Identifier.

-----------------------------------

Q:
What is a BSSID usually?

A:
The MAC address of an AP radio.

-----------------------------------

Q:
What does ESSID stand for?

A:
Extended Service Set Identifier.

-----------------------------------

Q:
What is the purpose of an ESSID?

A:
Allow multiple APs to share one wireless network identity.

-----------------------------------

Q:
Can one AP broadcast multiple SSIDs?

A:
Yes.

-----------------------------------

Q:
Does hiding an SSID provide strong security?

A:
No.

-----------------------------------

Q:
What commonly happens when different SSIDs are used?

A:
Users are separated into different VLANs or policies.

-----------------------------------

Q:
What allows wireless roaming between APs?

A:
Multiple APs sharing the same ESSID/SSID.

-----------------------------------

Q:
What identifies a specific AP rather than the wireless network itself?

A:
BSSID.