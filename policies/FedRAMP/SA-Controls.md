#13.15 System and Services Acquisition (SA)
## SA-1 System and Services Acquisition Policy and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
    (1)	A system and services acquisition policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the system and services acquisition policy and associated system and services acquisition controls; and
  (b)	Reviews and updates the current:
    (1)	System and services acquisition policy [_FedRAMP Assignment: at least every three (3) years_]; and
    (2)	System and services acquisition procedures [_FedRAMP Assignment: at least annually_].

## SA-2 Allocation of Resources (L) (M) (H)
The organization:
  (a)	Determines information security requirements for the information system or information system service in mission/business process planning;
  (b)	Determines, documents, and allocates the resources required to protect the information system or information system service as part of its capital planning and investment control process; and
  (c)	Establishes a discrete line item for information security in organizational programming and budgeting documentation.

## SA-3 System Development Life Cycle (L) (M) (H)
The organization:
  (a)	Manages the information system using [_Assignment: organization-defined system development life cycle_] that incorporates information security considerations;
  (b)	Defines and documents information security roles and responsibilities throughout the system development life cycle;
  (c)	Identifies individuals having information security roles and responsibilities; and
  (d)	Integrates the organizational information security risk management process into system development life cycle activities.

## SA-4 Acquisitions Process (L) (M) (H)
The organization includes the following requirements, descriptions, and criteria, explicitly or by reference, in the acquisition contract for the information system, system component, or information system service in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, guidelines, and organizational mission/business needs:
  (a)	Security functional requirements;
  (b)	Security strength requirements;
  (c)	Security assurance requirements;
  (d)	Security-related documentation requirements;
  (e)	Requirements for protecting security-related documentation;
  (f)	Description of the information system development environment and environment in which the system is intended to operate; and
  (g)	Acceptance criteria.
*Additional FedRAMP Requirements and Guidance:*
*Guidance:* The use of Common Criteria (ISO/IEC 15408) evaluated products is strongly preferred.  
See http://www.niap-ccevs.org/vpl or http://www.commoncriteriaportal.org/products.html.

### SA-4 (1) Control Enhancement (M) (H)
The organization requires the developer of the information system, system component, or information system service to provide a description of the functional properties of the security controls to be employed.

### SA-4 (2) Control Enhancement (L) (M)
The organization requires the developer of the information system, system component, or information system service to provide design and implementation information for the security controls to be employed that includes: [_FedRAMP Selection (one or more): to include security-relevant external system interfaces, and high-level design_]; [_Assignment: organization-defined design/implementation information_] at [_Assignment: organization-defined level of detail_].

### SA-4 (8) Control Enhancement (M) (H)
The organization requires the developer of the information system, system component, or information system service to produce a plan for the continuous monitoring of security control effectiveness that contains [_FedRAMP Assignment: at least the minimum requirement as defined in control CA-7_].

*SA-4 (8) Additional FedRAMP Requirements and Guidance:*
*Guidance:* CSP must use the same security standards regardless of where the system component or information system service is acquired.

### SA-4 (9) Control Enhancement (M) (H)
The organization requires the developer of the information system, system component, or information system service to identify early in the system development life cycle, the functions, ports, protocols, and services intended for organizational use.

### SA-4 (10) Control Enhancement (M) (H)
The organization employs only information technology products on the FIPS 201-approved products list for Personal Identity Verification (PIV) capability implemented within organizational information systems.

## SA-5 Information System Documentation (L) (M)
The organization:
  (a)	Obtains administrator documentation for the information system, system component, or information system service that describes:
    (1)	Secure configuration, installation, and operation of the system, component, or service;
    (2)	Effective use and maintenance of security functions/mechanisms; and
    (3)	Known vulnerabilities regarding configuration and use of administrative (i.e., privileged) functions;
  (b)	Obtains user documentation for the information system, system component, or information system service that describes:
    (1)	User-accessible security functions/mechanisms and how to effectively use those security functions/mechanisms;
    (2)	Methods for user interaction, which enables individuals to use the system, component, or service in a more secure manner; and
    (3)	User responsibilities in maintaining the security of the system, component, or service;
  (c)	Documents attempts to obtain information system, system component, or information system service documentation when such documentation is either unavailable or nonexistent and [_Assignment: organization-defined actions_] in response;
  (d)	Protects documentation as required, in accordance with the risk management strategy; and
  (e)	Distributes documentation to [_Assignment: organization-defined personnel or roles_].

