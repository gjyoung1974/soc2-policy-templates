#13.7 Identification and Authentication (IA)
## IA-1 Identification and Authentication Policy and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
    (1)	An identification and authentication policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the identification and authentication policy and associated identification and authentication controls; and
  (b)	Reviews and updates the current:
    (1)	Identification and authentication policy [_FedRAMP Assignment: at least every three (3) years_]; and
    (2)	Identification and authentication procedures [_FedRAMP Assignment: at least annually_].

## IA-2 User Identification and Authentication (L) (M) (H)
The information system uniquely identifies and authenticates organizational users (or processes acting on behalf of organizational users).
### IA-2 (1) Control Enhancement (L) (M) (H)
The information system implements multifactor authentication for network access to privileged accounts.
### IA-2 (2) Control Enhancement (M) (H)
The information system implements multifactor authentication for network access to non-privileged accounts.
### IA-2 (3) Control Enhancement (M) (H)
The information system implements multifactor authentication for local access to privileged accounts.
### IA-2 (5) Control Enhancement (M) (H)
The organization requires individuals to be authenticated with an individual authenticator when a group authenticator is employed.
### IA-2 (8) Control Enhancement (M) (H)
The information system implements replay-resistant authentication mechanisms for network access to privileged accounts.
### IA-2 (11) Control Enhancement (M) (H)
The information system implements multifactor authentication for remote access to privileged and non-privileged accounts such that one of the factors is provided by a device separate from the system gaining access and the device meets [_FedRAMP Assignment: FIPS 140-2, NIAP* Certification, or NSA approval_].
*National Information Assurance Partnership (NIAP)
*Additional FedRAMP Requirements and Guidance:*
*Guidance:* PIV = separate device. Please refer to NIST SP 800-157 Guidelines for Derived Personal Identity Verification (PIV) Credentials.  FIPS 140-2 means validated by the Cryptographic Module Validation Program (CMVP).
### IA-2 (12) Control Enhancement (L) (M) (H)
The information system accepts and electronically verifies Personal Identity Verification (PIV) credentials.
*IA-2 (12) Additional FedRAMP Requirements and Guidance:*
*Guidance:* Include Common Access Card (CAC), i.e., the DoD technical implementation of PIV/FIPS 201/HSPD-12.

## IA-3 Device Identification and Authentication (M) (H)
The information system uniquely identifies and authenticates [_Assignment: organization-defined specific and/or types of devices_] before establishing a [Selection (one or more): local; remote; network_] connection.

## IA-4 Identifier Management (L) (M)
The organization manages information system identifiers for users and devices by:
  (a)	Receiving authorization from [_Assignment: organization-defined personnel or roles_] to assign an individual, group, role, or device identifier;
  (b)	Selecting an identifier that identifies an individual, group, role, or device;
  (c)	Assigning the identifier to the intended individual, group, role, or device;
  (d)	Preventing reuse of identifiers for [_FedRAMP Assignment: at least two (2) years_]; and
  (e)	Disabling the identifier after [_FedRAMP Assignment: ninety days for user identifiers (see additional requirements and guidance)]
*IA-4e Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider defines the time period of inactivity for device identifiers.
Guidance:* For DoD clouds, see DoD cloud website for specific DoD requirements that go above and beyond FedRAMP http://iase.disa.mil/cloud_security/Pages/index.aspx.
### IA-4 (4) Control Enhancement (M) (H)
The organization manages individual identifiers by uniquely identifying each individual as [_FedRAMP Assignment: contractors; foreign nationals_].

## IA-5 Authenticator Management (L) (M)
The organization manages information system authenticators by:
  (a)	Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, or device receiving the authenticator;
  (b)	Establishing initial authenticator content for authenticators defined by the organization;
  (c)	Ensuring that authenticators have sufficient strength of mechanism for their intended use;
  (d)	Establishing and implementing administrative procedures for initial authenticator distribution, for lost/compromised or damaged authenticators, and for revoking authenticators;
  (e)	Changing default content of authenticators prior to information system installation;
  (f)	Establishing minimum and maximum lifetime restrictions and reuse conditions for authenticators;
  (g)	Changing/refreshing authenticators [_FedRAMP Assignment: to include sixty (60) days for passwords_].
  (h)	Protecting authenticator content from unauthorized disclosure and modification;
  (i)	Requiring individuals to take, and having devices implement, specific security safeguards to protect authenticators; and
  (j)	Changing authenticators for group/role accounts when membership to those accounts changes.
