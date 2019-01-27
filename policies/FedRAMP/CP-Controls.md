#13.6 Contingency Planning (CP)
## CP-1 Contingency Planning Policy and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
    (1)	A contingency planning policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the contingency planning policy and associated contingency planning controls; and
  (b)	Reviews and updates the current:
    (1)	Contingency planning policy [_FedRAMP Assignment: at least every three (3) years_].; and
    (2)	 Contingency planning procedures [_FedRAMP Assignment: at least annually_].

## CP-2 Contingency Plan (L) (M) (H)
The organization:
  (a)	Develops a contingency plan for the information system that:
    (1)	Identifies essential missions and business functions and associated contingency requirements;
    (2)	Provides recovery objectives, restoration priorities, and metrics;
    (3)	Addresses contingency roles, responsibilities, assigned individuals with contact information;
    (4)	Addresses maintaining essential missions and business functions despite an information system disruption, compromise, or failure;
    (5)	Addresses eventual, full information system restoration without deterioration of the security safeguards originally planned and implemented; and
    (6)	Is reviewed and approved by [_Assignment: organization-defined personnel or roles_];
  (b)	Distributes copies of the contingency plan to [_Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements_];
  (c)	Coordinates contingency planning activities with incident handling activities;
  (d)	Reviews the contingency plan for the information system [_FedRAMP Assignment: at least annually_];
  (e)	Updates the contingency plan to address changes to the organization, information system, or environment of operation and problems encountered during contingency plan implementation, execution, or testing;
  (f)	Communicates contingency plan changes to [_Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements_]; and
  (g)	Protects the contingency plan from unauthorized disclosure and modification.

## CP-2 Additional FedRAMP Requirements and Guidance:
*Requirement:* For JAB authorizations the contingency lists include designated FedRAMP personnel.
### CP-2 (1) Control Enhancement (M) (H)
The organization coordinates contingency plan development with organizational elements responsible for related plans.
### CP-2 (2) Control Enhancement (M) (H)
The organization conducts capacity planning so that necessary capacity for information processing, telecommunications, and environmental support exists during contingency operations.
### CP-2 (3) Control Enhancement (M) (H)
The organization plans for the resumption of essential missions and business functions within [_Assignment: organization-defined time period_] of contingency plan activation.
### CP-2 (8) Control Enhancement (M) (H)
The organization identifies critical information system assets supporting essential missions and business functions.

## CP-3 Contingency Training (L) (M) (H)
The organization provides contingency training to information system users consistent with assigned roles and responsibilities:
  (a)	Within [_FedRAMP Assignment: ten (10) days_] of assuming a contingency role or responsibility;
  (b)	 When required by information system changes; and
  (c)	[_FedRAMP Assignment: at least annually_] thereafter.

## CP-4 Contingency Plan Testing (H)
The organization:
  (a)	Tests the contingency plan for the information system [_FedRAMP Assignment: at least annually_] using [_FedRAMP Assignment: functional exercises_] to determine the effectiveness of the plan and the organizational readiness to execute the plan;
*CP-4(a) Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider develops test plans in accordance with NIST Special Publication 800-34 (as amended) and provides plans to FedRAMP prior to initiating testing.  Test plans are approved and accepted by the JAB/AO prior to initiating testing.
  (b)	Reviews the contingency plan test results; and
  (c)	Initiates corrective actions, if needed.
### CP-4 (1) Control Enhancement (M) (H)
The organization coordinates contingency plan testing and/or exercises with organizational elements responsible for related plans.

## CP-6 Alternate Storage Site (M) (H)
The organization:
  (a)	Establishes an alternate storage site including necessary agreements to permit the storage and retrieval of information system backup information; and
  (b)	Ensures that the alternate storage site provides information security safeguards equivalent to that of the primary site.
### CP-6 (1) Control Enhancement (M) (H)
The organization identifies an alternate storage site that is separated from the primary storage site to reduce susceptibility to the same threats.
### CP-6 (3) Control Enhancement (M) (H)
The organization identifies potential accessibility problems to the alternate storage site in the event of an area-wide disruption or disaster and outlines explicit mitigation actions.

