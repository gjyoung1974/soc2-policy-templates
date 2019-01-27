#13.5 Configuration Management (CM)


## CM-1 Configuration Management Policies and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
    (1)	A configuration management policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the configuration management policy and associated configuration management controls; and
  (b)	Reviews and updates the current:
    (1)	Configuration management policy [_FedRAMP Assignment: at least every three (3) years_]; and
    (2)	Configuration management procedures [_FedRAMP Assignment: at least annually_].

## CM-2 Baseline Configuration (L) (M) (H)
The organization develops, documents, and maintains under configuration control, a current baseline configuration of the information system.
### CM-2 (1) Control Enhancement (M)
The organization reviews and updates the baseline configuration of the information system:
  (a)	[_FedRAMP Assignment: at least annually_];
  (b)	When required due to [_FedRAMP Assignment: to include when directed by the JAB_]; and
  (c)	As an integral part of information system component installations and upgrades.
### CM-2 (2) Control Enhancement (M) (H)
The organization employs automated mechanisms to maintain an up-to-date, complete, accurate, and readily available baseline configuration of the information system.
### CM-2 (3) Control Enhancement (M)
The organization retains [_Assignment: organization-defined previous versions of baseline configurations of the information system_] to support rollback.
### CM-2 (7) Control Enhancement (M) (H)
The organization:
  (a)	Issues [_Assignment: organization-defined information systems, system components, or devices_] with [_Assignment: organization-defined configurations_] to individuals traveling to locations that the organization deems to be of significant risk; and
  (b)	Applies [_Assignment: organization-defined security safeguards_] to the devices when the individuals return.

## CM-3 Configuration Change Control (M) (H)
The organization:
  (b)	Reviews proposed configuration-controlled changes to the information system and approves or disapproves such changes with explicit consideration for security impact analyses;
  (c)	Documents configuration change decisions associated with the information system;
  (d)	Implements approved configuration-controlled changes to the information system;
  (e)	Retains records of configuration-controlled changes to the information system for [_Assignment: organization-defined time period_];
*CM-3 (e) Additional FedRAMP Requirements and Guidance:*
*Guidance:* In accordance with record retention policies and procedures.
  (f)	Audits and reviews activities associated with configuration-controlled changes to the information system; and
  (g)	Coordinates and provides oversight for configuration change control activities through [_FedRAMP Assignment: see additional FedRAMP requirements and guidance] that convenes [Selection (one or more): [_Assignment: organization-defined frequency_]; [_Assignment: organization-defined configuration change conditions_]].
*CM-3 Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider establishes a central means of communicating major changes to or developments in the information system or environment of operations that may affect its services to the federal government and associated service consumers (e.g., electronic bulletin board, web status page).  The means of communication are approved and accepted by the JAB/AO.

## CM-4 Security Impact Analysis (L) (M) (H)
The organization analyzes changes to the information system to determine potential security impacts prior to change implementation.  

## CM-5 Access Restrictions for Change (M) (H)
The organization defines, documents, approves, and enforces physical and logical access restrictions associated with changes to the information system.
### CM-5 (1) Control Enhancement (M) (H)
The information system enforces access restrictions and supports auditing of the enforcement actions.
### CM-5 (3) Control Enhancement (M) (H)
The information system prevents the installation of [_Assignment: organization-defined software and firmware components_] without verification that the component has been digitally signed using a certificate that is recognized and approved by the organization.
*CM-5 (3) Additional FedRAMP Requirements and Guidance:*
*Guidance:* If digital signatures/certificates are unavailable, alternative cryptographic integrity checks (hashes, self-signed certs, etc.) can be used.
### CM-5 (5) Control Enhancement (M) (H)
The organization:
  (a)	Limits privileges to change information system components and system-related information within a production or operational environment; and
  (b)	Reviews and reevaluates privileges [_FedRAMP Assignment: at least quarterly_].

## CM-6 Configuration Settings (L) (M) (H)
The organization:
  (a)	Establishes and documents configuration settings for information technology products employed within the information system using [_FedRAMP Assignment: see CM-6(a) Additional FedRAMP Requirements and Guidance_] that reflect the most restrictive mode consistent with operational requirements;
