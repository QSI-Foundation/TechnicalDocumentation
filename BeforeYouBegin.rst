
.. _settingup:

PRIMER: Quantum Safe Infrastructure (QSI), A Zero-Knowledge Authentication (ZKA) Security Framework
===================================================================================================


.. image:: /images/QSIF-ExpandedLogo.jpg
   :alt: QSI Foundation


* Bart Shields: bart@qsifoundation.org
* Valentin Bercovici: val@qsifoundation.org

**Abstract** -- 
*This document proposes a comprehensive autonomous cybersecure connectivity and digital asset relationship management framework designed for the unlimited application complexities posed by modern ICT based systems. QSI solves core cybersecurity protection problems regardless of identity, asset type, scale, or structure, providing a generational improvement over today’s encryption solutions.*

**Index of Key Terms** --
*Autonomous Key Management (AKM); Asset Integrity Management (AIM); cryptographic key generation; Information & Communications Technology (IT & ICT); Internet of Things (IOT) Security; Key Management System (KMS),; Parameter Data Vector (PDV); Perfect Forward Secrecy (PFS); Public Key Infrastructure (PKI); QSI Layer Security (QLS); Quantum Safe Infrastructure (QSI); QSI Security Relationship (QSR); Synchronized Data Set (SDS); Transport Layer Security (TLS); Zero Knowledge Authentication (ZKA).*

Introduction
------------

In a move to eliminate the burden and risk of password, key/secrets and certificate management, while mitigating the existential cyber risk of adversarial quantum decryption, Pure Security introduces Quantum Safe Infrastructure (QSI). QSI is comprised of two components; a cryptographic an autonomous cryptographic key management system (KMS), AKM, and its companion transport layer security protocol, QLS.  Together, AKM and QLS, provide a ZKA-based cybersecurity framework that was explicitly designed to be a drop-in replacement for PKI and TLS solution.  This is accomplished, by providing the level of protection necessary to support the complexity, extensibility, and scale of today’s hybrid Cloud-Edge + IOT + AI world.  Decades of reliance on PKI+TLS is a root cause of the persistent failures to protect digital assets/data from cyberattacks.  QSI simply and cost-effectively replaces these outdated standards with a solution explicitly designed to resolve all major issues plaguing PKI+TLS, regardless of architecture, connectivity, scale or digital asset type.

.. figure:: /images/QSIASR.jpg
   :alt: QSI Asset & Security Relationship Affiliations
   :scale: 40 %

   Figure 1: QSI Asset & Security Relationship Affiliations

QSI is a KMS and transport layer security protocol, that is autonomous, self-healing, simple to configure, and which requires very low human and operational overhead. QSI is natively resilient to quantum computer attacks, which are widely expected to soon overwhelm today’s vulnerable PKI+TLS-based systems.  The QSI security framework provides a universally applicable, network agnostic, certificate-free, and autonomously operated system to secure & monitor every individual digital asset and logically organized group of digital assets (i.e., users, devices, files, apps, metadata) via the QSI Fog Validation Manager (FVM).