## CP-7 Alternate Processing Site (M) (H)
The organization:
  (a)	Establishes an alternate processing site including necessary agreements to permit the transfer and resumption of [_Assignment: organization-defined information system operations_] for essential missions/business functions within [_FedRAMP Assignment: see additional FedRAMP requirements and guidance_] when the primary processing capabilities are unavailable;
*CP-7a Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider defines a time period consistent with the recovery time objectives and business impact analysis.  
(b)	Ensures that equipment and supplies required to transfer and resume operations are available at the alternate processing site or contracts are in place to support delivery to the site within the organization-defined time period for transfer/resumption; and
(c)	Ensures that the alternate processing site provides information security safeguards equivalent to that of the primary site.
### CP-7 (1) Control Enhancement (M) (H)
The organization identifies an alternate processing site that is separated from the primary processing site to reduce susceptibility to the same threats.
*CP-7(1) Additional FedRAMP Requirements and Guidance*
*Guidance:* The service provider may determine what is considered a sufficient degree of separation between the primary and alternate processing sites, based on the types of threats that are of concern.  For one particular type of threat (i.e., hostile cyber-attack), the degree of separation between sites will be less relevant.
### CP-7 (2) Control Enhancement (M) (H)
The organization identifies potential accessibility problems to the alternate processing site in the event of an area-wide disruption or disaster and outlines explicit mitigation actions.
### CP-7 (3) Control Enhancement (M) (H)
The organization develops alternate processing site agreements that contain priority-of-service provisions in accordance with organizational availability requirements (including recovery time objectives).

## CP-8 Telecommunications Services (M) (H)
The organization establishes alternate telecommunications services including necessary agreements to permit the resumption of [_Assignment: organization-defined information system operations] for essential missions and business functions within [_FedRAMP Assignment: See ## CP-8 additional FedRAMP requirements and guidance_] when the primary telecommunications capabilities are unavailable at either the primary or alternate processing or storage sites.
*CP-8 Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider defines a time period consistent with the recovery time objectives and business impact analysis.
### CP-8 (1) Control Enhancement (M) (H)
The organization:
  (a)	Develops primary and alternate telecommunications service agreements that contain priority- of-service provisions in accordance with organizational availability requirements (including recovery time objectives); and
  (b)	Requests Telecommunications Service Priority for all telecommunications services used for national security emergency preparedness in the event that the primary and/or alternate telecommunications services are provided by a common carrier.
### CP-8 (2) Control Enhancement (M) (H)
The organization obtains alternate telecommunications services to reduce the likelihood of sharing a single point of failure with primary telecommunications services.

## CP-9 Information System Backup (L) (M) (H)
The organization:
*CP-9 Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider shall determine what elements of the cloud environment require the Information System Backup control. The service provider shall determine how Information System Backup is going to be verified and appropriate periodicity of the check.
  (a)	Conducts backups of user-level information contained in the information system [_FedRAMP Assignment: daily incremental; weekly full_]
*CP-9 (a) Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider maintains at least three backup copies of user-level information (at least one of which is available online).
  (b)	Conducts backups of system-level information contained in the information system [_FedRAMP Assignment: daily incremental; weekly full_];
*CP-9 (b) Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider maintains at least three backup copies of system-level information (at least one of which is available online).
  (c)	Conducts backups of information system documentation including security-related documentation [_FedRAMP Assignment: daily incremental; weekly full_]; and
*CP-9 (c) Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider maintains at least three backup copies of information system documentation including security information (at least one of which is available online).
  (d)	Protects the confidentiality, integrity, and availability of backup information at storage locations.  
### CP-9 (1) Control Enhancement (M)
The organization tests backup information [_FedRAMP Assignment: at least annually_] to verify media reliability and information integrity.
### CP-9 (3) Control Enhancement (M) (H)
The organization stores backup copies of [_Assignment: organization-defined critical information system software and other security-related information_] in a separate facility or in a fire-rated container that is not collocated with the operational system.

## CP-10 Information System Recovery and Reconstitution (L) (M) (H)
The organization provides for the recovery and reconstitution of the information system to a known state after a disruption, compromise, or failure.
### CP-10 (2) Control Enhancement (M) (H)
The information system implements transaction recovery for systems that are transaction-based.
