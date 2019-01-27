#13.10 Media Protection (MP)
## MP-1 Media Protection Policy and Procedures (L) (M)
The organization:
  (a)	Develops, documents, and disseminates to [_Assignment: organization-defined personnel or roles_]:
    (1)	A media protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
    (2)	Procedures to facilitate the implementation of the media protection policy and associated media protection controls; and
  (b)	Reviews and updates the current:
    (1)	Media protection policy [_FedRAMP Assignment: at least every three (3) years_]; and
    (2)	Media protection procedures [_FedRAMP Assignment: at least annually_].

## MP-2 Media Access (L) (M)
The organization restricts access to [_Assignment: organization-defined types of digital and/or non-digital media_] to [_Assignment: organization-defined personnel or roles_].

## MP-3 Media Labeling (M) (H)
The organization:
  (a)	Marks information system media indicating the distribution limitations, handling caveats, and applicable security markings (if any) of the information; and
  (b)	Exempts [_FedRAMP Assignment: no removable media types_] from marking as long as the media remain within [_Assignment: organization-defined controlled areas_].
*MP-3(b) Additional FedRAMP Requirements and Guidance:*
*Guidance:* Second parameter in ## MP-3(b)-2 is not applicable.

## MP-4 Media Storage (M) (H)
The organization:
  (a)	Physically controls and securely stores [_FedRAMP Assignment: [all types of digital and non-digital media with sensitive information_]_] within [_FedRAMP Assignment: see additional FedRAMP requirements and guidance_]; and
*MP-4a Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider defines controlled areas within facilities where the information and information system reside.
  (b)	Protects information system media until the media are destroyed or sanitized using approved equipment, techniques, and procedures.

## MP-5 Media Transport (M) (H)
The organization:
  (a)	Protects and controls [_FedRAMP Assignment: all media with sensitive information_] during transport outside of controlled areas using [_FedRAMP Assignment: for digital media, encryption using a FIPS 140-2 validated encryption module; for non-digital media, secured in locked container_];
*MP-5a Additional FedRAMP Requirements and Guidance:*
*Requirement:* The service provider defines security measures to protect digital and non-digital media in transport.  The security measures are approved and accepted by the JAB/AO.
  (b)	Maintains accountability for information system media during transport outside of controlled areas;
  (c)	Documents activities associated with the transport of information system media; and
  (d)	Restricts the activities associated with transport of information system media to authorized personnel.
### MP-5 (4) Control Enhancement (M) (H)
The organization employs cryptographic mechanisms to protect the confidentiality and integrity of information stored on digital media during transport outside of controlled areas.

## MP-6 Media Sanitization and Disposal (L) (M)
The organization:
  (a)	Sanitizes [_Assignment: organization-defined information system media_] prior to disposal, release out of organizational control, or release for reuse using [_Assignment: organization-defined sanitization techniques and procedures_] in accordance with applicable federal and organizational standards and policies; and
  (b)	Employs sanitization mechanisms with strength and integrity commensurate with the classification or classification of the information.
### MP-6 (2) Control Enhancement (M)
The organization tests sanitization equipment and procedures [_FedRAMP Assignment: at least annually_] to verify that the intended sanitization is being achieved.
*MP-6(2) Additional FedRAMP Requirements and Guidance:*
Guidance:* Equipment and procedures may be tested or evaluated for effectiveness.

## MP-7 Media Use (L) (M) (H)
The organization [Selection: restricts; prohibits] the use of [_Assignment: organization-defined types of information system media_] on [_Assignment: organization-defined information systems or system components_] using [_Assignment: organization-defined security safeguards_].
### MP-7 (1) Control Enhancement (M) (H)
The organization prohibits the use of portable storage devices in organizational information systems when such devices have no identifiable owner.