## SA-8 Security Engineering Principles (M) (H)
The organization applies information system security engineering principles in the specification, design, development, implementation, and modification of the information system.

## SA-9 External Information System Services (L) (M) (H)
The organization:
  (a)	Requires that providers of external information system services comply with organizational information security requirements and employ [_FedRAMP Assignment: FedRAMP Security Controls Baseline(s) if Federal information is processed or stored within the external system_] in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance;
  (b)	Defines and documents government oversight and user roles and responsibilities with regard to external information system services; and
  (c)	Employs [_FedRAMP Assignment: Federal/FedRAMP Continuous Monitoring requirements must be met for external systems where Federal information is processed or stored_] to monitor security control compliance by external service providers on an ongoing basis.
*Additional FedRAMP Requirements and Guidance
*Guidance:* See the FedRAMP Documents page under Key Cloud Service Provider (CSP) Documents> Continuous Monitoring Strategy Guide
https://www.FedRAMP.gov/resources/documents

### SA-9 (1) Control Enhancement (M) (H)
The organization:
  (a)	Conducts an organizational assessment of risk prior to the acquisition or outsourcing of dedicated information security services; and
  (b)	Ensures that the acquisition or outsourcing of dedicated information security services is approved by [_Assignment: organization-defined personnel or roles_].

### SA-9 (2) Control Enhancement (M) (H)
The organization requires providers of [_FedRAMP Assignment: All external systems where Federal information is processed or stored_] to identify the functions, ports, protocols, and other services required for the use of such services.

### SA-9 (4) Control Enhancement (M) (H)
The organization employs [_Assignment: organization-defined security safeguards_] to ensure that the interests of [_FedRAMP Assignment: All external systems where Federal information is processed or stored_] are consistent with and reflect organizational interests.

### SA-9 (5) Control Enhancement (M) (H)
The organization restricts the location of [FedRAMP Selection: information processing, information data, AND information services_] to [_Assignment: organization-defined locations_] based on [_Assignment: organization-defined requirements or conditions_].
*Additional FedRAMP Requirements and Guidance
*Guidance:*  System services refer to FTP, Telnet, and TFTP, etc.

## SA-10 Developer Configuration Management (M) (H)
The organization requires the developer of the information system, system component, or information system service to:
  (a)	Perform configuration management during system, component, or service [_FedRAMP Selection: development, implementation, AND operation_];
  (b)	Document, manage, and control the integrity of changes to [_Assignment: organization-defined configuration items under configuration management_];
  (c)	Implement only organization-approved changes to the system, component, or service;
  (d)	Document approved changes to the system, component, or service and the potential security impacts of such changes; and
  (e)	Track security flaws and flaw resolution within the system, component, or service and report findings to [_Assignment: organization-defined personnel_].

*SA-10 (e) Additional FedRAMP Requirements and Guidance:*
*Requirement:* For JAB authorizations, track security flaws and flaw resolution within the system, component, or service and report findings to organization-defined personnel, to include FedRAMP ISSOs.

### SA-10 (1) Control Enhancement (M) (H)
The organization requires the developer of the information system, system component, or information system service to enable integrity verification of software and firmware components.

## SA-11 Developer Security Testing and Evaluation (M) (H)
The organization requires the developer of the information system, system component, or information system service to:
  (a)	Create and implement a security assessment plan;
  (b)	Perform [_Selection (one or more): unit; integration; system; regression_] testing/evaluation at [_Assignment: organization-defined depth and coverage_];
  (c)	Produce evidence of the execution of the security assessment plan and the results of the security testing/evaluation;
  (d)	Implement a verifiable flaw remediation process; and
  (e)	Correct flaws identified during security testing/evaluation.

### SA-11 (1) Control Enhancement (M) (H)
The organization requires the developer of the information system, system component, or information system service to employ static code analysis tools to identify common flaws and document the results of the analysis.

*SA-11 (1) Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider documents in the Continuous Monitoring Plan, how newly developed code for the information system is reviewed.

### SA-11 (2) Control Enhancement (M) (H)
The organization requires the developer of the information system, system component, or information system service to perform threat and vulnerability analyses and subsequent testing/evaluation of the as-built system, component, or service.

### SA-11 (8) Control Enhancement (M) (H)
The organization requires the developer of the information system, system component, or information system service to employ dynamic code analysis tools to identify common flaws and document the results of the analysis.
