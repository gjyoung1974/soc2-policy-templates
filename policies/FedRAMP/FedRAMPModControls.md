13.1 Access Control (AC)
-------------------------

### AC-1 Access Control Policy and Procedures Requirements (L) (M)

The organization:

\(a) Develops, documents and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) An access control policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the access control
policy and associated access controls; and 

\(b) Reviews and updates the current:

\(1) Access control policy \[*FedRAMP Assignment: at least every 3
years*\]; and

\(2) Access control procedures \[*FedRAMP Assignment: at least
annually*\].

### AC-2 Account Management (L) (M)

The organization:

\(a) Identifies and selects the following types of information system
accounts to support organizational missions/business functions:
\[*Assignment: organization-defined information system account types*\];

\(b) Assigns account managers for information system accounts;

\(c) Establishes conditions for group and role membership;

\(d) Specifies authorized users of the information system, group and role
membership, and access authorizations (i.e., privileges) and other
attributes (as required) for each account;

\(e) Requires approvals by \[*Assignment: organization-defined personnel
or roles*\] for requests to create information system accounts;

\(f) Creates, enables, modifies, disables, and removes information system
accounts in accordance with \[*Assignment: organization-defined
procedures or conditions*\];

\(g) Monitors the use of information system accounts;

\(h) Notifies account managers:

\(1) When accounts are no longer required;

\(2) When users are terminated or transferred; and

\(3) When individual information system usage or need-to-know changes;

\(i) Authorizes access to the information system based on:

\(1) A valid access authorization;

\(2) Intended system usage; and

\(3) Other attributes as required by the organization or associated
missions/business functions;

\(j) Reviews accounts for compliance with account management requirements
\[*FedRAMP Assignment: at least annually*\]; and

\(k) Establishes a process for reissuing shared/group account credentials
(if deployed) when individuals are removed from the group.

#### AC-2 (1) Control Enhancement (M) (H)

The organization employs automated mechanisms to support the management
of information system accounts.

#### AC-2 (2) Control Enhancement (M)

The information system automatically \[*Selection: removes; disables*\]
temporary and emergency accounts after \[*FedRAMP Assignment: no more
than 30 days for temporary and emergency account types*\].

#### AC-2 (3) Control Enhancement (M)

The information system automatically disables inactive accounts after
\[*FedRAMP Assignment: ninety (90) days for user accounts*\].

**AC-2 (3) Additional FedRAMP Requirements and Guidance:**

**Requirement**: The service provider defines the time period for
non-user accounts (e.g., accounts associated with devices). The time
periods are approved and accepted by the Joint Authorization Board
(JAB)/AO. Where user management is a function of the service, reports of
activity of consumer users shall be made available.

#### AC-2 (4) Control Enhancement (M)

The information system automatically audits account creation,
modification, enabling, disabling, and removal actions, and notifies
\[*Assignment: organization-defined personnel or roles*\].

#### AC-2 (5) Control Enhancement (M)

The organization requires that users log out when \[*Assignment:
organization-defined time-period of expected inactivity or description
of when to log out*\].

AC-2 (5) Additional FedRAMP Requirements and Guidance:

**Guidance**: Should use a shorter timeframe than AC-12

#### AC-2 (7) Control Enhancement (M)

The organization:

\(a) Establishes and administers privileged user accounts in accordance
with a role-based access scheme that organizes allowed information
system access and privileges into roles;

\(b) Monitors privileged role assignments; and

\(c) Takes \[*Assignment: organization-defined actions*\] when privileged
role assignments are no longer appropriate.

#### AC-2 (9) Control Enhancement (M)

The organization only permits the use of shared/group accounts that meet
\[*Assignment: organization-defined conditions for establishing
shared/group accounts*\].

**AC-2 (9) Additional FedRAMP Requirements and Guidance**: Required if
shared/group accounts are deployed.

#### AC-2 (10) Control Enhancement (M) (H)

The information system terminates shared/group account credentials when
members leave the group.

**AC-2 (10) Additional FedRAMP Requirements and Guidance:** Required if
shared/group accounts are deployed.

#### AC-2 (12) Control Enhancement (M)

The organization:

\(a) Monitors information system accounts for \[*Assignment:
organization-defined atypical use*\]; and

\(b) Reports atypical usage of information system accounts to
\[*Assignment: organization-defined personnel or roles*\].

**AC-2 (12) (a) and AC-2 (12) (b) Additional FedRAMP Requirements and
Guidance:** Required for privileged accounts.

### AC-3 Access Enforcement (L) (M) (H)

The information system enforces approved authorizations for logical
access to information and system resources in accordance with applicable
access control policies.

### AC-4 Information Flow Enforcement (M) (H)

The information system enforces approved authorizations for controlling
the flow of information within the system and between interconnected
systems based on \[*Assignment: organization-defined information flow
control policies*\].

#### AC-4 (21) Control Enhancement (M) (H)

The information system separates information flows logically or
physically using \[*Assignment: organization-defined mechanisms and/or
techniques*\] to accomplish \[*Assignment: organization-defined required
separations by types of information*\].

### AC-5 Separation of Duties (M) (H)

The organization:

\(a) Separates \[*Assignment: organization-defined duties of
individuals*\];

\(b) Documents separation of duties of individuals; and

\(c) Defines information system access authorizations to support
separation of duties.

**AC-5 Additional FedRAMP Requirements and Guidance:**

**Guidance**: CSPs have the option to provide a separation of duties
matrix as an attachment to the SSP. Directions for attaching the
Separation of Duties Matrix document may be found in Section 15.11
ATTACHMENT 11 - Separation of Duties Matrix.

### AC-6 Least Privilege (M) (H)

The organization employs the principle of least privilege, allowing only
authorized accesses for users (or processes acting on behalf of users)
which are necessary to accomplish assigned tasks in accordance with
organizational missions and business functions.

#### AC-6 (1) Control Enhancement (M)

The organization explicitly authorizes access to \[*Assignment:
organization-defined security functions (deployed in hardware, software,
and firmware) and security-relevant information*\].

#### AC-6 (2) Control Enhancement (M) (H)

The organization requires that users of information system accounts, or
roles, with access to \[*FedRAMP Assignment: all security functions*\],
use non-privileged accounts or roles, when accessing non-security
functions.

**AC-6 (2) Additional FedRAMP Requirements and Guidance:** Examples of
security functions include but are not limited to: establishing system
accounts, configuring access authorizations (i.e., permissions,
privileges), setting events to be audited, and setting intrusion
detection parameters, system programming, system and security
administration, other privileged functions.

#### AC 6 (5) Control Enhancement (M) (H)

The organization restricts privileged accounts on the information system
to \[*Assignment: organization-defined personnel or roles*\].

#### AC-6 (9) Control Enhancement (M) (H)

The information system audits the execution of privileged functions.

#### AC-6 (10) Control Enhancement (M) (H)

The information system prevents non-privileged users from executing
privileged functions to include disabling, circumventing, or altering
implemented security safeguards/countermeasures.

### AC-7 Unsuccessful Login Attempts (L) (M)

The organization:

\(a) Enforces a limit of \[*FedRAMP Assignment: not more than three
(3)*\] consecutive invalid logon attempts by a user during a \[*FedRAMP
Assignment: fifteen (15) minutes*\]; and

\(b) Automatically \[*Selection: locks the account/node for a* \[*FedRAMP
Assignment: thirty (30) minutes*\]; *delays next logon prompt according
to* \[*Assignment: organization-defined delay algorithm*\]\] when the
maximum number of unsuccessful attempts is exceeded.

### AC-8 System Use Notification (L) (M) (H)

The information system:

\(a) Displays to users \[*Assignment: organization-defined system use
notification message or banner (FedRAMP Assignment: see additional
Requirements and Guidance)*\] before granting access to the system that
provides privacy and security notices consistent with applicable federal
laws, Executive Orders, directives, policies, regulations, standards,
and guidance and states that:

\(1) Users are accessing a U.S. Government information system;

\(2) Information system usage may be monitored, recorded, and subject to
audit;

\(3) Unauthorized use of the information system is prohibited and subject
to criminal and civil penalties; and

\(4) Use of the information system indicates consent to monitoring and
recording;

\(b) Retains the notification message or banner on the screen until users
acknowledge the usage conditions and take explicit actions to log on to
or further access the information system; and

\(c) For publicly accessible systems:

\(1) Displays system use information \[*Assignment: organization-defined
conditions (FedRAMP Assignment: see additional Requirements and
Guidance)*\], before granting further access;

\(2) Displays references, if any, to monitoring, recording, or auditing
that are consistent with privacy accommodations for such systems that
generally prohibit those activities; and

\(3) Includes a description of the authorized uses of the system.

**AC-8 Additional FedRAMP Requirements and Guidance**:

**Requirement:** The service provider shall determine elements of the
cloud environment that require the System Use Notification control. The
elements of the cloud environment that require System Use Notification
are approved and accepted by the JAB/AO.

**Requirement:** The service provider shall determine how System Use
Notification is going to be verified and provide appropriate periodicity
of the check. The System Use Notification verification and periodicity
are approved and accepted by the JAB/AO.

**Guidance:** If performed as part of a Configuration Baseline check,
then the % of items requiring setting that are checked and that pass (or
fail) check can be provided.

**Requirement:** If not performed as part of a Configuration Baseline
check, then there must be documented agreement on how to provide results
of verification and the necessary periodicity of the verification by the
service provider. The documented agreement on how to provide
verification of the results are approved and accepted by the JAB/AO.

Additional FedRAMP Requirements and Guidance

**Requirement 1**: The service provider shall determine elements of the
cloud environment that require the System Use Notification control. The
elements of the cloud environment that require System Use Notification
are approved and accepted by the JAB/AO.

**Requirement 2**: The service provider shall determine how System Use
Notification is going to be verified and provide appropriate periodicity
of the check. The System Use Notification verification and periodicity
are approved and accepted by the JAB/AO. If performed as part of a
Configuration Baseline check, then the % of items requiring setting that
are checked and that pass (or fail) check can be provided.

**Requirement 3**: If not performed as part of a Configuration Baseline
check, then there must be documented agreement on how to provide results
of verification and the necessary periodicity of the verification by the
service provider. The documented agreement on how to provide
verification of the results are approved and accepted by the JAB/AO.

### AC-10 Concurrent Session Control (M) (H)

The information system limits the number of concurrent sessions for each
\[*Assignment: organization-defined account and/or account type*\] to
\[*FedRAMP Assignment: three (3) sessions for privileged access and two
(2) sessions for non-privileged access*\].

### AC-11 Session Lock (M) (H)

The information system:

\(a) Prevents further access to the system by initiating a session lock
after \[*FedRAMP Assignment: fifteen (15) minutes*\] of inactivity or
upon receiving a request from a user; and

\(b) Retains the session lock until the user reestablishes access using
established identification and authentication procedures.

#### AC-11 (1) Control Enhancement (M) (H)

The information system conceals, via the session lock, information
previously visible on the display with a publicly viewable image.

### AC-12 Session Termination (M) (H)

The information system automatically terminates a user session after
\[*Assignment: organization-defined conditions or trigger events
requiring session disconnect*\].

### AC-14 Permitted Actions without Identification or Authentication (L) (M) (H)

The organization:

\(a) Identifies \[*Assignment: organization-defined user actions*\] that
can be performed on the information system without identification or
authentication consistent with organizational missions/business
functions; and

\(b) Documents and provides supporting rationale in the security plan for
the information system, user actions not requiring identification or
authentication.

### AC-17 Remote Access (L) (M) (H)

The organization:

\(a) Establishes and documents usage restrictions,
configuration/connection requirements, and implementation guidance for
each type of remote access allowed; and

\(b) Authorizes remote access to the information system prior to allowing
such connections.

#### AC-17 (1) Control Enhancement (M) (H)

The information system monitors and controls remote access methods.

#### AC-17 (2) Control Enhancement (M) (H)

The information system implements cryptographic mechanisms to protect
the confidentiality and integrity of remote access sessions.

#### AC-17 (3) Control Enhancement (M) (H)

The information system routes all remote accesses through \[*Assignment:
organization-defined number*\] managed network access control points.

#### AC-17 (4) Control Enhancement (M) (H)

The organization:

\(a) Authorizes the execution of privileged commands and access to
security-relevant information via remote access only for \[*Assignment:
organization-defined needs*\]; and

\(b) Documents the rationale for such access in the security plan for the
information system.

#### AC-17 (9) Control Enhancement (M) (H)

The organization provides the capability to expeditiously disconnect or
disable remote access to the information system within \[*FedRAMP
Assignment: fifteen (15) minutes*\].

### AC-18 Wireless Access Restrictions (L) (M) (H)

The organization:

\(a) Establishes usage restrictions, configuration/connection
requirements, and implementation guidance for wireless access; and

\(b) Authorizes wireless access to the information system prior to
allowing such connections.

#### AC-18 (1) Control Enhancement (M) (H)

The information system protects wireless access to the system using
authentication of \[*Selection (one or more): users; devices*\] and
encryption.

### AC-19 Access Control for Portable and Mobile Systems (L) (M) (H)

The organization:

\(a) Establishes usage restrictions, configuration requirements,
connection requirements, and implementation guidance for
organization-controlled mobile devices; and

\(b) Authorizes the connection of mobile devices to organizational
information systems.

#### AC-19 (5) Control Enhancement (M) (H)

The organization employs \[*Selection: full-device encryption; container
encryption\]* to protect the confidentiality and integrity of
information on \[*Assignment: organization-defined mobile devices*\].

### AC-20 Use of External Information Systems (L) (M) (H)

The organization establishes terms and conditions, consistent with any
trust relationships established with other organizations owning,
operating, and/or maintaining external information systems, allowing
authorized individuals to:

\(a) Access the information system from external information systems; and

\(b) Process, store, or transmit organization-controlled information
using external information systems.

#### AC-20 (1) Control Enhancement (M) (H)

The organization permits authorized individuals to use an external
information system to access the information system or to process,
store, or transmit organization-controlled information only when the
organization:

\(a) Verifies the implementation of required security controls on the
external system as specified in the organization’s information security
policy and security plan; or

\(b) Retains approved information system connection or processing
agreements with the organizational entity hosting the external
information system.

#### AC-20 (2) Control Enhancement (M) (H)

The organization \[*Selection: restricts; prohibits*\] the use of
organization-controlled portable storage devices by authorized
individuals on external information systems.

### AC-21 Information Sharing (M) (H)

The organization:

\(a) Facilitates information sharing by enabling authorized users to
determine whether access authorizations assigned to the sharing partner
match the access restrictions on the information for \[*Assignment:
organization-defined information sharing circumstances where user
discretion is required*\]; and

\(b) Employs \[*Assignment: organization-defined automated mechanisms or
manual processes*\] to assist users in making information
sharing/collaboration decisions.

### AC-22 Publicly Accessible Content (L) (M) (H)

The organization:

\(a) Designates individuals authorized to post information onto a
publicly accessible information system;

\(b) Trains authorized individuals to ensure that publicly accessible
information does not contain nonpublic information;

\(c) Reviews the proposed content of information prior to posting onto
the publicly accessible information system to ensure that nonpublic
information is not included; and

