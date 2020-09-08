# Charter for Working Group

The words "Internet of Things" or IoT have come to mean anything and
everything  to a wide group of technology players.  The IETF has been working
on a wide variety of protocols for use by machine to machine communication.
This include CoAP, CBOR, 6TISCH, ROLL, SUIT, NETCONF SZTP, T2TRG, ANIMA's BRSKI onboarding
protocol, and most recently RFC8520, the Manufacturer Usage Description.

The IETF has tried to focus on categories of what limited things can do, and
this has resulted in a number of useful documents from the Light-Weight
Implementation Guide (LWIG).  RFC7228 is a key product, having provided
terminology and scaling understanding to the entire industry.
All of this has been about scaling the Internet technologies to small devices
and constrained networks.  In aggregate, these devices on small networks
present a significant operational risk to the Internet as a whole, and
even to individual Enterprise, simply due to their numbers, and lack of
opportunity for regular human supervision.

IoT devices already exist today in vast numbers.  Most devices that
people are personally familiar with are in the BlueTooth Connected devices,
or Web-Connected devices that use WiFi to reach servers on the Internet ("the Cloud").
Increasingly, the IETF view of machine to machine communications are colinizing
new greenfield situations.  The IETF notion of autonomous networks of devices
is still a minority view compared to the market IoT industry of cloud-only
connected devices, but the transition is occuring.

RFC8520 was created to bridge the gap between devices wholly controlled by
a local operator (such as Enterprise IT), and devices which can not assume
any infrastructure at all, and must rely entirely on cloud communications for
command and control.

This working group concerns itself with Operational Security of IoT systems.

This includes:
  * factory provisioning of devices
  * onboarding of devices
  * access control of devices to network resources
  * administrative control of devices
  * asset management of devices, as it pertains to software/firmware versions
  * isolation/quarantine of devices
  * remediation of broken devices
  * end of life management of devices

The WG is chartered explicitely to work on MUD (RFC8520) and extensions to
it within the point ("access control of devices...")

The WG is chartered to work on onboarding protocols, specifically including
derivaties of BRSKI (RFC-tbd), but not limited to just that protocol.  
The WG is not expected to pick a winner, and is encouraged to work on a
multitude of use-case specific protocols: better to get one use case right,
than to be too-complex jack of all trades.

The WG is expected to articulate clear applicability statements for each
protocol.  The WG is expected to produce concise Roadmap documents that
explain how a variety of IETF (and other) protocols can work together to
satisfy the Operational needs of specific IoT areas. 
These roadmap documents needn’t result in RFCs, the WG will decide with
advice from the responsible Area Director.

Neither the WG nor the IETF has exclusivity here, and an ideal document would
be one that the WG helps to start, but a specific industry alliance becomes
the lead editor for.

There will be coordination with many other WGs beyond the list above, and
this WG may accept applicability statement work from other WGs about specific
ways to deploy their protocols.

The WG will operate through a series of virtual interim meetings. This is
driven by a need to interact regularly with other industry grouops, and
due to the variety of topics which will not always be able to get quorum as a
committee of the whole.

{unusual, maybe not charter appropriate, but rather saag-like}
During in-person meetings, the WG will deal with typical status and document
progress issues during one hour (or less) of the time, and during another
hour, will be open to slideware presentations and tutorials on current
IETF or other-SDO IoT efforts.  The goal of these presentations is to quickly
communicate current IoT *systems* state to the rest of the IETF.  
It is acknowledged that part of the value is in YouTube content, and some
content should be done at IAB tech plenaries rather than at the WG.

The initial set of work items is included below as milestones, which
only require AD approval.

Milestones

* adopt the constrained-voucher/constrained-BRSKI work from ANIMA.
* adopt the dtsecurity-zero-touch work from 6tisch, which can not finish before a LAKE finishes.
* create a list of a series of MUD extensions, and revise this milestone
* adopt a cloud-less (MASA-less, AAA-less) onboarding mechanism (possibly a version of EAP-NOOB), that can be used at the retail level.
* negotiate with EMU WG on how to proceed with TEAP-BRSKI, and revise this milestone.
* adopt a cloud-driven onboarding mechanism that can be used in completely
  offline situations without requiring renewals (perhaps revising RFC8366).