The FVM creates synchronized QSI Security Relationships (QSRs) using a patented [#]_, [#]_, [#]_ cryptographic virtualization model to structure AKM-enabled digital assets into functionally (contextually) defined security relationships. 

Every AKM digital asset (representing both physical and virtual assets) is assigned a unique AKM identifier and can participate in unlimited concurrent security relationships.  Each QSR has unique end-to-end security credentials, policy-based rules, and distributed ledger, and operates autonomously and 100% isolated from every other QSR, as well as the network hardware (and software) over which it transits, resulting in a virtualized multipoint-to-multipoint communications security mesh that is perfect for IOT and AI systems.

.. figure:: /images/SimultaneousQSRs.jpg
   :alt: QSI Asset & Security Relationship Affiliations
   :scale: 50 %

   Figure 2: Simultaneous QSI Security Relationships

QSI provides the missing cybersecurity link required to support a future of autonomously managed, rules-based, IOT and AI systems that can safely operate and protect themselves independently of any IT personnel.

.. [#] “Secure communications using organically derived synchronized processes": US 10,382,208.
.. [#] “System and method for secure communications based on locally stored values”, US 10,382,196.: US 10,382,208.
.. [#] “Systems and methods for secure communications using organically derived synchronized encryption processes”, US 10,263,777.


THE PROBLEM STATEMENT (PKI+TLS)
-------------------------------

Traditional cybersecurity [#]_ was designed to protect IT network perimeters, rather than the innumerable web of digital assets that empower our hyper-connected world.  Despite enormous modernization efforts, traditional cybersecurity techniques have proven woefully inadequate to protect society from cyber-related risk.

Network barriers no longer exist, remote work from a mix of corporate and personal devices is the norm, 3rd party SaaS services outnumber internal systems, and external contractors are intermixed with regular staff on many projects. Even modern zero-trust (including SASE [#]_) deployments still require trust in central authorities and expensive ongoing IT management of passwords, keys/secrets and certificates.

User fatigue with password management (policy, rotation and multi-factor authentication) remains a constant drain on productivity and morale, while not mitigating dominant cyber risks of account takeover, social engineering and identity theft, which are all precursors to data breaches, ransomware, espionage and data loss.

Outside the office, billions of IOT devices stream data, most of which are deployed within environments that cannot justify the high cost and overhead complexity associated with implementing PKI (and TLS) as it was intended to protect associated systems and data.  That volume and complexity is now compounded by ever-increasing reliance upon AI, without which industries like knowledge automation and autonomous vehicles simply couldn’t exist.  Simply stated, PKI+TLS was designed for yesterday’s IT network centric security model, and is incapable of protecting our current digital asset centric world, where an asymmetric attack on a single weak link could have a systemically catastrophic impact on an entire digital ecosystem, as evidenced by the 2020 SolarWinds hack.

Unfortunately, industry-wide inertia set in and rather than replace PKI+TLS with a more suitable methodology, the industry tries to layer on additional fixes to “patch” PKI+TLS as new issues are identified.  This has resulted in multiple generations of band-aid solutions laid one on top of the other, in an attempt to mitigate a set of problems that should never have existed in the first place.  Ironically, the unintended consequences of trying to fix versus replace PKI + TLS is a disjointed (and dysfunctional) aggregation of patchwork band-aid solutions that have only served to increase the overall cost and complexity of the PKI model.  The resulting inordinate and unintended additional complexity of this approach has only served to amplify the number of threat vectors, resulting in an increase in frequency, severity, and systemic impact of cybersecurity risks associated with PKI-protected networks.

Problems plaguing traditional security have been well-documented; thus, finding a solution that achieves the following objectives would mitigate the limitations of PKI+TLS:

1) A security framework architecture that simplifies the overall ICT security process, as well as operational.
2) Elimination of the asymmetric key exchange, which remains a major ICT/IOT burden for ongoing key and certificate management, as well as high risk with spoofable certificate authorities that require explicit static trust.
3) Significantly reduction of overall costs of implementation and maintenance.
4) Frequent refresh of security credentials.
5) Provision of unique security credentials to each logical security relationship such that there is no association or relationship to security credentials in other logical security groups..
6) Mitigate or eliminate the many common threat vectors and design limitations that undermine PKI+TLS protected digital communications.
7) Sufficient scalability to handle unprecedented numbers of dynamically generated AI agents executing tasks autonomously throughout ICT environments.

A well-known example of deficiencies of PKI+TLS made an infamous appearance at the beginning of the COVID pandemic when much of the world was forced to work from home, it was discovered that Zoom’s multipoint encryption did not operate end-to-end as advertised.  A Zoom spokesperson, revealed this issue was caused by the limitations of how PKI+TLS works, because PKI+TLS does not facilitate multipoint, end-to-end encrypted communication.  This example illustrates the profound risks faced by a single threat vector from a single company whose product is universally adopted, resulting in a quick deployment of yet another band-aid solution in order to alleviate one company’s immediate negative publicity.