### IA-5 (1) Control Enhancement (L) (M)
The information system, for password-based authentication:
  (a)	Enforces minimum password complexity of [_FedRAMP Assignment: case sensitive, minimum of twelve (12) characters, and at least one (1) each of upper-case letters, lower-case letters, numbers, and special characters_];
  (b)	Enforces at least the following number of changed characters when new passwords are created: [_FedRAMP Assignment: at least one (1)_];
  (c)	Stores and transmits only cryptographically-protected passwords;
  (d)	Enforces password minimum and maximum lifetime restrictions of [_FedRAMP Assignment: one (1) day minimum, sixty (60) day maximum_];
  (e)	Prohibits password reuse for [_FedRAMP Assignment: twenty-four (24)_] generations; and
  (f)	Allows the use of a temporary password for system logons with an immediate change to a permanent password.
### IA-5 (2) Control Enhancement (M) (H)
The information system, for PKI-based authentication:
  (a)	Validates certifications by constructing and verifying a certification path to an accepted trust anchor including checking certificate status information;
  (b)	Enforces authorized access to the corresponding private key;
  (c)	Maps the authenticated identity to the account of the individual or group; and
  (d)	Implements a local cache of revocation data to support path discovery and validation in case of inability to access revocation information via the network.
### IA-5 (3) Control Enhancement (M) (H)
The organization requires that the registration process to receive [_FedRAMP Assignment: All hardware/biometric (multifactor authenticators_] be conducted [_FedRAMP Selection: in person_] before [_Assignment: organization-defined registration authority_] with authorization by [_Assignment: organization-defined personnel or roles_].
### IA-5 (4) Control Enhancement (M)
The organization employs automated tools to determine if password authenticators are sufficiently strong to satisfy [_Assignment: organization-defined requirements_].
*IA-5(4) Additional FedRAMP Requirements and Guidance:*
*Guidance:* If automated mechanisms which enforce password authenticator strength at creation are not used, automated mechanisms must be used to audit strength of created password authenticators.
### IA-5 (6) Control Enhancement (M) (H)
The organization protects authenticators commensurate with the security category of the information to which use of the authenticator permits access.
### IA-5 (7) Control Enhancement (M) (H)
The organization ensures that unencrypted static authenticators are not embedded in applications or access scripts or stored on function keys.
### IA-5 (11) Control Enhancement (L) (M) (H)
The information system, for hardware token-based authentication, employs mechanisms that satisfy [_Assignment: organization-defined token quality requirements_].

## IA-6 Authenticator Feedback (L) (M) (H)
The information system obscures feedback of authentication information during the authentication process to protect the information from possible exploitation/use by unauthorized individuals.

## IA-7 Cryptographic Module Authentication (L) (M) (H)
The information system implements mechanisms for authentication to a cryptographic module that meet the requirements of applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance for such authentication.

## IA-8 Identification and Authentication (Non-Organizational Users) (L) (M) (H)
The information system uniquely identifies and authenticates non-organizational users (or processes acting on behalf of non-organizational users).
### IA-8 (1) Control Enhancement (L) (M) (H)
The information system accepts and electronically verifies Personal Identity Verification (PIV) credentials from other federal agencies.
### IA-8 (2) Control Enhancement (L) (M) (H)
The information system accepts only FICAM-approved third-party credentials.
### IA-8 (3) Control Enhancement (L) (M) (H)
The organization employs only FICAM-approved information system components in [_Assignment: organization-defined information systems_] to accept third-party credentials.
### IA-8 (4) Control Enhancement (L) (M) (H)
The information system conforms to FICAM-issued profiles.
