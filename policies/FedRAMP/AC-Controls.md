# 13.1	Access Control (AC)
## AC-1 Access Control Policy and Procedures Requirements (L) (M)
The organization:
(a)	Develops, documents and disseminates to [*Assignment: organization-defined personnel or roles]:
    (1)	An access control policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the access control policy and associated access controls; and
(b)	Reviews and updates the current:
    (1)	Access control policy [*FedRAMP Assignment: at least every 3 years*]; and
    (2)	Access control procedures [*FedRAMP Assignment: at least annually*].
## AC-2 Account Management (L) (M)
The organization:
(a)	Identifies and selects the following types of information system accounts to support organizational missions/business functions: [*Assignment: organization-defined information system account types*];
(b)	Assigns account managers for information system accounts;
(c)	Establishes conditions for group and role membership;
(d)	Specifies authorized users of the information system, group and role membership, and access authorizations (i.e., privileges) and other attributes (as required) for each account;
(e)	Requires approvals by [*Assignment: organization-defined personnel or roles*] for requests to create information system accounts;
(f)	Creates, enables, modifies, disables, and removes information system accounts in accordance with [*Assignment: organization-defined procedures or conditions*];
(g)	Monitors the use of information system accounts;
(h)	Notifies account managers:
    (1)	When accounts are no longer required;
    (2)	When users are terminated or transferred; and
    (3)	When individual information system usage or need-to-know changes;
(i)	Authorizes access to the information system based on:
    (1)	A valid access authorization;
    (2)	Intended system usage; and
    (3)	Other attributes as required by the organization or associated missions/business functions;
