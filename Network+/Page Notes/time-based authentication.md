========================
Time-Based Authentication
TOTP / OTP Authentication
Network+ Review
========================

Primary Source:
Andrew Ramdayal Network+ N10-009 Last Minute Cram
Chapter 4 — Network Security
Section 4.1: Security Concepts
Pages 62–66


-----------------------------------
TIME-BASED AUTHENTICATION
-----------------------------------

Time-based authentication commonly refers to:
- temporary authentication codes that expire after a short time period

-----------------------------------
CORE PURPOSE
-----------------------------------

Time-based authentication helps improve:
- account security
- identity verification
- resistance to stolen passwords

-----------------------------------
WHY TIME-BASED AUTHENTICATION EXISTS
-----------------------------------

Passwords alone are vulnerable to:
- phishing
- credential theft
- brute-force attacks
- password reuse attacks

Time-based authentication adds:
- an additional authentication factor

-----------------------------------
MFA
-----------------------------------

Time-based authentication is commonly part of:
- MFA

-----------------------------------
MFA
-----------------------------------

MFA =
Multifactor Authentication

-----------------------------------
MFA PURPOSE
-----------------------------------

MFA requires:
- multiple authentication factors

-----------------------------------
AUTHENTICATION FACTORS
-----------------------------------

Common categories:
- something you know
- something you have
- something you are

-----------------------------------
TIME-BASED TOKENS
-----------------------------------

Time-based systems commonly use:
- temporary codes/tokens

-----------------------------------
OTP
-----------------------------------

OTP =
One-Time Password

-----------------------------------
OTP PURPOSE
-----------------------------------

OTPs are:
- valid for one login/session
or:
- limited time periods

-----------------------------------
TOTP
-----------------------------------

TOTP =
Time-Based One-Time Password

-----------------------------------
TOTP PURPOSE
-----------------------------------

TOTPs generate:
- temporary authentication codes
based on:
- time synchronization

-----------------------------------
HOW TOTP WORKS
-----------------------------------

Typical process:

1. User enrolls authenticator
2. Shared secret is established
3. Device/app generates temporary code
4. User enters code
5. Server validates code

-----------------------------------
TIME WINDOWS
-----------------------------------

TOTP codes commonly expire:
- every 30–60 seconds

-----------------------------------
WHY SHORT EXPIRATION MATTERS
-----------------------------------

Short expiration reduces usefulness of:
- stolen codes

-----------------------------------
AUTHENTICATOR APPS
-----------------------------------

Common authenticator apps:
- Google Authenticator
- Microsoft Authenticator
- Authy

-----------------------------------
SMARTPHONES
-----------------------------------

Time-based authentication commonly uses:
- smartphones

-----------------------------------
SHARED SECRET
-----------------------------------

TOTP systems commonly rely on:
- shared secrets between client/server

-----------------------------------
TIME SYNCHRONIZATION
-----------------------------------

TOTP requires:
- synchronized time

-----------------------------------
WHY TIME MATTERS
-----------------------------------

Incorrect clocks may cause:
- authentication failures

-----------------------------------
NTP
-----------------------------------

{{{
Additional Context:
Systems commonly use NTP to maintain accurate time synchronization.

Source:
NTP Documentation
https://www.ntp.org/
}}}

-----------------------------------
HOTP
-----------------------------------

{{{
Additional Context:
HOTP =
HMAC-Based One-Time Password

HOTP uses counters instead of time.

Source:
RFC 4226 HOTP
https://datatracker.ietf.org/
}}}

-----------------------------------
TOTP VS HOTP
-----------------------------------

TOTP:
- time-based

HOTP:
- counter-based

-----------------------------------
SMS AUTHENTICATION
-----------------------------------

{{{
Additional Context:
Some MFA systems send OTPs via SMS.

Source:
NIST Digital Identity Guidelines
https://csrc.nist.gov/
}}}

-----------------------------------
SMS RISKS
-----------------------------------

SMS-based authentication may be vulnerable to:
- SIM swapping
- interception
- social engineering

-----------------------------------
APP-BASED MFA
-----------------------------------

Authenticator apps are generally considered:
- more secure than SMS OTP

-----------------------------------
PUSH AUTHENTICATION
-----------------------------------

{{{
Additional Context:
Some MFA systems use push notifications instead of manual OTP entry.

Source:
Microsoft MFA Documentation
https://learn.microsoft.com/
}}}

-----------------------------------
HARDWARE TOKENS
-----------------------------------

{{{
Additional Context:
Hardware tokens may generate time-based authentication codes.

Examples:
- RSA SecurID
- YubiKey

Source:
Vendor Documentation
}}}

-----------------------------------
BIOMETRICS AND MFA
-----------------------------------

Time-based authentication may combine with:
- biometrics
- passwords
- smart cards

-----------------------------------
ACCOUNT SECURITY BENEFITS
-----------------------------------

Time-based authentication helps reduce risk from:
- stolen passwords
- password reuse
- credential stuffing

-----------------------------------
PHISHING RISKS
-----------------------------------