\(d) Reviews the content on the publicly accessible information system
for nonpublic information \[*FedRAMP Assignment: at least quarterly*\]
and removes such information, if discovered.

13.2 Awareness and Training (AT)
---------------------------------

### AT-1 Security Awareness and Training Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A security awareness and training policy that addresses purpose,
scope, roles, responsibilities, management commitment, coordination
among organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the security
awareness and training policy and associated security awareness and
training controls; and

\(b) Reviews and updates the current:

\(1) Security awareness and training policy \[*FedRAMP Assignment: at
least every 3 years*\]; and

\(2) Security awareness and training procedures \[*FedRAMP Assignment: at
least annually*\].

### AT-2 Security Awareness (L) (M) (H)

The organization provides basic security awareness training to
information system users (including managers, senior executives, and
contractors):

\(a) As part of initial training for new users;

\(b) When required by information system changes; and

\(c) \[*FedRAMP Assignment: at least annually*\] thereafter.

#### AT-2 (2) Control Enhancement (M) (H)

The organization includes security awareness training on recognizing and
reporting potential indicators of insider threat.

### AT-3 Role-Based Security Training (L) (M) (H)

The organization provides role-based security training to personnel with
assigned security roles and responsibilities:

\(a) Before authorizing access to the information system or performing
assigned duties;

\(b) When required by information system changes; and

\(c) \[*FedRAMP Assignment: at least annually*\] thereafter.

#### AT-4 Security Training Records (L) (M)

The organization:

\(a) Documents and monitors individual information system security
training activities including basic security awareness training and
specific information system security training; and

\(b) Retains individual training records for \[*FedRAMP Assignment: at
least one year*\].

13.3 Audit and Accountability (AU)
----------------------------------

### AU-1 Audit and Accountability Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) An audit and accountability policy that addresses purpose, scope,
roles, responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the audit and
accountability policy and associated audit and accountability controls;
and

\(b) Reviews and updates the current:

\(1) Audit and accountability policy \[*FedRAMP Assignment: at every 3
years*\]; and

\(2) Audit and accountability procedures \[*FedRAMP Assignment: at least
annually*\].

### AU-2 Audit Events (L) (M) (H)

The organization:

\(a) Determines that the information system is capable of auditing the
following events: \[*FedRAMP Assignment:* \[*Successful and unsuccessful
account logon events, account management events, object access, policy
change, privilege functions, process tracking, and system events. For
Web applications: all administrator activity, authentication checks,
authorization checks, data deletions, data access, data changes, and
permission changes*\];

\(b) Coordinates the security audit function with other organizational
entities requiring audit-related information to enhance mutual support
and to help guide the selection of auditable events;

\(c) Provides a rationale for why the auditable events are deemed to be
adequate to support after-the-fact investigations of security incidents;
and

\(d) Determines that the following events are to be audited within the
information system: \[*FedRAMP Assignment: organization-defined subset
of the auditable events defined in AU-2 a. to be audited continually for
each identified event*\].

**AU-2 Additional FedRAMP Requirements and Guidance:**

**Requirement**: Coordination between service provider and consumer
shall be documented and accepted by the JAB/AO.

#### AU-2 (3) Control Enhancement (M) (H)

The organization reviews and updates the audited events \[*FedRAMP
Assignment: annually or whenever there is a change in the threat
environment*\].

**AU-2 (3) Additional FedRAMP Requirements and Guidance:**

**Guidance**: Annually or whenever changes in the threat environment are
communicated to the service provider by the JAB/AO.

### AU-3 Content of Audit Records (L) (M) (H)

The information system generates audit records containing information
that establishes what type of event occurred, when the event occurred,
where the event occurred, the source of the event, the outcome of the
event, and the identity of any individuals or subjects associated with
the event.

#### AU-3 (1) Control Enhancement (M)

The information system generates audit records containing the following
additional information: \[*Assignment: organization-defined additional,
more detailed information*\].

**AU-3 (1) Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider defines audit record types
\[*FedRAMP Assignment: session, connection, transaction, or activity
duration; for client-server transactions, the number of bytes received
and bytes sent; additional informational messages to diagnose or
identify the event; characteristics that describe or identify the object
or resource being acted upon*\]. The audit record types are approved and
accepted by the JAB.

**Guidance:** For client-server transactions, the number of bytes sent
and received gives bidirectional transfer information that can be
helpful during an investigation or inquiry.

### AU-4 Audit Storage Capacity (L) (M) (H)

The organization allocates audit record storage capacity in accordance
with \[*Assignment: organization-defined audit record storage
requirements*\].

### AU-5 Response to Audit Processing Failures (L) (M) (H)

The information system:

\(a) Alerts \[*Assignment: organization-defined personnel or roles*\] in
the event of an audit processing failure; and

\(b) Takes the following additional actions: \[*FedRAMP Assignment:
organization-defined actions to be taken; (overwrite oldest record)*\].

### AU-6 Audit Review, Analysis, and Reporting (L) (M) (H)

The organization:

\(a) Reviews and analyzes information system audit records \[*FedRAMP
Assignment: at least weekly*\] for indications of \[*Assignment:
organization-defined inappropriate or unusual activity*\]; and

\(b) Reports findings to \[*Assignment: organization-defined personnel or
roles*\].

**AU-6 Additional FedRAMP Requirements and Guidance:**

**Requirement:** Coordination between service provider and consumer
shall be documented and accepted by the Authorizing Official. In
multi-tenant environments, capability and means for providing review,
analysis, and reporting to consumer for data pertaining to consumer
shall be documented.

#### AU-6 (1) Control Enhancement (M) (H)

The organization employs automated mechanisms to integrate audit review,
analysis, and reporting processes to support organizational processes
for investigation and response to suspicious activities.

#### AU-6 (3) Control Enhancement (M) (H)

The organization analyzes and correlates audit records across different
repositories to gain organization-wide situational awareness.

### AU-7 Audit Reduction and Report Generation (M) (H)

The information system provides an audit reduction and report generation
capability that:

\(a) Supports on-demand audit review, analysis, and reporting
requirements and after-the-fact investigations of security incidents;
and

\(b) Does not alter the original content or time ordering of audit
records.

#### AU-7 (1) Control Enhancement (M) (H)

The information system provides the capability to process audit records
for events of interest based on \[*Assignment: organization-defined
audit fields within audit records*\].

### AU-8 Time Stamps (L) (M) (H)

The information system:

\(a) Uses internal system clocks to generate time stamps for audit
records; and

\(b) Records time stamps for audit records that can be mapped to
Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) and meets
\[*Assignment: one second granularity of time measurement*\].

#### AU-8 (1) Control Enhancement (M) (H)

The information system:

