name: Test Information Security Policy
acronym: TISP
satisfies:
  TSC:
    - CC9.000
majorRevisions:
  - date: Jan 31 2019
    comment: Initial document
---

Coverhound, Inc. ("Coverhound")

Information Systems Security Policy

for the VGS Managed Cardholder Data Environment

> CONFIDENTIAL INFORMATION
>
> This document is the property of Very Good Security, Inc. customized
> for benefit of COVERHOUND; it contains information that is
> proprietary, confidential, or otherwise restricted from disclosure. If
> you are not an authorized recipient, please return this document to
> the above-named owner. Dissemination, distribution, copying or use of
> this document in whole or in part by anyone other than the intended
> recipient is strictly prohibited without prior written permission of
> VGS or Very Good Security, Inc.

Revision History

+-----------------+-----------------+-----------------+-----------------+
| Version         | Changes         | Approving       | Date            |
|                 |                 | Manager         |                 |
+-----------------+-----------------+-----------------+-----------------+
| > 1.00          | > Creation      | Mahmoud         | > March, 2016   |
|                 |                 | Abdelkader      |                 |
+-----------------+-----------------+-----------------+-----------------+
| > 1.01          | > Review, TN    | Mahmoud         | > April 14,     |
|                 |                 | Abdelkader      | > 2017          |
+-----------------+-----------------+-----------------+-----------------+
| > 2.00          | > Review and    | Gordon Young    | > July 6, 2017  |
|                 | > update, TN    |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| > 2.01          | > Include       | Gordon Young    | > July 10, 2017 |
|                 | > automated     |                 |                 |
|                 | > build         |                 |                 |
|                 | > configuration |                 |                 |
|                 | .               |                 |                 |
|                 | > TN            |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| > 2.02          | > Update WAN    | Gordon Young    | > March 07,     |
|                 | > review to     |                 | > 2018          |
|                 | > Daily, TN     |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| > 2.02 CH       | > Adapted to    | Tim Nguyen      | > January 28,   |
|                 | > Coverhound,   |                 | > 2019          |
+-----------------+-----------------+-----------------+-----------------+