.. [#] Public Key Infrastructure (PKI) is the traditional means for cryptographic key management and Transport Layer Security (TLS) is the traditional means for communication security within TCP/IP.
.. [#] Secure Access Service Edge – see Gartner Group.

QSI DESIGN REQUIREMENTS
-----------------------

In keeping with the aforementioned ICT simplification goals from the previous section, QSI (AKM+QLS) was explicitly designed to address all known issues plaguing the use of PKI+TLS, coupled with the addition of some much-needed security extensions.  These design goals were translated into the following requirements:

1) Given that in reality, most ICT implementations are closed systems (i.e., all actors are known entities using previously established associations prior to connecting), simplify the authentication process, since PKI+TLS assumes no knowledge of the other actors in a potential security relationship.  Thus, taking advantage of known actors, makes it possible to replace the asymmetric authentication phase with a much simpler (safer) solution.
2) Authenticate the sender without sharing any secrets, creating a Zero Knowledge Authentication (ZKA) solution.
3) Reduce to zero, if possible, any latency incurred during security session establishment.
4) Automate the security credential refresh process while still maintaining uniqueness between security credentials.
5) Unique security credentials every single session.
6) Eliminate Man-in-the-Middle (MITM) Attacks.
7) Eliminate Replay Attacks.
8) Allow sessions to be established as event driven and/or time driven.
9) Utilize any existing or new standard cryptographic functions[#]_, wherever required or desired (crypto-agnostic).

The QSI platform design resulting from the above requirements, not only addressed all known PKI+TLS issues as well as the additional security extensions deemed critical, but it exceeded expectations with an autonomous, ZKA-based solution that could effectively execute in perpetuity, it’s refreshing of multipoint, end-to-end security credentials without ever involving IT personnel or an IT network management device in its daily management and oversight.

.. [#] Example, NIST certified functions and libraries.

UNIQUE SECURITY CREDENTIALS
---------------------------

QSI can guarantee that no two sessions will ever have any direct correlation to one another, including past or future sessions within the same security relationship.  As a result, a core feature of QSI is that even if a security relationship could be breached, it would have built-in self-isolation.  Meaning, a breach provides zero insight into the breaching of other security relationships.

NO MITM WITH THE ZERO-TRUST ARCHITECTURE
----------------------------------------

The goal of eliminating “Man-in-the-Middle” (MITM) attacks inspired the concept of the QSI, zero-knowledge authentication (ZKA) solution.  In an QSI, ZKA-based architecture, zero information that could lead to a breach is ever exchanged.  As, all calculations are done internally and autonomously within and among all nodes within a QSR.

Part of implementing the QSI, ZKA based solution involved tying a unique hardware value that is specific to the specific hardware module to the AKM identifier for that module.  So doing, ensures that the AKM identifier could never be spoofed, because of the shared immutability of the hardware value being stored both locally within a HW Trust Zone as well as the administrative backend QSI server.

ELIMINATION OF REPLAY ATTACKS
-----------------------------

Eliminating replay attacks protects against spoofing and also serves as another means of preventing MITM attacks.  This is achieved by having a replay counter as part of every AKM protocol frame.  Even though the Replay Counter is unencrypted, the existence of both an unencrypted digital signature in the frame header and another encrypted digital signature at the end of each frame ensures that the Replay Counter cannot be modified without such modification being immediately detected.

NEXT SESSION TRIGGERS
---------------------

Session renewals are triggered by policy, thus to maximize the renewal opportunities, next session triggers can occur either as a consequence of time or an explicit event or in most situations, can occur for either reason.

This allows the end user to customize their environment according to whatever their desired level of obfuscation, by ensuring the bulk encryption key is a constantly moving target within their desired operational policy.

UNLIMITED SECURITY RELATIONSHIPS
--------------------------------

The concept of QSI security relationships enables unlimited and highly flexible use-case based security relationships, each tied to a specific application and accompanying set of policies and rules.  Making it possible for each security relationship to be highly contextual in nature, created and implemented on a data/type driven basis.  Allowing an unlimited number of overlapping, virtual security relationships, each cryptographically isolated from each other.

The below diagram illustrates four nodes, A, B, C, and D and the relationship tables for each node (where the relationship table for a node is contained within that node’s Synchronized Data Set (SDS) Relationship Table):

.. figure:: /images/QSI-SDS-RelationshipTables.jpg
   :alt: QSI Asset & Security Relationship Affiliations
   :scale: 50 %

   Figure 3: QSI SDS RELATIONSHIP TABLES

Where:
   * “Entry FP0” is the Factory Provisioning Relationship for provisioning at the factory
   * “Entry AP0” is an Authorized Provisioning Level 0 Relationship for provisioning at an authorized service center of Level 0
   * “Entry AP1” is an Authorized Provisioning Level 1 Relationship for provisioning at an authorized service center of Level 0
   * “Entry NPx” is the xth, Normal Relationship within the table.

The allowable relationships depicted in the tables are:
   * ABCD (multicast)
   * ACD (multicast)
   * AB (bidirectional unicast)
   * CD (bidirectional unicast)

Note that for each of the four relationships shown, the entries are identical per relationship within the specific nodes that comprise the relationship set.  Enabling each node within the QSR to accurately and specifically calculate the seeds, keys, and other related data without any exchange of secret information amongst edge nodes and across as many edge nodes as desired for a specific relationship.

QSI PROVISIONING & METHODOLOGY OVERVIEW
---------------------------------------

In the QSI solution, all endpoints within a security mesh must prove knowledge of the same shared secret via digital signatures embedded within the exchanged frames.  This information is instantiated once during the initial ‘factory’ provisioning and, in theory, unless otherwise required by policy, requires no additional provisioning for the duration of the device’s life cycle.  If no automatic re-provisioning module is included within a deployment, field provisioning should only be required for instances of device replacement or failure and/or adding additional nodes to a local network that were not present during original factory provisioning.  If, however, a policy driven, re-provisioning module were to be included within a deployment (such as within a centrally located network module such as a Wireless Gateway), not only could it act as an AKM-based hardware firewall, but it could also work in conjunction with virus and other threat detection functionality to re-provision potentially corrupted nodes on an automatic and as needed basis.

For added security and obfuscation purposes, all keys, seeds, and even cryptographic algorithms, including the bulk encryption algorithm, are internally refreshed on a periodic basis via synchronization algorithms, which are autonomously implemented and shared by all nodes within a QSR.   Unique, QSR specific secrets eliminate the possibility that a single link being compromised could lead to the compromise of other links or an entire system, for multiple reasons, not the least of which is the immutability of a QSR SDS.

Examples of items that could be pre-calculated without compromising the integrity of a QSI implementation are:

1) Seeds;
2) Bulk Encryption Keys;
3) Any other derived computational values which do not require real-time data.

