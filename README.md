# ISC2-study-material source : https://www.reddit.com/r/cissp/comments/11adad7/isc2_cybersecurity_cc_exam_notes_mike_chapels/

Published using Google Docs
Report abuseLearn more
CC- Mike Chapels Notes
Updated automatically every 5 minutes

Breakdown of Exam


Domain 1: Security Principles (26%)


Domain 2: Business Continuity, Disaster Recovery, and Incident Response (10%)


Domain 3: Access Control Concepts (22%)


Domain 4: Network Security (24%)


Domain 5: Security Operations (18%)

_____


ISC2 Code of Ethics


Protect society and infrastructure (Hacking)
Anyone may file a complaint

Act honorably, justly and within laws (Lying)
Anyone may file a complaint

Serve principles diligently and competently (Fulfill your duties)
Only employers and clients may file under a complaint, due to the nature of the code

Advance the information security profession (Helping cheat exams)
Other Professionals may file a complaint, due to the nature of the complaint
Professionals only

You are required to report any witness of violation of Code of Ethics
Failure to report witnessed violation is a violation
Submit a Complaints Form to report
You must have a standing before you make a complaint
Standing: Alleged behavior must harm you or your profession in someway
_____


3 Goals of Information Security

Confidentiality
Protects information from unauthorized disclosure
Integrity
Protects information from unauthorized changes
Availability
Protects authorized access to systems and data
Ensures information is available to authorized users
= CIA

Confidentiality Concerns

Snooping
Involves gathering information that is left out in the open
Clean desk policies protect against snooping
Dumpster Diving
Looking through trash for information
Shredding protects against Dumpster Diving
Eavesdropping
Rules about sensitive conversations prevent eavesdropping
Wiretapping
Electronic Eavesdropping
Encryption protects against wiretapping
Social Engineering
Attacker uses psychological tricks to persuade employee to give it or give access to information
Education and Training protects against social engineering
_____


Integrity Concerns