Table of Contents {#table-of-contents .TOCHeading}
=================

Chapter 1 Introduction and Scope 1

Introduction 1

What is Payment Card Industry (PCI) Compliance? 1

Scope of Compliance 1

Policy Roles and Responsibilities 2

Policy Applicability 2

Chief Security Officer 2

Information Security Department 2

Developer Operations (System Administrators) and Application
Administrators 3

PCI Requirements Reference 3

Human Resources 3

Users 4

IT Change Control Policy 6

Policy Applicability 6

Key Definitions 6

Normal Process Flow 7

Normal Process Flow Discussion 7

Emergency Process Flow 8

Emergency Process Flow Discussion 8

Request for Change Form 8

Change Identification 8

Change Description 8

Change Impact 8

Planning and Analysis 9

Authorization 9

Implementation Information 9

Github Pull Request Change Request Submission 9

Policy Applicability 9

Data Classification 10

Introduction 10

Information Categories 10

Data Access 10

Data Access Request Process 11

Physical Security 11

User Authentication 11

Users 11

Systems 12

Account and Access Management 14

Information Security Department Responsibilities 14

System Administrator Responsibilities 14

Data Retention and Disposal Policy 17

Policy Applicability 17

Retention Requirements 17

PCI Requirements Reference 17

Disposal Requirements 17

Disposal Process 18

PCI Requirements Reference 18

Firewall and Router Security Administration Policy 19

Policy Applicability 19

Device Management Responsibilities 19

System Administrator 19

Network Operations Center 19

Information Security Department 19

Firewall Configuration Changes 20

PCI Requirements Reference 20

Allowed Services 21

PCI Requirements Reference 21

Allowed Network Connection Paths and Configuration Requirements 21

PCI Requirements Reference 22

Configuration Review 22

PCI Requirements Reference 22

Personal Firewalls 22

PCI Requirements Reference 22

System Configuration Policy 22

Policy Applicability 22

System Build and Deployment 23

System Purpose 23

PCI Requirements Reference 23

System Configuration Standards 23

System Configuration Records 23

System Configuration Process 23

PCI Requirements Reference 24

Standard Software 24

PCI Requirements Reference 25

Network Time Protocol (NTP) 25

PCI Requirements Reference 25

Credit Card Information Processing Application 25

PCI Requirements Reference 26

Credit Card Storage Applications 26

PCI Requirements Reference: 26

Vulnerability Identification and System Updates 27

Vulnerability Identification 27

Risk Ranking 27

Vulnerability Testing 28

Security Patch Deployment 29

Anti-Virus Policy 30

Policy Applicability 30

Software Configuration 30

PCI Requirements Reference: 30

Signature Updates 30

PCI Requirements Reference: 30

Software Logging 30

PCI Requirements Reference: 31

Backup Policy 32

Policy Applicability 32

Location 32

Transport 32

Audit 32

*Media Destruction* 32

Encryption Policy 33

Policy Applicability 33

Encryption Key Management 33

Key Access 33

Split Knowledge and Dual Control 33

Key Generation 33

Key Distribution 34

Key Storage 34

Key Changes and Destruction 35

Transmission over Un-trusted Networks 36

PCI Requirements Reference: 36

Transmission of Confidential Information via End-User Messaging
Technology 36

Encryption of Wireless Networks 36

Special Technologies Usage Policy 37

Policy Applicability 37

PCI Requirements Reference: 37

Approval 37

PCI Requirements Reference: 37

Authentication 37

PCI Requirements Reference: 37

Device Inventory 38

PCI Requirements Reference: 38

Device Identification 38

PCI Requirements Reference: 38

Acceptable Use 38

PCI Requirements Reference: 38

Permitted Locations 38

PCI Requirements Reference: 39

Approved Products 39

PCI Requirements Reference: 39

Session Disconnect 39

PCI Requirements Reference: 39

Vendor Connections 39

PCI Requirements Reference: 39

Credit Card Data Access 39

PCI Requirements Reference: 39

Software Development Policy 41

Policy Applicability 41

Development Environment 41

PCI Requirements Reference: 41

Secure Software Development Procedures 41

Development Life-Cycle 42

Web-based Applications 43

Credit Card Informational and Processing Applications 44

Incident Response Plan and Procedures 45

Policy Applicability 45

Incident Identification 45

Reporting and Incident Declaration Procedures 45

PCI Requirements Reference: 46

Incident Severity Classification 46

Incident Response 48

Typical Response 48

Credit Card Compromise -- Special Response 49

Root Cause Analysis and Lessons Learned 50

Plan Testing and Training 51

Automated Security System Notifications 51

PCI Requirements Reference: 51

Logging Controls Policy 52

Policy Applicability 52

Events Logged 52

PCI Requirements Reference: 52

Event Log Structure 52

PCI Requirements Reference: 53

Log Security 53

PCI Requirements Reference: 53

Log Review 53

PCI Requirements Reference: 54

Appendix A Security Awareness and Acceptable Use Policy 55

VGS Network Security Policy 55

Web and Mail Specifics 57

Appendix B Authorization Request Form 59

Appendix C Change Request Form 61

Appendix D Media Inventory Log 66

Appendix E Permitted Network Services and Protocols 68

Appendix F System Configuration Standards 70

Applicability 70

PCI Requirements Reference: 70

Risk Ranking 70

Linux 70

Server Applications 70

Container Management 71

Emergency Patch Management Procedure 71

Appendix G System Configuration Record 72

VGS System Configuration Record 72

Appendix H Encryption Key Custodianship Form 74

VGS Encryption Key Custodianship Form 74

Appendix I Encryption Key Management Log 75

VGS Encryption Key Management Log 75

Appendix J Special Technologies Device Inventory 76

VGS Special Technologies Device Inventory 76

Appendix K Periodic Operational Security Procedures 77

VGS Periodic Operational Security Procedures 77

Appendix L MANAGEMENT of connected entities 79

Connection Standards 79

Connection Process 79

PCI Requirements Reference: 79

Appendix M RISK MITIGATION AND MIGRATION PLAN 80

AWS CloudFront delivers JavaScript contents via its CDN over early TLS
80

Migration Plan 80

Appendix N PCI INDEX 81

Introduction and Scope
======================

Introduction
------------

This document explains the information security requirements for
COVERHOUND's managed Cardholder Data Environment (CDE) as agreed upon by
COVERHOUND and VGS. VGS & COVERHOUND management has committed to these
policies to protect information utilized by VGS in attaining its
business goals. All employees are required to adhere to the policies
described within this document.

What is Payment Card Industry (PCI) Compliance?
-----------------------------------------------

The Payment Card Industry Data Security Standard (PCI DSS) Program is a
mandated set of security standards that were created by the major credit
card companies to offer merchants and service providers a complete,
unified approach to safeguarding credit cardholder information for all
credit card brands.

In September of 2006, a group of five leading payment brands including
American Express, Discover Financial Services, JCB, MasterCard Worldwide
and Visa International jointly announced formation of the PCI Security
Standards Council, an independent Council established to manage ongoing
evolution of the PCI standard. Concurrent with the announcement, the
council released version 1.1 of the PCI standard. In April of 2015, the
council released version 3.1 of the PCI Data Security Standard. This
document and the requirements herein represent VGS adherence to the
version 3.1 standard.

The PCI Data Security Standard requirements apply to all payment card
network members, merchants and service providers that store, process or
transmit cardholder data. The requirements apply to all methods of
credit card processing, from manual to computerized; the most
comprehensive and demanding of which apply to e-commerce websites and
retail POS systems that process credit cards over the internet.

Scope of Compliance
-------------------

The PCI requirements apply to all "system components." System components
are defined as any network component, server, or application that is
included in or connected to the cardholder data environment in an
isolated Amazon Web Services account.

**These policies and procedures shall only apply within the PCI
environment**. The PCI environment current exists on the Amazon Web
Services cloud. Amazon Web Services is a PCI DSS Level 1 compliant
vendor that provides a compliance package and various services, located
at: https://aws.amazon.com/compliance/pci-dss-level-1-faqs/

Policy Roles and Responsibilities
=================================

Policy Applicability
--------------------

All employees, contractors, vendors and third-parties service providers
that use, maintain or handle COVERHOUND CDE RELATED information assets
must follow this policy. Policy exemptions must be permitted only if
approved in advance and in writing by the Chief Security Officer. Policy
exemptions should be filed for a term of (1) year for audit purposes.

Chief Security Officer
----------------------

The Chief Security Officer is responsible for coordinating and
overseeing COVERHOUND CDE wide compliance with policies and procedures
regarding the confidentiality, integrity and security of its information
assets.

The Chief Security Officer may assume or work closely with other
COVERHOUND CDE managers and staff involved in securing the company's
information assets to enforce established policies, identify areas of
concern, and implement appropriate changes as needed. Specific
responsibilities of the Chief Security Officer include:

-   Make high-level decisions pertaining to the information security
    > policies and their content. Approve exceptions to these policies
    > in advance on a case-by-case basis.

-   On an annual basis, coordinate a formal risk assessment to identify
    > new threats and vulnerabilities and identify appropriate controls
    > to mitigate any new risks.

-   Annually review the Information Security policies and procedures to
    > maintain adequacy in light of emergent business requirements or
    > security threats.

-   Make sure that third parties, with whom cardholder data is shared,
    > are contractually required to adhere to the PCI DSS requirements
    > and to acknowledge that they are responsible for the security of
    > the cardholder data which they process.

-   Assure that connections to third parties are managed per PCI
    > requirements via the relationship procedures described in
    > Management of Connected Entities.

-   Complete tasks as required by the Periodic Operational Security
    > Procedures.

Information Security Department
-------------------------------

Successfully securing COVERHOUND CDE information systems requires that
the various departments and groups consistently adhere to a shared
vision for security.

The Information Security Department works with departmental system
managers, administrators and users to develop security policies,
standards and procedures to help protect the assets of THE COVERHOUND
CDE.

The Information Security Department is dedicated to security planning,
education and awareness. Specific responsibilities of the Information
Security Department:

-   Create new information security policies and procedures when needs
    > arise. Maintain and update existing information security policies
    > and procedures. Review the policy on an annual basis and assist
    > management with the approval process.

-   Review and update the Information Security policies as environment
    > changes.

-   Act as a central coordinating department for implementation of the
    > Information Security Policies.

-   Maintain and distribute incident response and escalation procedures.

-   Monitor and analyze security alerts and distribute information to
    > appropriate information security, technical and business unit
    > management personnel.

-   Review logs daily. Follow up on any exceptions identified.

-   Restrict and monitor access to sensitive areas. Ensure appropriate
    > physical controls are in place where sensitive cardholder
    > information is present.

-   Complete tasks as required by the [Periodic Operational Security
    > Procedures (Appendix N)](http://livepage.apple.com/).

-   Maintain a list of service providers that have access to cardholder
    > data.

-   Ensure contract with service providers that have access to
    > cardholder data, includes an acknowledgement that the service
    > provider is responsible for the security of cardholder data the
    > provider possesses.

-   Develop a vendor management program that includes:

    -   Due diligence process prior engaging any service provider.

    -   Monitoring of the service provider's PCI DSS compliance status
        > annually.

    -   Ensure service provider shares their SSAE 16 report on an annual
        > basis.

    -   Perform a security and policy review on an annual basis, unless
        > the Chief Security Officer considers copy of the Report on
        > Controls (ROC) and SSAE 16 presented by the service provider
        > suffices.

        -   Review log event alerts for all system components at least
            > daily. Log reviews should include those servers that
            > perform security functions like intrusion-detection
            > systems (IDS).

> Note: Log harvesting, parsing and alerting tools may and their use is
> advised to achieve compliance

-   Develop daily operational security procedures that are consistent
    > with requirements in this specification (e.g. user account
    > maintenance procedures and log review procedures).

-   Establish, document and distribute security incident response and
    > escalation procedures to ensure timely and effective handling of
    > all security risk situations.

-   Monitor and control all access to data and report timely any
    > anomaly.

Developer Operations (System Administrators) and Application Administrators
---------------------------------------------------------------------------

COVERHOUND CDE System Administrators are the direct link between
information security policies and the network, systems and data. System
Administrator responsibilities include:

-   Applying this information security policies and procedures to in
    > scope information assets.

-   Administering user account and authentication management.

-   Assisting the Information Security Department with monitoring and
    > controlling all access to VGS data.

-   Maintain an up to date network diagram.

-   Completing tasks as required by the [Periodic Operational Security
    > Procedures](http://livepage.apple.com/).

Application Administrators are responsible for managing all non-PCI
scope software application, including patches.

### PCI Requirements Reference

Human Resources
---------------

Due to their direct and constant relationship with existing employees,
as well as their unique position of having the first and last
interactions with new/terminated employees, the Human Resources
Department has an important role with regards to COVERHOUND CDE
information security. The following items are the ongoing responsibility
of the Human Resources:

-   Assist the Information Security Department with publishing and
    > disseminating COVERHOUND CDE information security policies and
    > acceptable use guidance to all relevant system users, including
    > vendors, contractors and business partners. Acknowledgement and
    > agreement to comply with policies should be confirmed in writing
    > (e.g. an email confirmation).

-   Perform background checks on potential employees who must have
    > access to systems, networks, or data, including background,
    > pre-employment, criminal, credit and reference checks.

-   Work with the Information Security Department on disseminating
    > security awareness information to system users.

-   Work with the Information Security Department to administer
    > sanctions and disciplinary action relative to violations of
    > Information Security Policy.

-   Notify Access Management personnel when any employee is terminated.

-   Maintain all [Security Awareness and Acceptable Use Policy
    > (Appendix A)](http://livepage.apple.com/) and [Authorization
    > Request Form (Appendix B)](http://livepage.apple.com/) in employee
    > files.

-   In conjunction with the Information Security Department, implement a
    > formal security awareness program for all employees emphasizing
    > the importance of cardholder data security.

-   Implement a "new employee" immersion training, which includes among
    > others, overview of COVERHOUND CDE and importance to comply with
    > the Information Security Policies.

Users
-----

Each user of COVERHOUND CDE computing and information resources must
realize the fundamental importance of information resources and
recognize their responsibility for the safekeeping of those resources.
Users must guard against abuses that disrupt or threaten the viability
of all systems. Users are broadly classified and defined as:

-   CTO -- Chief Technology Officer.

-   CSO -- Chief Security Officer.

-   COO -- Chief Operation Officer.

-   Applications Administrator -- Administrator supporting the
    production environment for Applications.

-   Developer Operations and Systems Administrator -- Resource
    responsible for technical infrastructure maintenance.

-   Customer Service Representative -- Resource accepting and resolving
    customer requests.

-   Human Resources -- HR submits requests to Developer Operations and
    Systems Administrator for starting or removing user's accounts.

The following are specific responsibilities of all COVERHOUND CDE users:

-   Understand what the consequences of their actions are with regard to
    > computing security practices and act accordingly. Embrace the
    > "Security is everyone's responsibility" philosophy to assist
    > COVERHOUND & VGS in meeting its business goals.

-   Maintain awareness of the contents of the information Security
    > Policies.

-   Read and sign the *VGS* [*Security Awareness and Acceptable Use
    > Policy (Appendix A)*](http://livepage.apple.com/).

-   Classify confidential and sensitive information that is received
    > unclassified. Limit the distribution of this information
    > accordingly. Employ need to know role-based access controls to
    > support data classification.

Access to production systems and sensitive data requires that the VGS or
Coverhound employee have passed a background check and received explicit
approval from the CISO.

The guidelines described above, are also applicable to the external
Customer Service Representatives (CSRs) who have limited access for
troubleshooting.

IT Change Control Policy
========================

Policy Applicability
--------------------

All proposed changes to the COVERHOUND CDE network, firewall rules,
cloud servers, infrastructure and application configurations must follow
this policy.

Change control procedures for the implementation of security patches and
software modifications, must include the following:

-   Documentation of impact.

-   Documented change approval by Change Leader ("**CL**")

-   Back-out procedures.& fail forward procedures.

-   Data Classification and Control Policy.

Key Definitions
---------------

-   Change Control Team (CCT). The CCT is a cross-functional group set
    > up to evaluate change requests for business need, priority,
    > cost/benefit, and potential impacts to other systems or processes.
    > Typically the CCT must make recommendations for implementation,
    > further analysis, deferment, or cancellation.

> The CCT convenes via the workflow management system, "Github", to
> review the RFC when pinged via Github notification. x

-   CCT Emergency Committee (CCT/EC). The subset of the CCT that deals
    > only with emergency changes. It is established to be able to meet
    > on short notice to authorize or reject changes with emergency
    > priority. The CSO at VGS must assume this role.

-   Change. Any new IT component (i.e. network configuration,
    > infrastructure configuration, application code, etc.) deliberately
    > introduced to the IT environment that may affect an IT service
    > level or otherwise affect the functioning of the environment or
    > one of its components.

-   Change leader. The primary person who is assigned to review the
    > Request for Change ("RFC") and is responsible for reviewing
    > changes and assessing past changes. The Change leader is
    > responsible in ensuring that proper testing procedures were done
    > to mitigate release risk. A Change leader will approve or reject a
    > RFC via phrases, including, but not limited to ":+1:", ":shipit:",
    > or "lgtm". If the RFC is not deemed an actionable item, then the
    > Change leader may close the RFC alongside an explanation of why
    > there's no action required.

-   Change initiator. A person, typically a member of the organization,
    > or an automated alerts system that initiates a request for change.

-   Change process owner. The role that is responsible for planning and
    > implementing a change in the IT environment. The change owner role
    > is assigned to an individual, typically an Application developer
    > or a Developer Operations/System Administrator, for a particular
    > change and assumes the responsibilities of preparing, testing,
    > and/or fixing the RFC to get ready for Release.

-   Change priority. The urgency of the need for the solution and the
    > business risk of not implementing the change are the main criteria
    > used to determine the priority.

-   Release. A collection of one or more changes that includes new
    > and/or changed configuration items that are tested and then
    > introduced into the production environment. Once the CCT approves
    > the requests, the changes may be released via an automated release
    > system.

-   Request for Change (RFC). This is the formal change request, tracked
    > via "Github pull request" or a "Github issue" that includes a
    > description of the change, components affected, business need,
    > cost estimates, risk assessment, resource requirements, and
    > approval status.

Normal Process Flow
-------------------

Change can be graphically represented as a process flow diagram that
presents the key tasks needed to be performed in order to successfully
deploy a change.

Normal Process Flow Discussion
------------------------------

The normal Change Management Process Flow can be broken down in to 6
distinct steps. It should be noted that this process does not cover the
application development scope change process, but rather the deployment
of such enhancements once development has been completed or any changes
made to the operating environment of the VGS network. Typically, any
person within a business environment can request a change and, by doing
so, become a change initiator.

-   Step 1: Initiate Change. Changes are brought to the attention of the
    > IT management staff through the normal lines of communication
    > (Help Desk ticket, feature request, compliance, etc.). If the
    > change is determined to be an emergency, proceed to Step 2,
    > otherwise proceed to Step 3.

-   Step 2: Emergency? A slightly modified process is followed (see
    > below). In the normal course of events, the process moves on to
    > Step 3.

-   Step 3: Create RFC and Support Documentation on Github. In this step
    > a Request for Change (RFC) is created, completed, and submitted on
    > Github, via Github issue, paired with any supplementary detail
    > and/or other relevant details relating to the RFC, including
    > documentation. Upon submission, the documentation is recorded and
    > preliminarily scheduled for release pending change approval.

-   Step 4: Implement RFC Change. The change is implemented according to
    > the plan laid out in the RFC. Finally, when completed, a pull
    > request is created, referencing the RFC, and the CCT team is
    > pinged to review the changes.

-   Step 5: Approved? This is granted via the Change Control Team (CCT),
    > which is pinged on Github to review the RFC, as needed. Upon
    > approval by the CCT, the change is merged into the main branch,
    > typically master. The change is then tagged, which signals an
    > immediate release via the continuous deployment systems.

-   Step 6: Review Change(s). A formal post mortem conducted.

Emergency Process Flow
----------------------

Emergency Process Flow Discussion
---------------------------------

Under extreme circumstances, emergency changes may be implemented with
the approval of the CCT/EC, typically the CSO or COO. It should be noted
that all steps of the normal process are still present. The order has
been changed for emergency purposes. Specifically, the implementation of
the change can be executed prior to all of the requisite documentation
(RFC, supporting documents, etc.).

Request for Change Form
-----------------------

Please see Appendix C -- Change Request Form for the RFC form used as a
Github Issue template.

Change Identification
---------------------

This section contains all of the basic Change identification fields,
such as Change Initiator, Change Process owner, etc.

There is often a degree of confusion surrounding the definition of
priority; the dictionary definition states: "Precedence, especially
established by order of importance or urgency." In the change management
process, the urgency is determined by how quick a change is required by
the business.

There are four recommended levels of priorities:

-   Emergency. A change that if not implemented immediately, can leave
    > the organization open to huge risk---for example, applying a
    > security patch. This is a RED colored Github label.

-   High. A change that is important for the organization and must be
    > implemented soon---for example, an upgrade in line with new
    > legislation requirements. This is an ORANGE colored Github label.

-   Medium. A change that should be implemented to gain benefit from the
    > changed service---for example, between versions upgrade to a
    > customer feedback service. This is a YELLOW colored Github label.

-   Low. A change that is not pressing but would be advantageous---for
    > example, a "nice to have" addition to a user profile. This is a
    > GREEN colored Github label.

It is important to note, however, that an emergency priority change
differs from the other change priorities in that it takes a different
path through the review process in order to implement the change as
quickly as possible. This priority is reserved for only changes that, if
not implemented quickly, might seriously affect service levels or result
in a large cost to the business. Emergency changes must be kept to an
absolute minimum due to the increased risk involved in implementing
them; their use should not replace good planning practices.

Change Description
------------------

The Change Description contains a detailed discussion of the nature of
the change including reference to supporting documentation and time
estimates. Estimates should always be given in terms of effort hours.
Three estimates are required; best case scenario, most likely, and
worst-case scenario.

Change Impact
-------------

The impact analysis should include a detailed itemization of the users,
systems, application, hardware, network, firewall rules, and other
technologies affected by the change. A discussion of the benefits of the
change and the risks of not implementing the change is required. If
necessary, include a sample communication targeted at the user community
describing the change and the impact to their systems.

Planning and Analysis
---------------------

This section must contain a step-by-step plan for implementing the
change in question. In addition, it must detail a specific back-out plan
including the timing threshold for when a back out is required (i.e. the
change must be aborted and the previous state restored). This section
should include high-level change verification, or test cases, to
identify if the change was successful.

Also discussed should be the itemization of risks and issues involving
the implementation. For the purposes of this process, a risk is defined
as a negative possibility. An issue is a risk that has been realized or
an existing challenge for the implementation. It is in this section of
the RFC that costs and resource requirements are also discussed.

Authorization
-------------

All changes should receive sign-off by a representative that is not the
Change Process Owner, but part of the CCT, after careful review of the
RFC and its accompanying implementation.

Implementation Information
--------------------------

This section includes the administrative portion of the release as well
as an implementation escalation list.

Github Pull Request Change Request Submission 
----------------------------------------------

From the Request for Change Process, Step 4, "Implement RFC Change",
identifies the point at which the change request and supporting
documentation are submitted for review by the CCT. The following section
describes how to submit a Request for Change to the appropriate JIRA
Project.

Once an employee logs into JIRA, the Change Control Team Project is made
available under Projects to all employees.

When selected, the COVERHOUND CDE Change Management list must be
displayed which offers a convenient representation of all changes by
approval status. Other available views include All Events, Calendar,
Current Events, Approve/Reject Items (which is available for CCT
members), and My Submissions.

To submit a request, simply click the New Item button. The New Item form
must offer you the fields to title, describe, schedule and attach
supporting documentation. When creating this item, the rudimentary data
requested must match the Request for Change form identically. The
Request for Change form must also be attached. This COVERHOUND CDE item
is simply the vehicle to present the attached Request for Change form,
and then manage the workflow and communication that the CCT must utilize
to review and approve, defer, cancel or request more information.

JIRA has ticket history reports that can track changes. Users can create
reports in addition to the standard reports available.

Policy Applicability
--------------------

All data stored and accessed on COVERHOUND CDE information systems,
whether managed by employees or by a third party, must follow this
policy. Policy Exemptions must be permitted only if approved in advance
and in writing by the Chief Security Officer.

Data Classification
-------------------

### 

### Introduction

The information creator or owner must classify all data stored on
COVERHOUND CDE computing resources. This classification level is used to
determine which users are permitted to access the data.

### Information Categories

The following are the classification levels assigned to data, based on
the sensitive information they contain.

-   Confidential - applies to the most sensitive business information,
    > which is intended strictly for use within the COVERHOUND CDE.
    > Unauthorized disclosure could seriously and adversely impact the
    > company, business partners, and/or its customers. Examples of
    > confidential information include: passwords, encryption keys,
    > cardholder information, bank account information, etc.

-   Sensitive - Applies to less sensitive business information, which is
    > intended for use within the COVERHOUND CDE. Unauthorized
    > disclosure could adversely impact the company, its business
    > partners, and/or its customers. Examples of sensitive information
    > include: internal market research, audit reports, etc.

-   Private - Applies to personal information, which is intended for use
    > within the COVERHOUND CDE. Unauthorized disclosure could adversely
    > impact the company and/or its employees. Examples of Private
    > information include: policies and procedures, procedure metrics,
    > intellectual property, etc.

-   Public - Applies to all other information which does not clearly fit
    > into any of the above three classifications. Unauthorized
    > disclosure isn't expected to seriously or adversely impact the
    > company. COVERHOUND Public Relations Department must authorize any
    > release of this information.

### Data Access

All confidential or sensitive data must be protected via access controls
to ensure that data is not improperly disclosed, modified, deleted or
rendered unavailable. The access controls must track all access to such
data and identify who and when the data was accessed (0: Logging
Controls Policy for more details).

Employees who have been authorized to view information at a particular
classification level must only be permitted to access information at
that level or at a lower level on a need to know basis. **All access to
systems must be configured to deny-all but what a particular user needs
to access per their business role**.

Computing resources and cardholder information access will be limited to
those individuals whose job requires such access. Access should be
provided in a controlled environment to avoid unauthorized individuals
access the sensitive information.

Access to systems or applications handling confidential, sensitive or
private information must follow the data access request process. All
requests require approval by the Information Security Department and a
valid [Authorization Request Form (Appendix
B)](http://livepage.apple.com/). Access to data exceeding the employee's
authorized role must also follow the data access request process and
must include documented limits around such access (e.g. access source,
access time limits, etc.).

### Data Access Request Process

The following generally describes the workflow used for requesting new
access:

1.  The user's manager must request authorization for access to
    > confidential data via the [Authorization Request Form
    > (Appendix B)](http://livepage.apple.com/)

2.  The user's manager must approve the request for access based on the
    > employee's role, identify any additional access requirements and
    > forward the request to the Information Security Department.

3.  If the access requested requires privileges above the employee's
    > role the Information Security Department must engage additional
    > system owners or management to collect approvals.

4.  The Information Security Department must forward the approved
    > request to the System Administrator for account creation.

5.  The System Administrator must create the user account(s) requested.
    > Once the accounts have been created the System Administrator must
    > forward the request form to the Human Resources department for
    > inclusion in the Users employee records and notify the Information
    > Security Department that the request has been completed.

Requests for change of access must be submitted by the user's manager
utilizing the [Authorization Request Form (Appendix
B)](http://livepage.apple.com/) and the workflow shall be the same as
above.

Direction regarding removal of an employee's access shall follow the
same workflow above except the request for removal can come from either
Human Resources or the employee's manager.

Physical Security
-----------------

Hard copy materials and electronic media containing sensitive or
confidential information must be protected by appropriate physical
access controls.

-   Cameras with recording capability must be used to monitor sensitive
    > areas. The data collected must be stored for at least 1 year
    > unless otherwise restricted by law.

-   Appropriate facility controls must be used to limit and monitor
    > physical access to systems that store confidential or sensitive
    > data.

-   Visitor logs and physical audit trails of access to these systems
    > must be collected and kept at least 1 year unless otherwise
    > restricted by law.

-   Physical access must be restricted to publicly accessible network
    > jacks, wireless access points, gateways and handheld devices.

-   Third party service providers that require access to security areas
    > must be escorted during their visit by an employee authorized to
    > access those secure areas.

User Authentication 
--------------------

### 

### Users

Each user's access privileges shall be authorized according to business
need. User access authority to computer resources shall be provided only
when necessary to perform tasks related to COVERHOUND CDE business.

If a user does have privileged and/or administrative access, the user
must operate under the least privilege unless the business requires such
user to elevate their privileges (i.e. on a \*nix machine, a user must
"sudo" to execute commands requiring elevated privileges).

Access to the system will be provided through combination of passwords,
two-factor authentications and security certificates.

The use of non-authenticated (e.g., no password) UserIDs or UserIDs not
associated with a single identified user are strictly prohibited. Shared
or group userIDs are never permitted for user-level access.

The following user levels have been approved at VGS:

-   CIO/CTO -- Chief Information Officer/ Chief Technology Officer.
    > Oversees the technology environment.

-   COO -- Chief Operations Officer. Oversees the overall operations
    environment and daily operation at VGS.

-   Applications Administrator -- Administrator supporting VGS
    production environment.

-   Systems Administrator -- Resource responsible for the technical
    infrastructure.

-   Customer Service Representative -- Resource accepting and resolving
    cardholder's requests. Direct contact with cardholders.

-   Human Resources -- HR submits requests to Application Administrator
    for starting or removing user accounts.

Every user must use a unique user account and a personal secret password
for access to COVERHOUND CDE information systems and networks. Systems
and applications must authenticate using a password or token entry.

All users must acknowledge understanding of the COVERHOUND CDE
Information Security Policies by reading and signing the VGS [Security
Acknowledgment and Acceptable Use Policy (Appendix
A)](http://livepage.apple.com/) prior to being allowed to access VGS
information systems and networks.

### Systems

Each computer system shall have an automated or procedural access
control process. The process must:

-   Identify each authorized user through a unique User Identifier (user
    > ID). The naming standard would be first initial and full last
    > name. In the event when a name is identical using the standard,
    > then middle initial would be used. In the event that this creates
    > an identical name, then numeric values must be used for every
    > instance of the identical name. For example (tmetzger, tametzger,
    > tametzger2).

-   Authenticate every user ID, system account and application account
    > with a password.

-   Employ TLS v1.2 Certificate and Password authentication where
    > applicable.

-   The TLS v1.2-enabled server must authenticate itself to an TLS
    > v1.2-enabled client, allow the client to authenticate itself to
    > the server and allow both machines to establish an encrypted
    > connection.

-   Require all passwords to be at least 8 alphanumeric characters in
    > length.

-   Require complex passwords, consisting of both numeric and alphabetic
    > characters. At least one of the alphabetic characters must be
    > capitalized. (e.g. ''mljw4eSAyCmiASDs2s" or "qt99DRacpcJJhCYabe").

-   Access to systems/applications that contain sensitive information
    > will require as part of the user ID a token assigned randomly and
    > updated on a daily basis.

-   Require that new passwords cannot be the same as the twenty
    > four (24) previously used passwords.

-   Lock out accounts after not more than three (3) invalid logon
    > attempts.

-   Require that once a user account is locked out it remains locked
    > until the System Administrator resets the account.

-   Require system/session idle time out of fifteen (15) minutes.

-   Require passwords to be reset at least every forty two (42) days.
    > Note: Job/Service user IDs may be exempt from this requirement
    > with management approval. Administrative user IDs (e.g. root,
    > oracle, Administrator) must comply.

-   Remove inactive users at least every ninety (90) days.

The requirements above are for authenticating all system users.

These requirements must also be documented in guidance provided to every
VGS customer utilizing a system that contains sensitive or confidential
data. See Appendix Q

#### PCI Requirements Reference

-   8.1 Identify all users with a unique username before allowing them
    to access system components or cardholder data.

-   8.2 In addition to assigning a unique ID, employ at least one of the
    following methods to authenticate all users:

<!-- -->

-   Something you know, such as a password or passphrase

-   Something you have, such as a token device or smart card

-   Something you are, such as a biometric

<!-- -->

-   8.5.5 Remove/disable inactive user accounts at least every 90 days

-   8.5.9 Change user passwords at least every 90 days.

-   8.5.10 Require a minimum password length of at least seven
    characters.

-   8.5.11 Use passwords containing both numeric and alphabetic
    characters.

-   8.5.12 Do not allow an individual to submit a new password that is
    the same as any of the last four passwords he or she has used.

-   8.5.13 Limit repeated access attempts by locking out the user ID
    after not more than six attempts.

-   8.5.14 Set the lockout duration to thirty (30) minutes or until
    administrator enables the user ID

-   8.5.15 If a session has been idle for more than 15 minutes, require
    the user to re-enter the password to re-activate the terminal or
    session.

Account and Access Management
-----------------------------

### Information Security Department Responsibilities

The Department must approve access authorization according to the role
and responsibilities of information system users. Each request for
access must contain written and/or electronic evidence of approval by
the Information Security Department.

Information Security, in conjunction with business unit management, must
determine the default access levels that must be granted per a user's
role.

The Information Security Department must perform a bi-annual audit of
computer resource authorizations to confirm that access privileges are
appropriate. The audit must consist of validating access rights for
sample user populations.

The Information Security Department must collect additional approvals
for all access that is not associated with a defined access role.

Extension authorizations for contractor accounts must go through the
Information Security Department to provide an audit trail.

An Emergency ID must be established when access is needed to diagnose
and/or correct a problem.

-   The request to create the Emergency ID must be made via the
    > Information Security Department which must notify the appropriate
    > system administration team.

-   The requestor must inform the Information Security Department upon
    > completion of the work so that the ID can be disabled.

-   The Information Security Department must ensure that the Emergency
    > ID Request Form is completed as soon as practical (the completion
    > of this form should NOT delay providing access). The completed
    > form must be filed by the Information Security Department.

### System Administrator Responsibilities

Account creation requests must specify access either explicitly or via a
"role" that has been mapped to the required access. New accounts created
by mirroring existing user accounts must be audited against the explicit
request or roles for appropriate access rights.

If a user requests a password reset via phone, email, web or other
non-face-to-face method, that user's identity must be verified before
the password is reset. To verify the identity of the user, have the user
submit a request through email and sign the email using their public GPG
key.

Access should be removed immediately upon notification that access is no
longer required. Written procedures must be in place to ensure that
access privileges of terminated or transferred users are revoked as soon
as possible. Whenever possible validate employment using VGS &
COVERHOUND Human Resources systems and immediately suspend users who are
on leave-of-absence or extended disability.

User IDs should be disabled after sixty (60) days of inactivity. After
an additional thirty (30) days, disabled user IDs must be purged. These
requirements may not apply to certain specialized accounts (e.g., root).
In those instances, the System Administrator must provide a written
waiver to the Information Security Department and document the
compensating controls around access to the accounts.

All computer resources capable of displaying a custom sign-on or similar
message must display the following message as part of the login process:

*This system is for the use of authorized users only. Individuals using
this computer system without authority, or in excess of their authority,
are subject to having all of their activities on this system monitored
and recorded by system personnel. In the course of monitoring
individuals improperly using this system, or in the course of system
maintenance, the activities of authorized users may also be monitored.
Anyone using this system expressly consents to such monitoring and is
advised that if such monitoring reveals possible criminal activity,
system personnel may provide the evidence of such monitoring to law
enforcement officials.*

-   System Administrators must enable audit logs to record user and
    > administrative activities. Audit logs must be archived for a
    > minimum of one year with (90) days available for on-line viewing.

-   Passwords set by System Administrators must be changed by the user
    > immediately upon the user's next login. Systems must set initial
    > passwords that are unique and compliant with the password rules.

-   System Administrators must validate the identity of the user before
    > performing a password reset. The approved means for validating
    > identity at VGS is to ask the caller to also verify via their VGS
    > email and Slack account.

-   Contractor accounts must have Information Security Department
    > approval and must automatically expire at the end of the contract
    > date. Extensions must be requested through the Information
    > Security Department. System Administrators must monitor these
    > accounts carefully while they are in use.

-   Access must be immediately revoked for terminated users and for user
    > access that is no longer required.

-   Vendor accounts used for remote maintenance must only be enabled
    > during the time that access is needed.

-   Ensure that all systems and especially access to any databases
    > containing cardholder information is authenticated (e.g., users,
    > applications, administrators, etc.).

#### PCI Requirements Reference

### 

-   8.5.1 Control addition, deletion, and modification of user IDs,
    credentials, and other identifier objects.

-   8.5.2 Verify user identity before performing password resets.

-   8.5.3 Examine password procedures and observe security personnel to
    confirm that first-time passwords for new users are set to a unique
    value per user, and changed after first use.

-   8.5.4 Immediately revoke access for any terminated users.

-   8.5.5 Remove inactive user accounts at least every 90 days.

-   8.5.6 Enable accounts used by vendors for remote maintenance only
    during the time needed.

-   8.5.8 Do not permit group, shared, or generic accounts/passwords.

-   8.5.9 Change user passwords at least every 90 days.

-   8.5.16 Authenticate all access to any databases containing
    cardholder data. This includes access by applications,
    administrators, and all other users. Restrict user direct access or
    queries to databases to database administrators.

-   10.1 Establish a process for linking all access to system components
    (especially access done with administrative privileges such as root)
    to each individual user.

Data Retention and Disposal Policy
==================================

Policy Applicability
--------------------

All data deemed sensitive or confidential by the Information Security
Department which is stored on COVERHOUND CDE networks and systems must
follow this policy. Exemptions from this policy must be permitted only
if approved in advance and in writing by the Chief Security Officer.

Retention Requirements
----------------------

All sensitive and confidential data, regardless of storage location,
must be retained only as long as required for legal, regulatory and
business requirements. The specific retention length must be established
by the data creator or System Administrator and approved by the Chief
Security Officer.

As a special case, cardholder data used for single transactions may be
kept for up to 13 months which includes the period in which a card
holder can chargeback a transaction and supporting data must be
available to support a request for copy of a receipt of a refund if
necessary as well as providing COVERHOUND CDE customer base one year of
transactional reporting. Card data storage may be marked for truncation

Cardholder "authorization data", including track, CVV2, and PIN
information, must be retained only until completion of the authorization
of a transaction. Storage of cardholder authorization data
post-authorization is forbidden.

All system and network audit logs must be retained for one year with (90
days kept available for online use).

Old database encryption keys would be held for 90 days in case we have
to revert back to older database tapes before it is destroyed. Upon
reaching 90 days after the replacement of the encryption keys all old
keys must be destroyed per the disposal and destruction requirements set
forth in this document.

### PCI Requirements Reference

-   3.1 Keep cardholder information storage to a minimum. Develop a data
    > retention and disposal policy. Limit your storage amount and
    > retention time to that which is required for business, legal,
    > and/or regulatory purposes, as documented in the data retention
    > policy.

-   3.2 Do not store sensitive authentication data subsequent to
    > authorization (not even if encrypted):

-   3.2.1 Do not store the full contents of any track from the magnetic
    > stripe (that is on the back of a card, in a chip or elsewhere).
    > This data is alternatively called full track, track, track 1,
    > track 2, and magnetic stripe data.

-   3.2.2 Do not store the card-validation code or value (three-digit or
    > four-digit number printed on the front or back of a payment card)
    > used to verify card-not-present transactions.

-   3.2.3 Do not store the personal identification number (PIN) or the
    > encrypted PIN block.

-   10.7 Retain audit trail history for a period of at least one year,
    > with a minimum of three months online available.

Disposal Requirements
---------------------

All confidential or sensitive electronic data, when no longer needed for
legal, regulatory or business requirements must be removed from
COVERHOUND CDE systems using an approved method documented in this
policy. This requirement includes all data stored in cloud systems.

Disposal Process
----------------

Amazon Web Services' datacenters will be responsible for following the
accepted disposal process and related reporting. A programmatic
(automatic) process must be executed on cardholder information systems
weekly to remove all sensitive and confidential data that exceeds
business retention requirements.

### PCI Requirements Reference

### 

-   3.1 Keep cardholder data storage to a minimum. Develop a data
    > retention and disposal policy. Limit storage amount and retention
    > time to that which is required for business, legal, and/or
    > regulatory purposes, as documented in the data retention policy.

-   3.1.1 Implement a data retention and disposal policy that includes:

    -   Limiting data storage amount and retention time to that which is
        required for legal, regulatory and business requirements.

    -   Processes for secure deletion of data when no longer needed.

    -   Specific retention requirements for cardholder data.

    -   A quarterly automatic or manual process for identifying and
        securely deleting stored cardholder data that exceeds defined
        retention requirements.

Firewall and Router Security Administration Policy
==================================================

Policy Applicability
--------------------

All firewalls and routers on COVERHOUND CDE networks, whether managed by
employees or by third parties, must follow this policy. Exemptions from
this policy must be permitted only if approved in advance and in writing
by the Chief Security Officer.

Device Management Responsibilities
----------------------------------

Management of all COVERHOUND CDE firewalls and routers shall be a
combined effort of the System Administrator, the Network Operations
Center and the Information Security Department. The following
subsections detail the responsibilities for these groups.

### System Administrator

-   Assure that changes to firewall hardware or software or security
    > rules are approved by the Information Security Department and
    > follow all change control policies and procedures.

-   Document all firewall security rule changes utilizing [Appendix E,
    > Permitted Network Services and
    > Protocols](http://livepage.apple.com/).

-   Following every change, review and update network diagrams to assure
    > they accurately describe all connections to confidential or
    > sensitive information and critical network protection mechanisms
    > (e.g., firewalls, IDS/IPS, Anti-virus systems, access control
    > systems, etc.).

-   Enable appropriate logging on all security systems and perform
    > active daily monitoring of the logs that report security events.

-   Provide the Network Operations Center with read-only access to logs
    > related to the critical systems health and performance.

-   Provide the Network Operations Center and Information Security
    > Department with read-only access to security event logs.

-   Report network security incidents to the Information Security
    > Department immediately upon discovery.

-   Coordinate an appropriate response with the Information Security
    > Department to mitigate security events.

-   Ensure that router configuration files are secured and synchronized
    > properly.

### Network Operations Center

-   Monitor system and application specific alerts on critical systems
    > (e.g., interface up/down, firewall daemon failing, system reboots,
    > etc.)

-   Notify the appropriate parties in the event of a security system
    > failure or security event.

### Information Security Department

-   Assure that security rules applied to the firewalls are sufficient
    > to protect COVERHOUND CDE networks and corporate assets from
    > external attacks and unauthorized access.

-   Assure that security rules applied to the firewalls are sufficient
    > to prevent internal security events from leaving the COVERHOUND
    > CDE network.

-   Review all firewall and router security rule change requests for
    > policy compliance prior to submission through the change
    > management process.

-   Ensure that all protocols/services allowed through the firewalls are
    > properly documented

-   Ensure risky protocols have undergone a risk assessment and have a
    > current documented business need.

-   Actively monitor firewall security events to identify internal or
    > external security incidents.

-   Conduct quarterly review of all firewall policies.

-   Coordinate an appropriate response with the System Administrator to
    > mitigate security events.

It is imperative that all changes to firewall configurations,
specifically on Amazon Web Services, such as, but not limited to
security groups or route tables to go through another set of internal or
external penetration testing. Please see:
<http://awsmedia.s3.amazonaws.com/pdf/aws_security_whitepaper.pdf>. In
Amazon Web Services, Traditional Layer 2 security attacks, including MAC
spoofing and ARP spoofing, are blocked. However, network and firewall
changes must be confirmed to make sure there is no accidental, intended
or unintended, unless via special exception by the Chief Security
Officer, risk vector that is opened.

#### PCI Requirements Reference

### 

1.1.4 Description of groups, roles, and responsibilities for logical
management of network components.

1.1.5 Documentation and business justification for use of all services,
protocols, and ports allowed, including documentation of security
features implemented for those protocols considered to be insecure.

1.1.7 Requirement to review firewall and router rule sets at least every
six months.

1.2.2 Secure and synchronize router configuration files.

Firewall Configuration Changes
------------------------------

Because firewalls support critical COVERHOUND CDE information systems
activities they are considered to be production systems.

Firewall changes should not be performed unless they have been approved
following the Change Control process.

All firewall changes must be approved by the Information Security
Department and must be adequately tested following production standards
as defined in the Change Control Policy. These changes include, but are
not limited to:

-   Firewall rule additions, deletions, and modifications.

-   Firewall software or system modifications.

-   Firewall software or system upgrades, patches, or hot-fixes.

### PCI Requirements Reference

### 

1.1.1There must be a formal process for approving and testing all
network connections and changes to the firewall and router
configuration.

Allowed Services
----------------

Every connectivity path and service that is not specifically permitted
by this policy, with supporting documents issued by the Information
Security Department, must be blocked by COVERHOUND CDE firewalls. The
list of currently approved paths and services, with justifications, is
listed in [Appendix E, Permitted Network Services and
Protocols](http://livepage.apple.com/).

Additions and / or deletions to the connectivity path must be approved
by Change Control Team and performed during the time frame it was
approved.

### PCI Requirements Reference

### 

1.1.5Documentation and business justification for use of all services,
protocols, and ports allowed, including documentation of security
features implemented for those protocols considered to be insecure.

1.1.5.aVerify that firewall and router configuration standards include a
documented list of services, protocols and ports necessary for
business---for example, HTTP and SSL, Secure Shell (SSH) and VPN
protocols.

1.2 Build a firewall configuration that denies all traffic from
"untrusted" networks and hosts, except for protocols necessary for the
cardholder data environment.

Allowed Network Connection Paths and Configuration Requirements
---------------------------------------------------------------

All Internet-based inbound traffic is only permitted into a firewall
segmented demilitarized zone (DMZ) network. In all cases, this traffic
should be limited to only ports necessary for COVERHOUND CDE business
requirements. Perimeter routers should not be configured with a route to
internal address space with the exception of the DMZ.

Internal IP addresses must be hidden utilizing Network Address
Translation (NAT) or Port Address Translation (PAT).

Anti-spoofing technologies must be configured on perimeter devices,
denying or rejecting all traffic with a:

-   Source IP address matching internally allocated or COVERHOUND CDE
    > owned address space.

-   Source IP address matching RFC 1918 address space.

-   Destination IP address matching RFC 1918 address space.

Outbound traffic from internal production systems must only be allowed
to the COVERHOUND CDE DMZ network. Additionally, this traffic should be
restricted to only required protocols and services.

Databases must be located on DMZ network segments which are segmented
from the COVERHOUND CDE application DMZ network. Inbound connections to
internal production payment systems and card holder systems, and
originating from COVERHOUND CDE wireless networks, are not permitted.

The use of a stateful packet inspection firewall must be utilized for
Internet and wireless segmentation to only allow established connections
into or out of each particular network segment. VLANs with compliant
ACLs may be used for cardholder environment segmentation so long as the
VLAN switch is compliant with PCI and hardened to prevent all currently
identified switch exploits (e.g. ARP cache flood). If VLANs are used for
segmenting all requirements for firewalls apply (e.g. deny all but
business necessary traffic, change control, etc.).

### PCI Requirements Reference

### 

1.1.3Requirements for a firewall at each Internet connection and between
any demilitarized zone (DMZ) and the internal network zone.

1.3 Prohibit direct public access between the Internet and any system
component in the cardholder data environment.

> 1.3.1Implement a DMZ to limit inbound traffic to only system
> components that provide authorized publically accessible services,
> protocols, and ports.
>
> 1.3.2Limit inbound Internet traffic to IP addresses within the DMZ.
>
> 1.3.3 Do not allow any direct connections inbound or outbound for
> traffic between the Internet and the cardholder data environment.
>
> 1.3.4 Do not allow internal addresses to pass from the Internet into
> the DMZ
>
> 1.3.5Do not allow unauthorized outbound traffic from the cardholder
> data environment to the Internet.
>
> 1.3.6Implementing stateful inspection, also known as dynamic packet
> filtering (that is, only \"established\" connections are allowed into
> the network).
>
> 1.3.7Place system components that store cardholder data (such as a
> database) in an internal network zone, segregated from the DMZ and
> other untrusted networks.

Configuration Review
--------------------

At least quarterly, the Information Security Department must thoroughly
review each firewall rule set and record results of the review. The
review must include the removal, when merited, of unused or unnecessary
access paths. All proposed changes identified as a result of this review
must go through the current change control process prior to
implementation.

### PCI Requirements Reference

### 

1.1.7 Requirement to review firewall and router rule sets at least every
six months.

Personal Firewalls
------------------

All mobile and/or employee-owned computers with direct connectivity to
the Internet (e.g., laptops used by employees) that are used to access
the COVERHOUND CDE network must have personal firewall software
installed and activated. All such software must have a non-user
alterable configuration as dictated by the Information Security
Department.

### PCI Requirements Reference

### 

1.4 Install personal firewall software on any mobile and employee-owned
computers with direct connectivity to the internet (for example laptops
used by employees), which are used to access the organization's network.

System Configuration Policy
===========================

Policy Applicability
--------------------

All servers and network devices on COVERHOUND CDE networks, whether
managed by employees or by third parties, must be built and deployed in
accordance with this policy. Exemptions from this policy must be
permitted only if approved in advance and in writing by the Chief
Security Officer.

System Build and Deployment
---------------------------

### System Purpose

All computing systems should be designated for a single primary purpose
where possible (e.g., web servers, database servers, and DNS should be
implemented on separate servers). No multi-purpose systems may, under
any circumstances, store, transmit, or process confidential or sensitive
data unless required by vendor documentation (e.g., SAP, Peoplesoft,
ipAngel, Cisco Pix with add-ons, etc.).

### 

### PCI Requirements Reference

### 

2.2.1 Implement only one primary function per server to prevent
functions that require different security levels from co-existing on the
same server (e.g., web servers, database servers, and DNS should be
implemented on separate servers).

System Configuration Standards
------------------------------

All systems, prior to deployment in the production environment must
conform to the [System Configuration Standards (Appendix
F)](http://livepage.apple.com/). A valid business justification and risk
assessment must exist for all deviations from VGS published
configuration standards. Deviations require written approval by the
Information Security Department and must be noted on the System
Configuration Record (Appendix G) for the system.

System Configuration Records
----------------------------

**(Automated) System Configuration Process **

All server virtual machine Instances within the COVERHOUND CDE
environment are built utilizing a VGS prepared private AMI images. VGS
uses stock AWS Marketplace source images to create VGS private images.
The stock source image is provided by the given distribution's vendor.
For instance, the VGS Ubuntu AMI was built from Canonicals' official AWS
Marketplace image.

VGS applies the appropriate Center for Internet Security (CIS) baselines
to VGS private images. CIS Baseline hardening is applied via an Ansible
playbook and the default rules from the Wazuh OSSEC plugin are used to
verify that the CIS Baseline is met before deployment and on a continual
basis thereafter. VGS VM instances are then deployed using a VGS private
image. OSSEC is configured to alert on any and all deviations from the
CIS standard. Each build script and playbook is reviewed by the CISO and
peer reviewed by Security Engineering to ensure that it is correct,
complete, and properly configured for each build.

(Manual) System Configuration Process
-------------------------------------

For all manually deployed systems, A [System Configuration Record
(Appendix G)](http://livepage.apple.com/) must be completed at the time
of installation and kept on file for as long as the system is in
service. This form must be updated with any future modifications to
system configurations.

All new *manual* system deployments must follow the following high level
procedure:

1.  Install operating system.

2.  Update all operating system software per vendor recommendations.

3.  Configure operating system parameters and secure the system
    > according to the system configuration build documentation
    > described in Appendix F.

4.  Install applications and software:

<!-- -->

a.  Install system specific applications and software according to
    > System Configuration Record (if this is a replacement for an
    > existing system).

b.  Install applications and software necessary for the systems purpose.

c.  Configure Network Time Protocol (NTP).

<!-- -->

5.  Update all application software per vendor recommendations.

6.  Configure application parameters according to build document
    > (application hardening).

7.  Enable logging per [[Logging Controls
    > (Section 15)]{.underline}](#Logging_Controls).

8.  For systems containing confidential or sensitive information deploy
    > file integrity monitoring (FIM) software to alert personnel to
    > unauthorized modification of critical system or content files.
    > Configure FIM to perform critical file comparisons at least
    > weekly.

9.  Complete system specific System Configuration Record (Appendix G)
    > and maintain on file.

### PCI Requirements Reference

### 

2.2.2Enable only necessary and secure services, protocols, daemons,
etc., as required for the function of the system. Implement security
features for any required services, protocols or daemons that are
considered to be insecure---for example, use secured technologies such
as SSH, S-FTP, SSL, or IPSec VPN to protect insecure services such as
NetBIOS, file-sharing, Telnet, FTP, etc.

2.2.3 Configure system security parameters to prevent misuse.

Audit Procedure 2.2.3.b Verify that common security parameter settings
are included in the system configuration standards.

2.2.4 Remove all unnecessary functionality, such as scripts, drivers,
features, subsystems, file systems, and unnecessary web servers. Also,
verify enabled functions are documented and only documented
functionality is present.

11.5 Deploy file integrity monitoring tools to alert personnel to
unauthorized modification of critical system files, configuration files,
or content files; and configure the software to perform critical file
comparisons at least weekly. Note: For file integrity monitoring
purposes, critical files are usually those that do not regularly change,
but the modification of which could indicate a system compromise or risk
of compromise. File integrity monitoring products usually come
pre-configured with critical files for the related operating system.
Other critical files, such as those for custom applications, must be
evaluated and defined by the entity (that is, the merchant or service
provider).

Standard Software
-----------------

The following list must be considered standard installed software on all
applicable systems. A valid business justification and risk assessment
must exist for all deviations from VGS published configuration
standards. Any such deviations require written approval by the
Information Security Department, and noted on the System Configuration
Record (Appendix G) for the system (see below).

-   File servers, mail servers, and Windows-based systems

-   Anti-Virus software

-   Critical production systems

-   File Integrity software

-   Notebooks/Laptops

-   Personal Firewall software

-   VPN Client software

### PCI Requirements Reference

> 1.4 Install personal firewall software on any mobile and/or
> employee-owned computers with direct connectivity to the Internet (for
> example, laptops used by employees), which are used to access the
> organization's network.
>
> 5.1 Deploy anti-virus software on all systems commonly affected by
> viruses (particularly personal computers and servers).
>
> 5.2 Ensure that all anti-virus mechanisms are current, actively
> running, and generating audit logs.

### 

Network Time Protocol (NTP)
---------------------------

With the exception of the internal COVERHOUND CDE NTP server(s), all
COVERHOUND CDE production systems must be configured to use one of the
internal NTP servers to maintain time synchronization with other systems
in the environment.

The internal COVERHOUND CDE NTP server would be configured to request
time updates from the Internet site time.nist.gov. All client systems
and workstations must request time updates from the MGMT1 server.
Firewall rules must allow all servers to access this server over the NTP
protocol.

The NTP system must at all times be running the latest available version
of the software.

### PCI Requirements Reference

### 

10.4 Using time-synchronization technology, synchronize all critical
system clocks and times and ensure that the following is implemented for
acquiring, distributing, and storing time. Note: One example of time
synchronization technology is Network Time Protocol (NTP).

> 10.4.1 Critical systems have the correct and consistent time.
>
> 10.4.2 Time data is protected.
>
> 10.4.3 Time settings are received from industry-accepted time sources.

Credit Card Information Processing Application
----------------------------------------------

All COVERHOUND CDE applications, dealing with the processing or
retrieval of cardholder information, must be configured in a manner
which masks or truncates displayed credit card number if possible. If
the application is designed for a specific purpose in which the full
credit card number must be displayed approval must be given by the
Information Security Department during the Requirements Phase as
described in section 12 Software Development Policy. In all cases
displaying full or masked card numbers must be limited to the fewest
number of users possible.

Display of cardholder information must be done only within controlled
environments with no access to fax machines, copy machines, internet,
printers and other devices that may allow copying sensitive data.

### PCI Requirements Reference

### 

3.3 Mask PAN when displayed (the first six and last four digits are the
number of digits to be displayed). Notes: This requirement does not
apply to employees or other parties with a legitimate business need to
see the full PAN. This requirement does not supersede stricter
requirements in place for displays of cardholder---for example, point of
sale (POS) receipts.

3.4Render PAN unreadable anywhere it is stored (including on portable
digital media, backup media, and in logs) by using any of the following
approaches:

-   One-way hashes based on strong cryptography (hash must be of the
    > entire PAN).

-   Truncation (hashing cannot be used to replace the truncated segment
    > of the PAN).

-   Index tokens and pads (pads must be securely stored).

-   Strong cryptography with associated key-management processes and
    > procedures.

Note: It is a relatively trivial effort for a malicious individual to
reconstruct original PAN data if they have access to both the truncated
and hashed version of the PAN. Where hashed and truncated versions of
the same PAN are present in an entity's environment, additional controls
should be in place to ensure that the hashed and truncated versions
cannot be correlated to reconstruct the original PAN.

Credit Card Storage Applications
--------------------------------

All COVERHOUND CDE applications, dealing with the storage of cardholder
information, must be configured in a manner which does not retain
sensitive cardholder data, such as full track data, card-validation
codes, card not present values, pins or pin blocks. Storage devices on a
network must be on an internal network segregated from the DMZ. All
access to networked storage devices must have its authentication and
communication encrypted. The PAN must be rendered unreadable through one
of the following:

-   Strong one-way hash functions (hashed indexes) with salts

-   Truncation

-   Index tokens and pads (pads must be securely stored)

-   Strong cryptography with associated key management processes and
    > procedures

### PCI Requirements Reference:

> 1.3.7 Place system components that store cardholder data (such as a
> database) in an internal network zone, segregated from the DMZ and
> other untrusted networks.

3.2.1 Do not store the full contents of any track (from the magnetic
stripe located on the back of a card, equivalent data contained on a
chip, or elsewhere). This data is alternatively called full track,
track, track 1, track 2, and magnetic stripe data. Note: In the normal
course of business, the following data elements from the magnetic stripe
may need to be retained:

-   The cardholder's name

-   Primary account number (PAN)

-   Expiration date

-   Service code

To minimize risk, store only these data elements as needed for business.

3.2.2 Do not store the card verification code or value (three-digit or
four-digit number printed on the front or back of a payment card) used
to verify card-not-present transactions.

3.2.3Do not store the personal identification number (PIN) or the
encrypted PIN block.

3.4 Render PAN unreadable anywhere it is stored (including on portable
digital media, backup media, and in logs) by using any of the following
approaches:

-   One-way hashes based on strong cryptography (hash must be of the
    > entire PAN).

-   Truncation (hashing cannot be used to replace the truncated segment
    > of the PAN).

-   Index tokens and pads (pads must be securely stored).

-   Strong cryptography with associated key-management processes and
    > procedures.

Note: It is a relatively trivial effort for a malicious individual to
reconstruct original PAN data if they have access to both the truncated
and hashed version of the PAN. Where hashed and truncated versions of
the same PAN are present in an entity's environment, additional controls
should be in place to ensure that the hashed and truncated versions
cannot be correlated to reconstruct the original PAN.

> 8.4 Render all passwords unreadable during transmission and storage on
> all system components using strong cryptography.

Vulnerability Identification and System Updates
-----------------------------------------------

### Vulnerability Identification

Members of the Information Security Department must be informed of
information security issues and vulnerabilities applicable to COVERHOUND
CDE computing systems immediately after they occur. When security issues
are identified, the Information Security Department is responsible for
notifying senior management, associations, regulators as required and
appropriate VGS and 3rd party service providers personnel, including
system and network administrators.

The primary method for identifying new threats as they arise must be
through vendor and security specific Internet mailing lists. Although
not complete, the following lists should be subscribed to as well as
other vendor lists applicable to VGS specific software packages and
systems:

-   CERT

-   Spiceworks

-   -   [National Vulnerability Database](https://nvd.nist.gov/)SANS

-   

[Mitre](https://cve.mitre.org/)COVERHOUND CDE System Configuration
Standards (Appendix F) must be updated to reflect measures required for
protection from any newly discovered vulnerability.

Risk Ranking
------------

Newly discovered vulnerabilities are typically ranked a score from 1 --
10 from the various vulnerability databases such as CERT, NVD, and
Mitre. VGS adheres to the scores provided by vendors and independent
3^rd^ party organizations unless otherwise justified in a documented and
approved business justification for mitigation.

-   Scores that range between 8 -- 10 are classified as EMERGENCY

-   Scores that range between 6 -- 8 are classified as HIGH

  Classification       Patch Timeline   NIST CVE rating   Explanation
  -------------------- ---------------- ----------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Critical/Emergency   \< 7 days        8-10              CVE rating of 8-10 and/or remotely exploitable
  High                 \< 15 days       6-8               CVE rating between 6 and 8. A vulnerability whose exploitation could result in compromise of the confidentiality, integrity, or availability of users data, or of the integrity or availability of processing resources.
  Medium               \< 30 days       \<6               CVE rating less than 6 or where exploitability is mitigated to a significant degree by factors such as default configuration, auditing, or difficulty of exploitation
  Low                  \< 45 days       \<5               A vulnerability whose exploitation is extremely difficult, or whose impact is minimal.

See Emergency Process Flow for more details.

#### PCI Requirements Reference:

6.2 Establish a process to identify and assign a risk ranking to newly
discovered security vulnerabilities. Notes:

-   Risk rankings should be based on industry best practices. For
    > example, criteria for ranking "High" risk vulnerabilities may
    > include CVSS base score of 4.0 or above and/or a vendor-supplied
    > patch classified by the vendor as "critical," and/or a
    > vulnerability affecting a critical system component.

-   The ranking of vulnerabilities as defined in 6.2.a is considered a
    > best practice until June 30, 2012, after which it becomes a
    > requirement.

6.2.a Interview responsible personnel to verify that processes are
implemented to identify new security vulnerabilities, and that a risk
ranking is assigned to such vulnerabilities. (At a minimum, the most
critical, highest risk vulnerabilities should be ranked as "High.")

### Vulnerability Testing

The Information Security Department is responsible for conducting
internal and external network vulnerability scans at least quarterly and
after any significant change in the network (e.g., new system component
installations, changes in network topology, firewall rule modifications,
product upgrades). This process includes identifying any unauthorized
wireless devices on the network.

Additional external vulnerability scans must be performed by a scan
vendor qualified by the payment card industry at least quarterly.

Penetration tests at both the application and network layer must be
performed annually or after any significant change in the network. VGS
must utilize a 3^rd^ party provider for all penetration testing.

Networks and systems that fall under payment card system scope must also
be monitored by an intrusion detection/prevention system that alerts
personnel of potential compromises

All potential vulnerabilities identified through vulnerability scans and
penetration tests must be communicated to appropriate personnel within
VGS for assessment and remediation. All high-level vulnerabilities must
be corrected utilizing the Change Control Policy. Follow up scans must
be performed to confirm compliance with VGS security standards.

The Chief Security Officer must coordinate an annual formal risk
assessment process that identifies any existing or new threats and
vulnerabilities to ensure COVERHOUND CDE assets are adequately
protected.

#### PCI Requirements Reference: 

11.1 Test for the presence of wireless access points and detect
unauthorized wireless access points on a quarterly basis. Note: Methods
that may be used in the process include but are not limited to wireless
network scans, physical/logical inspections of system components and
infrastructure, network access control (NAC), or wireless IDS/IPS.
Whichever methods are, they must be sufficient to detect and identify
any unauthorized devices.

11.2 Run internal and external network vulnerability scans at least
quarterly and after any significant change in the network (such as new
system component installations, changes in network topology, firewall
rule modifications, product upgrades).

11.3 Perform external and internal penetration testing at least once a
year and after any significant infrastructure or application upgrade or
modification (such as an operating system upgrade, a sub-network added
to the environment, or a web server added to environment).

These penetration tests must include the following:

11.3.1Network-layer penetration tests

11.3.2Application-layer penetration tests

11.4 Use intrusion-detection systems and/or intrusion prevention systems
to monitor all network traffic at the perimeter of the cardholder data
environment as well as at critical points inside the cardholder data
environment, and alert personnel to suspected compromises. Keep all
intrusion-detection and prevention engines, baselines, and signatures
up-to-date.

12.1.2 The information security policy includes an annual process that
identifies threats, and vulnerabilities, and results in a formal risk
assessment.

### Security Patch Deployment

All security patches, hot-fixes and service packs identified by the
Information Security Department or system administrators must be applied
to applicable systems within (30) days of vendor release. As with any
change to the environment the change management process must be
followed.

#### PCI Requirements Reference:

6.1 Ensure that all system components and software are protected from
known vulnerabilities by having the latest vendor-supplied security
patches installed. Install critical security patches within one month of
release.

Anti-Virus Policy
=================

Policy Applicability
--------------------

All Microsoft Windows based systems, file servers and email servers on
COVERHOUND CDE networks, whether managed by employees or by third
parties, must follow this policy. If any systems are added to the CDE
that are similarly vulnerable to malicious software, those systems must
also follow this policy. Exemptions from this policy must be permitted
only if approved in advance and in writing by the Chief Security
Officer.

Currently, neither Coverhound nor VGS utilizes any Microsoft Windows
based systems on COVERHOUND CDE networks.

Software Configuration
----------------------

VGS utilizes Google Business for email. Google maintains an up-to-date
database of virus signatures and continually checks for viruses in the
email system. On an annual basis, VGS monitors Google Business Suite's
compliances.

Under no circumstances should any system be allowed to disable its AV
application, or be placed into a production capacity without a fully
operational and updated anti-virus program prior to the system being
connected to the VGS network in any manner.

### PCI Requirements Reference:

5.1 Deploy anti-virus software on all systems commonly affected by
viruses (particularly personal computers and servers).

> 5.1.1 Ensure that anti-virus programs are capable of detecting,
> removing, and protecting against other forms of malicious software.

Signature Updates
-----------------

All systems with anti-virus software must be configured to update virus
signatures on at least a daily basis.

### PCI Requirements Reference:

5.2 Ensure that all anti-virus mechanisms are current, actively running,
and generating audit logs.

Software Logging
----------------

Anti-virus software must alert the Information Security Department in
real-time to the detection of a virus.

The Information Security Department must determine what steps to take
based on the []{.underline}Incident Response Plan and
Procedures[.]{.underline}

Retention of Anti-Virus software logs must be in accordance with
[]{.underline}Data Retention and Disposal Policy.

### PCI Requirements Reference:

5.2 Ensure that all anti-virus mechanisms are current, actively running,
and generating audit logs.

Backup Policy
=============

Policy Applicability
--------------------

All system and application backups, whether performed by employees or by
third parties, must follow this policy. Exemptions from this policy must
be permitted only if approved in advance and in writing by the Chief
Security Officer.

Location
--------

The backup media for each of these systems is relocated to a secure
off-site storage area.

The off-site storage location must be visited annually by management or
a member of the Department to confirm that it is physically secure and
fireproof.

Transport
---------

Offline storage media utilized for archival or back-up purposes must be
handled and retained in a secured environment such that only VGS
personnel and contracted storage facility personnel have access to the
archival media.

All media couriers and transport mechanisms must be certified by the
Information Security Department.

Positive log-out and log-in of archive media must take place during all
archive media transfers. All media that is transferred from one location
to another should be logged as being transferred, by whom, where, and
was it properly received, with signature from management. The Backup
Media Transfer Log is located in [Appendix
COVERHOUND](http://livepage.apple.com/).

All media containing confidential or sensitive data must be classified
and identifiable as such prior to transfer as detailed in the Data
Classification and Control Policy.

Audit
-----

All media used must be classified as confidential or sensitive and
assigned a unique tracking number or similar feature that uniquely
identifies the media. All media must be registered with the Information
Security Department for tracking prior to use.

Quarterly inventories of all stored media must take place. The
Information Security Department must compare their list of in-use media
with records at the storage facility using the [Media Inventory Log
(Appendix D)](http://livepage.apple.com/).

Media Destruction
-----------------

All media that is no longer needed or has reached end-of-life must be
destroyed or rendered unreadable so that no data may be extracted.
Information on acceptable destruction techniques is detailed in the Data
Retention and Disposal policy.

Encryption Policy
=================

Policy Applicability
--------------------

This policy documents the encryption standards that must be applied to
all applicable mechanisms and systems on COVERHOUND CDE networks,
whether managed by employees or by third parties. This policy also
applies to the management of encryption keys which may be shared with
customers to exchange confidential information. Documentation provided
to customers who have a need to exchange encryption keys with COVERHOUND
CDE must include these guidelines. Exemptions from this policy must be
permitted only if approved in advance and in writing by the Chief
Security Officer.

Encryption Key Management
-------------------------

Keys must be generated, accessed, distributed and stored in a controlled
and secured manner.

### Key Access

Keys used to encrypt and decrypt cardholder data must be protected from
general access. Only approved custodians should be able to access the
key components.

Access to encryption key components must only be granted to those
custodians specifically requiring access due to job function. All access
may only be granted by the Chief Security Officer and those requiring
access must have so noted on their [Authorization Request Form (Appendix
B)](http://livepage.apple.com/). Additionally, these users must sign the
[Encryption Key Custodianship Form (Appendix
I)](http://livepage.apple.com/) specifying that they understand their
key custodian responsibilities. These forms must be maintained by Human
Resources in the employee's file.

#### PCI Requirements Reference:

3.5.1 Restrict access to cryptographic keys to the fewest number of
custodians necessary.

3.6.8 Requirement for cryptographic key custodians to formally
acknowledge that they understand and accept their key-custodian
responsibilities.

### Split Knowledge and Dual Control

Two or three custodians (depending on the system) authorized by the
Information Security Department are required to collaborate to perform
any key action (such as key generation or loading the key).
Additionally, no single custodian may know or have access to all pieces
of a data encryption key.

#### PCI Requirements Reference:

3.6.6 If manual clear-text cryptographic key management operations are
used, these operations must be managed using split knowledge and dual
control (for example, require two or three people, each knowing only
their own key component, to reconstruct the whole key).

### Key Generation

Only strong encryption keys are to be used. Creation of encryption keys
must be accomplished using a random or pseudo-random number generation
algorithm. Depending on the encryption scheme in question, the following
are minimum length requirements for the encryption keys:

-   Triple-DES -- 128 bits

-   AES -- 128 bits

-   RSA -- 1024 bits

-   Vendor recommendations/best practices for other encryption
    > methodologies

Generating encryption keys must be accomplished by two (or three
depending on the system) custodians authorized by the Information
Security Department. Each custodian must generate one clear text piece
that would be used to create the encryption key.

To prevent unauthorized substitution of keys physical and logical access
to the key generating procedures and mechanisms must be secured.

#### PCI Requirements Reference:

3.6.1 Generation of strong cryptographic keys.

3.6.7 Prevention of unauthorized substitution of cryptographic keys.

### Key Distribution

Only custodians authorized by the Information Security Department are
allowed to retrieve key components from secure storage or distribute
keys. Custodians must document all such actions in the [Encryption Key
Management Log (Appendix J)](http://livepage.apple.com/). Key component
custodians may only convey keys using the Key Component Transfer Form
(Appendix R), sealed in individual tamper evident packaging and shipped
via separate traceable delivery services to the individual recipient key
custodians. Upon completion of key actions, the encryption keys must be
placed in secure, tamper-evident packaging prior to being returned to
secure storage.

#### PCI Requirements Reference:

3.6.b Service providers that share keys with customers for transmission
or storage of cardholder data must provide documentation that includes
guidance on how to securely transmit, store and update customer's keys.

3.6.2 Secure cryptographic key distribution

### Key Storage

All data encryption keys must be stored encrypted and in a secure
location. Key-encrypting keys must be stored separate from
data-encrypting keys within applicable applications.

Clear-text backups of encryption key components must be stored
separately in tamper-evident packaging in a secure location utilizing
split knowledge and dual controls.

In all cases, key components must be securely stored in the fewest
possible locations and forms.

#### PCI Requirements Reference:

3.5.2 Store cryptographic keys securely in the fewest possible locations
and forms.

3.5.2.a Review system configuration files to determine that storage of
cryptographic keys in encrypted format and storage of key-encrypting
keys separately from data-encrypting keys.

3.6.3 Secure cryptographic key storage.

3.6.6 If manual clear-text cryptographic key management operations are
used, these operations must be managed using split knowledge and dual
control (for example, require two or three people, each knowing only
their own key component, to reconstruct the whole key).

### Key Changes and Destruction

An encryption key change is the process of generating a new key,
decrypting the current production data and re-encrypting the
confidential data with the new key.

All data encryption keys must be changed yearly or when circumstances
dictate a change to maintain encryption or key integrity. The following
dictates when a key change is required:

-   Regular Rotation: Encryption Keys have a lifetime of 1 year and must
    > be changed a minimum of 1 time per year.

-   Suspicious Activity: This change is driven by any activity related
    > to the key process which raises concern regarding the security of
    > the existing key.

-   Resource Change: Keys must be changed if a resource with knowledge
    > of the keys terminates employment or assumes a new job role that
    > no longer requires access to an encryption process.

-   Technical Requirement: Keys must be changed if the key in place has
    > become questionable due to a technical issue such as corruption or
    > instability.

Encryption keys no longer in service are to be disposed of in accordance
with the process outlined in the Data Retention and Disposal Policy.

#### PCI Requirements Reference:

> 3.6.4 Cryptographic keys must be changed when those keys have reached
> the end of their crypto period (for example, after a defined period of
> time has passed and/or after a certain amount of cipher-text has been
> produced by a given key), as defined by the associated application
> vendor or key owner, and based on industry best practices and
> guidelines (for example, NIST Special Publication 800-57).
>
> 3.6.5 Retirement or replacement (for example, archiving, destruction,
> and/or revocation) of keys as deemed necessary when the integrity of
> the key has been weakened (for example departure of an employee with
> knowledge of a clear-text key), or keys are suspected of being
> compromised. Note: If retired or replaced cryptographic keys need to
> be retained, these keys must be securely archived (for example, by
> using a key encryption key). Archived cryptographic keys should only
> be used for decryption/verification purposes.

#### PCI Requirements Reference:

> 3.6.4 Cryptographic keys must be changed when those keys have reached
> the end of their cryptoperiod (for example, after a defined period of
> time has passed and/or after a certain amount of cipher-text has been
> produced by a given key), as defined by the associated application
> vendor or key owner, and based on industry best practices and
> guidelines (for example, NIST Special Publication 800-57).
>
> 3.6.5 Retirement or replacement (for example, archiving, destruction,
> and/or revocation) of keys as deemed necessary when the integrity of
> the key has been weakened (for example departure of an employee with
> knowledge of a clear-text key), or keys are suspected of being
> compromised. Note: If retired or replaced cryptographic keys need to
> be retained, these keys must be securely archived (for example, by
> using a key encryption key). Archived cryptographic keys should only
> be used for decryption/verification purposes.

Transmission over Un-trusted Networks
-------------------------------------

Confidential and sensitive information must be encrypted during
transmission over networks in which is it easy and common for the data
to be intercepted, modified or diverted. Only strong encryption that are
acceptable are:

-   Transport Layer Security v1.2+ (TLS)

### PCI Requirements Reference:

4.1 Use strong cryptography and security protocols (for example,
SSL/TLS, IPSEC, SSH, etc.) to safeguard sensitive cardholder data during
transmission over open, public networks.

### Transmission of Confidential Information via End-User Messaging Technology

Confidential and sensitive information is never to be sent unencrypted
through email, instant messaging, chat, etc. Employees, with a valid
business justification, must be issued email encryption software by the
Information Security Department. Under no circumstances is card holder
or any identification sensitive data sent via electronic email.

#### PCI Requirements Reference:

4.2 Never send unprotected PANs by end-user messaging technologies (for
example, e-mail, instant messaging, chat, etc.).

### Encryption of Wireless Networks

All wireless networks in use at VGS facilities must be protected using
industry best practices for strong encryption of authentication and
transmission.

Under no circumstances should the encryption strength be configured to
be less than 128 bits. Wireless encryption keys would be changed every
ninety (90) days or whenever an administrator with knowledge of the keys
is terminated.

#### PCI Requirements Reference:

4.1.1 Ensure wireless networks transmitting cardholder data or connected
to the cardholder data environment, use industry best practices (for
example, IEEE 802.11i) to implement strong encryption for authentication
and transmission.

Special Technologies Usage Policy
=================================

Policy Applicability
--------------------

All users of special technologies deployed on COVERHOUND CDE networks,
whether employees or contractors, must follow this policy. Exemptions
from this policy must be permitted only if approved in advance and in
writing by the Chief Security Officer.

Currently, "special technologies" refers to modem use, modem access,
wireless networks and other employee-facing technologies within the
COVERHOUND CDE computing environment. This policy must be modified in
the future to include any new "special technologies" used.

PCI Requirements Reference:
---------------------------

12.3 Develop usage policies for critical technologies (for example,
remote-access technologies, wireless technologies, removable electronic
media, laptops, tablets, personal data/digital assistants (PDAs), e-mail
usage and Internet usage) and define proper use of these technologies.

Approval
--------

The Information Security Department must explicitly approve any use or
deployment of special technologies by job function role or on an
individual basis. For general user application, this includes: dial-in
modem access, personal modem deployment, and wireless network access.
These approvals must be documented on the user's [Authorization Request
Form (Appendix B)](http://livepage.apple.com/).

PCI Requirements Reference:
---------------------------

12.3.1 Explicit approval by authorized parties.

Authentication
--------------

User authentication mechanisms, where possible, must be integrated into
the current COVERHOUND CDE authentication systems. Under no
circumstances may the user authentication requirements be less strict
than currently defined policies and procedures (e.g., complex passwords,
password change interval, etc.).

All remote access to the COVERHOUND CDE network using these technologies
must be authenticated via a strong two-factor authentication scheme
approved by the Information Security Department.

### PCI Requirements Reference:

8.3 Incorporate two-factor authentication for remote access
(network-level access originating from outside the network) by
employees, administrators, and third parties. (For example, remote
authentication and dial-in service (RADIUS) with tokens; terminal access
controller access control system (TACACS) with tokens; or other
technologies that facilitate two-factor authentication.)

Device Inventory
----------------

All approved user devices (personal modems and wireless network
interfaces) must be noted on the [Special Technologies Device Inventory
(Appendix K)](http://livepage.apple.com/) by the Information Security
Department. All approved users of these technologies must be noted on
the [Special Technologies User List (Appendix
L)](http://livepage.apple.com/). Users that must be documented include:

-   Wireless network users

-   Personal modem possessors

-   Employees with dial-in access

-   Vendors with dial-in access

### PCI Requirements Reference:

12.3.3 A list of all such devices and personnel with access.

Device Identification
---------------------

All personal modems and wireless access points must be labeled with the
device owner, contact information and device purpose.

### PCI Requirements Reference:

12.3.4 Labeling of devices to determine owner, contact information, and
purpose.

Acceptable Use
--------------

Acceptable use of COVERHOUND CDE special technologies is subject to the
same guidelines and restrictions put forth in the [Security Awareness
and Acceptable Use Policy (Appendix A)](http://livepage.apple.com/).

### PCI Requirements Reference:

12.3.5 Acceptable uses for the technology.

Permitted Locations
-------------------

The Information Security Department must authorize the placement of any
wireless access points and dial-in modems. Dial-in modems are typically
limited to the data center. Wireless access points are normally placed
in the ceiling plenum. However at the moment VGS does not maintain a
physical data center so dial-in modems are not permitted.

The use of these devices must be logged according to the [Special
Technologies Device Inventory (Appendix K)](#Appendix_K_) and [Special
Technologies User List (Appendix L)](#Appendix_L_)

Wireless routers must be inspected on a daily basis to ensure that no
unapproved devices have been added.

### PCI Requirements Reference:

12.3.6 Acceptable network locations for the technologies.

Approved Products
-----------------

Only Information Security Department approved devices may be deployed
into the COVERHOUND CDE network. The use of these devices must be logged
according to the [Special Technologies Device Inventory (Appendix
K)](#Appendix_K_) and [Special Technologies User List (Appendix
L)](#Appendix_L_)

### PCI Requirements Reference:

12.3.7 A list of company-approved products.

Session Disconnect
------------------

All remote-access technologies, including dial-in modems and modem
banks, must be configured to automatically disconnect sessions after
thirty (30) minutes of inactivity.

### PCI Requirements Reference:

12.3.8 Automatic disconnect of sessions for remote-access technologies
after a specific period of inactivity.

Vendor Connections
------------------

Remote-access technologies, systems and accounts used solely for the
purpose of vendor maintenance and support must remain disconnected
and/or disabled until required. Activating these remotes access paths
requires approval from the Department or established problem management
procedures and they must be disabled immediately after use.

### PCI Requirements Reference:

12.3.9 Activation of remote-access technologies for vendors and business
partners only when needed by vendors and business partners, with
immediate deactivation after use.

Credit Card Data Access
-----------------------

If any credit card data is available through remote-access technologies
special precautions must be taken. The following are prohibited:

-   Storage of the cardholder data onto local hard drives, floppy disks,
    > and other media is prohibited.

-   Cut, paste, and print functions of remote PCs is prohibited for the
    > duration of the connection.

### PCI Requirements Reference:

12.3.10 For personnel accessing cardholder data via remote-access
technologies, prohibit copy, move, and storage of cardholder data onto
local hard drives and removable electronic media, unless explicitly
authorized for a defined business need.

Software Development Policy
===========================

Policy Applicability
--------------------

All development efforts of software designed to run on COVERHOUND CDE
computing systems, whether managed by employees or by third parties,
must follow this policy. Exemptions from this policy must be permitted
only if approved in advance and in writing by the Chief Security
Officer.

Development Environment
-----------------------

A test/development environment, separate from the production
environment, must be used to test all new software. If the network has
network connectivity with the production COVERHOUND CDE network, access
controls must be in place to enforce the separation.

Production data which needs to be protected as per PCI requirements must
not be used for testing and development purposes without being
sanitized. In no case may live credit card or sensitive data may be used
for testing on non-production systems and software. If testing is
required, please observe guidance on how to test using valid fake data.
For example, any valid, yet fake, credit card generator website such as:
<http://www.getcreditcardnumbers.com/> or test data provided by
applicable 3^rd^ party payment processors or acquirers.

All test data, custom application accounts, usernames and passwords must
be removed at the conclusion of testing, and in all cases before
software becomes active.

All code promotion to the production environment must be accomplished by
the System Administrators. Under no circumstances must the Development
Department have full time read/write access to production applications
or data. Under emergency situations developers may assist in
troubleshooting, utilizing an Emergency ID described in section 3.6.1
Information Security Department Responsibilities

### PCI Requirements Reference:

6.3 Develop software applications (internal and external, and including
web-based administrative access to applications) in accordance with PCI
DSS (for example, secure authentication and logging), and based on
industry best practices. Incorporate information security throughout the
software development lifecycle.

> 6.3.1 Removal of custom application accounts, user IDs, and passwords
> before applications become active or are released to customers.
>
> 6.3.2 Review custom code prior to release to production or customers
> in order to identify any potential coding vulnerability.

6.4 Follow change control processes and procedures for changes to system
components.

> 6.4.1 Separate development/test and production environments.
>
> 6.4.2 Separation of duties between development/test and production
> environments.
>
> 6.4.3 Production data (live PANs) are not used for testing or
> development.
>
> 6.4.4 Removal of test data and accounts before production systems
> become active.

.

Secure Software Development Procedures
--------------------------------------

### Development Life-Cycle

Internal and 3^rd^ party development of proprietary software must
utilize industry recognized best practices for software development such
as described at [CERT Secure Coding
Standard](https://www.securecoding.cert.org/confluence/display/java/SEI+CERT+Oracle+Coding+Standard+for+Java).
Security checks and control measures must be considered throughout the
development life-cycle.

Java

For Java specifically, especially Java 8, [Oracle's Secure Coding
Guidelines](http://www.oracle.com/technetwork/java/seccodeguide-139067.html)
are directly applicable.

Development

The high level overview of the security measures taking place within
each phase of the COVERHOUND CDE development process are as follows:

-   Requirements Analysis -- developers should determine whether
    > application requirements are inherently insecure.

-   Design -- application components must be planned in a manner
    > consistent with data and network security.

-   Development -- developers must consider all application
    > vulnerabilities (i.e.: memory bound issues, privilege and access
    > bypass, etc.).

-   Code Review -- a second developer must conduct code reviews of all
    > new and changed software, specifically in an attempt to identify
    > security issues.

-   QA Implementation - implementation must not compromise security
    > controls already in place, or introduce new vulnerabilities.

-   QA Testing - in addition to functional and efficiency testing, all
    > security features of the application must be tested.

-   Documentation -- all application feature and implementation
    > documentation must include direction on proper security
    > configurations.

-   Production Implementation -- implementation must not compromise
    > security controls already in place, or introduce new
    > vulnerabilities.

-   Production Testing -- in addition to functional and efficiency
    > testing, all security features of the application must be tested.

-   Maintenance -- all future application maintenance should not
    > compromise security controls already in place, or introduce new
    > vulnerabilities. Any new code must be reviewed and tested as
    > detailed above.

#### PCI Requirements Reference:

6.3 Develop software applications (internal and external, and including
web-based administrative access to applications) in accordance with PCI
DSS (for example, secure authentication and logging), and based on
industry best practices. Incorporate information security throughout the
software development lifecycle.

> 6.3.2 Review custom code prior to release to production or customers
> in order to identify any potential coding vulnerability.

### Web-based Applications

In addition to the Development Life-Cycle security measures that take
place throughout the application development life-cycle, special care
should be given to COVERHOUND CDE applications that are web-based.

All COVERHOUND CDE developers must receive training on secure coding
practices. All development must be done taking the OWASP guidelines into
account, <https://www.owasp.org/index.php/Main_Page>, the following
vulnerabilities must be considered and checked for during the Code
Review and Testing phases:

-   Invalidated Input

-   Malicious Use of User IDs

-   Malicious Use of Account Credentials and Session Cookies

-   Cross-Site Scripting

-   Buffer Overflows

-   SQL Injection and other Command Injection Flaws

-   Error Handling Flaws

-   Insecure Storage

-   Denial of Service

-   Insecure Configuration Management

Annually, and whenever significant modifications have taken place, all
web-based applications must be put through an application-specific
penetration test conducted by a 3^rd^ party.

#### PCI Requirements Reference:

6.5 Develop applications based on secure coding guidelines. Prevent
common coding vulnerabilities in software development processes. Note:
The vulnerabilities listed at 6.5.1 through 6.5.9 were current with
industry best practices when this version of the PCI DSS (version 2.0)
was published. However, as industry best practices for vulnerability
management are updated (for example, the OWASP Guide, SANS CWE Top 25,
CERT Secure Coding, etc.), the current best practices must be used for
these requirements.

> 6.5.1 Injection flaws, particularly SQL injection. Also consider OS
> Command injection, LDAP and XPath injection flaws as well as other
> injection flaws.
>
> 6.5.2 Buffer overflow.
>
> 6.5.3 Insecure cryptographic storage.
>
> 6.5.4 Insecure communications.
>
> 6.5.5 Improper error handling.
>
> 6.5.6 All "High" vulnerabilities identified in the vulnerability
> identification process (as defined in PCI DSS Requirement 6.2). Note:
> This requirement is considered a best practice until June 30, 2012,
> after which it becomes a requirement.
>
> 6.5.7 Cross-site scripting (XSS).
>
> 6.5.8 Improper Access Control (such as insecure direct object
> references, failure to restrict URL access, and directory traversal).
>
> 6.5.9 Cross-site request forgery (CSRF)

6.6 For public-facing web applications, address new threats and
vulnerabilities on an ongoing basis and ensure these applications are
protected against known attacks by either of the following methods:

-   Reviewing public-facing web applications via manual or automated
    > application vulnerability security assessment tools or methods, at
    > least annually and after any changes.

-   Installing a web-application firewall in front of public-facing web
    > applications.

### Credit Card Informational and Processing Applications

All COVERHOUND CDE proprietary or custom applications dealing with the
processing or retrieval of cardholder information must be configured in
a manner which masks or truncates the displayed credit card number.
Cardholder information is to be masked only the first 6 and last 4
digits may remain displayed. As a service that tokenizes cardholder
information, there is no need for full PAN to be retrieved from the
secure vault.

#### PCI Requirements Reference:

3.3 Mask PAN when displayed (the first six and last four digits are the
number of digits to be displayed). Notes: This requirement does not
apply to employees or other parties with a legitimate business need to
see the full PAN. This requirement does not supersede stricter
requirements in place for displays of cardholder---for example, point of
sale (POS) receipts.

Incident Response Plan and Procedures
=====================================

Policy Applicability
--------------------

All incident detections and responses, especially related to critical
systems, must follow this policy. Exemptions from this policy must be
permitted only if approved in advance and in writing by the Chief
Security Officer.

### Incident Identification

Employees must be aware of their responsibilities in detecting security
incidents to facilitate the incident response plan and procedures. All
employees have the responsibility to assist in the incident response
procedures within their particular areas of responsibility. Some
examples of security incidents that an employee might recognize in their
day to day activities include, but are not limited to:

-   Theft, damage, or unauthorized access (e.g., unauthorized logins,
    > papers missing from their desk, broken locks, missing log files,
    > alert from security guard, video evidence of a break-in or
    > unscheduled/unauthorized physical entry)

-   Fraud -- Inaccurate information within databases, logs, files or
    > paper records

-   Abnormal system behavior (e.g., unscheduled system reboot,
    > unexpected messages, abnormal errors in system log files or on
    > terminals)

-   Security event notifications (e.g., file integrity alerts, intrusion
    > detection alarms, physical security alarms such as fire alarms,
    > environmental alarms, natural disaster alerts)

All employees, regardless of job responsibilities, should be aware of
the potential incident identifiers and who to notify in these
situations. In all cases, every employee should report incidents per the
instructions under 14.3 Incident Reporting unless they are assigned
other activities within the incident response plan.

Reporting and Incident Declaration Procedures
---------------------------------------------

The Information Security Department should be notified immediately of
any suspected or real security incidents involving COVERHOUND CDE
computing assets, particularly any critical system. If it is unclear as
to whether a situation should be considered a security incident, the
Information Security Department should be contacted to evaluate the
situation.

With the exception of steps outlined below, it is imperative that any
investigative or corrective action be taken only by Information Security
Department personnel or under the oversight of Information Security
Department personnel, to assure the integrity of the incident
investigation and recovery process. When faced with a potential
situation you should do the following:

-   If the incident involves a compromised computer system.

<!-- -->

-   Do not alter the state of the computer system.

> The computer system should remain on and all currently running
> computer programs left as is. Do not shutdown the computer or restart
> the computer.

-   Immediately disconnect the computer from the network by removing the
    > network cable from the back of the computer.

<!-- -->

-   Reporting the security incident.

<!-- -->

-   Contact the Information Security Department to report any suspected
    > or actual incidents.

-   No one should communicate with anyone outside of their supervisor(s)
    > or the Information Security Department about any details or
    > generalities surrounding any suspected or actual incident. All
    > communications with law enforcement or the public must be
    > coordinated by the Information Security Department.

-   Document any information you know while waiting for the Information
    > Security Department to respond to the incident. This must include
    > date, time, and the nature of the incident, if known. Any
    > information you can provide would aid in responding in an
    > appropriate manner.

### PCI Requirements Reference:

12.9 Implement an incident response plan. Be prepared to respond
immediately to a system breach.

> 12.9.1 Create the incident response plan to be implemented in the
> event of a system breach. Ensure the plan address the following, at a
> minimum:

-   Roles, responsibilities, and communication and contact strategies in
    > the event of a compromise including notification of the payment
    > brands, at a minimum.

-   Specific incident response procedures.

-   Business recovery and continuity procedures.

-   Data back-up processes.

-   Analysis of legal requirements for reporting compromises.

-   Coverage and responses of all critical system components.

-   Reference or inclusion of incident response procedures from the
    > payment brands.

> 12.9.2 Test the plan at least annually.

Incident Severity Classification
--------------------------------

The Information Security Department must first attempt to determine if
the security incident justifies a formal incident response.

In cases where a security incident does not require an incident response
the situation must be forwarded to the appropriate area of IT to ensure
that all technology support services required are rendered.

The following descriptions should be used to determine what response the
Information Security Department must take.

-   Level 1 - One instance of potentially unfriendly activity (e.g.,
    > finger, unauthorized telnet, port scan, corrected virus detection,
    > unexpected performance peak, etc.).

-   Level 2 - One instance of a clear attempt to obtain unauthorized
    > information or access (e.g., attempted download of secure password
    > files, attempt to access restricted areas, single computer
    > successful virus infection on a non-critical system, unauthorized
    > vulnerability scan, etc.) or a second Level 1 attack.

-   Level 3 - Serious attempt or actual breach of security (e.g.,
    > multi-pronged attack, denial of service attempt, virus infection
    > of a critical system or the network, successful buffer/stack
    > overflow, successful unauthorized access to sensitive or critical
    > data or systems, broken lock, stolen papers, etc.) or a second
    > Level 2 attack.

> Any Level 1 type incident occurring against systems storing sensitive
> or confidential data or originating from unauthorized internal systems
> is classified as a Level 2.

 Incident Response
-----------------

### Typical Response

Responses can include or proceed through the following stages:
identification, severity classification, containment, eradication,
recovery and root cause analysis resulting in improvement of security
controls. The following actions should be taken by the Information
Security Department once an incident has been identified and classified.

#### Level 1

Contain and Monitor

If possible, record the user, IP address and domain of intruder.

> Utilize approved technology controls to temporarily or permanently
> block the intruder's access.
>
> Maintain vigilance for future break-in attempts from this user or IP
> address.

#### Level 2

Contain, Monitor and Warn

> Collect and protect information associated with the intrusion.
>
> Utilize approved technology controls to temporarily or permanently
> block the intruder's access.
>
> Research the origin of the connection.
>
> Contact ISP and ask for more information regarding the attempt and
> intruder.
>
> Research potential risks related to intrusion method attempted and
> re-evaluate for higher classification and incident containment,
> eradication, and recovery as described for Level 3 incident
> classifications.
>
> Upon identification, inform malicious user of our knowledge of their
> actions and warn of future recriminations if attempt is repeated. If
> an employee is the malicious user management should work with Human
> Resources to address the Acceptable Use violation appropriately.

#### Level 3

Contain, Eradicate, Recover and perform Root Cause Analysis

> If the incident involved credit card systems the Acquirer and
> applicable card associations must be notified. See section 14.5.2 for
> more details.
>
> Contain the intrusion and decide what action to take. Consider
> unplugging the network cables, applying highly restrictive ACLs,
> deactivating or isolating the switch port, deactivating the userID,
> terminating the user's session/change password etc.
>
> Collect and protect information associated with the intrusion via
> offline methods. In the event that forensic investigation is required
> the Information Security Department must work with legal and
> management to identify appropriate forensic specialists.
>
> Notify management of the situation and maintain notification of
> progress at each following step.
>
> Eliminate the intruder\'s means of access and any related
> vulnerabilities.
>
> Research the origin of the connection.
>
> Contact ISP and ask for more information regarding attempt and
> intruder, reminding them of their responsibility to assist in this
> regard.
>
> Research potential risks related to or damage caused by intrusion
> method used.

### Credit Card Compromise -- Special Response

For any incidents involving potential compromises of credit card
information, the Information Security Department must use the following
procedure:

> Contain and limit the exposure. Conduct a thorough investigation of
> the suspected or confirmed loss or theft of account information within
> 24 hours of the compromise. To facilitate the investigation:
>
> [Log all actions taken]{.underline} (e.g., bound notebook, video
> camera, etc.).
>
> [Utilize chain of custody techniques during all transfers of equipment
> and information related to the incident.]{.underline}
>
> [Do not access or alter compromised systems]{.underline} (e.g., do not
> log on or change passwords; do not log in as ROOT).
>
> [Do not turn off the compromised machine]{.underline}. Instead,
> isolate compromised systems from the network (e.g., unplug the network
> cable, deactivate switch port, isolate to contained environment e.g.
> isolated VLAN). Utilize Disaster Recovery / Business continuity
> procedures to recover business processes.
>
> [Preserve logs and electronic evidence.]{.underline}
>
> If using a wireless network, [change SSID on the access point and
> other machines that may be using this connection]{.underline} (with
> the exception of any systems believed to be compromised).
>
> [Be on high alert and monitor all cardholder information
> systems]{.underline}.
>
> Alert all necessary parties. Be sure to notify:
>
> Internal or External Incident Response or Forensics Team, if they are
> not already involved
>
> Merchant bank
>
> Local FBI Office
>
> U.S. Secret Service (if Visa, MasterCard, Discover / Diners Club /
> Carte Blanche, American Express and / or JCB payment data is
> compromised)
>
> Document event for Audit purposes
>
> Follow appropriate procedures for each card association which
> COVERHOUND CDE utilizes for credit card services.

#### Visa 

> Immediately contact the Visa Fraud Investigations and Incident
> Management group at (650) 432-2978. Provide the compromised Visa
> accounts to the merchant bank within ten (10) business days. Account
> numbers must be securely sent as instructed by the Visa Fraud
> Investigations and Incident Management group. It is critical that all
> potentially compromised accounts are provided. Visa would distribute
> the compromised Visa account numbers to issuers and ensure the
> confidentiality of entity and non-public information. See Visa's "What
> to do if Compromised" documentation for additional activities that
> must be performed. That documentation can be found at
> [[http://usa.visa.com/merchants/risk\_management/cisp\_if\_compromised.html]{.underline}](http://usa.visa.com/merchants/risk_management/cisp_if_compromised.html).

#### MasterCard

> Contact your merchant bank for specific details on what to do
> following a compromise. Details on the merchant bank (aka. the
> acquirer) can be found in the Merchant Manual at
> <http://www.mastercard.com/us/wce/PDF/12999_MERC-Entire_Manual.pdf.>
> Your merchant bank will assist when you call MasterCard at (636)
> 722-4100.

#### American Express

> Contact your relationship manager or call the support line at (800)
> 528-4800for further guidance.

#### Discover Card/Diners Club/Carte Blanche

> Contact Discover Network at (800) 347-7052 and speak with a fraud
> prevention specialist.

#### JCB

> Contact your relationship manager or call the support line at (213)
> 896-3718 for further guidance.

##### PCI Requirements Reference:

12.9.1 Create the incident response plan to be implemented in the event
of a system breach. Ensure the plan address the following, at a minimum:

-   Roles, responsibilities, and communication and contact strategies in
    > the event of a compromise including notification of the payment
    > brands, at a minimum.

-   Specific incident response procedures.

-   Business recovery and continuity procedures.

-   Data back-up processes.

-   Analysis of legal requirements for reporting compromises.

-   Coverage and responses of all critical system components.

-   Reference or inclusion of incident response procedures from the
    > payment brands.

### Root Cause Analysis and Lessons Learned

Not more than one week following the incident, members of the
Information Security Department and all affected parties must meet to
review the results of the investigation conducted under step 1, section
14.5.2 of this document to determine the root cause of the compromise
and evaluate the effectiveness of the Incident Response Plan. Review
other security controls to determine their appropriateness for the
current risks. Any identified areas in which the plan, policy or
security control can be made more effective or efficient, must be
updated accordingly.

#### PCI Requirements Reference:

12.9.6 Develop a process to modify and evolve the incident response plan
according to lessons learned and incorporate industry developments.

 Plan Testing and Training
-------------------------

At least once a year, a mock-incident must be initiated to facilitate
testing of the current plan. The exact incident to be tested must be at
the discretion of the Information Security Department. Once complete, a
follow-up session, as detailed above, would be held.

All COVERHOUND CDE employees that could have an active role within
incident response should be part of the test process.

Training regarding incident response responsibilities should be
performed regularly to ensure employee's readiness for test and actual
incidents.

PCI Requirements Reference:

12.9.2 Test the plan at least annually.

12.9.4 Provide appropriate training to staff with security breach
response responsibilities.

Automated Security System Notifications
---------------------------------------

All automated intrusion detection systems within the COVERHOUND CDE
environment, including intrusion detection sensors and file integrity
checking systems, must be configured to automatically notify the
Department of any potential compromises or attacks.

An engineer with the Department must be available on a 24/7 basis to
initiate the incident response plan if warranted.

### PCI Requirements Reference:

12.9.5 Include alerts from intrusion-detection, intrusion-prevention,
and file-integrity monitoring systems.

12.9.3 Designate specific personnel to be available on a 24/7 basis to
respond to alerts.

Logging Controls Policy
=======================

Policy Applicability
--------------------

All users, administrators, applications and systems fall under this
policy when performing their duties. Exemptions from this policy must be
permitted only if approved in advance and in writing by the Chief
Security Officer.

Events Logged
-------------

Automated audit trails must be implemented for all system components to
reconstruct the following events:

-   All user access to cardholder data.

-   All administrative actions utilizing userIDs with significant
    > privileges above a general user (e.g. root userIDs with
    > Administrator group privilege, database, etc.).

-   Access or initialization of audit log files.

-   Any user or administrator authentication attempts (both valid and
    > invalid).

-   Creation or deletion of system-level objects.

-   Invalid logical access attempts.

### PCI Requirements Reference:

10.2.1 All individual user accesses to cardholder data.

10.2.2 All actions taken by any individual with root or administrative
privileges.

10.2.3 Access to all audit trails.

10.2.4 Invalid logical access attempts.

10.2 5 Use of identification and authentication mechanisms.

10.2.6 Initialization of the audit logs.

10.2.7 Creation and deletion of system-level objects.

Event Log Structure
-------------------

All system access event logs must contain at least the following
information.

-   User Identification

-   Type of event

-   Date and time of event

-   Result of the event

-   Originating location of the event

-   The name of the affected data, system component or resource

###  PCI Requirements Reference:

10.3 Record at least the following audit trail entries for all system
components for each event:

10.3.1 User identification.

10.3.2 Type of event.

10.3.3 Date and time.

10.3.4 Success or failure indication.

10.3.5 Origination of event.

10.3.6 Identity or name of affected data, system component, or resource.

Log Security
------------

All changes to firewall configuration parameters, enabled services, and
permitted connectivity paths must be logged, and all logs must be
retained, for a minimum of one year. All suspicious activity that might
be an indication of either unauthorized usage or an attempt to
compromise security measures also must be logged. The integrity of these
logs must be protected with checksums, digital signatures, encryption,
or similar measures. These logs must be promptly removed from the
recording systems and stored in a physically protected container for at
least one year after the time they were recorded. These logs must be
reviewed periodically to ensure that the firewalls are operating in a
secure manner.

Currently configuration changes are recorded at VGS on Amazon Web
Services' Secure Storage Server (S3), and appropriately logged and
archived. Similarly, syslogs are directed to the syslog server, and logs
are archived monthly to S3 for secure storage and preservation.
Procedures on these processes are outlined in the COVERHOUND CDE
Information Security Procedures documentation.

### PCI Requirements Reference:

10.5 Secure audit trails so they cannot be altered.

10.5.1 Limit viewing of audit trails to those with a job-related need.

10.5.2 Protect audit trail files from unauthorized modifications.

10.5.3 Promptly back-up audit trail files to a centralized log server or
media that is difficult to alter.

10.5.4 Write logs for external-facing technologies onto a log server on
the internal LAN.

> 10.5.5 Use file-integrity monitoring and change-detection software on
> logs to ensure that existing log data cannot be changed without
> generating alerts (although new data being added should not cause an
> alert).

Log Review
----------

Each day, on 0:00 +UTC time, System Administrators, who are on call for
PagerDuty, must review all logs daily and investigate any potential
anomaly detections. Confirmation of the daily log review should be done
by sending an email to the infosec-review list with the date of review,
a link to the anomaly detection snapshot as well as interesting reported
findings. If there are no interesting reported findings, note that in
the daily log review. If further investigation is needed, follow the
procedures defined in Incident Response Plan and Procedures.

Example:

-   "nothing important of note to report"

### PCI Requirements Reference:

10.6 Review logs and security events for all system components to
identify anomalies or suspicious activity.

########### Security Awareness and Acceptable Use Policy

COVERHOUND CDE Network Security Policy
--------------------------------------

The information that is stored in the COVERHOUND CDE is extremely
valuable and is a prized target of hackers, criminals, and other
miscreants. VGS must make every effort to safeguard such data from being
compromised. This security awareness policy describes the importance and
role of the employees, consultants and service providers in the security
framework of COVERHOUND.

As an employee, consultant or service provider of VGS or COVERHOUND, it
is of primary importance to protect the integrity, and confidentiality
of critical information. This information can consist of sensitive,
proprietary company information such as trade secrets, or sensitive
cardholder data to include account numbers, names and addresses. The
compromise of such information could cause significant and permanent
damage to the fiscal viability of COVERHOUND CDE and permanently damage
the reputation of the company and its employees. It is important to
understand that if critical information is compromised either
intentionally or unintentionally through neglect, it could result in
disciplinary actions including termination. It is therefore critical
that each employee ensure that they are cognizant of the importance of
cardholder data and is diligent in the protection of COVERHOUND CDE
critical information assets.

If compromise is discovered or suspected, you should immediately report
the incident through the appropriate chain of management. Any and all
suspicious activity should be immediately reported.

Many unscrupulous individuals may try to use a tactic called \'social
engineering\' in an attempt to convince you to inadvertently provide
sensitive information such as employee data, business operating models,
passwords and other data. "Social Engineering" techniques are used
mostly over phone communications, so be cautious and security minded
when answering phone calls. Do not, at any time, give credit card number
out over the phone. Many times, the information they must pursue appears
innocuous and irrelevant. When compiled however, this information
provides significant information for criminals to access the systems and
infrastructure of COVERHOUND CDE. For this reason, no information should
be shared with anyone who is not identified as working with the company
or authorized to have such information. Any questions related to the
verification of such individuals should be directed to management. Do
not freely offer information related to the operations, personnel, or
business of VGS and COVERHOUND.

Each individual employee or contractor is assigned a User ID and
password for the various computers that are needed to perform their job
function. Each employee is only given access to the machines that they
need access to and only to the functions that they need to access on
those machines. If you identify anyone using shared user ID\'s or
passwords, this must be reported immediately.

Access to the sensitive data storage ("vault") is highly restricted.
Only employees with a need to access the vault are given access to the
vault. If you see employees or other people accessing the vault that do
not have normal access to it, report it immediately.

COVERHOUND CDE IT systems and accounts are to be used only for the
purpose for which they are authorized and are not to be used for non-VGS
related activities. Unauthorized use of an VGS account and/or system is
in violation of Section 799, Title 18, U.S. Code, and constitutes theft
and is punishable by law. Therefore, unauthorized use of VGS IT
computing systems and facilities may constitute grounds for dismissal
and either civil or criminal prosecution. In the text below, "users"
refers to users of COVERHOUND CDE IT computing systems and facilities.

The Internet is an open and globally accessible computer network. It is
connected to the COVERHOUND CDE computer network, where essential
operating systems run and mission-critical data are stored.

For safety and security reasons, a special device is installed between
the two networks (Internet and internal Network). This device, which is
called a "firewall", is regularly maintained to keep the IOS
(Inter-networking Operating System) up-to-date. The firewall helps
enforce security policy and monitor access. Nevertheless, any Internet
security must only be efficient with the involvement and fair play of
all users. Please turn to your usual IT support unit for advice
concerning Internet problems or questions.

1.  The user has to comply with the following rules. VGS may modify
    these rules without prior notice if required.

2.  Normal Internet access is only permitted through the ISA (Internet
    Security and Acceleration) Server and the Firewall. The direct
    connection of any networked computer (e.g. dial-up connection to the
    Internet via modem) is prohibited.

3.  The applications permitted are e-mail or outgoing web browsing.
    Downloading is only permitted if up-to-date anti-virus software is
    installed and in use. ALL files received over the Internet must be
    scanned, either automatically or manually, using the usual
    anti-virus procedures!

4.  All Internet use must be for company purposes: Internet access may
    not be used for private purposes.

5.  The user acknowledges that the legal aspects of Internet use are not
    yet well defined, and that Internet access involves electronic
    communication across various countries with their own applicable
    laws. Users are solely responsible for their actions.

6.  Logs must generally be kept of all Internet access.

7.  Worldwide Internet standards are generally supported. However, since
    security and high performance are the highest priority, special
    applications, functions or protocols may be restricted.

8.  Special restrictions are in force in public places (WIFI-Walk in
    Facilities, Internet Café, etc.).

9.  The speed and availability of Internet services may vary from time
    to time. This is in the nature of the Internet and its facilities:
    the problem may not be attributable to VGS or its responsibilities.

10. The streaming of audio and video that result in excessive use of
    network resources is strictly prohibited.

11. The COVERHOUND CDE IT computing systems are classified as either
    transaction processing systems or software development systems.
    Therefore, non-payment related and/or non-development related
    information may not be processed, entered or stored on a COVERHOUND
    CDE IT transaction processing system. However, all Information
    contained on, in or manipulated by COVERHOUND CDE IT is considered
    confidential and must be treated as such.

12. Users are responsible for protecting any information used and/or
    stored on/in their COVERHOUND CDE workstation or IT resource
    accounts.

13. Users are requested to report any weaknesses in VGS computer
    security or any incidents of possible misuse or violation of this
    agreement to the proper authorities by contacting the VGS Service
    Desk.

14. Users shall not attempt to access any data or programs contained on
    COVERHOUND CDE IT computer systems for which they do not have
    authorization or explicit consent from the owner of the data or
    program.

15. Users shall not make unauthorized copies of copyrighted software,
    except as permitted by law or by the owner of the copyright.
    Unregistered software may not be installed.

16. Users shall not make copies of system configuration files for their
    own, unauthorized personal use or to provide to others for
    unauthorized uses.

17. Users shall not purposely engage in activity with the intent to:
    harass other users; degrade the performance of systems; deprive an
    authorized COVERHOUND CDE user access to an COVERHOUND CDE resource;
    obtain extra resources beyond those allocated; circumvent COVERHOUND
    CDE computer security measures or gain access to an COVERHOUND CDE
    processing or development system for which proper authorization has
    not been given.

18. Electronic communication facilities (such as e-mail) are for
    authorized use only. Fraudulent, harassing or obscene messages
    and/or materials shall not be sent from, to or stored on any
    COVERHOUND CDE IT resource. VGS reserves the right to inspect
    content of electronic communication and prevent delivery of
    prohibited content.

19. Users shall not download, install or run security programs or
    utilities that reveal weaknesses in the security of a system. For
    example, COVERHOUND CDE users shall not run password-cracking
    programs, "network sniffer" utilities or other sleuthing or tracing
    programs on COVERHOUND CDE IT computing systems.

20. COVERHOUND CDE may immediately cancel the Internet access of any
    user in the event of misuse, abuse, or threat to COVERHOUND CDE
    systems.

Web and Mail Specifics
----------------------

Web usage ("surfing") enables us to find various items of information
all around the world

a)  Users are reminded, however, that the information found might not be

-   up-to-date,

-   true,

-   or provided by the person they assume.

> Users should thus use any information obtained from the Internet with
> the greatest care. Moreover, under certain circumstances, transactions
> (e.g. with credit card) over the Internet might be risky. The user at
> their own risk makes any Internet transaction, and users must be held
> responsible for any losses they may incur.

b)  Users acknowledge and appreciate that speed and/or availability
    > cannot be guaranteed, and must depend on the time of the day or
    > the number of current users worldwide. For this reason, users
    > should not rely on the Internet for critical business needs.

c)  Users also acknowledge that the Internet is a low-speed and
    > unstructured network, and that web usage can thus be very
    > time-consuming.

d)  Users further acknowledge that some web pages contain malicious
    > programs which could have unpredictable effects on their computer
    > or on third-party systems.

For mail purposes, Microsoft Outlook/Exchange/Google Apps are the only
supported mail sub-system

Mail on the Internet enables users to exchange e-mail and files
(documents) with other Internet users.

a)  Users acknowledge that e-mail does not have any legal value

b)  Users also acknowledge that the confidentiality, delivery,
    > authenticity or integrity of Internet e-mails cannot be
    > guaranteed, and that the sender might not be the person they claim
    > to be. Users are therefore advised not to send/receive any
    > critical data over the Internet.

<!-- -->

c)  Users acknowledge that subscribing to automatic mailing lists can
    > generate a large amount of mails (daily) and be very
    > time-consuming.

d)  Users are required to follow the netiquette[^1] of the mail user
    > community: no junk mails, no flames[^2], and no mailing chains or
    > mail bombs[^3].

Any noncompliance with these requirements must constitute a security
violation and must be reported to the Chief Information Officer and must
result in short-term or permanent loss of access to COVERHOUND CDE IT
computing systems. Serious violations may result in civil or criminal
prosecution.

The user must sign this document before given access to any COVERHOUND
CDE computer system.

Note: Each user needs a separate form for each computer that person has
an account on. For the computer listed below this document supersedes
all previous documents pertaining to this user, please destroy all
previous documents.

I have read and understand the COVERHOUND CDE IT Division Computing
Systems Acceptable Use Policy for use of the COVERHOUND CDE computing
facility and agree to abide by it.

Full Name (Print):
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Manager:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

User ID:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Signature:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

Date:
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

########### Authorization Request Form

COVERHOUND CDE Authorization Request Form

+-----------------+-----------------+-----------------+-----------------+
| PART I (To be   |                 |                 |                 |
| filled out by   |                 |                 |                 |
| the Requestor   |                 |                 |                 |
| or Requestor's  |                 |                 |                 |
| Supervisor)     |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 1\. Type of     | 2\. Office:     |                 |                 |
| Request:        |                 |                 |                 |
|                 |                 |                 |                 |
| □ Initial □     |                 |                 |                 |
| Modification □  |                 |                 |                 |
| Deletion        |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 3\. Name        | 4\. Title:      |                 |                 |
| (Last, First,   |                 |                 |                 |
| MI):            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 5.              | 6\. Phone       | 7\. Start       | 8\. Stop Date:  |
| Organization:   | Number:         | Date:           |                 |
+-----------------+-----------------+-----------------+-----------------+
| 9. Requestor's  | 10\. Date:      |                 |                 |
| Signature:      |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| PART II (To be  |                 |                 |                 |
| filled out by   |                 |                 |                 |
| the             |                 |                 |                 |
| Requestor\'s    |                 |                 |                 |
| Supervisor)     |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 11\. Profile    |                 |                 |                 |
| (Check the      |                 |                 |                 |
| appropriate     |                 |                 |                 |
| standard        |                 |                 |                 |
| profile(s)):    |                 |                 |                 |
|                 |                 |                 |                 |
| □ Basic User □  |                 |                 |                 |
| System Engineer |                 |                 |                 |
| □ Security      |                 |                 |                 |
| Engineer □ Key  |                 |                 |                 |
| Custodian       |                 |                 |                 |
|                 |                 |                 |                 |
| □ Network       |                 |                 |                 |
| Engineer □      |                 |                 |                 |
| Software        |                 |                 |                 |
| Engineer □      |                 |                 |                 |
| Security        |                 |                 |                 |
| Manager □ Other |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_  |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 12\. ID Badge:  | 13\. System     |                 |                 |
|                 | Type:           |                 |                 |
| □ Visitor □     |                 |                 |                 |
| Building        | □ Windows □     |                 |                 |
|                 | Unix □ Wireless |                 |                 |
| □ Internal      | Use             |                 |                 |
| Doors □         |                 |                 |                 |
| Datacenter      | □ Modem Use □   |                 |                 |
|                 | Modem           |                 |                 |
|                 | Possession      |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 14.             |                 |                 |                 |
| Justification   |                 |                 |                 |
| for Accesses:   |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 15. Supervising |                 |                 |                 |
| Official        |                 |                 |                 |
| Certification:  |                 |                 |                 |
|                 |                 |                 |                 |
| Name Phone      |                 |                 |                 |
| Signature Date  |                 |                 |                 |
|                 |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_        |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| PART III (To be |                 |                 |                 |
| completed by    |                 |                 |                 |
| the Information |                 |                 |                 |
| Security        |                 |                 |                 |
| Department)     |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 16. Background  | 17\. Performed  | 18\. Date       |                 |
| Check           | By:             | Granted:        |                 |
| Completed:      |                 |                 |                 |
|                 |                 |                 |                 |
| □ Yes □ No      |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 19\. Security   |                 |                 |                 |
| Officer         |                 |                 |                 |
| Official        |                 |                 |                 |
| Certification:  |                 |                 |                 |
|                 |                 |                 |                 |
| Name Phone      |                 |                 |                 |
| Signature Date  |                 |                 |                 |
|                 |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_        |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| PART IV (To be  |                 |                 |                 |
| completed by    |                 |                 |                 |
| System          |                 |                 |                 |
| Administrator)  |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 20\. User ID:   | 21\. Date User  | 22\. Date       |                 |
|                 | Notified:       | Deleted:        |                 |
+-----------------+-----------------+-----------------+-----------------+
| 23\. System     |                 |                 |                 |
| Engineer        |                 |                 |                 |
| Official        |                 |                 |                 |
| Certification:  |                 |                 |                 |
|                 |                 |                 |                 |
| Name Phone      |                 |                 |                 |
| Signature Date  |                 |                 |                 |
|                 |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_             |                 |                 |                 |
| \_\_\_\_        |                 |                 |                 |
| \_\_\_\_\_\_\_\ |                 |                 |                 |
| _\_\_\_\_\_\_\_ |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| Notes           |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| 24. Additional  |                 |                 |                 |
| Comments /      |                 |                 |                 |
| Notes:          |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+

########### Change Request Form

  --------------------------- -- ------------------ --
  1\. Change Identification                         
  Change Request ID:             Date Opened:       
  Project/System:                Priority:          
  Change Initiator:              Magic Ticket \#:   
  Change Process Owner:          Date Closed:       
  --------------------------- -- ------------------ --

  ------------------------
  2\. Change Description
  ------------------------

2.1 Full Description of the Nature of Change

2.2 Implementation Timing

  ------------------- ----------- ------------- ------------
                      Best Case   Most Likely   Worst Case
  Duration in Hours                             
  Requested Date                                
  Start Time                                    
  ------------------- ----------- ------------- ------------

2.3 Additional Reference Documentation (and location of reference)

  -------------------
  3\. Change Impact
  -------------------

3.1 Systems Impacted by Change (Applications, Hardware, other
Technologies)

3.2 User Community Impacted by the Change

3.3 Identified Benefits of Change

3.4 Identified Risks of No Change

3.5 Sample Communication to User Community

  ---------------------------
  4\. Planning and Analysis
  ---------------------------

4.1 Detailed Planned Approach

4.2 Detailed Back-Out Plan

4.3 High-Level Change Verification/Test Cases

4.4 Identified Risks and Issues of Implementation

4.5 Implementation Costs and Resource Requirements.

  ------------------------------------------------------- ------- ------- --
  5\. Authorization                                                       
  Change Initiator Approval:                              Name:   Date:   
  Change Process Owner Approval:                          Name:   Date:   
  Change Board Approval:                                  Name:   Date:   
  Independent Code Reviewer Approval (for development):   Name:   Date:   
  ------------------------------------------------------- ------- ------- --

I have personally tested and verified that the application has been
reviewed / tested for the following PCI compliance items:

> 6.5 Develop all web applications based on secure coding guidelines
> such as the [[Open Web Application Security Project
> guidelines]{.underline}](http://www.owasp.org/index.php/Main_Page).
> Review custom application code to identify coding vulnerabilities.
> Cover prevention of common coding vulnerabilities in software
> development processes, to include the following:

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------- -------
  [[OWASP Top 10 Vulnerabilities]{.underline}](http://www.owasp.org/index.php/OWASP_Top_Ten_Project):                                                                                                Name / Initial:   Date:
  6.5.1 [[Invalidated input]{.underline}](http://www.owasp.org/index.php/Unvalidated_Input)                                                                                                                            
  6.5.2 [[Broken access control]{.underline}](http://www.owasp.org/index.php/Broken_Access_Control) (for example, malicious use of user IDs)                                                                           
  6.5.3 [[Broken authentication and session management]{.underline}](http://www.owasp.org/index.php/Broken_Authentication_and_Session_Management) (use of account credentials and session cookies)                     
  6.5.4 [[Cross-site scripting (XSS) attacks]{.underline}](http://www.owasp.org/index.php/Cross_Site_Scripting)                                                                                                        
  6.5.5 [[Buffer overflows]{.underline}](http://www.owasp.org/index.php/Buffer_Overflow)                                                                                                                               
  6.5.6 [[Injection flaws]{.underline}](http://www.owasp.org/index.php/Injection_Flaws) (for example, structured query language (SQL) injection)                                                                       
  6.5.7 [[Improper error handling]{.underline}](http://www.owasp.org/index.php/Improper_Error_Handling)                                                                                                                
  6.5.8 [[Insecure storage]{.underline}](http://www.owasp.org/index.php/Insecure_Storage)                                                                                                                              
  6.5.9 [[Denial of service]{.underline}](http://www.owasp.org/index.php/Application_Denial_of_Service)                                                                                                                
  6.5.10 [[Insecure configuration management]{.underline}](http://www.owasp.org/index.php/Insecure_Configuration_Management)                                                                                           
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------------- -------

  ----------------------------------------- -- --------------- --
  6\. Implementation Information                               
  Implemented in Product Release/Version:      Release Date:   
  ----------------------------------------- -- --------------- --

  ----------------- ----------- ------ -------
  Escalation List   Extension   Cell   Other
                                       
                                       
                                       
  ----------------- ----------- ------ -------

########### Media Inventory Log

COVERHOUND CDE Media Inventory Log

  ------ ---------- ------ ----------- ------------
  Date   Location   Name   Signature   Acceptable
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
                                       □ Yes □ No
  ------ ---------- ------ ----------- ------------

########### Permitted Network Services and Protocols

> *See: 2018 Appendix E\_ Permitted Network Services and Protocols (pg
> 75) - Sheet1.pdf*
>
> Also located
> [here](https://docs.google.com/spreadsheets/d/1n1Q5OtJRn526856I2G7QT32dpALDeYO-rnZHJLwg2t4/edit#gid=0).

########### System Configuration Standards 

Applicability
-------------

This appendix includes hardening and installation procedures for all
off-the-shelf operating systems and applications used at COVERHOUND CDE.
All installations of these operating systems and applications must
adhere to these requirements.

### PCI Requirements Reference:

2.1 Always change vendor-supplied defaults before installing a system on
the network, including but not limited to passwords, simple network
management protocol (SNMP) community strings, and elimination of
unnecessary accounts.

> 2.1.1 For wireless environments connected to the cardholder data
> environment or transmitting cardholder data, change wireless vendor
> defaults, including but not limited to default wireless encryption
> keys, passwords, and SNMP community strings.

2.2 Develop configuration standards for all system components. Assure
that these standards address all known security vulnerabilities and are
consistent with industry-accepted system hardening standards. Sources of
industry-accepted system hardening standards may include, but are not
limited to:

-   Center for Internet Security (CIS)

-   International Organization for Standardization (ISO)

-   Sys Admin Audit Network Security (SANS) Institute

-   National Institute of Standards Technology (NIST).

> 2.2.1 Implement only one primary function per server to prevent
> functions that require different security levels from co-existing on
> the same server. (For example, web servers, database servers, and DNS
> should be implemented on separate servers.)

6.1 Ensure that all system components and software are protected from
known vulnerabilities by having the latest vendor-supplied security
patches installed. Install critical security patches within one month of
release.

Risk Ranking
------------

Newly discovered vulnerabilities are typically ranked a score from 1 --
10 from the various vulnerability databases such as CERT, NVD, and
Mitre. VGS adheres to the scores provided by vendors and independent
3^rd^ party organizations unless otherwise justified in a documented and
approved business justification for mitigation.

Linux
-----

The system hardening document located at the following link must be used
as the basis for all VGS linux system deployments:
https://benchmarks.cisecurity.org/downloads/show-single/?file=ubuntu1404.100

While configuring the system, all exceptions to this hardening standard
must be noted on the completed System Configuration Record.

Server Applications
-------------------

The following general install procedures must be followed for all VGS
server application deployments:

1.  Install necessary software using configuration management systems,
    > such as Ansible, Chef, or Puppet.

    a.  Unless explicitly approved otherwise, software must be installed
        > via system configuration management systems.

2.  Update application software per vendor recommendations.

3.  Configure application parameters according to build document
    > (application hardening).

4.  Update system specific System Configuration Record and maintain on
    > file.

Container Management
--------------------

1.  Container base images be updated after any incident and where
    feasible on at least a *monthly* basis

2.  Where feasible, AMI/Virtual Machines should be refreshed where
    feasible on at least a *monthly* basis

Emergency Patch Management Procedure
------------------------------------

This outlines the procedure for critical patches that need to updated
immediately, however emergency patch management should follow the
overarching guidelines in Emergency Process Flow section on page 9.

1.  An Emergency RFC must be made to the CTO and the Information
    Security team. Documentation of patch management. This RFC must
    include:

    a.  Notice and overview about the critical issue (if possible a link
        to the notice promulgated by the upstream patch vendor or by a
        trusted source should be included).

    b.  A stated reason for patching citing the vulnerability as well as
        the proposed patch

    c.  The engineer in charge of implementing the patch

    d.  Estimate of update's impact on uptime/performance. Include
        impacted

        i.  Components

        ii. Operations

        iii. Customers

2.  The CISO or CTO must approve emergency Patch Management requests.

3.  Pull request structure should follow the Github Pull Request policy
    on page 10 of this policy

4.  Once change is ready for review, engineer must notify other
    engineers as well as the CTO so that the pull request can be
    reviewed (usually done via \@channel in the slack dev channel).

5.  Code review must be conducted by CISO or CTO before pushing to
    production.

6.  For 2 weeks following the patch, a monitoring plan for affected
    systems must be in place with support personnel and engineers on
    pager duty rotation made aware of the patch and of potential
    issues/types of issues that may arise as a result.

########### System Configuration Record

COVERHOUND CDE System Configuration Record
------------------------------------------

+-----------------------+-----------------------+-----------------------+
| General System        |                       |                       |
| Information           |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 1\. System Name:      | 2\. System Purpose:   | 3\. Build Date:       |
+-----------------------+-----------------------+-----------------------+
| 4\. Build Engineer:   | 5\. Comments:         |                       |
+-----------------------+-----------------------+-----------------------+
| IP Information        |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 6\. IP Address:       | 7\. Subnet Mask:      | 8\. Default Gateway:  |
+-----------------------+-----------------------+-----------------------+
| 9\. DNS/WINS          | 10\. Domain:          | 11\. Other Settings:  |
| Entries:              |                       |                       |
+-----------------------+-----------------------+-----------------------+
| Operating System      |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 12\. Operating        | 13\. Version:         |                       |
| System:               |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 14\. Date Patched     | 15: Patch Exceptions: |                       |
| to:                   |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 16\. System           | 17\. Hardened by      |                       |
| Hardened:             | Which Standard:       |                       |
|                       |                       |                       |
| □ Yes □ No            |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 18\. Hardening        |                       |                       |
| Exceptions:           |                       |                       |
|                       |                       |                       |
| Document Number       |                       |                       |
| Reason for Exception  |                       |                       |
|                       |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_           |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_               |                       |                       |
|                       |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_           |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_               |                       |                       |
+-----------------------+-----------------------+-----------------------+
| Application (Attach   |                       |                       |
| additional Sheets for |                       |                       |
| Other Entries)        |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 19\. Operating        | 20\. Version:         |                       |
| System:               |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 21\. Date Patched     | 22: Patch Exceptions: |                       |
| to:                   |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 23\. System           | 24\. Hardened by      |                       |
| Hardened:             | Which Standard:       |                       |
|                       |                       |                       |
| □ Yes □ No            |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 25\. Hardening        |                       |                       |
| Exceptions:           |                       |                       |
|                       |                       |                       |
| Document Number and   |                       |                       |
| Reason for Exception  |                       |                       |
|                       |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_           |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_               |                       |                       |
|                       |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_           |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_\_\_\_\_\_\_\_ |                       |                       |
| \_\_\_\_\_\_\_\_\_\_\ |                       |                       |
| _\_\_\_               |                       |                       |
+-----------------------+-----------------------+-----------------------+
| Notes                 |                       |                       |
+-----------------------+-----------------------+-----------------------+
| 26\. Additional       |                       |                       |
| Comments / Notes:     |                       |                       |
+-----------------------+-----------------------+-----------------------+

########### Encryption Key Custodianship Form

COVERHOUND CDE Encryption Key Custodianship Form
------------------------------------------------

> Encryption key custodians are those person(s) delegated the
> responsibility of managing, handling and protecting access to
> COVERHOUND CDE encryption keys. Custodians are responsible for the
> safety and integrity of keys in their custody. The custodian has
> responsibility to:

-   Implement all encryption key controls as specified by the
    > Information Security Department and documented in information
    > security policies and procedures.

-   Provide safeguards for encryption keys during generation, loading
    > and storage.

-   Administer access to the encryption keys and make provisions for
    > timely detection, reporting, and analysis of unauthorized attempts
    > to gain access to these keys.

-   Control access and secrecy of the combination of the safe containing
    > the clear-text encryption keys.

-   Appropriate and complete the Encryption Key Management Log for any
    > activity involving cryptographic keys.

-   Participation in the encryption key generation, distribution,
    > change, and destruction processes.

> Key Custodian Signature Date
>
> Printed Name

########### Encryption Key Management Log

COVERHOUND CDE Encryption Key Management Log
--------------------------------------------

  ------ ------ ----- ----------------------- --------
  Date   Time   Key   Custodian and Witness   Reason
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
                                              
  ------ ------ ----- ----------------------- --------

########### Special Technologies Device Inventory

COVERHOUND CDE Special Technologies Device Inventory
----------------------------------------------------

  ------ ------------- ---------- ----------------------- ---------------
  Type   Device Name   Location   Owner / Administrator   Justification
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
                                                          
  ------ ------------- ---------- ----------------------- ---------------

########### Periodic Operational Security Procedures

COVERHOUND CDE Periodic Operational Security Procedures
-------------------------------------------------------

  ---------------------------------------------------------------------------------------------------------------------- ------- -------- --------- ----------- ---------- -------------
  Task                                                                                                                   Daily   Weekly   Monthly   Quarterly   Annually   As Required
  Security Policy                                                                                                                                                          
  Enterprise Risk Analysis                                                                                                                                      X          
  Policy/standards review                                                                                                                                       X          
  Security awareness orientation                                                                                                                    X                      
  Organizational Security                                                                                                                                                  
  Distribute Security Alerts                                                                                                                                               X
  Review security policy exceptions compliance                                                                                                      X                      
  Asset Classification and Control                                                                                                                                         
  Review system access controls                                                                                                                     X                      
  Review access request approvals & audit trail                                                                                                     X                      
  Audit disposal of data and media                                                                                                                  X                      
  Personnel Security                                                                                                                                                       
  New employee security orientation                                                                                                                             X          X
  Process employee data access requests                                                                                                                                    X
  Audit terminated employee samples for system, network, application access                                                                         X                      
  Incident response team meeting                                                                                                          X                                
  Physical and Environmental Security                                                                                                                                      
  Physical walkthrough of facility, work areas and data center (N/A handled by Annual review of AWS SOC2 and PCI ROC).                                                     
  Review compliance of data center access & visitor logs (N/A handled by Annual review of AWS SOC2 and PCI ROC).                                                           
  System Security                                                                                                                                                          
  Review intrusion detection (IDS/IPS) logs                                                                              X                                                 
  File Integrity Scans                                                                                                   X                                                 
  Scan desktops for vulnerabilities and security compliance                                                                                         X                      
  Scan servers and network for vulnerabilities and security compliance                                                                              X                      
  External application scans                                                                                                                        X                      
  Use a Wireless Analyzer to detect wireless devices in use                                                                                         X                      
  Review all security and event logs                                                                                     X                                                 
  Perform network-layer and application-layer penetration testing                                                                                               X          
  ---------------------------------------------------------------------------------------------------------------------- ------- -------- --------- ----------- ---------- -------------

########### MANAGEMENT of connected entities

Connection Standards
--------------------

All entities which are temporally or permanently connected to any
COVERHOUND CDE computing systems must be properly documented in the form
included in this appendix and must meet the following standards:

-   Every connection from an external entity must be documented and
    > authorized by management before allowing access to any internal
    > system.

-   If the external entity is connecting to any system within the
    > cardholder environment, it must be verified that such entity
    > complies with the PCI DSS.

-   Access to internal systems must be allowed only for the time
    > requested and the connection must be monitored.

Connection Process
------------------

The following process must be observed by the System Administrators to
connect and disconnect entities:

-   Verify that the Management of Connected Entities Form (Appendix P)
    > has been properly completed and authorized by management before
    > allowing any access.

-   In case of uncertainty, contact the manager authorizing the
    > connection to verify the authenticity of the authorization.

-   Allow access at the appointed time.

-   Monitor connection.

-   Disable access after the allowed time is over.

-   Monitor system performance before and after the connection to
    > identify any anomaly.

### PCI Requirements Reference:

12.8 Maintain and implement policies and procedures to manage service
providers with whom cardholder data is shared, or that could affect the
security of cardholder data, as follows::

12.8.1 Maintain a list of service providers..

> 12.8.2 Maintain a written agreement that includes an acknowledgement
> that the service providers are responsible for the security of
> cardholder data the service providers possess or otherwise store,
> process or transmit on behalf of the customer, or to the extent that
> they could impact the security of the customer's cardholder data
> environment..
>
> 12.8.3 Ensure there is an established process for engaging service
> providers including proper due diligence prior to engagement..
>
> 12.8.4 Maintain a program to monitor service providers' PCI DSS
> compliance status at least annually.
>
> 12.8.5 Maintain information about which PCI DSS requirements are
> managed by each service provider, and which are managed by the entity.

RISK MITIGATION AND MIGRATION PLAN
----------------------------------

12.8 7912.8.1 7912.8.2 7912.8.3 7912.8.4 7912.8.5 792.1 702.1.1 702.2 702.2.1 706.1 70AWS CloudFront delivers JavaScript contents via its CDN over early TLS
------------------------------------------------------------------------------------------------------------------------------------------------------------

CloudFront currently delivers all content over SSLv3 and TLSv1.1.
Amazon's reason for using CloudFront to deliver these assets over older
SSL/TLS is for older client support. The approved delivery protocol
should be over TLSv1.1. As this is delivering static content that
executes on the client side, the guidance to securing over TLSv1.2 is
un-applicable. The intention of the guidance to ensure transport is over
TLSv1.2+ is when transmitting information from the client side to the
server. The transport endpoint's destination is
<https://api.verygoodproxy.com> which is already secured via TLSv1.2, so
it satisfies the guidance in that respect. The issue here is focused
over whether there is any risk on delivery of the JavaScript content to
the client via TLSv1.1. However, it is important, for this specific use
case, TLSv1.1 is just as secure as TLSv1.2.

### Migration Plan

There is no *real* security issue in
[TLSv1.1](http://tools.ietf.org/html/rfc4346) that
[TLSv1.2](http://tools.ietf.org/html/rfc5246) fixes. However, there are
changes and improvements, which can be argued to qualify as \"fixing\".
Mainly:

1.  The PRF in TLSv1.1 is based on a combination of MD5 and SHA-1. Both
    MD5 and SHA-1 are, as cryptographic hash function, academically
    broken (in the case of SHA-1, this is only theoretical for the
    moment). However, there is no known weakness in the PRF of TLSv1.1
    (nor, for that matter, in the PRF of SSLv3.0 and TLSv1.0): that PRF
    uses MD5 and SHA-1 but does not seem to be impacted by the known
    weaknesses in MD5 and SHA-1. Nevertheless, MD5 and SHA-1 are \"bad
    press.\" Common implementations of TLSv1.2 replaces both with
    SHA-256 (well, actually it could be any other hash function, but in
    practice it is SHA-256).

2.  TLSv1.2 allows the use of [authenticated
    encryption](http://en.wikipedia.org/wiki/Authenticated_encryption)
    modes like GCM. This can replace the more traditional CBC encryption
    mode, which has historically been a source of many flaws. Properly
    implemented CBC encryption is still fine; however, it appears that
    properly implementing CBC encryption is easier said than done.
    Getting GCM right seems a more readily achievable goal.

3.  TLSv1.2 mandates support for TLS\_RSA\_WITH\_AES\_128\_CBC\_SHA
    whereas TLSv1.1 required only TLS\_RSA\_WITH\_3DES\_EDE\_CBC\_SHA.
    Thus, if you use TLSv1.2 then you have a \"guarantee\" that AES
    encryption will be available. (This is not in fact completely true:
    the guarantee holds only as long as no \"application specific
    profile\" mandates otherwise. Also, you will get AES only if both
    client and server support it, and if they both support it, then it
    is available, regardless of whether TLSv1.1 or v1.2 is used.)

To summarize, there is no real flaw in TLSv1.1 that needed fixing and
would make a switch to TLSv1.2 mandatory or even recommended. However,
there is no reason either to stick to TLS 1.1 if implementation know
TLSv1.2.

In conclusion, the risk for transporting CDN content over TLSv1.1
instead of TLSv1.2 to support older clients is minimal specifically
since the transport of the card data payload happens over the guidance
recommended TLSv1.2.

########### PCI INDEX {#pci-index .APPENDIX}

12.8 7912.8.1 7912.8.2 7912.8.3 7912.8.4 7912.8.5 792.1 702.1.1 702.2
702.2.1 706.1 70

This page is intentionally blank to indicate the end of this document.

[^1]: Netiquette: Neologism of Network and Etiquette; the Knigge (book
    on etiquette) for online-users.

[^2]: Flame: Exaggerated verbal response to an article found on the
    Internet or in a Newsgroup that pollutes the network senselessly

[^3]: Mail bomb: Mail with huge attachment of rubbish or multiple
    broadcasting of nonsense