Because there are no exposed shared secrets in a QSI system, the likelihood of a breach is significantly reduced over traditional PKI-based systems.

RANDOMNESS
----------

One important challenge for a QSI deployment with continually refreshed keys, seeds, and potentially even pseudorandom rotation of algorithms, is the ability to maintain synchronization in the event of failures.  Thus, a robust key refresh has been implemented so as to ensure re-synchronization in the event that an anomalous situation causes one or more nodes to lose sync.  A solution containing multiple levels of re-synchronization would be most robust.

Provisioning and related personalization efforts of devices in the field using QSI is significantly smaller than a traditional PKI system.  Field provisioning devices, that effectively act as proxy servers and built into QSI deployments, enable autonomous re-provisioning with no external connection to a back-end., without ever involving IT personnel.

The QSI architecture can be easily retrofitted within an existing PKI Library and/or integrated into an existing HSM, thereby, enjoying many practical benefits, including the ability to reuse underlying and time tested NIST certified functions and libraries.  Making a QSI deployment a PKI extension, thus simplifying and streamlining of QSI into both integrations and existing standards and regulations.

QSI IMPLEMENTATION DETAILS
--------------------------

Although, QSI deployments can vary, the implementation inferred throughout this paper has the following basic characteristics:

1) Keys, seeds, algorithms, and related data represent a specific relationship and are maintained within each edge node within the QSR via the SDS (of the associated QSR).
2) Edge Nodes may have multiple, simultaneous, and overlapping, QSRs.  Hence, maintaining separate secure communications on a per QSR basis.
3) SDS data, including the specification of the algorithms used, are maintained internally and are refreshed based upon specific and configured policy.
4) Each refresh utilizes random data, which provides the basis for, Perfect Forward Secrecy.
5) All refreshes utilize a subset of the aforementioned random data.  Hence, assuming the algorithms used are context sensitive with respect to the order of the input random data, then, the nPr function may be used to accurately predict the underlying entropy.   
6) All QSR security credentials include separate fallback (and  fail-safe) re-synchronization security credential information.  Providing two levels of back-up resynchronization.