TOTP codes may still be vulnerable to:
- real-time phishing attacks

-----------------------------------
MFA FATIGUE
-----------------------------------

{{{
Additional Context:
Attackers may repeatedly trigger MFA requests hoping users approve them accidentally.

Source:
Microsoft MFA Attack Guidance
https://learn.microsoft.com/
}}}

-----------------------------------
ZERO TRUST
-----------------------------------

Time-based authentication supports:
- Zero Trust security models

-----------------------------------
ZERO TRUST
-----------------------------------

{{{
Additional Context:
Zero Trust emphasizes:
- continuous verification
- strong identity validation

Source:
NIST Zero Trust Architecture
https://csrc.nist.gov/
}}}

-----------------------------------
FEDERATED IDENTITY
-----------------------------------

Time-based authentication commonly integrates with:
- SAML
- SSO
- cloud identity providers

-----------------------------------
IAM
-----------------------------------

IAM =
Identity and Access Management

-----------------------------------
IAM PURPOSE
-----------------------------------

IAM systems commonly manage:
- MFA policies
- authentication methods
- identity verification

-----------------------------------
RECOVERY METHODS
-----------------------------------

Organizations commonly provide:
- backup recovery codes
- alternate verification methods

-----------------------------------
WHY RECOVERY MATTERS
-----------------------------------

Users may:
- lose devices
- replace phones
- become locked out

-----------------------------------
HIGH-YIELD NETWORK+ FACTS
-----------------------------------

Very important exam facts:

- TOTP = Time-Based One-Time Password
- OTPs expire quickly
- Time-based authentication is commonly part of MFA
- TOTP relies on synchronized time
- Authenticator apps commonly generate TOTPs
- MFA improves account security
- SMS MFA is less secure than app-based MFA
- HOTP uses counters instead of time
- Shared secrets are important for TOTP systems

-----------------------------------
COMMON EXAM SCENARIOS
-----------------------------------

Scenario:
"A user enters a 6-digit code that changes every 30 seconds."

Answer:
TOTP/time-based authentication

-----------------------------------

Scenario:
"A company requires password plus temporary phone code."

Answer:
MFA

-----------------------------------

Scenario:
"A login system generates temporary codes based on synchronized clocks."

Answer:
TOTP

-----------------------------------

Scenario:
"A user authenticates using Google Authenticator."

Answer:
Time-based OTP authentication

-----------------------------------

Scenario:
"A company wants stronger authentication than passwords alone."

Answer:
MFA/TOTP

-----------------------------------

Scenario:
"A system generates authentication codes using counters instead of clocks."

Answer:
HOTP

-----------------------------------

Scenario:
"A user receives a texted authentication code."

Answer:
SMS-based OTP authentication

-----------------------------------

Scenario:
"Authentication fails because device time is incorrect."

Answer:
TOTP time synchronization issue

-----------------------------------
COMMON EXAM TRAPS
-----------------------------------

Trap:
Thinking MFA means multiple passwords.

Wrong.

MFA requires:
- multiple factor categories

-----------------------------------

Trap:
Confusing HOTP and TOTP.

HOTP:
- counter-based

TOTP:
- time-based

-----------------------------------

Trap:
Thinking OTPs are permanently valid.

Wrong.

OTPs:
- expire quickly

-----------------------------------

Trap:
Thinking SMS MFA is the most secure MFA method.

Wrong.

Authenticator apps/hardware tokens are generally stronger.

-----------------------------------

Trap:
Thinking time-based authentication replaces passwords entirely.

Wrong.

It commonly supplements:
- passwords

-----------------------------------

Trap:
Thinking TOTP works without synchronized time.

Wrong.

Clock synchronization is critical.

-----------------------------------
MEMORIZATION SHORTCUT
-----------------------------------

OTP =
One-time code

TOTP =
Time-based code

HOTP =
Counter-based code

MFA =
Multiple factors

Authenticator app =
Generates temporary codes

-----------------------------------
HIGH-YIELD FLASHCARDS
-----------------------------------

Q:
What does OTP stand for?

A:
One-Time Password.

-----------------------------------

Q:
What does TOTP stand for?

A:
Time-Based One-Time Password.

-----------------------------------

Q:
What is the purpose of time-based authentication?

A:
Improve authentication security using temporary codes.

-----------------------------------

Q:
What does MFA stand for?

A:
Multifactor Authentication.

-----------------------------------

Q:
How long are TOTP codes commonly valid?

A:
Usually 30–60 seconds.

-----------------------------------

Q:
What does HOTP use instead of time?

A:
Counters.

-----------------------------------

Q:
Why is time synchronization important for TOTP?

A:
Incorrect clocks can cause authentication failure.

-----------------------------------

Q:
What is generally more secure than SMS MFA?

A:
Authenticator apps or hardware tokens.

-----------------------------------

Q:
What category of authentication factor is a TOTP app?

A:
Something you have.

-----------------------------------

Q:
Why do OTPs improve security?

A:
Stolen passwords alone are insufficient for access.