(j)	Reviews accounts for compliance with account management requirements [*FedRAMP Assignment: at least annually*]; and
(k)	Establishes a process for reissuing shared/group account credentials (if deployed) when individuals are removed from the group.
### AC-2 (1) Control Enhancement (M) (H)
The organization employs automated mechanisms to support the management of information system accounts.
### AC-2 (2) Control Enhancement (M)
The information system automatically [*Selection: removes; disables*] temporary and emergency accounts after [*FedRAMP Assignment: no more than 30 days for temporary and emergency account types*].
### AC-2 (3) Control Enhancement (M)
The information system automatically disables inactive accounts after [*FedRAMP Assignment: ninety (90) days for user accounts*].
### AC-2 (3) Additional FedRAMP Requirements and Guidance:
Requirement: The service provider defines the time period for non-user accounts (e.g., accounts associated with devices).  The time periods are approved and accepted by the Joint Authorization Board (JAB)/AO. Where user management is a function of the service, reports of activity of consumer users shall be made available.
### AC-2 (4) Control Enhancement (M)
The information system automatically audits account creation, modification, enabling, disabling, and removal actions, and notifies [*Assignment: organization-defined personnel or roles*].
### AC-2 (5) Control Enhancement (M)
The organization requires that users log out when [*Assignment: organization-defined time-period of expected inactivity or description of when to log out*].
## AC-2 (5) Additional FedRAMP Requirements and Guidance:
Guidance: Should use a shorter timeframe than ## AC-12
### AC-2 (7) Control Enhancement (M)
The organization:
(a)	Establishes and administers privileged user accounts in accordance with a role-based access scheme that organizes allowed information system access and privileges into roles;
(b)	Monitors privileged role assignments; and
(c)	Takes [*Assignment: organization-defined actions*] when privileged role assignments are no longer appropriate.
### AC-2 (9) Control Enhancement (M)
The organization only permits the use of shared/group accounts that meet [*Assignment: organization-defined conditions for establishing shared/group accounts*].
### AC-2 (9) Additional FedRAMP Requirements and Guidance:
Required if shared/group accounts are deployed.
### AC-2 (10) Control Enhancement (M) (H)
The information system terminates shared/group account credentials when members leave the group.
### AC-2 (10) Additional FedRAMP Requirements and Guidance:
Required if shared/group accounts are deployed.
### AC-2 (12) Control Enhancement (M)
The organization:
(a)	Monitors information system accounts for [*Assignment: organization-defined atypical use*]; and
(b)	Reports atypical usage of information system accounts to [*Assignment: organization-defined personnel or roles*].
### AC-2 (12) (a) and ## AC-2 (12) (b) Additional FedRAMP Requirements and Guidance:
Required for privileged accounts.
## AC-3 Access Enforcement (L) (M) (H)
The information system enforces approved authorizations for logical access to information and system resources in accordance with applicable access control policies.
## AC-4 Information Flow Enforcement (M) (H)
The information system enforces approved authorizations for controlling the flow of information within the system and between interconnected systems based on [*Assignment: organization-defined information flow control policies*].
### AC-4 (21) Control Enhancement (M) (H)
The information system separates information flows logically or physically using [*Assignment: organization-defined mechanisms and/or techniques*] to accomplish [*Assignment: organization-defined required separations by types of information*].
## AC-5 Separation of Duties (M) (H)
The organization:
(a)	Separates [*Assignment: organization-defined duties of individuals*];
(b)	Documents separation of duties of individuals; and
(c)	Defines information system access authorizations to support separation of duties.
## AC-5 Additional FedRAMP Requirements and Guidance:
Guidance: CSPs have the option to provide a separation of duties matrix as an attachment to the SSP.  Directions for attaching the Separation of Duties Matrix document may be found in Section 15.11 ATTACHMENT 11 - Separation of Duties Matrix.
## AC-6 Least Privilege (M) (H)
The organization employs the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) which are necessary to accomplish assigned tasks in accordance with organizational missions and business functions.
### AC-6 (1) Control Enhancement (M)
The organization explicitly authorizes access to [*Assignment: organization-defined security functions (deployed in hardware, software, and firmware) and security-relevant information*].
### AC-6 (2) Control Enhancement (M) (H)
The organization requires that users of information system accounts, or roles, with access to [*FedRAMP Assignment: all security functions*], use non-privileged accounts or roles, when accessing non-security functions.
## AC-6 (2) Additional FedRAMP Requirements and Guidance:
Examples of security functions include but are not limited to: establishing system accounts, configuring access authorizations (i.e., permissions, privileges), setting events to be audited, and setting intrusion detection parameters, system programming, system and security administration, other privileged functions.
### AC-6 (5) Control Enhancement (M) (H)
The organization restricts privileged accounts on the information system to [*Assignment: organization-defined personnel or roles*].
### AC-6 (9) Control Enhancement (M) (H)
The information system audits the execution of privileged functions.
### AC-6 (10) Control Enhancement (M) (H)
The information system prevents non-privileged users from executing privileged functions to include disabling, circumventing, or altering implemented security safeguards/countermeasures.
## AC-7 Unsuccessful Login Attempts (L) (M)
The organization:
(a)	Enforces a limit of [*FedRAMP Assignment: not more than three (3)] consecutive invalid logon attempts by a user during a [*FedRAMP Assignment: fifteen (15) minutes*]; and
(b)	Automatically [*Selection: locks the account/node for a* [*FedRAMP Assignment: thirty (30) minutes*]*; delays next logon prompt according to* [*Assignment: organization-defined delay algorithm*]] when the maximum number of unsuccessful attempts is exceeded.
## AC-8 System Use Notification (L) (M) (H)
The information system:
(a)	Displays to users [*Assignment: organization-defined system use notification message or banner (FedRAMP Assignment: see additional Requirements and Guidance)*] before granting access to the system that provides privacy and security notices consistent with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance and states that:
(1)	Users are accessing a U.S. Government information system;
(2)	Information system usage may be monitored, recorded, and subject to audit;
(3)	Unauthorized use of the information system is prohibited and subject to criminal and civil penalties; and
(4)	Use of the information system indicates consent to monitoring and recording;
(b)	Retains the notification message or banner on the screen until users acknowledge the usage conditions and take explicit actions to log on to or further access the information system; and
(c)	For publicly accessible systems:
(1)	Displays system use information [*Assignment: organization-defined conditions (FedRAMP Assignment: see additional Requirements and Guidance)*], before granting further access;
(2)	Displays references, if any, to monitoring, recording, or auditing that are consistent with privacy accommodations for such systems that generally prohibit those activities; and
(3)	Includes a description of the authorized uses of the system.
## AC-8 Additional FedRAMP Requirements and Guidance:
Requirement:  The service provider shall determine elements of the cloud environment that require the System Use Notification control.  The elements of the cloud environment that require System Use Notification are approved and accepted by the JAB/AO.
Requirement: The service provider shall determine how System Use Notification is going to be verified and provide appropriate periodicity of the check.  The System Use Notification verification and periodicity are approved and accepted by the JAB/AO.
Guidance: If performed as part of a Configuration Baseline check, then the % of items requiring setting that are checked and that pass (or fail) check can be provided.
Requirement: If not performed as part of a Configuration Baseline check, then there must be documented agreement on how to provide results of verification and the necessary periodicity of the verification by the service provider.  The documented agreement on how to provide verification of the results are approved and accepted by the JAB/AO.
Additional FedRAMP Requirements and Guidance
Requirement 1: The service provider shall determine elements of the cloud environment that require the System Use Notification control.  The elements of the cloud environment that require System Use Notification are approved and accepted by the JAB/AO.
Requirement 2: The service provider shall determine how System Use Notification is going to be verified and provide appropriate periodicity of the check.  The System Use Notification verification and periodicity are approved and accepted by the JAB/AO.  If performed as part of a Configuration Baseline check, then the % of items requiring setting that are checked and that pass (or fail) check can be provided.
Requirement 3: If not performed as part of a Configuration Baseline check, then there must be documented agreement on how to provide results of verification and the necessary periodicity of the verification by the service provider.  The documented agreement on how to provide verification of the results are approved and accepted by the JAB/AO.
## AC-10 Concurrent Session Control (M) (H)
The information system limits the number of concurrent sessions for each [*Assignment: organization-defined account and/or account type*] to [*FedRAMP Assignment: three (3) sessions for privileged access and two (2) sessions for non-privileged access*].
## AC-11 Session Lock (M) (H)
The information system:
(a)	Prevents further access to the system by initiating a session lock after [*FedRAMP Assignment: fifteen (15) minutes*] of inactivity or upon receiving a request from a user; and
(b)	Retains the session lock until the user reestablishes access using established identification and authentication procedures.
### AC-11 (1) Control Enhancement (M) (H)
The information system conceals, via the session lock, information previously visible on the display with a publicly viewable image.
### AC-12 Session Termination (M) (H)
The information system automatically terminates a user session after [*Assignment: organization-defined conditions or trigger events requiring session disconnect*].
## AC-14 Permitted Actions without Identification or Authentication (L) (M) (H)
The organization:
(a)	Identifies [*Assignment: organization-defined user actions*] that can be performed on the information system without identification or authentication consistent with organizational missions/business functions; and
(b)	Documents and provides supporting rationale in the security plan for the information system, user actions not requiring identification or authentication.
## AC-17 Remote Access (L) (M) (H)
The organization:
(a)	Establishes and documents usage restrictions, configuration/connection requirements, and implementation guidance for each type of remote access allowed; and
(b)	Authorizes remote access to the information system prior to allowing such connections.
### AC-17 (1) Control Enhancement (M) (H)
The information system monitors and controls remote access methods.
### AC-17 (2) Control Enhancement (M) (H)
The information system implements cryptographic mechanisms to protect the confidentiality and integrity of remote access sessions.
### AC-17 (3) Control Enhancement (M) (H)
The information system routes all remote accesses through [*Assignment: organization-defined number*] managed network access control points.
### AC-17 (4) Control Enhancement (M) (H)
The organization:
(a)	Authorizes the execution of privileged commands and access to security-relevant information via remote access only for [*Assignment: organization-defined needs*]; and
(b)	Documents the rationale for such access in the security plan for the information system.
### AC-17 (9) Control Enhancement (M) (H)
The organization provides the capability to expeditiously disconnect or disable remote access to the information system within [*FedRAMP Assignment: fifteen (15) minutes*].
## AC-18 Wireless Access Restrictions (L) (M) (H)
The organization:
(a)	Establishes usage restrictions, configuration/connection requirements, and implementation guidance for wireless access; and
(b)	Authorizes wireless access to the information system prior to allowing such connections.
### AC-18 (1) Control Enhancement (M) (H)
The information system protects wireless access to the system using authentication of [*Selection (one or more): users; devices*] and encryption.
## AC-19 Access Control for Portable and Mobile Systems (L) (M) (H)
The organization:
(a)	Establishes usage restrictions, configuration requirements, connection requirements, and implementation guidance for organization-controlled mobile devices; and
(b)	Authorizes the connection of mobile devices to organizational information systems.
### AC-19 (5) Control Enhancement (M) (H)
The organization employs [*Selection: full-device encryption; container encryption*] to protect the confidentiality and integrity of information on [*Assignment: organization-defined mobile devices*].
## AC-20 Use of External Information Systems (L) (M) (H)
The organization establishes terms and conditions, consistent with any trust relationships established with other organizations owning, operating, and/or maintaining external information systems, allowing authorized individuals to:
(a)	Access the information system from external information systems; and
(b)	Process, store, or transmit organization-controlled information using external information systems.
### AC-20 (1) Control Enhancement (M) (H)
The organization permits authorized individuals to use an external information system to access the information system or to process, store, or transmit organization-controlled information only when the organization:
(a)	Verifies the implementation of required security controls on the external system as specified in the organization’s information security policy and security plan; or
(b)	Retains approved information system connection or processing agreements with the organizational entity hosting the external information system.
### AC-20 (2) Control Enhancement (M) (H)
The organization [*Selection: restricts; prohibits*] the use of organization-controlled portable storage devices by authorized individuals on external information systems.
## AC-21 Information Sharing (M) (H)
The organization:
(a)	Facilitates information sharing by enabling authorized users to determine whether access authorizations assigned to the sharing partner match the access restrictions on the information for [*Assignment: organization-defined information sharing circumstances where user discretion is required*]; and
(b)	Employs [*Assignment: organization-defined automated mechanisms or manual processes*] to assist users in making information sharing/collaboration decisions.
## AC-22 Publicly Accessible Content (L) (M) (H)
The organization:
(a)	Designates individuals authorized to post information onto a publicly accessible information system;
(b)	Trains authorized individuals to ensure that publicly accessible information does not contain nonpublic information;
(c)	Reviews the proposed content of information prior to posting onto the publicly accessible information system to ensure that nonpublic information is not included; and
(d)	Reviews the content on the publicly accessible information system for nonpublic information [*FedRAMP Assignment: at least quarterly*] and removes such information, if discovered.