The entire process for maintaining synchronization and maintaining secrets is both simplistic and mechanical in nature.  Thus, reducing thereat surface of a given deployment  down to the security of the FIPS certified HSM or key stores.

ATTACKS AND COUNTERMEASURES
---------------------------

Except for the initial provisioning of an AKM node (which may be done internally at the factory behind a company firewall), AKM does not communicate any secrets with other AKM nodes when establishing a new session.  New session seeds and keys are derived within each AKM node belonging to the same QSR, processing the same set of random data from the local QSR SDS, in the same way as all of the other AKM nodes within the same QSR.

Because AKM maintains all of its secrets internally, there is no possibility of intercepting a secret which could compromise the encryption.  However, the implication is that QSI is only as secure as the physical security in which the information is stored.  Thus, depending upon the application, this aspect of QSI must be taken into account when implementing an QSI security solution.

Replay Attacks are another common threat, which an AKM defined implementation can easily defend against.  It does this in two ways.  First, with the use of a Digital Signature or GCC, with session specific initialize seeds and/or vectors, will ensure that messages from prior sessions cannot be used again in subsequent sessions.  Second, by adding a Replay Counter and triggering a new session anytime a replay counter rolls over, this will ensure that every message is unique within a given session.

TRUE MULTIPOINT END-TO-END ENCRYPTION
-------------------------------------

Because:

1) QSRs can be of any size up to the supported implementation maximum, and,
2) AKM utilizes a broadcast architecture to communicate with other nodes within a security relationship;

all communication is secured from one endpoint to all of the other endpoints within a QSR.

SECURE TUNNELING
----------------

Secure tunnels may be created with QSI communication by defining an AKM sub-relationship within a broader AKM base relationship.  This is a relative new feature of AKM and allows a QSR to have two levels of encryption in order to ensure security.

ASSET INTEGRITY MANAGEMENT (AIM)
---------------------------------

One of the key concerns in implementing the infrastructure for an IT network, is the integrity of not only the hardware assets connecting to the network, but also ensuring that only trust applications can be executed within the trusted hardware device.

Asset Integrity Management (AIM), which adheres to the ISO standard, IEC 62443[1], ensures that all covered assets can neither be spoofed nor modified without detection and covers both hardware assets as well as software (virtual) assets.  Additionally, AIM can also be configured such that only trusted applications (i.e., virtual assets) are allowed to execute on a given trusted hardware platform (i.e., hardware asset).  Thus, preventing unwanted applications such as ransomware, zero-day attacks, and other malware from executing.

