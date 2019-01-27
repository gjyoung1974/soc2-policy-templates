#13.17 System and Information Integrity (SI)
## SI-1 System and Information Integrity Policy and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
    (1)	A system and information integrity policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the system and information integrity policy and associated system and information integrity controls; and
  (b)	Reviews and updates the current:
    (1)	System and information integrity policy [_FedRAMP Assignment: at least every three (3) years_]; and
    (2)	System and information integrity procedures [_FedRAMP Assignment: at least at least annually_].

## SI-2 Flaw Remediation (L) (M) (H)
The organization:
  (a)	Identifies, reports, and corrects information system flaws;
  (b)	Tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;
  (c)	Installs security-relevant software and firmware updates within [_FedRAMP Assignment: thirty 30 days of release of updates_] of the release of the updates; and
  (d)	Incorporates flaw remediation into the organizational configuration management process.

### SI-2 (2) Control Enhancement (M) (H)
The organization employs automated mechanisms [_FedRAMP Assignment: at least monthly_] to determine the state of information system components with regard to flaw remediation.

### SI-2 (3) Control Enhancement (M) (H)
The organization:
  (a)	Measures the time between flaw identification and flaw remediation; and
  (b)	Establishes [_Assignment: organization-defined benchmarks_] for taking corrective actions.

## SI-3 Malicious Code Protection (L) (M)
The organization:
  (a)	Employs malicious code protection mechanisms at information system entry and exit points to detect and eradicate malicious code;
  (b)	Updates malicious code protection mechanisms whenever new releases are available in accordance with organizational configuration management policy and procedures;
  (c)	Configures malicious code protection mechanisms to:
    (1)	Perform periodic scans of the information system [_FedRAMP Assignment: at least weekly_] and real-time scans of files from external sources at [_FedRAMP Assignment: to include endpoints_] as the files are downloaded, opened, or executed in accordance with organizational security policy; and
    (2)	[_FedRAMP Assignment: to include alerting administrator or defined security personnel_] in response to malicious code detection; and
  (d)	Addresses the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the information system.

## SI-3 (1) Control Enhancement (M) (H)
The organization centrally manages malicious code protection mechanisms.

## SI-3 (2) Control Enhancement (M) (H)
The information system automatically updates malicious code protection mechanisms.

### SI-3 (7) Control Enhancement (M) (H)
The information system implements nonsignature-based malicious code detection mechanisms.

## SI-4 Information System Monitoring (L) (M) (H)
The organization:
  (a)	Monitors the information system to detect:
    (1)	Attacks and indicators of potential attacks in accordance with [_Assignment: organization-defined monitoring objectives_]; and
    (2)	Unauthorized local, network, and remote connections;
  (b)	Identifies unauthorized use of the information system through [_Assignment: organization-defined techniques and methods_];
  (c)	Deploys monitoring devices (i) strategically within the information system to collect organization-determined essential information; and (ii) at ad hoc locations within the system to track specific types of transactions of interest to the organization;
  (d)	Protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion;
  (e)	Heightens the level of information system monitoring activity whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information;
  (f)	Obtains legal opinion with regard to information system monitoring activities in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations; and
  (g)	Provides [_Assignment: organization-defined information system monitoring information_] to [_Assignment: organization-defined personnel or roles_] [Selection (one or more): as needed; [_Assignment: organization-defined frequency_]].

*SI-4 Additional FedRAMP Requirements and Guidance:*
*Guidance:* See US-CERT Incident Response Reporting Guidelines.

### SI-4 (1) Control Enhancement (M) (H)
The organization connects and configures individual intrusion detection tools into an information system-wide intrusion detection system.

### SI-4 (2) Control Enhancement (M) (H)
The organization employs automated tools to support near real-time analysis of events.

### SI-4 (4) Control Enhancement (M) (H)
The information system monitors inbound and outbound communications traffic [_FedRAMP Assignment: continuously_] for unusual or unauthorized activities or conditions.