Unauthorized Modification
Attackers make changes without permission (can be internal=employees or external
Follow the Rules of Least Privilege to prevent unauthorized modification
Impersonation
Attackers pretend to be someone else
User education protects against Impersonation
Man-in-the-Middle (MITM)
Attackers place the themselves in the middle of communication sessions
Intercepts network traffic as users are logging in to their system and assumes their role.
Impersonation on an electronic/digital level.
Encryption prevents man-in-the-middle attacks
Replay
Attackers eavesdrop on logins and reuse the captured credentials
Encryption prevents Replay attacks
_____


Availability Concerns

Denial of Service (DoS)
When a malicious individual bombards a system with an overwhelming amount of traffic.
The idea to is to send so many requests to a server that it is unable to answer any requests from legitimate users
Firewalls block unauthorized connections to protect against Denial of Service attacks
Power Outages
Having redundant power sources and back-up generators protect against power outages
Hardware Failures
Failure of servers, hard drives, network gear etc
Redundant components protect against hardware failure
Building systems that have a built-in redundancy, so that if one component fails, the other will take over
Destruction
Backup data centers protect against destruction (ex=cloud)
Service Outages
Service outage may occur due to programming errors, failure of underlying equipment, and many more reasons
Building systems that are resilient in the fact of errors and hardware failures protect against service outages
_____


Authentication & Authorization


Access Control Process


Identification
Identification involves making a claim of identity (Can be false)
Electronic identification commonly uses usernames 
Authentication
Authentication requires proving a claim of identity
Electronic authentication commonly uses passwords
Authorization
Authorization ensures that an action is allowed
Electronic authorization commonly takes the form of access control lists
Access Control Lists also provides Accounting functionality
Accounting allows to track and maintain logs of user activity
Can track systems and web browsing history


Authentication + Authorization + Accounting = AAA

_____


Password Security


Controls you can implement when setting password requirements:

Password length requirements
Password complexity requirements
Password expiration requirements
Force password changes
Password history requirements
Cannot use previously used passwords

Every organization should make it easy for users to change their passwords, however, be careful of password reset process as it may provide an opportunity for attackers to take advantage through unauthorized password reset.


Password Managers

Secured password vaults often protected by biometric mechanisms (ex=fingerprints)
Facilitates  the use of strong, unique passwords
Stores passwords
_____

Multi Factor Authentication


3 types of authentication factors

Something you know
Passwords, Pins
Something you are
Biometric Security Mechanisms
Fingerprints
Voice
Something you have
Software and Hardware Tokens

You combine these factors all together = Multi Factor Authentication


Note: Passwords combined with security questions are NOT multi factor authentication. Passwords and security questions are both something you know



Single Sign-On (SSO)

Shares authenticated sessions across systems
Organizations create SSO solutions within their organizations to avoid users repeatedly authenticating  
_____

Non-repudiation

Prevents someone from denying the truth
Physical signatures can provide non-repudiation on contracts, receipts etc 
Digital signatures use encryption to provide non-repudiation
Other methods can be biometric security controls, Video-surveillance etc

_____

Privacy


Organization Privacy Concerns

Protecting our down data
 Protect your down organizations data
Educating on users
Educated users of how they can protect their own personal information
Protecting data collected by our organizations
Protecting data that was entrusted to the organization (ex= client’s data)

2 Types of Private Information

Personally-Identifiable Information (PII)
Any information that can be tied back to a specific individual
Protected Health Information (PHI)
Health care records
Regulated by HIPPA

Reasonable expectation of privacy

Many laws that govern whether information must be protected are based upon whether the person disclosing the information had a reasonable expectation of privacy
Ex= if you upload a YouTube video, you do not have a expectation of privacy
You do have some expectation of privacy for private electronic communications such as: email, instant chats etc
You do not have a reasonable expectation of privacy when sharing PII with an organization
You do not have a reasonable expectation of privacy when using employer resources
_____

Risk Management



Internal Risks
Risks that arise from within the organization
Internal control prevents internal risks
External Risks
Risks that arise outside the organization
Build controls that reduce the chance of attack/risks being successful (ex= multi factor authentication, or social engineering awareness campaigns)

Multiparty Risks
Risks that affect more than one organization
Intellectual property theft poses a risk to knowledge-based organizations
If attackers are able to alter, delete or steal this information, it would cause significant damage to the organization and its customers/counterparties
Software license agreements issues risk fines and legal actions for violation of license agreements
_____

Risk Assessment

Identifies and triages risks


Threat

Are external forces that jeopardize security
Threat Vector
Threat Vectors are methods used by attackers to get to their target (ex= social engineering, hacker toolkit, etc)

Vulnerabilities

Are weaknesses in your security controls
Examples : Missing patches, Promiscuous Firewall rules, other security misconfiguration

Threat + Vulnerability = Risk


______


Ranking of Risks

We rank risks by likelihood and impact 


Likelihood

Probability a risk will occur
Impact

Amount of damage a risk will cause


2 Categories of Risk Assessment

Qualitative Techniques
Uses subjective ratings to evaluate risk likelihood and impact: Usually in the form of low, medium or high on both the likelihood and impact scales.
Quantitative Techniques
Uses subjective numeric ratings to evaluate risk likelihood and impact
_____


Risk Treatment (Management)

Analyzes and implements possible responses to control risk


4 Types of Risk Treatment

Risk Avoidance
Changes business practices to make a risk irrelevant
Risk Transference
Attempting to shift the impact of a risk from your organization to another organization
Example : Insurance policy
Note that you cannot always transfer the risk completely. Reputation damage etc.
Risk Mitigation
Actions that reduce the likelihood or impact of a risk
Risk Acceptance
Choice to continue operations in the face of a risk

Risk Profile

Combination of risks that an organization faces
_____

Inherent Risk

Initial level of risk, before any controls are put in place

Residual Risk

Risk that is reduced and what is left of it is known as the residual risk

Control Risk

New risk that may have been introduced by the controls applied to mitigate risk
Example : Controls Applied may be installing a firewall. While that firewall may have mitigated the inherent risk, the risk of that firewall failing is another newly introduced risk


Inherent Risk → Controls Applied → (Residual Risk + Control Risk)



Risk Tolerance

Is the level of risk an organization is willing to accept
_____


Security Controls

Are procedures and mechanisms that reduce the likelihood or impact of a risk and help identify issues


Defense in Depth

Uses overlapping security controls
Different methods of security with a common objective

Security professionals uses different categories to group similar security controls


First you must group Controls by their purpose. 3 Types of Control Purposes are:

Prevent
Stops a security issue from occurring
Detect
Identify security issues requiring investigation
Correct
Remediate security issues that have already occurred

Then group them by their Control Mechanism: 3 Types of Control Mechanisms are:

Technical
Use technology to achieve control objectives
Examples: Firewalls, Encryption, Data Loss Prevention, Antivirus Software)
Technical Control a.k.a Logical Control
Administrative
Uses processes to achieve control objectives
Examples: User access reviews, log monitoring, performing background checks)
Physical
Controls that impact the physical world
Examples: Locks, Security guard
_____