As part of addressing IEC 62443, AIM not only authenticates the integrity of individual hardware assets and/or software (virtual) assets, but also authenticate the integrity of groups of hardware assets forming a subsystem or system and within a hierarchical methodology, including groups of subsystems.

All inter-module communication, utilizes an expanded concept of QSRs in order to ensure the highest possible level of security and integrity for communication between devices.

Although, AIM is primarily a runtime application, ideally, AIM is additionally anchored within the boot code of a specific device.  The advantage of doing so, is twofold.

First, AIM anchored within the boot code implements a secure boot mechanism.  Second, AIM eliminates the possibility of any potentially illicit modifications to the runtime applications by cross referencing each application as a separate virtual asset with an associated QSI IM Integrity Code that is maintained within a secure trust zone (preferably a hardware trust zone).  If the integrity code that is calculated does not match the integrity code stored within the trust zone, then the asset is flagged and not allowed to load.  Third, during runtime, AIM periodically monitors each software asset and flags and isolates any potential asset that no longer matches the expected value of the precalculated integrity code stored within the trust zone.

CONCLUSION
----------

A QSI, ZKA-based security architecture, provides a secure, efficient, effective, and simplistic approach to network security, regardless of network location, scale, or complexity. When compared to a traditional PKI KMS solution, there are numerous advantages including significantly minimized key management, simplified device provisioning, reduced latency, reduced processing requirements and decreased power needs.  If implemented throughout the system, a ZKQ security architecture provides a built-in firewall for the system as a whole and makes end-to-end security system integration in complex ecosystems much more feasible, manageable, and extensible.

ABBREVIATIONS
-------------

**AKM** – Autonomous Key Management

**FIPS** – Federal Information Processing Standard

**HSM** – Hardware Security Module

**IoT** – Internet of Things

**IT** – Information Technology

**KMS** – Key Management System

**NIST** – National Institute of Standards & Technology

**nPr** – Number of Permutations for a given set size, 'n', and subset size, 'r'

**PKI** – Public Key Infrastructure

**QSI** – Quantum Safe Infrastructure

REFERENCES
----------

.. _references:

[1]	SANS Institute, InfoSec Reading Room, "An Overview of Hardware Security Modules", © SANS Institute 2002., https://www.isa.org/intech-home/2018/september-october/departments/new-standard-specifies-security-capabilities-for-c, September/October 2018

ABOUT THE AUTHORS
-----------------

.. image:: /images/BartShieldsBioPic.jpg
   :alt: Bart Shields Headshot
   :scale: 100 %

**Bart Shields** has over 40-years of experience in wireless communication and transportation related technologies, with multiple patents, including separate patents covering wireless MAC layer protocols and communication security.  Bart is a founding member of the **QSI Foundation** and is also the CTO and co-founder of **Autonomous Cyber Systems, Inc.**, an innovative cybersecurity company that provides tomorrow’s next generation security, today.

.. image:: /images/ValBercoviciBioPic.png
   :alt: Val Bercovici Headshot
   :scale: 150 %

**Val Bercovici**, is a founding member of the **QSI Foundation**, and is also the CEO and co-founder of **Autonomous Cyber Systems, Inc.**.  Val is a visionary Silicon Valley tech exec, who holds the industry's first NFT patents, alongside other Augmented Reality/Metaverse patents. Throughout his career, Val led the development of next-gen platforms (web1, web2 & web3) with Microsoft, NetApp, VMware, Yahoo!, Facebook, AWS & Google.

After serving as CTO of NetApp/SolidFire and as a founding member of the CNCF board—kickstarting the wildly popular Kubernetes Open Source project—Val dedicated his career in 2017 to Cyber Security, DLT/Blockchain, Crypto Currencies, NFTs and DeFi, forecasting that artificial intelligence will be the killer app for web3.