### SI-4 (5) Control Enhancement (M) (H)
The information system alerts [_Assignment: organization-defined personnel or roles_] when the following indications of compromise or potential compromise occur: [_Assignment: organization-defined compromise indicators_].

*SI-4(5) Additional FedRAMP Requirements and Guidance:*
*Guidance:* In accordance with the incident response plan.

### SI-4 (14) Control Enhancement (M) (H)
The organization employs a wireless intrusion detection system to identify rogue wireless devices and to detect attack attempts and potential compromises/breaches to the information system.

### SI-4 (16) Control Enhancement (M) (H)
The organization correlates information from monitoring tools employed throughout the information system.

### SI-4 (23) Control Enhancement (M) (H)
The organization implements [_Assignment: organization-defined host-based monitoring mechanisms_] at [_Assignment: organization-defined information system components_].

## SI-5 Security Alerts & Advisories (L) (M) (H)
The organization:
  (a)	Receives information system security alerts, advisories, and directives from [_FedRAMP Assignment: to include US-CERT_] on an ongoing basis;
  (b)	Generates internal security alerts, advisories, and directives as deemed necessary;
  (c)	Disseminates security alerts, advisories, and directives to [_FedRAMP Assignment: to include system security personnel and administrators with configuration/patch-management responsibilities_]; and
  (d)	Implements security directives in accordance with established time frames, or notifies the issuing organization of the degree of noncompliance.

## SI-6 Security Functionality Verification (M) (H)
The information system:
  (a)	Verifies the correct operation of [_Assignment: organization-defined security functions_];
  (b)	Performs this verification [_FedRAMP Assignment: to include upon system startup and/or restart at least monthly_];
  (c)	Notifies [_FedRAMP Assignment: to include system administrators and security personnel_] of failed security verification tests; and
  (d)	[_Selection (one or more): shuts the information system down; restarts the information system; [FedRAMP Assignment: to include notification of system administrators and security personnel_] when anomalies are discovered.

## SI-7 Software & Information Integrity (M) (H)
The organization employs integrity verification tools to detect unauthorized changes to [_Assignment: organization-defined software, firmware, and information_].

### SI-7 (1) Control Enhancement (M) (H)
The information system performs an integrity check of [_Assignment: organization-defined software, firmware, and information_] [_FedRAMP Selection (one or more): at startup; at [_FedRAMP Assignment: to include security-relevant events_]; [_FedRAMP Assignment: at least monthly]_].

### SI-7 (7) Control Enhancement (M) (H)
The organization incorporates the detection of unauthorized [_Assignment: organization-defined security-relevant changes to the information system_] into the organizational incident response capability.

## SI-8 Spam Protection (M) (H)
The organization:
  (a)	Employs spam protection mechanisms at information system entry and exit points to detect and take action on unsolicited messages; and
  (b)	Updates spam protection mechanisms when new releases are available in accordance with organizational configuration management policies and procedures.

### SI-8 (1) Control Enhancement (M) (H)
The organization centrally manages spam protection mechanisms.

### SI-8 (2) Control Enhancement (M) (H)
The organization automatically updates spam protection mechanisms.

## SI-10 Information Input Validation (M) (H)
The information system checks the validity of [_Assignment: organization-defined information inputs_].

## SI-11 Error Handling (M) (H)
The information system:
  (a)	 Generates error messages that provide information necessary for corrective actions without revealing information that could be exploited by adversaries; and
  (b)	 Reveals error messages only to [_Assignment: organization-defined personnel or roles_].

## SI-12 Information Output Handling and Retention (L) (M) (H)
The organization handles and retains information within the information system and information output from the system in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and operational requirements.

## SI-16 Memory Protection (M) (H)
The information system implements [_Assignment: organization-defined fail-safe procedures_] to protect its memory from unauthorized code execution.
