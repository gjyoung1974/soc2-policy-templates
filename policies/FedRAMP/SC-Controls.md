#13.16 System and Communications Protection (SC)
## SC-1 System and Communications Protection Policy and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
    (1)	A system and communications protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the system and communications protection policy and associated system and communications protection controls; and
  (b)	Reviews and updates the current:
    (1)	System and communications protection policy [_FedRAMP Assignment: at least every three (3) years_]; and
    (2)	System and communications protection procedures [_FedRAMP Assignment: at least annually_].

## SC-2 Application Partitioning (M) (H)
The information system separates user functionality (including user interface services) from information system management functionality.

## SC-4 Information in Shared Resources (M) (H)
The information system prevents unauthorized and unintended information transfer via shared system resources.

## SC-5 Denial of Service Protection (L) (M) (H)
The information system protects against or limits the effects of the following types of denial of service attacks: [_Assignment: organization-defined types of denial of service attacks or reference to source for such information_] by employing [_Assignment: organization-defined security safeguards_].

## SC-6 Resource Availability (M) (H)
The information system protects the availability of resources by allocating [_Assignment: organization-defined resources_] by [_Selection (one or more); priority; quota; [Assignment: organization-defined security safeguards_]].

## SC-7 Boundary Protection (L) (M) (H)
The information system:
  (a)	Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system; and
  (b)	Implements subnetworks for publicly accessible system components that are [_Selection: physically; logically_] separated from internal organizational networks; and
  (c)	Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with organizational security architecture.

### SC-7 (3) Control Enhancement (M) (H)
The organization limits the number external network connections to the information system.

### SC-7 (4) Control Enhancement (M)
The organization:
  (a)	Implements a managed interface for each external telecommunication service;
  (b)	Establishes a traffic flow policy for each managed interface;
  (c)	Protects the confidentiality and integrity of the information being transmitted across each interface;
  (d)	Documents each exception to the traffic flow policy with a supporting mission/business need and duration of that need; and
  (e)	Reviews exceptions to the traffic flow policy [_FedRAMP Assignment: at least at least annually_] and removes exceptions that are no longer supported by an explicit mission/business need.

### SC-7 (5) Control Enhancement (M) (H)
The information system at managed interfaces denies network traffic by default and allows network communications traffic by exception (i.e., deny all, permit by exception).

### SC-7 (7) Control Enhancement (M) (H)
The information system, in conjunction with a remote device, prevents the device from simultaneously establishing non-remote connections with the system and communicating via some other connection to resources in external networks.

### SC-7 (8) Control Enhancement (M) (H)
The information system routes [_Assignment: organization-defined internal communications traffic_] to [_Assignment: organization-defined external networks_] through authenticated proxy servers at managed interfaces.

### SC-7 (12) Control Enhancement (M)
The organization implements [_Assignment: organization-defined host-based boundary protection mechanisms_] at [_Assignment: organization-defined information system components_].

### SC-7 (13) Control Enhancement (M)
The organization isolates [_FedRAMP Assignment: See SC-7 (13) additional FedRAMP Requirements and Guidance_] from other internal information system components by implementing physically separate subnetworks with managed interfaces to other components of the system.

*SC-7 (13) Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider defines key information security tools, mechanisms, and support components associated with system and security administration and isolates those tools, mechanisms, and support components from other internal information system components via physically or logically separate subnets.  

### SC-7 (18) Control Enhancement (M) (H)
The information system fails securely in the event of an operational failure of a boundary protection device.

## SC-8 Transmission confidentiality and Integrity (M) (H)
The information system protects the [_FedRAMP Assignment: confidentiality AND integrity_] of transmitted information.

### SC-8 (1) Control Enhancement (M) (H)
The information system implements cryptographic mechanisms to [_FedRAMP Assignment: prevent unauthorized disclosure of information AND detect changes to information_] during transmission unless otherwise protected by [_FedRAMP Assignment: a hardened or alarmed carrier Protective Distribution System (PDS)_].

## SC-10 Network Disconnect (M)
The information system terminates the network connection associated with a communications session at the end of the session or after [_FedRAMP Assignment: no longer than thirty (30) minutes for RAS-based sessions and no longer than sixty (60) minutes for non-interactive user sessions_] of inactivity.

