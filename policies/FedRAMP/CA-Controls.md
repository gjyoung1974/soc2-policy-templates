# 13.4 Security Assessment and Authorization (CA)
## CA-1 Certification, Authorization, Security Assessment Policy and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
(1)	A security assessment and authorization policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
(2)	Procedures to facilitate the implementation of the security assessment and authorization policy and associated security assessment and authorization controls; and
  (b)	Reviews and updates the current:
(1)	Security assessment and authorization policy [_FedRAMP Assignment: at least every three (3) years_]; and
(2)	Security assessment and authorization procedures [_FedRAMP Assignment: at least annually_].
## CA-2 Security Assessments (L) (M) (H)
The organization:
  (a)	Develops a security assessment plan that describes the scope of the assessment including:
(1)	Security controls and control enhancements under assessment;
(2)	Assessment procedures to be used to determine security control effectiveness; and
(3)	Assessment environment, assessment team, and assessment roles and responsibilities;
  (b)	Assesses the security controls in the information system and its environment of operation [_FedRAMP Assignment: at least annually_] to determine the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements;
(c)	Produces a security assessment report that documents the results of the assessment; and
(d)	Provides the results of the security control assessment to [_FedRAMP Assignment: individuals or roles to include the FedRAMP Program Management Office (PMO)_].
### CA-2 (1) Control Enhancement (L) (M) (H)
The organization employs assessors or assessment teams with [_Assignment: organization-defined level of independence_] to conduct security control assessments.
*CA-2 (1) Additional FedRAMP Requirements and Guidance:*
*Requirement:* For JAB Authorization, must use an accredited Third Party Assessment Organization (3PAO).
### CA-2 (2) Control Enhancement (M) (H)
The organization includes as part of security control assessments, [_FedRAMP Assignment: at least annually_], [Selection: announced; unannounced], [Selection (one or more): in-depth monitoring; vulnerability scanning; malicious user testing; insider threat assessment; performance/load testing; [_Assignment: organization-defined other forms of security assessment_]].
## CA-2 (2) Additional FedRAMP Requirements and Guidance:*
*Requirement:* To include 'announced', 'vulnerability scanning’ to occur at least annually.
### CA-2 (3) Control Enhancement (M) (H)
The organization accepts the results of an assessment of [_FedRAMP Assignment: organization-defined information system_] performed by [_FedRAMP Assignment: any FedRAMP Accredited 3PAO_] when the assessment meets [_FedRAMP Assignment: the conditions of the JAB/AO in the FedRAMP Repository_].
## CA-3 System Interconnections (L) (M) (H)
The organization:
  (a)	Authorizes connections from the information system to other information systems through the use of Interconnection Security Agreements;
  (b)	Documents, for each interconnection, the interface characteristics, security requirements, and the nature of the information communicated; and
(c)	Reviews and updates Interconnection Security Agreements [_FedRAMP Assignment: at least annually and on input from FedRAMP_].
### CA-3 (3) Control Enhancement (M) (H)
The organization prohibits the direct connection of an [_Assignment: organization-defined unclassified, non-national security system_] to an external network without the use of [_FedRAMP Assignment: boundary protections which meet Trusted Internet Connection (TIC) requirements_].
*CA-3 (3) Additional FedRAMP Requirements and Guidance:* Refer to Appendix H – Cloud Considerations of the TIC 2.0 Reference Architecture document. Link: https://www.fedramp.gov/files/2015/04/TIC_Ref_Arch_v2-0_2013.pdf
### CA-3 (5) Control Enhancement (M)
The organization employs [Selection: allow-all, deny-by-exception, deny-all, permit by exception] policy for allowing [_Assignment: organization-defined information systems_] to connect to external information systems.
*CA-3 (5) Additional FedRAMP Requirements and Guidance:*
*Guidance:* For JAB Authorization, CSPs shall include details of this control in their Architecture Briefing
## CA-5 Plan of Action and Milestones (L) (M) (H)
The organization:
  (a)	Develops a plan of action and milestones for the information system to document the organization’s planned remedial actions to correct weaknesses or deficiencies noted during the assessment of the security controls and to reduce or eliminate known vulnerabilities in the system; and
  (b)	Updates existing plan of action and milestones [_FedRAMP Assignment: at least monthly_] based on the findings from security controls assessments, security impact analyses, and continuous monitoring activities.
*CA-5 Additional FedRAMP Requirements and Guidance:*
*Requirement:* Plan Of Action & Milestones (POA&M)s must be provided at least monthly.
## CA-6 Security Authorization (L) (M) (H)
The organization:
  (a)	Assigns a senior-level executive or manager as the authorizing official for the information system;
  (b)	Ensures that the authorizing official authorizes the information system for processing before commencing operations; and
(c)	Updates the security authorization [_FedRAMP Assignment: in accordance with OMB A-130 requirements or when a significant change occurs_].
## CA-6c Additional FedRAMP Requirements and Guidance:*
*Guidance:* Significant change is defined in NIST Special Publication 800-37 Revision 1, Appendix F (SP 800-37).  The service provider describes the types of changes to the information system or the environment of operations that would impact the risk posture.  The types of changes are approved and accepted by the JAB/AO.
## CA-7 Continuous Monitoring (L) (M) (H)
The organization develops a continuous monitoring strategy and implements a continuous monitoring program that includes:
  (a)	Establishment of [_Assignment: organization-defined metrics_] to be monitored;
  (b)	Establishment of [_Assignment: organization-defined frequencies_] for monitoring and [_Assignment: organization-defined frequencies_] for assessments supporting such monitoring;
  (c)	Ongoing security control assessments in accordance with the organizational continuous monitoring strategy;
  (d)	Ongoing security status monitoring of organization-defined metrics in accordance with the organizational continuous monitoring strategy;
  (e)	Correlation and analysis of security-related information generated by assessments and monitoring;
  (f)	Response actions to address results of the analysis of security-related information; and
  (g)	Reporting the security status of organization and the information system to [_FedRAMP Assignment: to meet Federal and FedRAMP requirements_] [_Assignment: organization-defined frequency_].
*CA-7 Additional FedRAMP Requirements and Guidance:*
*Requirement:* Operating System Scans: at least monthly Database and Web Application Scans: at least monthly All scans performed by Independent Assessor: at least annually.
Guidance:* CSPs must provide evidence of closure and remediation of a high vulnerability within the timeframe for standard POA&M updates.
*CA-7 Additional FedRAMP Requirements and Guidance:*
*Requirement 1:* Operating System Scans: at least monthly
*Requirement 2:* Database and Web Application Scans: at least monthly
*Requirement 3:* All scans performed by Independent Assessor: at least annually
### CA-7 (1) Control Enhancement (M) (H)
The organization employs assessors or assessment teams with [_Assignment: organization-defined level of independence_] to monitor the security controls in the information system on an ongoing basis.
## CA-8 Penetration Testing (M) (H)
The organization conducts penetration testing [_FedRAMP Assignment: at least annually_] on [_Assignment: organization-defined information systems or system components_].
### CA-8 (1) Control Enhancement (M) (H)
The organization employs an independent penetration agent or penetration team to perform penetration testing on the information system or system components.
## CA-9 Internal System Connections (L) (M) (H)
The organization:
  (a)	Authorizes internal connections of [_Assignment: organization-defined information system components or classes of components_] to the information system; and
  (b)	Documents, for each internal connection, the interface characteristics, security requirements, and the nature of the information communicated.