Configuration Management

Tracks the way specific devices are set up
Tracks both operating system settings and the inventory of software installed on a device
Should also create Artifacts that may be used to help understand system configuration (Legend, Diagrams, etc)  

Baselines

Provide a configuration snapshot
Dual Net
You can use the snapshot to assess if the settings are outside of an approved change management process system
Basically the default configuration setting set by an organization
Versioning/Version Controls

Assigns each release of a piece of software and an incrementing version number that may be used to identify any given copy
These verison #s are written as three part decimals, with the
First number representing the major version of software
Second number representing a major updates
Third number representing minor updates
Ex= IPhone IOS 14.1.2



Standardizing Device Configurations by:

Standardizing Naming conventions
IP Addressing schemas

_____

Security Governance



You must first identify how domestic and international Laws and Regulations apply to an organization


Security Policy Framework

A framework that everyone in an organization must follow
There are 4 types of documents in a Security Policy Framework
Policies
Provide the foundation for an organization’s information security program
Describes organization’s security expectations
Policies are set by Senior Management
Policies should stand the test of time anticipating future changes
Compliance with Policies are mandatory
Standards
Describes the specific details of security controls
Compliance with Standards are mandatory
Guidelines
Provide advice to the rest of the organization on best practices
Compliance with Guidelines are optional
Procedures
Step-by-step procedures of an objective.
Compliance can be mandatory or optional
_____

Best Practice of Security Policies

Acceptable Use Policies (AUP)
Described authorized uses of technology
Data Handling Policies
Describe how to protect sensitive information
Password Policies
Describes password security practices
An area where all the password requirements (length, complexity) gets officially documented
Bring Your Own Device Policies (BYOD)
Cover the usage of personal devices with company information
Privacy Policies
Cover the use of personally identifiable information
Can be enforced by National & Local authorities
Change Management Policies
Cover the documentation, approval, and rollback of technology changes

_____


Business Continuity



Business Continuity Planning (BCP)

The set of controls designed to keep a business running in the face of adversity, whether natural or man-made
Also known as Continuity Of Operations Planning (COOP)
Directly impacts the #3 goal of security = Availability
When planning, proactively as what business activities, systems, and controls will it configure

Business Impact Assessment (BIA)

A risk assessment that uses a quantitative or qualitative process
Begins by identifying organization’s mission essential functions and then traces those backwards to identify the critical IT systems that support those functions

In Clouding, Business Continuity Planning requires collaboration between cloud providers and customers



Redundancy

The level of protection and against the failure of a single component

Single Point of Failure Analysis

Provides a mechanism to identify and remove single points of failure from their systems
The SPOF analysis continues until the cost of addressing risk outweighs the benefit
SPOF can be used in many areas other than the IT Infrastructure, it can be applied in management of HR, 3rd party vendor reliance etc)
_____


Continued Operation of Systems

Can be ensured in 2 ways:

High Availability
Uses multiple systems to protect against service failure (Different from AWS Cloud as in that it does not just apply to AZs but rather everything including multiple firewalls etc)
Fault-Tolerance
Makes a single system resilient against technical failures

Load Balancing

Spreads demand across available systems

Common Points of Failure

