# 13.3 Audit and Accountability (AU)
## AU-1 Audit and Accountability Policy and Procedures (L) (M)
The organization:
(a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
(1)	An audit and accountability policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
(2)	Procedures to facilitate the implementation of the audit and accountability policy and associated audit and accountability controls; and
(b)	Reviews and updates the current:
(1)	Audit and accountability policy [_FedRAMP Assignment: at least every 3 years_]; and
(2)	Audit and accountability procedures [_FedRAMP Assignment: at least annually_].
## AU-2 Audit Events (L) (M) (H)
The organization:
(a)	Determines that the information system is capable of auditing the following events: [_FedRAMP Assignment: [Successful and unsuccessful account logon events, account management events, object access, policy change, privilege functions, process tracking, and system events.  For Web applications: all administrator activity, authentication checks, authorization checks, data deletions, data access, data changes, and permission changes_];
(b)	Coordinates the security audit function with other organizational entities requiring audit-related information to enhance mutual support and to help guide the selection of auditable events;
(c)	Provides a rationale for why the auditable events are deemed to be adequate to support after-the-fact investigations of security incidents; and
(d)	Determines that the following events are to be audited within the information system: [_FedRAMP Assignment: organization-defined subset of the auditable events defined in AU-2 a. to be audited continually for each identified event_].
*AU-2 Additional FedRAMP Requirements and Guidance: *
*Requirement*: Coordination between service provider and consumer shall be documented and accepted by the JAB/AO.
### AU-2 (3) Control Enhancement (M) (H)
The organization reviews and updates the audited events [_FedRAMP Assignment: annually or whenever there is a change in the threat environment_].
*AU-2 (3) Additional FedRAMP Requirements and Guidance:
Guidance*: Annually or whenever changes in the threat environment are communicated to the service provider by the JAB/AO.
## AU-3 Content of Audit Records (L) (M) (H)
The information system generates audit records containing information that establishes what type of event occurred, when the event occurred, where the event occurred, the source of the event, the outcome of the event, and the identity of any individuals or subjects associated with the event.
### AU-3 (1) Control Enhancement (M)
The information system generates audit records containing the following additional information: [_Assignment: organization-defined additional, more detailed information_].
*AU-3 (1) Additional FedRAMP Requirements and Guidance:
Requirement:* The service provider defines audit record types [_FedRAMP Assignment: session, connection, transaction, or activity duration; for client-server transactions, the number of bytes received and bytes sent; additional informational messages to diagnose or identify the event; characteristics that describe or identify the object or resource being acted upon_].  The audit record types are approved and accepted by the JAB.
*Guidance:* For client-server transactions, the number of bytes sent and received gives bidirectional transfer information that can be helpful during an investigation or inquiry.
## AU-4 Audit Storage Capacity (L) (M) (H)
The organization allocates audit record storage capacity in accordance with [_Assignment: organization-defined audit record storage requirements_].
## AU-5 Response to Audit Processing Failures (L) (M) (H)
The information system:
(a)	Alerts [_Assignment: organization-defined personnel or roles_] in the event of an audit processing failure; and
(b)	Takes the following additional actions: [_FedRAMP Assignment: organization-defined actions to be taken; (overwrite oldest record)_].
## AU-6 Audit Review, Analysis, and Reporting (L) (M) (H)
The organization:
(a)	Reviews and analyzes information system audit records [_FedRAMP Assignment: at least weekly] for indications of [_Assignment: organization-defined inappropriate or unusual activity_]; and
(b)	Reports findings to [_Assignment: organization-defined personnel or roles_].
*AU-6 Additional FedRAMP Requirements and Guidance: *
*Requirement:* Coordination between service provider and consumer shall be documented and accepted by the Authorizing Official. In multi-tenant environments, capability and means for providing review, analysis, and reporting to consumer for data pertaining to consumer shall be documented.
### AU-6 (1) Control Enhancement (M) (H)
The organization employs automated mechanisms to integrate audit review, analysis, and reporting processes to support organizational processes for investigation and response to suspicious activities.
### AU-6 (3) Control Enhancement (M) (H)
The organization analyzes and correlates audit records across different repositories to gain organization-wide situational awareness.
## AU-7 Audit Reduction and Report Generation (M) (H)
The information system provides an audit reduction and report generation capability that:
(a)	Supports on-demand audit review, analysis, and reporting requirements and after-the-fact investigations of security incidents; and
(b)	Does not alter the original content or time ordering of audit records.
### AU-7 (1) Control Enhancement (M) (H)
The information system provides the capability to process audit records for events of interest based on [_Assignment: organization-defined audit fields within audit records_].
## AU-8 Time Stamps (L) (M) (H)
The information system:
(a)	Uses internal system clocks to generate time stamps for audit records; and
(b)	Records time stamps for audit records that can be mapped to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) and meets [_Assignment: one second granularity of time measurement_].
### AU-8 (1) Control Enhancement (M) (H)
The information system:
(a)	Compares the internal information system clocks  with [_FedRAMP Assignment: authoritative time source: [http://tf.nist.gov/tf-cgi/servers.cgi] [at least hourly]_]; and
(b)	Synchronizes the internal system clocks to the authoritative time source when the time difference is greater than [_Assignment: organization-defined time period_].
  *AU-8 (1) Additional FedRAMP Requirements and Guidance: *
  *Requirement:* The service provider selects primary and secondary time servers used by the NIST Internet time service. The secondary server is selected from a different geographic region than the primary server.
  *Requirement:* The service provider synchronizes the system clocks of network computers that run operating systems other than Windows to the Windows Server Domain Controller emulator or to the same time source for that server.
  *Guidance:* The service provider selects primary and secondary time servers used by the NIST Internet time service, or by a Stratum-1 time server. The secondary server is selected from a different geographic region than the primary server.
If using Windows Active Directory, all servers should synchronize time with the time source for the Windows Domain Controller. If using some other directory services (e.g., LDAP), all servers should synchronize time with the time source for the directory server
  *AU-8 (1) Additional FedRAMP Requirements and Guidance: *
  *Requirement 1:* The service provider selects primary and secondary time servers used by the NIST Internet time service.  The secondary server is selected from a different geographic region than the primary server.
  *Requirement 2:* The service provider synchronizes the system clocks of network computers that run operating systems other than Windows to the Windows Server Domain Controller emulator or to the same time source for that server.
  *Guidance:* Synchronization of system clocks improves the accuracy of log analysis.
## AU-9 Protection of Audit Information (L) (M) (H)
The information system protects audit information and audit tools from unauthorized access, modification, and deletion.
### AU-9 (2) Control Enhancement (M) (H)
The information system backs up audit records [_FedRAMP Assignment: at least weekly_] onto a physically different system or system component than the system or component being audited.
### AU-9 (4) Control Enhancement (M) (H)
The organization authorizes access to management of audit functionality to only [_Assignment: organization-defined subset of privileged users_].
## AU-11 Audit Record Retention (M)
The organization retains audit records for [_FedRAMP Assignment: at least ninety (90) days_] to provide support for after-the-fact investigations of security incidents and to meet regulatory and organizational information retention requirements.
  *AU-11 Additional FedRAMP Requirements and Guidance:*
  *Requirement:* The service provider retains audit records on-line for at least ninety days and further preserves audit records off-line for a period that is in accordance with NARA requirements
## AU-12 Audit Generation (L) (M) (H)
The information system:
(a)	Provides audit record generation capability for the auditable events defined in ## AU-2 a. at [_FedRAMP Assignment: all information system components where audit capability is deployed/available_];
(b)	Allows [_Assignment: organization-defined personnel or roles_] to select which auditable events are to be audited by specific components of the information system; and
(c)	Generates audit records for the events defined in AU-2 d. with the content defined in AU-3.