\(a) Compares the internal information system clocks with \[*FedRAMP
Assignment: authoritative time source:*
\[[*http://tf.nist.gov/tf-cgi/servers.cgi*](http://tf.nist.gov/tf-cgi/servers.cgi)\]
*\[at least hourly\]*\]; and

\(b) Synchronizes the internal system clocks to the authoritative time
source when the time difference is greater than \[*Assignment:
organization-defined time period*\].

**AU-8 (1) Additional FedRAMP Requirements and Guidance:**

**Requirement**: The service provider selects primary and secondary time
servers used by the NIST Internet time service. The secondary server is
selected from a different geographic region than the primary server.

**Requirement**: The service provider synchronizes the system clocks of
network computers that run operating systems other than Windows to the
Windows Server Domain Controller emulator or to the same time source for
that server.

**Guidance**: The service provider selects primary and secondary time
servers used by the NIST Internet time service, or by a Stratum-1 time
server. The secondary server is selected from a different geographic
region than the primary server.

If using Windows Active Directory, all servers should synchronize time
with the time source for the Windows Domain Controller. If using some
other directory services (e.g., LDAP), all servers should synchronize
time with the time source for the directory server

AU-8 (1) Additional FedRAMP Requirements and Guidance:

**Requirement 1:** The service provider selects primary and secondary
time servers used by the NIST Internet time service. The secondary
server is selected from a different geographic region than the primary
server.

**Requirement 2:** The service provider synchronizes the system clocks
of network computers that run operating systems other than Windows to
the Windows Server Domain Controller emulator or to the same time source
for that server.

**Guidance:** Synchronization of system clocks improves the accuracy of
log analysis.

### AU-9 Protection of Audit Information (L) (M) (H)

The information system protects audit information and audit tools from
unauthorized access, modification, and deletion.

#### AU-9 (2) Control Enhancement (M) (H)

The information system backs up audit records \[*FedRAMP Assignment: at
least weekly*\] onto a physically different system or system component
than the system or component being audited.

#### AU-9 (4) Control Enhancement (M) (H)

The organization authorizes access to management of audit functionality
to only \[*Assignment: organization-defined subset of privileged
users*\].

### AU-11 Audit Record Retention (M)

The organization retains audit records for \[*FedRAMP Assignment: at
least ninety (90) days*\] to provide support for after-the-fact
investigations of security incidents and to meet regulatory and
organizational information retention requirements.

**AU-11 Additional FedRAMP Requirements and Guidance:**

**Requirement**: The service provider retains audit records on-line for
at least ninety days and further preserves audit records off-line for a
period that is in accordance with NARA requirements

### AU-12 Audit Generation (L) (M) (H)

The information system:

\(a) Provides audit record generation capability for the auditable events
defined in AU-2 a. at \[*FedRAMP Assignment:* *all information system
components where audit capability is deployed/available*\];

\(b) Allows \[*Assignment: organization-defined personnel or roles*\] to
select which auditable events are to be audited by specific components
of the information system; and

\(c) Generates audit records for the events defined in AU-2 d. with the
content defined in AU-3.

13.4 Security Assessment and Authorization (CA)
-----------------------------------------------

### CA-1 Certification, Authorization, Security Assessment Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A security assessment and authorization policy that addresses
purpose, scope, roles, responsibilities, management commitment,
coordination among organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the security
assessment and authorization policy and associated security assessment
and authorization controls; and

\(b) Reviews and updates the current:

\(1) Security assessment and authorization policy \[*FedRAMP Assignment:
at least every three (3) years*\]; and

\(2) Security assessment and authorization procedures \[*FedRAMP
Assignment: at least annually*\].

### CA-2 Security Assessments (L) (M) (H)

The organization:

\(a) Develops a security assessment plan that describes the scope of the
assessment including:

\(1) Security controls and control enhancements under assessment;

\(2) Assessment procedures to be used to determine security control
effectiveness; and

\(3) Assessment environment, assessment team, and assessment roles and
responsibilities;

\(b) Assesses the security controls in the information system and its
environment of operation \[*FedRAMP Assignment: at least annually*\] to
determine the extent to which the controls are implemented correctly,
operating as intended, and producing the desired outcome with respect to
meeting established security requirements;

\(c) Produces a security assessment report that documents the results of
the assessment; and

\(d) Provides the results of the security control assessment to
\[*FedRAMP Assignment: individuals or roles to include the FedRAMP
Program Management Office (PMO)*\].

#### CA-2 (1) Control Enhancement (L) (M) (H)

The organization employs assessors or assessment teams with
\[*Assignment: organization-defined level of independence*\] to conduct
security control assessments.

CA-2 (1) Additional FedRAMP Requirements and Guidance:

**Requirement:** For JAB Authorization, must use an accredited Third
Party Assessment Organization (3PAO).

#### CA-2 (2) Control Enhancement (M) (H)

The organization includes as part of security control assessments,
\[*FedRAMP Assignment: at least annually*\], \[*Selection: announced;
unannounced*\], \[*Selection (one or more): in-depth monitoring;
vulnerability scanning; malicious user testing; insider threat
assessment; performance/load testing;* \[*Assignment:
organization-defined other forms of security assessment*\]\].

**CA-2 (2) Additional FedRAMP Requirements and Guidance:**

**Requirement**: To include *'announced'*, *'vulnerability scanning’ to
occur at least annually*.

#### CA-2 (3) Control Enhancement (M) (H)

The organization accepts the results of an assessment of \[*FedRAMP
Assignment: organization-defined information system*\] performed by
\[*FedRAMP Assignment: any FedRAMP Accredited 3PAO*\] when the
assessment meets \[*FedRAMP Assignment: the conditions of the* JAB/AO
*in the FedRAMP Repository*\].

### CA-3 System Interconnections (L) (M) (H)

The organization:

\(a) Authorizes connections from the information system to other
information systems through the use of Interconnection Security
Agreements;

\(b) Documents, for each interconnection, the interface characteristics,
security requirements, and the nature of the information communicated;
and

\(c) Reviews and updates Interconnection Security Agreements \[*FedRAMP
Assignment: at least annually and on input from FedRAMP*\].

Table 13‑3 CA-3 Authorized Connections

#### CA-3 (3) Control Enhancement (M) (H)

The organization prohibits the direct connection of an \[*Assignment:
organization-defined unclassified, non-national security system*\] to an
external network without the use of \[*FedRAMP Assignment: boundary
protections which meet Trusted Internet Connection (TIC)
requirements*\].

**CA-3 (3) Additional FedRAMP Requirements and Guidance:** Refer to
Appendix H – Cloud Considerations of the TIC 2.0 Reference Architecture
document. Link:
https://www.fedramp.gov/files/2015/04/TIC\_Ref\_Arch\_v2-0\_2013.pdf

#### CA-3 (5) Control Enhancement (M)

The organization employs \[*Selection: allow-all, deny-by-exception,
deny-all, permit by exception*\] policy for allowing \[*Assignment:
organization-defined information systems*\] to connect to external
information systems.

**CA-3 (5) Additional FedRAMP Requirements and Guidance:**

**Guidance**: For JAB Authorization, CSPs shall include details of this
control in their Architecture Briefing

### CA-5 Plan of Action and Milestones (L) (M) (H)

The organization:

\(a) Develops a plan of action and milestones for the information system
to document the organization’s planned remedial actions to correct
weaknesses or deficiencies noted during the assessment of the security
controls and to reduce or eliminate known vulnerabilities in the system;
and

\(b) Updates existing plan of action and milestones \[*FedRAMP
Assignment: at least monthly*\] based on the findings from security
controls assessments, security impact analyses, and continuous
monitoring activities.

**CA-5 Additional FedRAMP Requirements and Guidance:**

**Requirement**: Plan Of Action & Milestones (POA&M)s must be provided
at least monthly.

### CA-6 Security Authorization (L) (M) (H)

The organization:

\(a) Assigns a senior-level executive or manager as the authorizing
official for the information system;

\(b) Ensures that the authorizing official authorizes the information
system for processing before commencing operations; and

\(c) Updates the security authorization \[*FedRAMP Assignment: in
accordance with OMB A-130 requirements or when a significant change
occurs*\].

**CA-6c Additional FedRAMP Requirements and Guidance:**

**Guidance**: Significant change is defined in NIST Special Publication
800-37 Revision 1, Appendix F ([SP
800-37](http://csrc.nist.gov/publications/nistpubs/800-37-rev1/sp800-37-rev1-final.pdf)).
The service provider describes the types of changes to the information
system or the environment of operations that would impact the risk
posture. The types of changes are approved and accepted by the JAB/AO.

### CA-7 Continuous Monitoring (L) (M) (H)

The organization develops a continuous monitoring strategy and
implements a continuous monitoring program that includes:

\(a) Establishment of \[*Assignment: organization-defined metrics*\] to
be monitored;

\(b) Establishment of \[*Assignment: organization-defined frequencies*\]
for monitoring and \[*Assignment: organization-defined frequencies*\]
for assessments supporting such monitoring;

\(c) Ongoing security control assessments in accordance with the
organizational continuous monitoring strategy;

\(d) Ongoing security status monitoring of organization-defined metrics
in accordance with the organizational continuous monitoring strategy;

\(e) Correlation and analysis of security-related information generated
by assessments and monitoring;

\(f) Response actions to address results of the analysis of
security-related information; and

\(g) Reporting the security status of organization and the information
system to \[*FedRAMP Assignment: to meet Federal and FedRAMP
requirements*\] \[*Assignment: organization-defined frequency*\].

**CA-7 Additional FedRAMP Requirements and Guidance**:

**Requirement:** Operating System Scans: at least monthly Database and
Web Application Scans: at least monthly All scans performed by
Independent Assessor: at least annually.

**Guidance**: CSPs must provide evidence of closure and remediation of a
high vulnerability within the timeframe for standard POA&M updates.

CA-7 Additional FedRAMP Requirements and Guidance:

**Requirement 1:** Operating System Scans: at least monthly

**Requirement 2:** Database and Web Application Scans: at least monthly

**Requirement 3:** All scans performed by Independent Assessor: at least
annually

#### CA-7 (1) Control Enhancement (M) (H)

The organization employs assessors or assessment teams with
\[*Assignment: organization-defined level of independence*\] to monitor
the security controls in the information system on an ongoing basis.

### CA-8 Penetration Testing (M) (H)

The organization conducts penetration testing \[*FedRAMP Assignment: at
least annually*\] on \[*Assignment: organization-defined information
systems or system components*\].

#### CA-8 (1) Control Enhancement (M) (H)

The organization employs an independent penetration agent or penetration
team to perform penetration testing on the information system or system
components.

### CA-9 Internal System Connections (L) (M) (H)

The organization:

\(a) Authorizes internal connections of \[*Assignment:
organization-defined information system components or classes of
components*\] to the information system; and

\(b) Documents, for each internal connection, the interface
characteristics, security requirements, and the nature of the
information communicated.

13.5 Configuration Management (CM)
----------------------------------

### CM-1 Configuration Management Policies and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles\]:*

\(1) A configuration management policy that addresses purpose, scope,
roles, responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the configuration
management policy and associated configuration management controls; and

\(b) Reviews and updates the current:

\(1) Configuration management policy \[*FedRAMP Assignment: at least
every three (3) years*\]; and

\(2) Configuration management procedures \[*FedRAMP Assignment: at least
annually*\].

### CM-2 Baseline Configuration (L) (M) (H)

The organization develops, documents, and maintains under configuration
control, a current baseline configuration of the information system.

#### CM-2 (1) Control Enhancement (M)

The organization reviews and updates the baseline configuration of the
information system:

\(a) \[*FedRAMP Assignment: at least annually*\];

\(b) When required due to \[*FedRAMP Assignment: to include when directed
by the JAB*\]; and

\(c) As an integral part of information system component installations
and upgrades.

#### CM-2 (2) Control Enhancement (M) (H)

The organization employs automated mechanisms to maintain an up-to-date,
complete, accurate, and readily available baseline configuration of the
information system.

#### CM-2 (3) Control Enhancement (M)

The organization retains \[*Assignment: organization-defined previous
versions of baseline configurations of the information system*\] to
support rollback.

#### CM-2 (7) Control Enhancement (M) (H)

The organization:

\(a) Issues \[*Assignment: organization-defined information systems,
system components, or devices*\] with \[*Assignment:
organization-defined configurations*\] to individuals traveling to
locations that the organization deems to be of significant risk; and

\(b) Applies \[*Assignment: organization-defined security safeguards*\]
to the devices when the individuals return.

### CM-3 Configuration Change Control (M) (H)

The organization:

\(a) Determines the types of changes to the information system that are
configuration-controlled;

\(b) Reviews proposed configuration-controlled changes to the information
system and approves or disapproves such changes with explicit
consideration for security impact analyses;

\(c) Documents configuration change decisions associated with the
information system;

\(d) Implements approved configuration-controlled changes to the
information system;

\(e) Retains records of configuration-controlled changes to the
information system for \[*Assignment: organization-defined time
period*\];

**CM-3 (e) Additional FedRAMP Requirements and Guidance**:

**Guidance**: In accordance with record retention policies and
procedures.

\(f) Audits and reviews activities associated with
configuration-controlled changes to the information system; and

\(g) Coordinates and provides oversight for configuration change control
activities through \[*FedRAMP Assignment: see additional FedRAMP
requirements and guidance*\] that convenes \[*Selection (one or more):
\[Assignment: organization-defined frequency*\]; \[*Assignment:
organization-defined configuration change conditions*\]\].

CM-3 Additional FedRAMP Requirements and Guidance:

**Requirement**: The service provider establishes a central means of
communicating major changes to or developments in the information system
or environment of operations that may affect its services to the federal
government and associated service consumers (e.g., electronic bulletin
board, web status page). The means of communication are approved and
accepted by the JAB/AO.

### CM-4 Security Impact Analysis (L) (M) (H)

The organization analyzes changes to the information system to determine
potential security impacts prior to change implementation.

### CM-5 Access Restrictions for Change (M) (H)

The organization defines, documents, approves, and enforces physical and
logical access restrictions associated with changes to the information
system.

#### CM-5 (1) Control Enhancement (M) (H)

The information system enforces access restrictions and supports
auditing of the enforcement actions.

#### CM-5 (3) Control Enhancement (M) (H)

The information system prevents the installation of \[*Assignment:
organization-defined software and firmware components*\] without
verification that the component has been digitally signed using a
certificate that is recognized and approved by the organization.

**CM-5 (3) Additional FedRAMP Requirements and Guidance**:

**Guidance**: If digital signatures/certificates are unavailable,
alternative cryptographic integrity checks (hashes, self-signed certs,
etc.) can be used.

#### CM-5 (5) Control Enhancement (M) (H)

The organization:

\(a) Limits privileges to change information system components and
system-related information within a production or operational
environment; and

\(b) Reviews and reevaluates privileges \[*FedRAMP Assignment: at least
quarterly*\].

### CM-6 Configuration Settings (L) (M) (H)

The organization:

\(a) Establishes and documents configuration settings for information
technology products employed within the information system using
\[*FedRAMP Assignment: see CM-6(a) Additional FedRAMP Requirements and
Guidance*\] that reflect the most restrictive mode consistent with
operational requirements;

CM-6(a) Additional FedRAMP Requirements and Guidance:

**Requirement 1:** The service provider shall use the Center for
Internet Security guidelines (Level 1) to establish configuration
settings or establishes its own configuration settings if USGCB is not
available. If no recognized USGCB is available for the technology in
use, the CSP should create their own baseline and include a
justification statement as to how they came up with the baseline
configuration settings.

**Requirement 2:** The service provider shall ensure that checklists for
configuration settings are Security Content Automation Protocol (SCAP)
(<http://scap.nist.gov/>) validated or SCAP compatible (if validated
checklists are not available).

**Guidance:** Information on the USGCB checklists can be found at:
<http://usgcb.nist.gov/usgcb_faq.html#usgcbfaq_usgcbfdcc>.

\(b) Implements the configuration settings;

\(c) Identifies, documents, and approves any deviations from established
configuration settings for \[*Assignment: organization-defined
information system components*\] based on \[*Assignment:
organization-defined operational requirements*\]; and

\(d) Monitors and controls changes to the configuration settings in
accordance with organizational policies and procedures.

#### CM-6 (1) Control Enhancement (M) (H)

The organization employs automated mechanisms to centrally manage,
apply, and verify configuration settings for \[*Assignment:
organization-defined information system components*\].

### CM-7 Least Functionality (L) (M) (H)

The organization:

\(a) Configures the information system to provide only essential
capabilities; and

\(b) Prohibits or restricts the use of the following functions, ports,
protocols, and/or services \[*FedRAMP Assignment: United States
Government Configuration Baseline (USGCB)*\]

**CM-7 Additional FedRAMP Requirements and Guidance:**

**Requirement**: The service provider shall use the Center for Internet
Security guidelines (Level 1) to establish list of prohibited or
restricted functions, ports, protocols, and/or services or establishes
its own list of prohibited or restricted functions, ports, protocols,
and/or services if USGCB is not available. If no recognized USGCB is
available for the technology in use, the CSP should create their own
baseline and include a justification statement as to how they came up
with the baseline configuration settings.

**Guidance**: Information on the USGCB checklists can be found at:
<http://usgcb.nist.gov/usgcb_faq.html#usgcbfaq_usgcbfdcc>

Partially derived from AC-17 (8).

#### CM-7 (1) Control Enhancement (M) (H)

The organization:

\(a) Reviews the information system \[*FedRAMP Assignment: at least
Monthly*\] to identify unnecessary and/or nonsecure functions, ports,
protocols, and services; and

\(b) Disables \[*Assignment: organization-defined functions, ports,
protocols, and services within the information system deemed to be
unnecessary and/or nonsecure*\].

#### CM-7 (2) Control Enhancement (M) (H)

The information system prevents program execution in accordance with
\[*Selection (one or more): \[Assignment: organization-defined policies
regarding software program usage and restrictions\]; rules authorizing
the terms and conditions of software program usage*\].

**CM-7(2) Additional FedRAMP Requirements and Guidance**:

**Guidance**: This control shall be implemented in a technical manner on
the information system to only allow programs to run that adhere to the
policy (i.e., white listing). This control is not to be based off of
strictly written policy on what is allowed or not allowed to run.

#### CM-7 (5) Control Enhancement (M)

The organization:

\(a) Identifies \[*Assignment: organization-defined software programs
authorized to execute on the information system*\];

\(b) Employs a deny-all, permit-by-exception policy to allow the
execution of authorized software programs on the information system; and

\(c) Reviews and updates the list of authorized software programs
\[*FedRAMP Assignment: at least annually or when there is a change*\].

### CM-8 Information System Component Inventory (L) (M) (H)

The organization:

\(a) Develops and documents an inventory of information system components
that:

\(1) Accurately reflects the current information system;

\(2) Includes all components within the authorization boundary of the
information system;

\(3) Is at the level of granularity deemed necessary for tracking and
reporting; and

\(4) Includes \[*Assignment: organization-defined information deemed
necessary to achieve effective information system component
accountability*\]; and

\(b) Reviews and updates the information system component inventory
\[*FedRAMP Assignment: at least monthly*\].

**CM-8 Additional FedRAMP Requirements and Guidance**:

**Requirement**: Must be provided at least monthly or when there is a
change.

#### CM-8 (1) Control Enhancement (M) (H)

The organization updates the inventory of information system components
as an integral part of component installations, removals, and
information system updates.

Instruction: A description of the inventory information is documented in
Section 10. It is not necessary to re-document it here.

Delete this and all other instructions from your final version of this
document.

#### CM-8 (3) Control Enhancement (M) (H)

The organization:

\(a) Employs automated mechanisms \[*FedRAMP Assignment: Continuously,
using automated mechanisms with a maximum five-minute delay in
detection*\] to detect the presence of unauthorized hardware, software,
and firmware components within the information system; and

\(b) Takes the following actions when unauthorized components are
detected: \[*Selection (one or more): disables network access by such
components; isolates the components; notifies* \[*Assignment:
organization-defined personnel or roles*\]\].

#### CM-8 (5) Control Enhancement (M) (H)

The organization verifies that all components within the authorization
boundary of the information system are not duplicated in other
information system inventories.

### CM-9 Configuration Management Plan (M) (H)

The organization develops, documents, and implements a configuration
management plan for the information system that:

\(a) Addresses roles, responsibilities, and configuration management
processes and procedures;

\(b) Establishes a process for identifying configuration items throughout
the system development life cycle and for managing the configuration of
the configuration items;

\(c) Defines the configuration items for the information system and
places the configuration items under configuration management; and

\(d) Protects the configuration management plan for unauthorized
disclosure and modification.

### CM-10 Software Usage Restrictions (L) (M) (H)

The organization:

\(a) Uses software and associated documentation in accordance with
contract agreements and copyright laws;

\(b) Tracks the use of software and associated documentation protected by
quantity licenses to control copying and distribution; and

\(c) Controls and documents the use of peer-to-peer file sharing
technology to ensure that this capability is not used for the
unauthorized distribution, display, performance, or reproduction of
copyrighted work.

#### CM-10 (1) Control Enhancement (M) (H)

The organization establishes the following restrictions on the use of
open source software: \[*Assignment: organization-defined
restrictions*\].

### CM-11 User-Installed Software (M) (H)

The organization:

\(a) Establishes \[*Assignment: organization-defined policies*\]
governing the installation of software by users;

\(b) Enforces software installation policies through \[*Assignment:
organization-defined methods*\]; and

\(c) Monitors policy compliance \[*FedRAMP* *Assignment: Continuously
(via CM-7 (5))*\].

13.6 Contingency Planning (CP)
------------------------------

### CP-1 Contingency Planning Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A contingency planning policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the contingency
planning policy and associated contingency planning controls; and

\(b) Reviews and updates the current:

\(1) Contingency planning policy \[*FedRAMP Assignment: at least every
three (3) years*\].; and

\(2) Contingency planning procedures \[*FedRAMP Assignment: at least
annually*\].

### CP-2 Contingency Plan (L) (M) (H)

The organization:

\(a) Develops a contingency plan for the information system that:

\(1) Identifies essential missions and business functions and associated
contingency requirements;

\(2) Provides recovery objectives, restoration priorities, and metrics;

\(3) Addresses contingency roles, responsibilities, assigned individuals
with contact information;

\(4) Addresses maintaining essential missions and business functions
despite an information system disruption, compromise, or failure;

\(5) Addresses eventual, full information system restoration without
deterioration of the security safeguards originally planned and
implemented; and

\(6) Is reviewed and approved by \[*Assignment: organization-defined
personnel or roles*\];

\(b) Distributes copies of the contingency plan to \[*Assignment:
organization-defined key contingency personnel (identified by name
and/or by role) and organizational elements*\];

\(c) Coordinates contingency planning activities with incident handling
activities;

\(d) Reviews the contingency plan for the information system \[*FedRAMP
Assignment: at least annually*\];

\(e) Updates the contingency plan to address changes to the organization,
information system, or environment of operation and problems encountered
during contingency plan implementation, execution, or testing;

\(f) Communicates contingency plan changes to \[*Assignment:
organization-defined key contingency personnel (identified by name
and/or by role) and organizational elements*\]; and

\(g) Protects the contingency plan from unauthorized disclosure and
modification.

**CP-2 Additional FedRAMP Requirements and Guidance:**

**Requirement**: For JAB authorizations the contingency lists include
designated FedRAMP personnel.

#### CP-2 (1) Control Enhancement (M) (H)

The organization coordinates contingency plan development with
organizational elements responsible for related plans.

#### CP-2 (2) Control Enhancement (M) (H)

The organization conducts capacity planning so that necessary capacity
for information processing, telecommunications, and environmental
support exists during contingency operations.

#### CP-2 (3) Control Enhancement (M) (H)

The organization plans for the resumption of essential missions and
business functions within \[*Assignment: organization-defined time
period*\] of contingency plan activation.

#### CP-2 (8) Control Enhancement (M) (H)

The organization identifies critical information system assets
supporting essential missions and business functions.

### CP-3 Contingency Training (L) (M) (H)

The organization provides contingency training to information system
users consistent with assigned roles and responsibilities:

\(a) Within \[*FedRAMP Assignment: ten (10) days*\] of assuming a
contingency role or responsibility;

\(b) When required by information system changes; and

\(c) \[*FedRAMP Assignment: at least annually*\] thereafter.

### CP-4 Contingency Plan Testing (H)

The organization:

\(a) Tests the contingency plan for the information system \[*FedRAMP
Assignment: at least annually*\] using \[*FedRAMP Assignment: functional
exercises*\] to determine the effectiveness of the plan and the
organizational readiness to execute the plan;

CP-4(a) Additional FedRAMP Requirements and Guidance:

**Requirement:** The service provider develops test plans in accordance
with NIST Special Publication 800-34 (as amended) and provides plans to
FedRAMP prior to initiating testing. Test plans are approved and
accepted by the JAB/AO prior to initiating testing.

\(b) Reviews the contingency plan test results; and

\(c) Initiates corrective actions, if needed.

#### CP-4 (1) Control Enhancement (M) (H)

The organization coordinates contingency plan testing and/or exercises
with organizational elements responsible for related plans.

### CP-6 Alternate Storage Site (M) (H)

The organization:

\(a) Establishes an alternate storage site including necessary agreements
to permit the storage and retrieval of information system backup
information; and

\(b) Ensures that the alternate storage site provides information
security safeguards equivalent to that of the primary site.

#### CP-6 (1) Control Enhancement (M) (H)

The organization identifies an alternate storage site that is separated
from the primary storage site to reduce susceptibility to the same
threats.

#### CP-6 (3) Control Enhancement (M) (H)

The organization identifies potential accessibility problems to the
alternate storage site in the event of an area-wide disruption or
disaster and outlines explicit mitigation actions.

### CP-7 Alternate Processing Site (M) (H)

The organization:

\(a) Establishes an alternate processing site including necessary
agreements to permit the transfer and resumption of \[*Assignment:
organization-defined information system operations*\] for essential
missions/business functions within \[*FedRAMP Assignment: see additional
FedRAMP requirements and guidance*\] when the primary processing
capabilities are unavailable;

CP-7a Additional FedRAMP Requirements and Guidance:

**Requirement:** The service provider defines a time period consistent
with the recovery time objectives and business impact analysis.

\(b) Ensures that equipment and supplies required to transfer and resume
operations are available at the alternate processing site or contracts
are in place to support delivery to the site within the
organization-defined time period for transfer/resumption; and

\(c) Ensures that the alternate processing site provides information
security safeguards equivalent to that of the primary site.

#### CP-7 (1) Control Enhancement (M) (H)

The organization identifies an alternate processing site that is
separated from the primary processing site to reduce susceptibility to
the same threats.

**CP-7(1) Additional FedRAMP Requirements and Guidance**

**Guidance:** The service provider may determine what is considered a
sufficient degree of separation between the primary and alternate
processing sites, based on the types of threats that are of concern. For
one particular type of threat (i.e., hostile cyber-attack), the degree
of separation between sites will be less relevant.

#### CP-7 (2) Control Enhancement (M) (H)

The organization identifies potential accessibility problems to the
alternate processing site in the event of an area-wide disruption or
disaster and outlines explicit mitigation actions.

#### CP-7 (3) Control Enhancement (M) (H)

The organization develops alternate processing site agreements that
contain priority-of-service provisions in accordance with organizational
availability requirements (including recovery time objectives).

### CP-8 Telecommunications Services (M) (H)

The organization establishes alternate telecommunications services
including necessary agreements to permit the resumption of
\[*Assignment: organization-defined information system operations*\] for
essential missions and business functions within \[*FedRAMP Assignment:
See CP-8 additional FedRAMP requirements and guidance*\] when the
primary telecommunications capabilities are unavailable at either the
primary or alternate processing or storage sites.

**CP-8 Additional FedRAMP Requirements and Guidance**:

**Requirement:** The service provider defines a time period consistent
with the recovery time objectives and business impact analysis.

#### CP-8 (1) Control Enhancement (M) (H)

The organization:

\(a) Develops primary and alternate telecommunications service agreements
that contain priority- of-service provisions in accordance with
organizational availability requirements (including recovery time
objectives); and

\(b) Requests Telecommunications Service Priority for all
telecommunications services used for national security emergency
preparedness in the event that the primary and/or alternate
telecommunications services are provided by a common carrier.

#### CP-8 (2) Control Enhancement (M) (H)

The organization obtains alternate telecommunications services to reduce
the likelihood of sharing a single point of failure with primary
telecommunications services.

### CP-9 Information System Backup (L) (M) (H)

The organization:

CP-9 Additional FedRAMP Requirements and Guidance:

**Requirement:** The service provider shall determine what elements of
the cloud environment require the Information System Backup control. The
service provider shall determine how Information System Backup is going
to be verified and appropriate periodicity of the check.

\(a) Conducts backups of user-level information contained in the
information system \[*FedRAMP Assignment: daily incremental; weekly
full*\]

CP-9 (a) Additional FedRAMP Requirements and Guidance:

**Requirement:** The service provider maintains at least three backup
copies of user-level information (at least one of which is available
online).

\(b) Conducts backups of system-level information contained in the
information system \[*FedRAMP Assignment: daily incremental; weekly
full*\];

CP-9 (b) Additional FedRAMP Requirements and Guidance:

**Requirement**: The service provider maintains at least three backup
copies of system-level information (at least one of which is available
online).

\(c) Conducts backups of information system documentation including
security-related documentation \[*FedRAMP Assignment: daily incremental;
weekly full* \]; and

CP-9 (c) Additional FedRAMP Requirements and Guidance:

**Requirement:** The service provider maintains at least three backup
copies of information system documentation including security
information (at least one of which is available online).

\(d) Protects the confidentiality, integrity, and availability of backup
information at storage locations.

#### CP-9 (1) Control Enhancement (M)

The organization tests backup information \[*FedRAMP Assignment: at
least annually*\] to verify media reliability and information integrity.

#### CP-9 (3) Control Enhancement (M) (H)

The organization stores backup copies of \[*Assignment:
organization-defined critical information system software and other
security-related information*\] in a separate facility or in a
fire-rated container that is not collocated with the operational system.

### CP-10 Information System Recovery and Reconstitution (L) (M) (H)

The organization provides for the recovery and reconstitution of the
information system to a known state after a disruption, compromise, or
failure.

#### CP-10 (2) Control Enhancement (M) (H)

The information system implements transaction recovery for systems that
are transaction-based.

13.7 Identification and Authentication (IA)
-------------------------------------------

### IA-1 Identification and Authentication Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) An identification and authentication policy that addresses purpose,
scope, roles, responsibilities, management commitment, coordination
among organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the identification
and authentication policy and associated identification and
authentication controls; and

\(b) Reviews and updates the current:

\(1) Identification and authentication policy \[*FedRAMP Assignment: at
least every three (3) years*\]; and

\(2) Identification and authentication procedures \[*FedRAMP Assignment:
at least annually*\].

### IA-2 User Identification and Authentication (L) (M) (H)

The information system uniquely identifies and authenticates
organizational users (or processes acting on behalf of organizational
users).

#### IA-2 (1) Control Enhancement (L) (M) (H)

The information system implements multifactor authentication for network
access to privileged accounts.

#### IA-2 (2) Control Enhancement (M) (H)

The information system implements multifactor authentication for network
access to non-privileged accounts.

#### IA-2 (3) Control Enhancement (M) (H)

The information system implements multifactor authentication for local
access to privileged accounts.

#### IA-2 (5) Control Enhancement (M) (H)

The organization requires individuals to be authenticated with an
individual authenticator when a group authenticator is employed.

#### IA-2 (8) Control Enhancement (M) (H)

The information system implements replay-resistant authentication
mechanisms for network access to privileged accounts.

#### IA-2 (11) Control Enhancement (M) (H)

The information system implements multifactor authentication for remote
access to privileged and non-privileged accounts such that one of the
factors is provided by a device separate from the system gaining access
and the device meets \[*FedRAMP* *Assignment: FIPS 140-2, NIAP\*
Certification, or NSA approval*\].

\*National Information Assurance Partnership (NIAP)

**Additional FedRAMP Requirements and Guidance:**

**Guidance:** PIV = separate device. Please refer to NIST SP 800-157
Guidelines for Derived Personal Identity Verification (PIV) Credentials.
FIPS 140-2 means validated by the Cryptographic Module Validation
Program (CMVP).

#### IA-2 (12) Control Enhancement (L) (M) (H)

The information system accepts and electronically verifies Personal
Identity Verification (PIV) credentials.

**IA-2 (12) Additional FedRAMP Requirements and Guidance**:

**Guidance**: Include Common Access Card (CAC), i.e., the DoD technical
implementation of PIV/FIPS 201/HSPD-12.

### IA-3 Device Identification and Authentication (M) (H)

The information system uniquely identifies and authenticates
\[*Assignment: organization-defined specific and/or types of devices*\]
before establishing a \[*Selection (one or more): local; remote;
network*\] connection.

### IA-4 Identifier Management (L) (M)

The organization manages information system identifiers for users and
devices by:

\(a) Receiving authorization from \[*Assignment: organization-defined
personnel or roles*\] to assign an individual, group, role, or device
identifier;

\(b) Selecting an identifier that identifies an individual, group, role,
or device;

\(c) Assigning the identifier to the intended individual, group, role, or
device;

\(d) Preventing reuse of identifiers for \[*FedRAMP Assignment: at least
two (2) years*\]; and

\(e) Disabling the identifier after \[*FedRAMP Assignment: ninety days
for user identifiers (see additional requirements and guidance)*\]

**IA-4e Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider defines the time period of
inactivity for device identifiers.

**Guidance:** For DoD clouds, see DoD cloud website for specific DoD
requirements that go above and beyond FedRAMP
http://iase.disa.mil/cloud\_security/Pages/index.aspx.

#### IA-4 (4) Control Enhancement (M) (H)

The organization manages individual identifiers by uniquely identifying
each individual as \[*FedRAMP* *Assignment: contractors; foreign
nationals*\].

### IA-5 Authenticator Management (L) (M)

The organization manages information system authenticators by:

\(a) Verifying, as part of the initial authenticator distribution, the
identity of the individual, group, role, or device receiving the
authenticator;

\(b) Establishing initial authenticator content for authenticators
defined by the organization;

\(c) Ensuring that authenticators have sufficient strength of mechanism
for their intended use;

\(d) Establishing and implementing administrative procedures for initial
authenticator distribution, for lost/compromised or damaged
authenticators, and for revoking authenticators;

\(e) Changing default content of authenticators prior to information
system installation;

\(f) Establishing minimum and maximum lifetime restrictions and reuse
conditions for authenticators;

\(g) Changing/refreshing authenticators \[*FedRAMP* *Assignment: to
include sixty (60) days for passwords*\].

\(h) Protecting authenticator content from unauthorized disclosure and
modification;

\(i) Requiring individuals to take, and having devices implement,
specific security safeguards to protect authenticators; and

\(j) Changing authenticators for group/role accounts when membership to
those accounts changes.

#### IA-5 (1) Control Enhancement (L) (M)

The information system, for password-based authentication:

\(a) Enforces minimum password complexity of \[*FedRAMP* *Assignment:*
*case sensitive, minimum of twelve (12) characters, and at least one (1)
each of upper-case letters, lower-case letters, numbers, and special
characters*\];

\(b) Enforces at least the following number of changed characters when
new passwords are created: \[*FedRAMP* *Assignment: at least one (1)*\];

\(c) Stores and transmits only cryptographically-protected passwords;

\(d) Enforces password minimum and maximum lifetime restrictions of
\[*FedRAMP* *Assignment: one (1) day minimum, sixty (60) day maximum*\];

\(e) Prohibits password reuse for \[*FedRAMP Assignment: twenty-four
(24)*\] generations; and

\(f) Allows the use of a temporary password for system logons with an
immediate change to a permanent password.

#### IA-5 (2) Control Enhancement (M) (H)

The information system, for PKI-based authentication:

\(a) Validates certifications by constructing and verifying a
certification path to an accepted trust anchor including checking
certificate status information;

\(b) Enforces authorized access to the corresponding private key;

\(c) Maps the authenticated identity to the account of the individual or
group; and

\(d) Implements a local cache of revocation data to support path
discovery and validation in case of inability to access revocation
information via the network.

#### IA-5 (3) Control Enhancement (M) (H)

The organization requires that the registration process to receive
\[*FedRAMP* *Assignment: All hardware/biometric (multifactor
authenticators*\] be conducted \[*FedRAMP* *Selection: in person*\]
before \[*Assignment: organization-defined registration authority*\]
with authorization by \[*Assignment: organization-defined personnel or
roles*\].

#### IA-5 (4) Control Enhancement (M)

The organization employs automated tools to determine if password
authenticators are sufficiently strong to satisfy \[*Assignment:
organization-defined requirements*\].

**IA-5(4) Additional FedRAMP Requirements and Guidance:**

**Guidance:** If automated mechanisms which enforce password
authenticator strength at creation are not used, automated mechanisms
must be used to audit strength of created password authenticators.

#### IA-5 (6) Control Enhancement (M) (H)

The organization protects authenticators commensurate with the security
category of the information to which use of the authenticator permits
access.

#### IA-5 (7) Control Enhancement (M) (H)

The organization ensures that unencrypted static authenticators are not
embedded in applications or access scripts or stored on function keys.

#### IA-5 (11) Control Enhancement (L) (M) (H)

The information system, for hardware token-based authentication, employs
mechanisms that satisfy \[*Assignment: organization-defined token
quality requirements*\].

### IA-6 Authenticator Feedback (L) (M) (H)

The information system obscures feedback of authentication information
during the authentication process to protect the information from
possible exploitation/use by unauthorized individuals.

### IA-7 Cryptographic Module Authentication (L) (M) (H)

The information system implements mechanisms for authentication to a
cryptographic module that meet the requirements of applicable federal
laws, Executive Orders, directives, policies, regulations, standards,
and guidance for such authentication.

### IA-8 Identification and Authentication (Non-Organizational Users) (L) (M) (H)

The information system uniquely identifies and authenticates
non-organizational users (or processes acting on behalf of
non-organizational users).

#### IA-8 (1) Control Enhancement (L) (M) (H)

The information system accepts and electronically verifies Personal
Identity Verification (PIV) credentials from other federal agencies.

#### IA-8 (2) Control Enhancement (L) (M) (H)

The information system accepts only FICAM-approved third-party
credentials.

#### IA-8 (3) Control Enhancement (L) (M) (H)

The organization employs only FICAM-approved information system
components in \[*Assignment: organization-defined information systems*\]
to accept third-party credentials.

#### IA-8 (4) Control Enhancement (L) (M) (H)

The information system conforms to FICAM-issued profiles.

13.8 Incident Response (IR)
---------------------------

### IR-1 Incident Response Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) An incident response policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the incident response
policy and associated incident response controls; and

\(b) Reviews and updates the current:

\(1) Incident response policy \[*FedRAMP Assignment: at least every three
(3) years*\]; and

\(2) Incident response procedures \[*FedRAMP Assignment: at least
annually*\].

### IR-2 Incident Response Training (L) (M)

The organization provides incident response training to information
system users consistent with assigned roles and responsibilities in
accordance with NIST SP 800-53 Rev 4:

\(a) Within \[*Assignment: organization-defined time period*\] of
assuming an incident response role or responsibility;

\(b) When required by information system changes; and

\(c) \[*FedRAMP Assignment: at least annually*\] thereafter.

### IR-3 Incident Response Testing (M)

The organization tests the incident response capability for the
information system \[*FedRAMP Assignment: at least annually*\] using
\[*FedRAMP Assignment: see additional FedRAMP Requirements and
Guidance*\] to determine the incident response effectiveness and
documents the results.

**IR-3 Additional FedRAMP Requirements and Guidance:**

**Requirements:** The service provider defines tests and/or exercises in
accordance with NIST Special Publication 800-61 (as amended). For JAB
authorization, the service provider provides test plans to the JAB/AO
annually. Test plans are approved and accepted by the JAB/AO prior to
the test commencing.

#### IR-3 (2) Control Enhancement (M) (H)

The organization coordinates incident response testing with
organizational elements responsible for related plans.

### IR-4 Incident Handling (L) (M) (H)

The organization:

\(a) Implements an incident handling capability for security incidents
that includes preparation, detection and analysis, containment,
eradication, and recovery;

\(b) Coordinates incident handling activities with contingency planning
activities; and

\(c) Incorporates lessons learned from ongoing incident handling
activities into incident response procedures, training, and
testing/exercises, and implements the resulting changes accordingly.

**IR-4 Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider ensures that individuals
conducting incident handling meet personnel security requirements
commensurate with the criticality/sensitivity of the information being
processed, stored, and transmitted by the information system.

#### IR-4 (1) Control Enhancement (M) (H)

The organization employs automated mechanisms to support the incident
handling process.

### IR-5 Incident Monitoring (L) (M) (H)

The organization tracks and documents information system security
incidents.

### IR-6 Incident Reporting (L) (M) (H)

The organization:

\(a) Requires personnel to report suspected security incidents to the
organizational incident response capability within \[*FedRAMP
Assignment: US-CERT incident reporting timelines as specified in NIST
SP800-61 (as amended)*\]; and

\(b) Reports security incident information to \[*Assignment:
organization-defined authorities*\].

**IR-6 Additional FedRAMP Requirements and Guidance**

**Requirement:** Report security incident information according to
FedRAMP Incident Communications Procedure.

#### IR-6 (1) Control Enhancement (M) (H)

The organization employs automated mechanisms to assist in the reporting
of security incidents.

### IR-7 Incident Response Assistance (L) (M) (H)

The organization provides an incident response support resource,
integral to the organizational incident response capability that offers
advice and assistance to users of the information system for the
handling and reporting of security incidents.

#### IR-7 (1) Control Enhancement (M) (H)

The organization employs automated mechanisms to increase the
availability of incident response related information and support.

#### IR-7 (2) Control Enhancement (M) (H)

The organization:

\(a) Establishes a direct, cooperative relationship between its incident
response capability and external providers of information system
protection capability; and

\(b) Identifies organizational incident response team members to the
external providers.

### IR-8 Incident Response Plan (L) (M) (H)

The organization:

\(a) Develops an incident response plan that:

\(1) Provides the organization with a roadmap for implementing its
incident response capability;

\(2) Describes the structure and organization of the incident response
capability;

\(3) Provides a high-level approach for how the incident response
capability fits into the overall organization;

\(4) Meets the unique requirements of the organization, which relate to
mission, size, structure, and functions;

\(5) Defines reportable incidents;

\(6) Provides metrics for measuring the incident response capability
within the organization;

\(7) Defines the resources and management support needed to effectively
maintain and mature an incident response capability; and

\(8) Is reviewed and approved by \[*Assignment: organization-defined
personnel or roles*\];

\(b) Distributes copies of the incident response plan to \[*FedRAMP
Assignment: see additional FedRAMP Requirements and Guidance*\].

**IR-8(b) Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider defines a list of incident
response personnel (identified by name and/or by role) and
organizational elements. The incident response list includes designated
FedRAMP personnel.

\(c) Reviews the incident response plan \[*FedRAMP Assignment: at least
annually*\];

\(d) Updates the incident response plan to address system/organizational
changes or problems encountered during plan implementation, execution,
or testing;

\(e) Communicates incident response plan changes to \[*FedRAMP
Assignment: see additional FedRAMP Requirements and Guidance*\].

**IR-8(e) Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider defines a list of incident
response personnel (identified by name and/or by role) and
organizational elements. The incident response list includes designated
FedRAMP personnel.

\(f) Protects the incident response plan from unauthorized disclosure and
modification.

### IR-9 Information Spillage Response (M) (H)

The organization responds to information spills by:

\(a) Identifying the specific information involved in the information
system contamination;

\(b) Alerting \[*Assignment: organization-defined personnel or roles*\]
of the information spill using a method of communication not associated
with the spill;

\(c) Isolating the contaminated information system or system component;

\(d) Eradicating the information from the contaminated information system
or component;

\(e) Identifying other information systems or system components that may
have been subsequently contaminated; and

\(f) Performing other \[*Assignment: organization-defined actions*\].

#### IR-9 (1) Control Enhancement (M) (H)

The organization assigns \[*Assignment: organization-defined personnel
or roles*\] with responsibility for responding to information spills.

#### IR-9 (2) Control Enhancement (M)

The organization provides information spillage response training
\[*Assignment: organization- defined frequency*\].

#### IR-9 (3) Control Enhancement (M) (H)

The organization implements \[*Assignment: organization-defined
procedures*\] to ensure that organizational personnel impacted by
information spills can continue to carry out assigned tasks while
contaminated systems are undergoing corrective actions.

#### IR-9 (4) Control Enhancement (M) (H)

The organization employs \[*Assignment: organization-defined security
safeguards*\] for personnel exposed to information not within assigned
access authorizations.

13.9 Maintenance (MA)
---------------------

### MA-1 System Maintenance Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A system maintenance policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the system
maintenance policy and associated system maintenance controls; and

\(b) Reviews and updates the current:

\(1) System maintenance policy \[*FedRAMP Assignment: at least every
three (3) years*\]; and

\(2) System maintenance procedures \[*FedRAMP Assignment: at least
annually*\].

### MA-2 Controlled Maintenance (L) (M) (H)

The organization:

\(a) Schedules, performs, documents, and reviews records of maintenance
and repairs on information system components in accordance with
manufacturer or vendor specifications and/or organizational
requirements;

\(b) Approves and monitors all maintenance activities, whether performed
on site or remotely and whether the equipment is serviced on site or
removed to another location;

\(c) Requires that \[*Assignment: organization-defined personnel or
roles*\] explicitly approve the removal of the information system or
system components from organizational facilities for off-site
maintenance or repairs;

\(d) Sanitizes equipment to remove all information from associated media
prior to removal from organizational facilities for off-site maintenance
or repairs;

\(e) Checks all potentially impacted security controls to verify that the
controls are still functioning properly following maintenance or repair
actions; and

\(f) Includes *\[Assignment: organization-defined maintenance-related
information*\] in organizational maintenance records.

### MA-3 Maintenance Tools (M) (H)

The organization approves, controls, and monitors information system
maintenance tools.

#### MA-3 (1) Control Enhancement (M) (H)

The organization inspects the maintenance tools carried into a facility
by maintenance personnel for improper or unauthorized modifications.

#### MA-3 (2) Control Enhancement (M) (H)

The organization checks media containing diagnostic and test programs
for malicious code before the media are used in the information system.

#### MA-3 (3) Control Enhancement (M) (H)

The organization prevents the unauthorized removal of maintenance
equipment containing organizational information by:

\(a) Verifying that there is no organizational information contained on
the equipment;

\(b) Sanitizing or destroying the equipment;

\(c) Retaining the equipment within the facility; or

\(d) Obtaining an exemption from \[*FedRAMP Assignment: the information
owner explicitly authorizes removal of the equipment from the
facility*\].

### MA-4 Remote Maintenance (L) (M) (H)

The organization:

\(a) Approves and monitors nonlocal maintenance and diagnostic
activities;

\(b) Allows the use of nonlocal maintenance and diagnostic tools only as
consistent with organizational policy and documented in the security
plan for the information system;

\(c) Employs strong authenticators in the establishment of nonlocal
maintenance and diagnostic sessions;

\(d) Maintains records for nonlocal maintenance and diagnostic
activities; and

\(e) Terminates session and network connections when nonlocal maintenance
is completed.

#### MA-4 (2) Control Enhancement (M) (H)

The organization documents in the security plan for the information
system, the policies and procedures for the establishment and use of
nonlocal maintenance and diagnostic connections.

### MA-5 Maintenance Personnel (L) (M) (H)

The organization:

\(a) Establishes a process for maintenance personnel authorization and
maintains a list of authorized maintenance organizations or personnel;

\(b) Ensures that non-escorted personnel performing maintenance on the
information system have required access authorizations; and

\(c) Designates organizational personnel with required access
authorizations and technical competence to supervise the maintenance
activities of personnel who do not possess the required access
authorizations.

#### MA-5 (1) Control Enhancement (L) (M)

The organization:

\(a) Implements procedures for the use of maintenance personnel that lack
appropriate security clearances or are not U.S. citizens, that include
the following requirements:

\(1) Maintenance personnel who do not have needed access authorizations,
clearances, or formal access approvals are escorted and supervised
during the performance of maintenance and diagnostic activities on the
information system by approved organizational personnel who are fully
cleared, have appropriate access authorizations, and are technically
qualified;

\(2) Prior to initiating maintenance or diagnostic activities by
personnel who do not have needed access authorizations, clearances or
formal access approvals, all volatile information storage components
within the information system are sanitized and all nonvolatile storage
media are removed or physically disconnected from the system and
secured; and

\(b) Develops and implements alternate security safeguards in the event
an information system component cannot be sanitized, removed, or
disconnected from the system.

**MA-5 (1) Additional FedRAMP Requirements and Guidance:**

**Requirement:** Only MA-5 (1) (a) (1) is required by FedRAMP

### MA-6 Timely Maintenance (M) (H)

The organization obtains maintenance support and/or spare parts for
\[*Assignment: organization-defined information system components*\]
within \[*Assignment: organization-defined time period*\] of failure.

13.10 Media Protection (MP)
---------------------------

### MP-1 Media Protection Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A media protection policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the media protection
policy and associated media protection controls; and

\(b) Reviews and updates the current:

\(1) Media protection policy \[*FedRAMP Assignment: at least every three
(3) years*\]; and

\(2) Media protection procedures \[*FedRAMP Assignment: at least
annually*\].

### MP-2 Media Access (L) (M)

The organization restricts access to \[*Assignment: organization-defined
types of digital and/or non-digital media*\] to \[*Assignment:
organization-defined personnel or roles*\].

### MP-3 Media Labeling (M) (H)

The organization:

\(a) Marks information system media indicating the distribution
limitations, handling caveats, and applicable security markings (if any)
of the information; and

\(b) Exempts \[*FedRAMP Assignment: no removable media types*\] from
marking as long as the media remain within \[*Assignment:
organization-defined controlled areas*\].

**MP-3(b) Additional FedRAMP Requirements and Guidance:**

**Guidance:** Second parameter in MP-3(b)-2 is not applicable.

### MP-4 Media Storage (M) (H)

The organization:

\(a) Physically controls and securely stores \[*FedRAMP Assignment: \[all
types of digital and non-digital media with sensitive information*\]\]
within \[*FedRAMP Assignment: see additional FedRAMP requirements and
guidance*\]; and

**MP-4a Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider defines controlled areas within
facilities where the information and information system reside.

\(b) Protects information system media until the media are destroyed or
sanitized using approved equipment, techniques, and procedures.

### MP-5 Media Transport (M) (H)

The organization:

\(a) Protects and controls \[*FedRAMP Assignment: all media with
sensitive information*\] during transport outside of controlled areas
using \[*FedRAMP Assignment:* *for digital media, encryption using a
FIPS 140-2 validated encryption module; for non-digital media, secured
in locked container*\];

**MP-5a Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider defines security measures to
protect digital and non-digital media in transport. The security
measures are approved and accepted by the JAB/AO.

\(b) Maintains accountability for information system media during
transport outside of controlled areas;

\(c) Documents activities associated with the transport of information
system media; and

\(d) Restricts the activities associated with transport of information
system media to authorized personnel.

#### MP-5 (4) Control Enhancement (M) (H)

The organization employs cryptographic mechanisms to protect the
confidentiality and integrity of information stored on digital media
during transport outside of controlled areas.

### MP-6 Media Sanitization and Disposal (L) (M)

The organization:

\(a) Sanitizes \[*Assignment: organization-defined information system
media*\] prior to disposal, release out of organizational control, or
release for reuse using \[*Assignment: organization-defined sanitization
techniques and procedures*\] in accordance with applicable federal and
organizational standards and policies; and

\(b) Employs sanitization mechanisms with strength and integrity
commensurate with the classification or classification of the
information.

#### MP-6 (2) Control Enhancement (M)

The organization tests sanitization equipment and procedures \[*FedRAMP
Assignment: at least annually*\] to verify that the intended
sanitization is being achieved.

**MP-6(2) Additional FedRAMP Requirements and Guidance:**

**Guidance:** Equipment and procedures may be tested or evaluated for
effectiveness.

### MP-7 Media Use (L) (M) (H)

The organization \[*Selection: restricts; prohibits*\] the use of
\[*Assignment: organization-defined types of information system media*\]
on \[*Assignment: organization-defined information systems or system
components*\] using \[*Assignment: organization-defined security
safeguards*\].

#### MP-7 (1) Control Enhancement (M) (H)

The organization prohibits the use of portable storage devices in
organizational information systems when such devices have no
identifiable owner.

13.11 Physical and Environmental Protection (PE)
------------------------------------------------

### PE-1 Physical and Environmental Protection Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A physical and environmental protection policy that addresses
purpose, scope, roles, responsibilities, management commitment,
coordination among organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the physical and
environmental protection policy and associated physical and
environmental protection controls; and

\(b) Reviews and updates the current:

\(1) Physical and environmental protection policy \[*FedRAMP Assignment:
at least every three (3) years*\]; and

\(2) Physical and environmental protection procedures \[*FedRAMP
Assignment: at least annually*\].

### PE-2 Physical Access Authorizations (L) (M)

The organization:

\(a) Develops, approves, and maintains a list of individuals with
authorized access to the facility where the information system resides;

\(b) Issues authorization credentials for facility access;

\(c) Reviews the access list detailing authorized facility access by
individuals \[*FedRAMP Assignment: at least annually*\]; and

\(d) Removes individuals from the facility access list when access is no
longer required.

### PE-3 Physical Access Control (L) (M) (H)

The organization:

\(a) Enforces physical access authorizations at \[*Assignment:
organization-defined entry/exit points to the facility where the
information system resides*\] by:

\(1) Verifying individual access authorizations before granting access to
the facility; and

\(2) Controlling ingress/egress to the facility using \[*FedRAMP
Assignment: CSP defined physical access control systems/devices AND
guards*\];

\(b) Maintains physical access audit logs for \[*Assignment:
organization-defined entry/exit points*\];

\(c) Provides \[*Assignment: organization-defined security safeguards*\]
to control access to areas within the facility officially designated as
publicly accessible;

\(d) Escorts visitors and monitors visitor activity \[*FedRAMP
Assignment: in all circumstances within restricted access area where the
information system resides*\];

\(e) Secures keys, combinations, and other physical access devices;

\(f) Inventories \[*Assignment: organization-defined physical access
devices*\] every \[*FedRAMP Assignment: at least annually*\]; and

\(g) Changes combinations and keys \[*FedRAMP Assignment: at least
annually*\] and/or when keys are lost, combinations are compromised, or
individuals are transferred or terminated.

### PE-4 Access Control for Transmission Medium (M) (H)

The organization controls physical access to \[*Assignment:
organization-defined information system distribution and transmission
lines*\] within organizational facilities using \[*Assignment:
organization-defined security safeguards*\].

### PE-5 Access Control for Output Devices (M) (H)

The organization controls physical access to information system output
devices to prevent unauthorized individuals from obtaining the output.

### PE-6 Monitoring Physical Access (L) (M) (H)

The organization:

\(a) Monitors physical access to the facility where the information
system resides to detect and respond to physical security incidents;

\(b) Reviews physical access logs \[*FedRAMP Assignment: at least
monthly*\] and upon occurrence of \[*Assignment: organization-defined
events or potential indications of events*\]; and

\(c) Coordinates results of reviews and investigations with the
organization’s incident response capability.

#### PE-6 (1) Control Enhancement (M) (H)

The organization monitors physical intrusion alarms and surveillance
equipment.

### PE-8 Visitor Access Records (L) (M) (H)

The organization:

\(a) Maintains visitor access records to the facility where the
information system resides for \[*FedRAMP Assignment: for a minimum of
one (1) year*\]; and

\(b) Reviews visitor access records \[*FedRAMP Assignment: at least
monthly*\]

### PE-9 Power Equipment and Cabling (M) (H)

The organization protects power equipment and power cabling for the
information system from damage and destruction.

### PE-10 Emergency Shutoff (M) (H)

The organization:

\(a) Provides the capability of shutting off power to the information
system or individual system components in emergency situations;

\(b) Places emergency shutoff switches or devices in \[*Assignment:
organization-defined location by information system or system
component*\] to facilitate safe and easy access for personnel; and

\(c) Protects emergency power shutoff capability from unauthorized
activation.

### PE-11 Emergency Power (M) (H)

The organization provides a short-term uninterruptible power supply to
facilitate \[*Selection (one or more): an orderly shutdown of the
information system; transition of the information system to long-term
alternate power*\] in the event of a primary power source loss.

### PE-12 Emergency Lighting (L) (M) (H)

The organization employs and maintains automatic emergency lighting for
the information system that activates in the event of a power outage or
disruption and that covers emergency exits and evacuation routes within
the facility.

### PE-13 Fire Protection (L) (M) (H)

The organization employs and maintains fire suppression and detection
devices/systems for the information system that are supported by an
independent energy source.

#### PE-13 (2) Control Enhancement (M) (H)

The organization employs fire suppression devices/systems for the
information system that provide automatic notification of any activation
\[*Assignment: organization-defined personnel or roles*\] and
\[*Assignment: organization-defined emergency responders*\].

#### PE-13 (3) Control Enhancement (M) (H)

The organization employs an automatic fire suppression capability for
the information system when the facility is not staffed on a continuous
basis.

### PE-14 Temperature and Humidity Controls (L) (M) (H)

The organization:

\(a) Maintains temperature and humidity levels within the facility where
the information system resides at \[*FedRAMP Assignment: consistent with
American Society of Heating, Refrigerating and Air-conditioning
Engineers (ASHRAE) document entitled "Thermal Guidelines for Data
Processing Environments*\]; and

**PE-14 (a) Additional FedRAMP Requirements and Guidance:\
Requirement:** *The service provider measures temperature at server
inlets and humidity levels by dew point*.

\(b) Monitors temperature and humidity levels \[*FedRAMP Assignment:
continuously*\].

#### PE-14 (2) Control Enhancement (M) (H)

The organization employs temperature and humidity monitoring that
provides an alarm or notification of changes potentially harmful to
personnel or equipment.

### PE-15 Water Damage Protection (L) (M) (H)

The organization protects the information system from damage resulting
from water leakage by providing master shutoff or isolation valves that
are accessible, working properly, and known to key personnel.

### PE-16 Delivery and Removal (L) (M) (H)

The organization authorizes, monitors, and controls \[*FedRAMP
Assignment: all information system components*\] entering and exiting
the facility and maintains records of those items.

### PE-17 Alternate Work Site (M) (H)

The organization:

\(a) Employs \[*Assignment: organization-defined security controls*\] at
alternate work sites*;*

\(b) Assesses as feasible, the effectiveness of security controls at
alternate work sites; and

\(c) Provides a means for employees to communicate with information
security personnel in case of security incidents or problems.

13.12 Planning (PL)
-------------------

### PL-1 Security Planning Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A security planning policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the security planning
policy and associated security planning controls; and

\(b) Reviews and updates the current:

\(1) Security planning policy \[*FedRAMP Assignment: at least every three
(3) years*\]; and

\(2) Security planning procedures \[*FedRAMP Assignment: at least
annually*\].

### PL-2 System Security Plan (L) (M) (H)

The organization:

\(a) Develops a security plan for the information system that:

\(1) Is consistent with the organization’s enterprise architecture;

\(2) Explicitly defines the authorization boundary for the system;

\(3) Describes the operational context of the information system in terms
of missions and business processes;

\(4) Provides the security categorization of the information system
including supporting rationale;

\(5) Describes the operational environment for the information system and
relationships with or connections to other information;

\(6) Provides an overview of the security requirements for the system;

\(7) Identifies any relevant overlays, if applicable;

\(8) Describes the security controls in place or planned for meeting
those requirements including a rationale for the tailoring decisions;
and

\(9) Is reviewed and approved by the authorizing official or designated
representative prior to plan implementation;

\(b) Distributes copies of the security plan and communicates subsequent
changes to the plan to \[*Assignment: organization-defined personnel or
roles*\];

\(c) Reviews the security plan for the information system \[*FedRAMP
Assignment: at least annually*\];

\(d) Updates the plan to address changes to the information
system/environment of operation or problems identified during plan
implementation or security control assessments; and

\(e) Protects the security plan from unauthorized disclosure and
modification.

#### PL-2 (3) Control Enhancement (M) (H)

The organization plans and coordinates security-related activities
affecting the information system with \[*Assignment:
organization-defined individuals or groups*\] before conducting such
activities in order to reduce the impact on other organizational
entities.

### PL-4 Rules of Behavior (L) (M)

The organization:

\(a) Establishes and makes readily available to individuals requiring
access to the information system, the rules that describe their
responsibilities and expected behavior with regard to information and
information system usage;

\(b) Receives a signed acknowledgment from such individuals, indicating
that they have read, understand, and agree to abide by the rules of
behavior, before authorizing access to information and the information
system;

\(c) Reviews and updates the rules of behavior \[*FedRAMP Assignment: at
least every three (3) years*\]; and

\(d) Requires individuals who have signed a previous version of the rules
of behavior to read and resign when the rules of behavior are
revised/updated.

#### PL-4 (1) Control Enhancement (M) (H)

The organization includes in the rules of behavior, explicit
restrictions on the use of social media/networking sites and posting
organizational information on public websites.

### PL-8 Information Security Architecture (M) (H)

The organization:

\(a) Develops an information security architecture for the information
system that:

\(1) Describes the overall philosophy, requirements, and approach to be
taken with regard to protecting the confidentiality, integrity, and
availability of organizational information;

\(2) Describes how the information security architecture is integrated
into and supports the enterprise architecture; and

\(3) Describes any information security assumptions about, and
dependencies on, external services;

\(b) Reviews and updates the information security architecture \[*FedRAMP
Assignment: at least annually or when a significant change occurs*\] to
reflect updates in the enterprise architecture; and

PL-8 (b) Additional FedRAMP Requirements and Guidance:

**Guidance:** Significant change is defined in NIST Special Publication
800-37 Revision 1, Appendix F, on Page F-7.

\(c) Ensures that planned information security architecture changes are
reflected in the security plan, the security Concept of Operations
(CONOPS), and organizational procurements/acquisitions.

13.13 Personnel Security (PS)
-----------------------------

### PS-1 Personnel Security Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A personnel security policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the personnel
security policy and associated personnel security controls; and

\(b) Reviews and updates the current:

\(1) Personnel security policy \[*FedRAMP Assignment: at least every
three (3) years*\]; and

\(2) Personnel security procedures \[*FedRAMP Assignment: at least
annually*\].

### PS-2 Position Categorization (L) (M)

The organization:

\(a) Assigns a risk designation to all positions;

\(b) Establishes screening criteria for individuals filling those
positions; and

\(c) Reviews and revises position risk designations \[*FedRAMP*
*Assignment: at least every three (3) years*\].

### PS-3 Personnel Screening (L) (M) (H)

The organization:

\(a) Screens individuals prior to authorizing access to the information
system; and

\(b) Rescreens individuals according to \[*FedRAMP* *Assignment: For
national security clearances; a reinvestigation is required during the
fifth (5th) year for top secret security clearance, the tenth (10th)
year for secret security clearance, and fifteenth (15th) year for
confidential security clearance. For moderate risk law enforcement and
high impact public trust level, a reinvestigation is required during the
fifth (5th) year. There is no reinvestigation for other moderate risk
positions or any low risk positions*\].

#### PS-3 (3) Control Enhancement (M) (H)

The organization ensures that individuals accessing an information
system processing, storing, or transmitting information requiring
special protection:

\(a) Have valid access authorizations that are demonstrated by assigned
official government duties; and

\(b) Satisfy \[*FedRAMP Assignment: personnel screening criteria – as
required by specific information*\].

### PS-4 Personnel Termination (L) (M)

The organization, upon termination of individual employment:

\(a) Disables information system access within \[*FedRAMP Assignment:
same day*\];

\(b) Terminates/revokes any authenticators/credentials associated with
the individual;

\(c) Conducts exit interviews that include a discussion of \[*Assignment:
organization-defined information security topics*\];

\(d) Retrieves all security-related organizational information
system-related property;

\(e) Retains access to organizational information and information systems
formerly controlled by terminated individual; and

\(f) Notifies \[*Assignment: organization-defined personnel or roles\]*
within \[*Assignment: organization-defined time period*\].

### PS-5 Personnel Transfer (L) (M)

The organization:

\(a) Reviews and confirms ongoing operational need for current logical
and physical access authorizations to information systems/facilities
when individuals are reassigned or transferred to other positions within
the organization;

\(b) Initiates \[*Assignment: organization-defined transfer or
reassignment actions*\] within \[*Assignment: organization-defined time
period following the formal transfer action*\];

\(c) Modifies access authorization as needed to correspond with any
changes in operational need due to reassignment or transfer; and

\(d) Notifies \[*Assignment: organization-defined personnel or roles*\]
within \[*FedRAMP Assignment: within five days of the formal transfer
action (DoD 24 hours)*\].

### PS-6 Access Agreements (L) (M)

The organization:

\(a) Develops and documents access agreements for organizational
information systems;

\(b) Reviews and updates the access agreements \[*FedRAMP Assignment: at
least annually*\]; and

\(c) Ensures that individuals requiring access to organizational
information and information systems:

\(1) Sign appropriate access agreements prior to being granted access;
and

\(2) Re-sign access agreements to maintain access to organizational
information systems when access agreements have been updated or
\[*FedRAMP Assignment: at least annually*\].

### PS-7 Third-Party Personnel Security (L) (M)

The organization:

\(a) Establishes personnel security requirements including security roles
and responsibilities for third-party providers;

\(b) Requires third-party providers to comply with personnel security
policies and procedures established by the organization;

\(c) Documents personnel security requirements;

\(d) Requires third-party providers to notify \[*Assignment:
organization-defined personnel or roles*\] of any personnel transfers or
terminations of third-party personnel who possess organizational
credentials and/or badges, or who have information system privileges
within \[*FedRAMP Assignment: same day*\]; and

\(e) Monitors provider compliance.

### PS-8 Personnel Sanctions (L) (M)

The organization:

\(a) Employs a formal sanctions process for personnel failing to comply
with established information security policies and procedures; and

\(b) Notifies \[A*ssignment: organization-defined personnel or roles*\]
within \[*Assignment: organization-defined time period*\] when a formal
employee sanctions process is initiated, identifying the individual
sanctioned and the reason for the sanction.

13.14 Risk Assessment (RA)
--------------------------

### RA-1 Risk Assessment Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A risk assessment policy that addresses purpose, scope, roles,
responsibilities, management commitment, coordination among
organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the risk assessment
policy and associated risk assessment controls; and

\(b) Reviews and updates the current:

\(1) Risk assessment policy \[*FedRAMP Assignment: at least every three
(3) years*\]; and

\(2) Risk assessment procedures \[*FedRAMP Assignment: at least
annually*\].

### RA-2 Security Categorization (L) (M) (H)

The organization:

\(a) Categorizes information and the information system in accordance
with applicable Federal Laws, Executive Orders, directives, policies,
regulations, standards, and guidance;

\(b) Documents the security categorization results (including supporting
rationale) in the security plan for the information system; and

\(c) Ensures the security categorization decision is reviewed and
approved by the AO or authorizing official designated representative.

### RA-3 Risk Assessment (L) (M)

The organization:

\(a) Conducts an assessment of risk, including the likelihood and
magnitude of harm, from the unauthorized access, use, disclosure,
disruption, modification, or destruction of the information system and
the information it processes, stores, or transmits;

\(b) Documents risk assessment results in \[*Selection: security plan;
risk assessment report;* \[*FedRAMP Assignment: security assessment
report*\]\];

\(c) Reviews risk assessment results \[*FedRAMP Assignment: in accordance
with OMB A-130 requirements or when a significant change occurs*\];

\(d) Disseminates risk assessment results to \[*Assignment:
organization-defined personnel or roles*\]; and

\(e) Updates the risk assessment \[*FedRAMP Assignment: in accordance
with OMB A-130 requirements or when a significant change occurs*\] or
whenever there are significant changes to the information system or
environment of operation (including the identification of new threats
and vulnerabilities), or other conditions that may impact the security
state of the system.

**RA-3 Additional FedRAMP Requirements and Guidance:**

**Guidance:** Significant change is defined in NIST Special Publication
800-37 Revision 1, Appendix F

**RA-3 (d) Requirement:** Include the Authorizing Official; for JAB
authorizations to include FedRAMP.

### RA-5 Vulnerability Scanning (L) (M) (H)

The organization:

\(a) Scans for vulnerabilities in the information system and hosted
applications \[*FedRAMP Assignment: monthly operating
system/infrastructure; monthly web applications and databases*\] and
when new vulnerabilities potentially affecting the system/applications
are identified and reported;

**RA-5 (a) Additional FedRAMP Requirements and Guidance:**

**Requirement:** An accredited independent assessor scans operating
systems/infrastructure, web applications, and databases once annually.

\(b) Employs vulnerability scanning tools and techniques that promote
interoperability among tools and automate parts of the vulnerability
management process by using standards for:

\(1) Enumerating platforms, software flaws, and improper configurations;

\(2) Formatting and making transparent, checklists and test procedures;
and

\(3) Measuring vulnerability impact;

\(c) Analyzes vulnerability scan reports and results from security
control assessments

\(d) Remediates legitimate vulnerabilities; \[*FedRAMP Assignment:
high-risk vulnerabilities mitigated within thirty (30) days from date of
discovery; moderate risk vulnerabilities mitigated within ninety (90)
days from date of discovery*\], in accordance with an organizational
assessment of risk; and

\(e) Shares information obtained from the vulnerability scanning process
and security control assessments with \[*Assignment:
organization-defined personnel or roles*\] to help eliminate similar
vulnerabilities in other information systems (i.e., systemic weaknesses
or deficiencies).

**RA-5 (e) Additional FedRAMP Requirements and Guidance:**

**Requirement:** To include the Risk Executive; for JAB authorizations
to include FedRAMP ISSOs.

#### RA-5 (1) Control Enhancement (M) (H)

The organization employs vulnerability scanning tools that include the
capability to readily update the list of information system
vulnerabilities to be scanned.

#### RA-5 (2) Control Enhancement (M) (H)

The organization updates the information system vulnerabilities scanned
\[*Selection (one or more):* \[*FedRAMP* *Assignment: prior to a new
scan*\]\].

#### RA-5 (3) Control Enhancement (M) (H)

The organization employs vulnerability scanning procedures that can
demonstrate the breadth and depth of coverage (i.e., information system
components scanned and vulnerabilities checked).

#### RA-5 (5) Control Enhancement (M) (H)

The organization includes privileged access authorization to \[*FedRAMP
Assignment: operating systems, databases, web applications*\] for
selected \[*FedRAMP Assignment: all scans*\].

#### RA-5 (6) Control Enhancement (M) (H)

The organization employs automated mechanisms to compare the results of
vulnerability scans over time to determine trends in information system
vulnerabilities.

**RA-5(6) Additional FedRAMP Requirements and Guidance:**

**Guidance:** Include in Continuous Monitoring ISSO digest/report to
JAB/AO.

#### RA-5 (8) Control Enhancement (L) (M) (H)

The organization reviews historic audit logs to determine if a
vulnerability identified in the information system has been previously
exploited.

**RA-5(8) Additional FedRAMP Requirements and Guidance:**

**Requirement:** This enhancement is required for all high vulnerability
scan findings.

**Guidance:** While scanning tools may label findings as high or
critical, the intent of the control is based around NIST's definition of
high vulnerability.

13.15 System and Services Acquisition (SA)
------------------------------------------

### SA-1 System and Services Acquisition Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A system and services acquisition policy that addresses purpose,
scope, roles, responsibilities, management commitment, coordination
among organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the system and
services acquisition policy and associated system and services
acquisition controls; and

\(b) Reviews and updates the current:

\(1) System and services acquisition policy \[*FedRAMP Assignment: at
least every three (3) years*\]; and

\(2) System and services acquisition procedures \[*FedRAMP Assignment: at
least annually*\].

### SA-2 Allocation of Resources (L) (M) (H)

The organization:

\(a) Determines information security requirements for the information
system or information system service in mission/business process
planning;

\(b) Determines, documents, and allocates the resources required to
protect the information system or information system service as part of
its capital planning and investment control process; and

\(c) Establishes a discrete line item for information security in
organizational programming and budgeting documentation.

### SA-3 System Development Life Cycle (L) (M) (H)

The organization:

\(a) Manages the information system using \[*Assignment:
organization-defined system development life cycle*\] that incorporates
information security considerations;

\(b) Defines and documents information security roles and
responsibilities throughout the system development life cycle;

\(c) Identifies individuals having information security roles and
responsibilities; and

\(d) Integrates the organizational information security risk management
process into system development life cycle activities.

### SA-4 Acquisitions Process (L) (M) (H)

The organization includes the following requirements, descriptions, and
criteria, explicitly or by reference, in the acquisition contract for
the information system, system component, or information system service
in accordance with applicable federal laws, Executive Orders,
directives, policies, regulations, standards, guidelines, and
organizational mission/business needs:

\(a) Security functional requirements;

\(b) Security strength requirements;

\(c) Security assurance requirements;

\(d) Security-related documentation requirements;

\(e) Requirements for protecting security-related documentation;

\(f) Description of the information system development environment and
environment in which the system is intended to operate; and

\(g) Acceptance criteria.

**Additional FedRAMP Requirements and Guidance:**

**Guidance**: The use of Common Criteria (ISO/IEC 15408) evaluated
products is strongly preferred.\
See <http://www.niap-ccevs.org/vpl> or
<http://www.commoncriteriaportal.org/products.html>.

#### SA-4 (1) Control Enhancement (M) (H)

The organization requires the developer of the information system,
system component, or information system service to provide a description
of the functional properties of the security controls to be employed.

#### SA-4 (2) Control Enhancement (L) (M)

The organization requires the developer of the information system,
system component, or information system service to provide design and
implementation information for the security controls to be employed that
includes: \[*FedRAMP Selection (one or more): to include
security-relevant external system interfaces, and high-level design*\];
\[*Assignment: organization-defined design/implementation information*\]
at \[*Assignment: organization-defined level of detail*\].

#### SA-4 (8) Control Enhancement (M) (H)

The organization requires the developer of the information system,
system component, or information system service to produce a plan for
the continuous monitoring of security control effectiveness that
contains \[*FedRAMP Assignment: at least the minimum requirement as
defined in control CA-7*\].

**SA-4 (8) Additional FedRAMP Requirements and Guidance:**

**Guidance:** CSP must use the same security standards regardless of
where the system component or information system service is acquired.

#### SA-4 (9) Control Enhancement (M) (H)

The organization requires the developer of the information system,
system component, or information system service to identify early in the
system development life cycle, the functions, ports, protocols, and
services intended for organizational use.

#### SA-4 (10) Control Enhancement (M) (H)

The organization employs only information technology products on the
FIPS 201-approved products list for Personal Identity Verification (PIV)
capability implemented within organizational information systems.

### SA-5 Information System Documentation (L) (M)

The organization:

\(a) Obtains administrator documentation for the information system,
system component, or information system service that describes:

\(1) Secure configuration, installation, and operation of the system,
component, or service;

\(2) Effective use and maintenance of security functions/mechanisms; and

\(3) Known vulnerabilities regarding configuration and use of
administrative (i.e., privileged) functions;

\(b) Obtains user documentation for the information system, system
component, or information system service that describes:

\(1) User-accessible security functions/mechanisms and how to effectively
use those security functions/mechanisms;

\(2) Methods for user interaction, which enables individuals to use the
system, component, or service in a more secure manner; and

\(3) User responsibilities in maintaining the security of the system,
component, or service;

\(c) Documents attempts to obtain information system, system component,
or information system service documentation when such documentation is
either unavailable or nonexistent and \[*Assignment:
organization-defined actions*\] in response;

\(d) Protects documentation as required, in accordance with the risk
management strategy; and

\(e) Distributes documentation to \[*Assignment: organization-defined
personnel or roles)*\].

### SA-8 Security Engineering Principles (M) (H)

The organization applies information system security engineering
principles in the specification, design, development, implementation,
and modification of the information system.

### SA-9 External Information System Services (L) (M) (H)

The organization:

\(a) Requires that providers of external information system services
comply with organizational information security requirements and employ
\[*FedRAMP Assignment: FedRAMP Security Controls Baseline(s) if Federal
information is processed or stored within the external system*\] in
accordance with applicable federal laws, Executive Orders, directives,
policies, regulations, standards, and guidance;

\(b) Defines and documents government oversight and user roles and
responsibilities with regard to external information system services;
and

\(c) Employs \[*FedRAMP Assignment: Federal/FedRAMP Continuous Monitoring
requirements must be met for external systems where Federal information
is processed or stored*\] to monitor security control compliance by
external service providers on an ongoing basis.

**Additional FedRAMP Requirements and Guidance**

**Guidance:** See the FedRAMP Documents page under Key Cloud Service
Provider (CSP) Documents&gt; Continuous Monitoring Strategy Guide\
[https://www.FedRAMP.gov/resources/documents](https://www.fedramp.gov/resources/documents)

#### SA-9 (1) Control Enhancement (M) (H)

The organization:

\(a) Conducts an organizational assessment of risk prior to the
acquisition or outsourcing of dedicated information security services;
and

\(b) Ensures that the acquisition or outsourcing of dedicated information
security services is approved by \[*Assignment: organization-defined
personnel or roles*\].

#### SA-9 (2) Control Enhancement (M) (H)

The organization requires providers of \[*FedRAMP Assignment: All
external systems where Federal information is processed or stored*\] to
identify the functions, ports, protocols, and other services required
for the use of such services.

#### SA-9 (4) Control Enhancement (M) (H)

The organization employs \[*Assignment: organization-defined security
safeguards*\] to ensure that the interests of \[*FedRAMP Assignment: All
external systems where Federal information is processed or stored*\] are
consistent with and reflect organizational interests.

#### SA-9 (5) Control Enhancement (M) (H)

The organization restricts the location of \[*FedRAMP Selection:
information processing, information data, AND information services*\] to
\[*Assignment: organization-defined locations*\] based on \[*Assignment:
organization-defined requirements or conditions*\].

**Additional FedRAMP Requirements and Guidance**

**Guidance**: System services refer to FTP, Telnet, and TFTP, etc.

### SA-10 Developer Configuration Management (M) (H)

The organization requires the developer of the information system,
system component, or information system service to:

\(a) Perform configuration management during system, component, or
service \[*FedRAMP Selection: development, implementation, AND
operation*\];

\(b) Document, manage, and control the integrity of changes to
\[*Assignment: organization-defined configuration items under
configuration management*\];

\(c) Implement only organization-approved changes to the system,
component, or service;

\(d) Document approved changes to the system, component, or service and
the potential security impacts of such changes; and

\(e) Track security flaws and flaw resolution within the system,
component, or service and report findings to \[*Assignment:
organization-defined personnel*\].

**SA-10 (e) Additional FedRAMP Requirements and Guidance:**

**Requirement:** For JAB authorizations, track security flaws and flaw
resolution within the system, component, or service and report findings
to organization-defined personnel, to include FedRAMP ISSOs.

#### SA-10 (1) Control Enhancement (M) (H)

The organization requires the developer of the information system,
system component, or information system service to enable integrity
verification of software and firmware components.

### SA-11 Developer Security Testing and Evaluation (M) (H)

The organization requires the developer of the information system,
system component, or information system service to:

\(a) Create and implement a security assessment plan;

\(b) Perform \[*Selection (one or more): unit; integration; system;
regression*\] testing/evaluation at \[*Assignment: organization-defined
depth and coverage*\];

\(c) Produce evidence of the execution of the security assessment plan
and the results of the security testing/evaluation;

\(d) Implement a verifiable flaw remediation process; and

\(e) Correct flaws identified during security testing/evaluation.

#### SA-11 (1) Control Enhancement (M) (H)

The organization requires the developer of the information system,
system component, or information system service to employ static code
analysis tools to identify common flaws and document the results of the
analysis.

**SA-11 (1) Additional FedRAMP Requirements and Guidance:**

**Requirement:** The service provider documents in the Continuous
Monitoring Plan, how newly developed code for the information system is
reviewed.

#### SA-11 (2) Control Enhancement (M) (H)

The organization requires the developer of the information system,
system component, or information system service to perform threat and
vulnerability analyses and subsequent testing/evaluation of the as-built
system, component, or service.

#### SA-11 (8) Control Enhancement (M) (H)

The organization requires the developer of the information system,
system component, or information system service to employ dynamic code
analysis tools to identify common flaws and document the results of the
analysis.

13.16 System and Communications Protection (SC)
------------------------------------------------

### SC-1 System and Communications Protection Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A system and communications protection policy that addresses
purpose, scope, roles, responsibilities, management commitment,
coordination among organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the system and
communications protection policy and associated system and
communications protection controls; and

\(b) Reviews and updates the current:

\(1) System and communications protection policy \[*FedRAMP* *Assignment:
at least every three (3) years*\]; and

\(2) System and communications protection procedures \[*FedRAMP
Assignment: at least annually*\].

### SC-2 Application Partitioning (M) (H)

The information system separates user functionality (including user
interface services) from information system management functionality.

### SC-4 Information in Shared Resources (M) (H)

The information system prevents unauthorized and unintended information
transfer via shared system resources.

### SC-5 Denial of Service Protection (L) (M) (H)

The information system protects against or limits the effects of the
following types of denial of service attacks: \[*Assignment:
organization-defined types of denial of service attacks or reference to
source for such information*\] by employing \[*Assignment:
organization-defined security safeguards*\].

### SC-6 Resource Availability (M) (H)

The information system protects the availability of resources by
allocating \[*Assignment: organization-defined resources*\] by
\[*Selection (one or more); priority; quota;* \[*Assignment:
organization-defined security safeguards*\]\].

### SC-7 Boundary Protection (L) (M) (H)

The information system:

\(a) Monitors and controls communications at the external boundary of the
system and at key internal boundaries within the system; and

\(b) Implements subnetworks for publicly accessible system components
that are \[*Selection: physically; logically*\] separated from internal
organizational networks; and

\(c) Connects to external networks or information systems only through
managed interfaces consisting of boundary protection devices arranged in
accordance with organizational security architecture.

#### SC-7 (3) Control Enhancement (M) (H)

The organization limits the number external network connections to the
information system.

#### SC-7 (4) Control Enhancement (M)

The organization:

\(a) Implements a managed interface for each external telecommunication
service;

\(b) Establishes a traffic flow policy for each managed interface;

\(c) Protects the confidentiality and integrity of the information being
transmitted across each interface;

\(d) Documents each exception to the traffic flow policy with a
supporting mission/business need and duration of that need; and

\(e) Reviews exceptions to the traffic flow policy \[*FedRAMP Assignment:
at least at least annually*\] and removes exceptions that are no longer
supported by an explicit mission/business need.

#### SC-7 (5) Control Enhancement (M) (H)

The information system at managed interfaces denies network traffic by
default and allows network communications traffic by exception (i.e.,
deny all, permit by exception).

#### SC-7 (7) Control Enhancement (M) (H)

The information system, in conjunction with a remote device, prevents
the device from simultaneously establishing non-remote connections with
the system and communicating via some other connection to resources in
external networks.

#### SC-7 (8) Control Enhancement (M) (H)

The information system routes \[*Assignment: organization-defined
internal communications traffic*\] to \[*Assignment:
organization-defined external networks*\] through authenticated proxy
servers at managed interfaces.

#### SC-7 (12) Control Enhancement (M)

The organization implements \[*Assignment: organization-defined
host-based boundary protection mechanisms*\] at \[*Assignment:
organization-defined information system components*\].

#### SC-7 (13) Control Enhancement (M)

The organization isolates \[*FedRAMP* *Assignment: See SC-7 (13)
additional FedRAMP Requirements and Guidance*\] from other internal
information system components by implementing physically separate
subnetworks with managed interfaces to other components of the system.

**SC-7 (13) Additional FedRAMP Requirements and Guidance:**

**Requirement**: The service provider defines key information security
tools, mechanisms, and support components associated with system and
security administration and isolates those tools, mechanisms, and
support components from other internal information system components via
physically or logically separate subnets.

#### SC-7 (18) Control Enhancement (M) (H)

The information system fails securely in the event of an operational
failure of a boundary protection device.

### SC-8 Transmission confidentiality and Integrity (M) (H)

The information system protects the \[*FedRAMP Assignment:
confidentiality AND integrity*\] of transmitted information.

#### SC-8 (1) Control Enhancement (M) (H)

The information system implements cryptographic mechanisms to \[*FedRAMP
Assignment: prevent unauthorized disclosure of information AND detect
changes to information*\] during transmission unless otherwise protected
by \[*FedRAMP Assignment: a hardened or alarmed carrier Protective
Distribution System (PDS)*\].

### SC-10 Network Disconnect (M)

The information system terminates the network connection associated with
a communications session at the end of the session or after \[*FedRAMP
Assignment: no longer than thirty (30) minutes for RAS-based sessions
and no longer than sixty (60) minutes for non-interactive user
sessions*\] of inactivity.

### SC-12 Cryptographic Key Establishment & Management (L) (M) (H)

The organization establishes and manages cryptographic keys for required
cryptography employed within the information system in accordance with
\[*Assignment: organization-defined requirements for key generation,
distribution, storage, access, and destruction*\].

**SC-12 Additional FedRAMP Requirements and Guidance:**

**Guidance:** Federally approved and validated cryptography.

#### SC-12 (2) Control Enhancement (M) (H)

The organization produces, controls, and distributes symmetric
cryptographic keys using \[*FedRAMP* *Selection: NIST FIPS-compliant*\]
key management technology and processes.

#### SC-12 (3) Control Enhancement (M) (H)

The organization produces, controls, and distributes asymmetric
cryptographic keys using \[*Selection: NSA-approved key management
technology and processes; approved PKI Class 3 certificates or
prepositioned keying material; approved PKI Class 3 or Class 4
certificates and hardware security tokens that protect the user’s
private key*\].

### SC-13 Use of Cryptography (L) (M) (H)

The information system implements \[*FedRAMP Assignment:*
*FIPS-validated or NSA-approved cryptography\]* in accordance with
applicable federal laws, Executive Orders, directives, policies,
regulations, and standards.

### SC-15 Collaborative Computing Devices (M) (H)

The information system:

\(a) Prohibits remote activation of collaborative computing devices with
the following exceptions:\[*FedRAMP Assignment: no exceptions*\] and

\(b) Provides an explicit indication of use to users physically present
at the devices.

**SC-15 Additional FedRAMP Requirements and Guidance:**

**Requirement:** The information system provides disablement (instead of
physical disconnect) of collaborative computing devices in a manner that
supports ease of use.

**SC-15 Additional FedRAMP Requirements and Guidance:**

**Requirement**: The information system provides disablement (instead of
physical disconnect) of collaborative computing devices in a manner that
supports ease of use.

### SC-17 Public Key Infrastructure Certificates (M) (H)

The organization issues public key certificates under an \[*Assignment:
organization-defined certificate policy*\] or obtains public key
certificates from an approved service provider.

### SC-18 Mobile Code (M) (H)

The organization:

\(a) Defines acceptable and unacceptable mobile code and mobile code
technologies;

\(b) Establishes usage restrictions and implementation guidance for
acceptable mobile code and mobile code technologies; and

\(c) Authorizes, monitors, and controls the use of mobile code within the
information system.

### SC-19 Voice Over Internet Protocol (M) (H)

The organization:

\(a) Establishes usage restrictions and implementation guidance for Voice
over Internet Protocol (VoIP) technologies based on the potential to
cause damage to the information system if used maliciously; and

\(b) Authorizes, monitors, and controls the use of VoIP within the
information system.

### SC-20 Secure Name / Address Resolution Service (Authoritative Source) (L) (M) (H)

The information system:

\(a) Provides additional data origin authentication and integrity
verification artifacts along with the authoritative name resolution data
the system returns in response to external name/address resolution
queries; and

\(b) Provides the means to indicate the security status of child zones
and (if the child supports secure resolution services) to enable
verification of a chain of trust among parent and child domains, when
operating as part of a distributed, hierarchical namespace.

### SC-21 Secure Name / Address Resolution Service (Recursive or Caching Resolver) (L) (M) (H)

The information system requests and performs data origin authentication
and data integrity verification on the name/address resolution responses
the system receives from authoritative sources.

### SC-22 Architecture and Provisioning for Name / Address Resolution Service (L) (M) (H)

The information systems that collectively provide name/address
resolution service for an organization are fault-tolerant and implement
internal/external role separation.

### SC-23 Session Authenticity (M) (H)

The information system protects the authenticity of communications
sessions.

### SC-28 Protection of Information at Rest (M) (H)

The information system protects the \[*FedRAMP* *Selection:
confidentiality AND integrity\]*\] of \[*Assignment:
organization-defined information at rest*\].

**SC-28 Additional FedRAMP Requirements and Guidance:**

**Guidance:** The organization supports the capability to use
cryptographic mechanisms to protect information at rest.

#### SC-28 (1) Control Enhancement (M)

The information system implements cryptographic mechanisms to prevent
unauthorized disclosure and modification of \[*Assignment:
organization-defined information*\] on \[*Assignment:
organization-defined information system components*\]

### SC-39 Process Isolation (L) (M) (H)

The information system maintains a separate execution domain for each
executing process.

13.17 System and Information Integrity (SI)
-------------------------------------------

### SI-1 System and Information Integrity Policy and Procedures (L) (M)

The organization:

\(a) Develops, documents, and disseminates to \[*Assignment:
organization-defined personnel or roles*\]:

\(1) A system and information integrity policy that addresses purpose,
scope, roles, responsibilities, management commitment, coordination
among organizational entities, and compliance; and

\(2) Procedures to facilitate the implementation of the system and
information integrity policy and associated system and information
integrity controls; and

\(b) Reviews and updates the current:

\(1) System and information integrity policy \[*FedRAMP Assignment: at
least every three (3) years*\]; and

\(2) System and information integrity procedures \[*FedRAMP Assignment:
at least at least annually*\].

### SI-2 Flaw Remediation (L) (M) (H)

The organization:

\(a) Identifies, reports, and corrects information system flaws;

\(b) Tests software and firmware updates related to flaw remediation for
effectiveness and potential side effects before installation;

\(c) Installs security-relevant software and firmware updates within
\[*FedRAMP Assignment: thirty 30 days of release of updates*\] of the
release of the updates; and

\(d) Incorporates flaw remediation into the organizational configuration
management process.

#### SI-2 (2) Control Enhancement (M) (H)

The organization employs automated mechanisms \[*FedRAMP Assignment: at
least monthly*\] to determine the state of information system components
with regard to flaw remediation.

#### SI-2 (3) Control Enhancement (M) (H)

The organization:

\(a) Measures the time between flaw identification and flaw remediation;
and

\(b) Establishes \[*Assignment: organization-defined benchmarks*\] for
taking corrective actions.

### SI-3 Malicious Code Protection (L) (M)

The organization:

\(a) Employs malicious code protection mechanisms at information system
entry and exit points to detect and eradicate malicious code;

\(b) Updates malicious code protection mechanisms whenever new releases
are available in accordance with organizational configuration management
policy and procedures;

\(c) Configures malicious code protection mechanisms to:

\(1) Perform periodic scans of the information system \[*FedRAMP
Assignment: at least weekly*\] and real-time scans of files from
external sources at \[*FedRAMP Assignment: to include endpoints*\] as
the files are downloaded, opened, or executed in accordance with
organizational security policy; and

\(2) \[*FedRAMP Assignment: to include alerting administrator or defined
security personnel*\] in response to malicious code detection; and

\(d) Addresses the receipt of false positives during malicious code
detection and eradication and the resulting potential impact on the
availability of the information system.

#### SI-3 (1) Control Enhancement (M) (H)

The organization centrally manages malicious code protection mechanisms.

#### SI-3 (2) Control Enhancement (M) (H)

The information system automatically updates malicious code protection
mechanisms.

#### SI-3 (7) Control Enhancement (M) (H)

The information system implements nonsignature-based malicious code
detection mechanisms.

### SI-4 Information System Monitoring (L) (M) (H)

The organization:

\(a) Monitors the information system to detect:

\(1) Attacks and indicators of potential attacks in accordance with
\[*Assignment: organization-defined monitoring objectives*\]; and

\(2) Unauthorized local, network, and remote connections;

\(b) Identifies unauthorized use of the information system through
\[*Assignment: organization-defined techniques and methods*\];

\(c) Deploys monitoring devices (i) strategically within the information
system to collect organization-determined essential information; and
(ii) at ad hoc locations within the system to track specific types of
transactions of interest to the organization;

\(d) Protects information obtained from intrusion-monitoring tools from
unauthorized access, modification, and deletion;

\(e) Heightens the level of information system monitoring activity
whenever there is an indication of increased risk to organizational
operations and assets, individuals, other organizations, or the Nation
based on law enforcement information, intelligence information, or other
credible sources of information;

\(f) Obtains legal opinion with regard to information system monitoring
activities in accordance with applicable federal laws, Executive Orders,
directives, policies, or regulations; and

\(g) Provides \[*Assignment: organization-defined information system
monitoring information*\] to \[*Assignment: organization-defined
personnel or roles*\] \[*Selection (one or more): as needed;*
\[*Assignment: organization-defined frequency*\]\].

**SI-4 Additional FedRAMP Requirements and Guidance:**

**Guidance**: See US-CERT Incident Response Reporting Guidelines.

#### SI-4 (1) Control Enhancement (M) (H)

The organization connects and configures individual intrusion detection
tools into an information system-wide intrusion detection system.

#### SI-4 (2) Control Enhancement (M) (H)

The organization employs automated tools to support near real-time
analysis of events.

#### SI-4 (4) Control Enhancement (M) (H)

The information system monitors inbound and outbound communications
traffic \[*FedRAMP Assignment:* *continuously\]* for unusual or
unauthorized activities or conditions.

#### SI-4 (5) Control Enhancement (M) (H)

The information system alerts \[*Assignment: organization-defined
personnel or roles*\] when the following indications of compromise or
potential compromise occur: \[*Assignment: organization-defined
compromise indicators*\].

SI-4(5) Additional FedRAMP Requirements and Guidance:

**Guidance**: In accordance with the incident response plan.

#### SI-4 (14) Control Enhancement (M) (H)

The organization employs a wireless intrusion detection system to
identify rogue wireless devices and to detect attack attempts and
potential compromises/breaches to the information system.

#### SI-4 (16) Control Enhancement (M) (H)

The organization correlates information from monitoring tools employed
throughout the information system.

#### SI-4 (23) Control Enhancement (M) (H)

The organization implements \[*Assignment: organization-defined
host-based monitoring mechanisms*\] at \[*Assignment:
organization-defined information system components*\].

### SI-5 Security Alerts & Advisories (L) (M) (H)

The organization:

\(a) Receives information system security alerts, advisories, and
directives from \[*FedRAMP Assignment: to include US-CERT*\] on an
ongoing basis;

\(b) Generates internal security alerts, advisories, and directives as
deemed necessary;

\(c) Disseminates security alerts, advisories, and directives to
\[*FedRAMP Assignment: to include system security personnel and
administrators with configuration/patch-management responsibilities*\];
and

\(d) Implements security directives in accordance with established time
frames, or notifies the issuing organization of the degree of
noncompliance.

### SI-6 Security Functionality Verification (M) (H)

The information system:

\(a) Verifies the correct operation of \[*Assignment:
organization-defined security functions*\];

\(b) Performs this verification \[*FedRAMP Assignment: to include upon
system startup and/or restart at least monthly*\];

\(c) Notifies \[*FedRAMP Assignment: to include system administrators and
security personnel*\] of failed security verification tests; and

\(d) \[*Selection (one or more): shuts the information system down;
restarts the information system;* \[*FedRAMP Assignment: to include
notification of system administrators and security personnel*\] when
anomalies are discovered.

### SI-7 Software & Information Integrity (M) (H)

The organization employs integrity verification tools to detect
unauthorized changes to \[*Assignment: organization-defined software,
firmware, and information*\].

#### SI-7 (1) Control Enhancement (M) (H)

The information system performs an integrity check of \[*Assignment:
organization-defined software, firmware, and information*\] \[*FedRAMP
Selection (one or more): at startup; at \[FedRAMP Assignment: to include
security-relevant events*\]; \[*FedRAMP Assignment: at least
monthly*\]\].

#### SI-7 (7) Control Enhancement (M) (H)

The organization incorporates the detection of unauthorized
\[*Assignment: organization-defined security-relevant changes to the
information system*\] into the organizational incident response
capability.

### SI-8 Spam Protection (M) (H)

The organization:

\(a) Employs spam protection mechanisms at information system entry and
exit points to detect and take action on unsolicited messages; and

\(b) Updates spam protection mechanisms when new releases are available
in accordance with organizational configuration management policies and
procedures.

#### SI-8 (1) Control Enhancement (M) (H)

The organization centrally manages spam protection mechanisms.

#### SI-8 (2) Control Enhancement (M) (H)

The organization automatically updates spam protection mechanisms.

### SI-10 Information Input Validation (M) (H)

The information system checks the validity of \[*Assignment:
organization-defined information inputs*\].

### SI-11 Error Handling (M) (H)

The information system:

\(a) Generates error messages that provide information necessary for
corrective actions without revealing information that could be exploited
by adversaries; and

\(b) Reveals error messages only to \[*Assignment: organization-defined
personnel or roles*\].

### SI-12 Information Output Handling and Retention (L) (M) (H)

The organization handles and retains information within the information
system and information output from the system in accordance with
applicable federal laws, Executive Orders, directives, policies,
regulations, standards, and operational requirements.

### SI-16 Memory Protection (M) (H)

The information system implements \[*Assignment: organization-defined
fail-safe procedures*\] to protect its memory from unauthorized code
execution.