## SC-12 Cryptographic Key Establishment & Management (L) (M) (H)
The organization establishes and manages cryptographic keys for required cryptography employed within the information system in accordance with [_Assignment: organization-defined requirements for key generation, distribution, storage, access, and destruction_].

*SC-12 Additional FedRAMP Requirements and Guidance:*
*Guidance:* Federally approved and validated cryptography.

### SC-12 (2) Control Enhancement (M) (H)
The organization produces, controls, and distributes symmetric cryptographic keys using [_FedRAMP Selection: NIST FIPS-compliant_] key management technology and processes.

### SC-12 (3) Control Enhancement (M) (H)
The organization produces, controls, and distributes asymmetric cryptographic keys using [_Selection: NSA-approved key management technology and processes; approved PKI Class 3  certificates or prepositioned keying material; approved PKI Class 3 or Class 4 certificates and  hardware security tokens that protect the user’s private key_].

## SC-13 Use of Cryptography (L) (M) (H)
The information system implements [_FedRAMP Assignment: FIPS-validated or NSA-approved cryptography_] in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, and standards.

## SC-15 Collaborative Computing Devices (M) (H)
The information system:
  (a)	Prohibits remote activation of collaborative computing devices with the following exceptions:[_FedRAMP Assignment: no exceptions_] and
  (b)	Provides an explicit indication of use to users physically present at the devices.

*SC-15 Additional FedRAMP Requirements and Guidance:*
*Requirement:* The information system provides disablement (instead of physical disconnect) of collaborative computing devices in a manner that supports ease of use.

*SC-15 Additional FedRAMP Requirements and Guidance:*
*Requirement:* The information system provides disablement (instead of physical disconnect) of collaborative computing devices in a manner that supports ease of use.

## SC-17 Public Key Infrastructure Certificates (M) (H)
The organization issues public key certificates under an [_Assignment: organization-defined certificate policy_] or obtains public key certificates from an approved service provider.

## SC-18 Mobile Code (M) (H)
The organization:
  (a)	Defines acceptable and unacceptable mobile code and mobile code technologies;
  (b)	Establishes usage restrictions and implementation guidance for acceptable mobile code and mobile code technologies; and
  (c)	Authorizes, monitors, and controls the use of mobile code within the information system.

## SC-19 Voice Over Internet Protocol (M) (H)
The organization:
  (a)	Establishes usage restrictions and implementation guidance for Voice over Internet Protocol (VoIP) technologies based on the potential to cause damage to the information system if used maliciously; and
  (b)	Authorizes, monitors, and controls the use of VoIP within the information system.

## SC-20 Secure Name / Address Resolution Service (Authoritative Source) (L) (M) (H)
The information system:
  (a)	Provides additional data origin authentication and integrity verification artifacts along with the authoritative name resolution data the system returns in response to external name/address resolution queries; and
  (b)	Provides the means to indicate the security status of child zones and (if the child supports secure resolution services) to enable verification of a chain of trust among parent and child domains, when operating as part of a distributed, hierarchical namespace.

## SC-21 Secure Name / Address Resolution Service (Recursive or Caching Resolver) (L) (M) (H)
The information system requests and performs data origin authentication and data integrity verification on the name/address resolution responses the system receives from authoritative sources.

## SC-22 Architecture and Provisioning for Name / Address Resolution Service (L) (M) (H)
The information systems that collectively provide name/address resolution service for an organization are fault-tolerant and implement internal/external role separation.

## SC-23 Session Authenticity (M) (H)
The information system protects the authenticity of communications sessions.

## SC-28 Protection of Information at Rest (M) (H)
The information system protects the [FedRAMP Selection: confidentiality AND integrity_]] of [_Assignment: organization-defined information at rest_].

*SC-28 Additional FedRAMP Requirements and Guidance:*
*Guidance:* The organization supports the capability to use cryptographic mechanisms to protect information at rest.  

### SC-28 (1) Control Enhancement (M)
The information system implements cryptographic mechanisms to prevent unauthorized disclosure and modification of [_Assignment: organization-defined information_] on [_Assignment: organization-defined information system components_]

## SC-39 Process Isolation (L) (M) (H)
The information system maintains a separate execution domain for each executing process.