Power Supply
Contains moving parts
High failure rate
Can use multiple power supplies
Uninterruptible Power Supplies (UPS) - supplies battery to devices during brief power disruptions. UPS may be backed up by an additional power generator  
Power Distribution Units (PDUs) provide power clearing and management for a rack
Storage Media
Protection against the failure of a single storage divide
Redundant Array of Inexpensive Disks (RAID) : Comes in many different forms but each is designed to provide redundancy by having more discs than needed to meet business needs  
There are 2 RAID technologies
Mirroring
Considered to be RAID Lvl 1
Server contains 2 identical synchronized discs
Striping
Disc Striping with parity
RAID Lvl 5
Contains 3 or more discs
Also includes an extra disc called Parity Block
When one of the disc fails, the Parity Block is used to regenerate the failed disc’s content
RAID is a Fault-Tolerance technique NOT a Back-up strategy




Networking
Improve networking redundancy by having multiple Internet service providers
Improve networking redundancy by having dual-network interface cards (NIC) or NIC Teaming (similar to how you use multiple power supplies)
Implement Multipath Networking 

Fault-Tolerance mechanisms prevents systems from failing, even if one of these above points experience a complete failure


Always attempt to add Diversity in your infrastructure to improve redundancy

Diversity in Technology Used
Diversity of Vendors Diversity of Cryptography
Diversity of Security Controls
_____


Incident Response



Incident Response Plans

Provide structure during cybersecurity incidents
Outlines policies, procedures and guidelines that govern cybersecurity incidents

Elements of a Incident Response Plan

Statement of Purpose
Strategies and goals for incident response
Approach to incident response
Communication with other groups
Senior leadership approval


Tips on best practices:

When developing your Incident Response Plan, consult NIST SP 800-61 as you develop your plan
Also review other organization’s plan

NIST SP 800-61

Assists organization mitigating the potential business impact of information security incidents providing practical guidance.
_____


Building a Incident Response Team


IR Team should consist of:

Management
Information Security Personnel
SMEs
Legal Counsel
Public Affairs
Human Resources
Physical Security

If your organization lacks personnels from these areas:

Use incident response service providers to assist  if necessary
_____

Incident Communication Plan

Communications Plans ensure that all participants have timely, accurate information
Make sure to minimize or limit communications to third parties (Media etc)
You will have to choose whether or not to involve law enforcement
Drawbacks of law enforcement engagement can be release of sensitive details to public which may be unfavorable to the organization
Always involve your own organization’s legal team to ensure compliance with laws and organization’s obligations with 3rd parties.
Describe communication paths on how information will trickle down the organization
_____

Incident Identification



Organizations have a responsibility to collect, analyze and retain security information


Data is crucial to incidence detection


Incident Data Sources

IDS/IPS - Intrusion Detection System/Intrusion Prevention System
Designed to only provide an alert about a potential incident
Firewalls
Authentication Systems
Integrity Monitors
Vulnerability Scanners
System Event Logs
Netflow Records
Antimalware Packages

Security Incident and Event Management (SIEM)

Security solution that collects information from diverse sources, analyzes it for signs for security incidents and retains it for later use.
Centralized log repositories
Basically take a load of data, feed it to the SIEM, and it will spit out details regarding risk


When these systems and security mechanisms FAIL do detect risks before dealt with internally, an EXTERNAL source (customer) may be first to detect a risk


Therefore, IR Team should have a consistent method for receiving, recording, and evaluating external reports

_____


First Responder Duty

First responders (whomever they are, whom encounters the risk first) have a set of responsibilities as they may have the power to tremendously reduce risk

Highest Priority

The highest priority of a First Responder must be containing damage through isolation
_____


Disaster Recovery



Disaster Recovery (DR)

Restores normal operations as quickly as possible following a disaster
Disaster recovery plan steps in when business continuity plan fails 
Disaster recovery plan effort is not finished until organization is completely back to normal
Flexibility is key during a disaster response

Initial Response Goals

Contain the damage through isolation
Recover normal operations

Communications required for an effective DR

Initial Report
Status updates
Ad hoc messages


Once Initial Response is implemented, the DR team shifts to Assessment Mode

Assessment Mode

Goal of this mode is to triage/analyze the damage and i