*CM-6(a) Additional FedRAMP Requirements and Guidance:*
*Requirement 1:* The service provider shall use the Center for Internet Security guidelines (Level 1) to establish configuration settings or establishes its own configuration settings if USGCB is not available. If no recognized USGCB is available for the technology in use, the CSP should create their own baseline and include a justification statement as to how they came up with the baseline configuration settings.
*Requirement 2:* The service provider shall ensure that checklists for configuration settings are Security Content Automation Protocol (SCAP) (http://scap.nist.gov/) validated or SCAP compatible (if validated checklists are not available).
Guidance:* Information on the USGCB checklists can be found at: http://usgcb.nist.gov/usgcb_faq.html#usgcbfaq_usgcbfdcc.  
  (b)	Implements the configuration settings;
  (c)	Identifies, documents, and approves any deviations from established configuration settings for [_Assignment: organization-defined information system components_] based on [_Assignment: organization-defined operational requirements_]; and
  (d)	Monitors and controls changes to the configuration settings in accordance with organizational policies and procedures.  
### CM-6 (1) Control Enhancement (M) (H)
The organization employs automated mechanisms to centrally manage, apply, and verify configuration settings for [_Assignment: organization-defined information system components_].

## CM-7 Least Functionality (L) (M) (H)
The organization:
  (a)	Configures the information system to provide only essential capabilities; and
  (b)	Prohibits or restricts the use of the following functions, ports, protocols, and/or services [_FedRAMP Assignment: United States Government Configuration Baseline (USGCB)_]
*CM-7 Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider shall use the Center for Internet Security guidelines (Level 1) to establish list of prohibited or restricted functions, ports, protocols, and/or services or establishes its own list of prohibited or restricted functions, ports, protocols, and/or services if USGCB is not available. If no recognized USGCB is available for the technology in use, the CSP should create their own baseline and include a justification statement as to how they came up with the baseline configuration settings.
Guidance:* Information on the USGCB checklists can be found at: http://usgcb.nist.gov/usgcb_faq.html#usgcbfaq_usgcbfdcc
Partially derived from AC-17 (8).
### CM-7 (1) Control Enhancement (M) (H)
The organization:
  (a)	Reviews the information system [_FedRAMP Assignment: at least Monthly_] to identify unnecessary and/or nonsecure functions, ports, protocols, and services; and
  (b)	Disables [_Assignment: organization-defined functions, ports, protocols, and services within the information system deemed to be unnecessary and/or nonsecure_].
### CM-7 (2) Control Enhancement (M) (H)
The information system prevents program execution in accordance with [_Selection (one or more): [Assignment: organization-defined policies regarding software program usage and restrictions]; rules authorizing the terms and conditions of software program usage_].
*CM-7(2) Additional FedRAMP Requirements and Guidance:*
Guidance:* This control shall be implemented in a technical manner on the information system to only allow programs to run that adhere to the policy (i.e., white listing).  This control is not to be based off of strictly written policy on what is allowed or not allowed to run.
### CM-7 (5) Control Enhancement (M)
The organization:
  (a)	Identifies [_Assignment: organization-defined software programs authorized to execute on the information system_];
  (b)	Employs a deny-all, permit-by-exception policy to allow the execution of authorized software programs on the information system; and
  (c)	Reviews and updates the list of authorized software programs [_FedRAMP Assignment: at least annually or when there is a change_].

## CM-8 Information System Component Inventory (L) (M) (H)
The organization:
  (a)	Develops and documents an inventory of information system components that:
    (1)	Accurately reflects the current information system;
    (2)	Includes all components within the authorization boundary of the information system;
    (3)	Is at the level of granularity deemed necessary for tracking and reporting; and
    (4)	Includes [_Assignment: organization-defined information deemed necessary to achieve effective information system component accountability_]; and
  (b)	Reviews and updates the information system component inventory [_FedRAMP Assignment: at least monthly_].
*CM-8 Additional FedRAMP Requirements and Guidance:*
*Requirement:* Must be provided at least monthly or when there is a change.
### CM-8 (1) Control Enhancement (M) (H)
The organization updates the inventory of information system components as an integral part of component installations, removals, and information system updates.
### CM-8 (3) Control Enhancement (M) (H)
The organization:
  (a)	Employs automated mechanisms [_FedRAMP Assignment: Continuously, using automated mechanisms with a maximum five-minute delay in detection_] to detect the presence of unauthorized hardware, software, and firmware components within the information system; and
  (b)	Takes the following actions when unauthorized components are detected: [_Selection (one or more): disables network access by such components; isolates the components; notifies [_Assignment: organization-defined personnel or roles]_].
### CM-8 (5) Control Enhancement (M) (H)
The organization verifies that all components within the authorization boundary of the information system are not duplicated in other information system inventories.

## CM-9 Configuration Management Plan (M) (H)
The organization develops, documents, and implements a configuration management plan for the information system that:
  (a)	Addresses roles, responsibilities, and configuration management processes and procedures;
  (b)	Establishes a process for identifying configuration items throughout the system development life cycle and for managing the configuration of the configuration items;
  (c)	Defines the configuration items for the information system and places the configuration items under configuration management; and
  (d)	Protects the configuration management plan for unauthorized disclosure and modification.

## CM-10 Software Usage Restrictions (L) (M) (H)
The organization:
  (a)	Uses software and associated documentation in accordance with contract agreements and copyright laws;
  (b)	Tracks the use of software and associated documentation protected by quantity licenses to control copying and distribution; and
  (c)	Controls and documents the use of peer-to-peer file sharing technology to ensure that this capability is not used for the unauthorized distribution, display, performance, or reproduction of copyrighted work.
### CM-10 (1) Control Enhancement (M) (H)
The organization establishes the following restrictions on the use of open source software: [_Assignment: organization-defined restrictions_].

## CM-11 User-Installed Software (M) (H)
The organization:
  (a)	Establishes [_Assignment: organization-defined policies_] governing the installation of software by users;
  (b)	Enforces software installation policies through [_Assignment: organization-defined methods_]; and
  (c)	Monitors policy compliance [_FedRAMP Assignment: Continuously (via CM-7 (5))_].
