## SATRE Architecture


The current version of the architecture can be viewed on [the architecture viewer](https://satre-archimate.readthedocs.io/en/latest/?view=id-4349bc52159b48e9b785e9809a876c03).

You can also explore the specification on the [SATRE Specification site](https://satre-specification.readthedocs.io/).

Reference this work via the [DOI on Zenodo](https://doi.org/10.5281/zenodo.10053383)

 Standard Architecture for Trusted Research Environments (TREs) provides a comprehensive high-level architecture for research organisations handling sensitive data safely. The architecture is documented using the ArchiMate modelling language with models created using the open source modelling tool [Archi](https://www.archimatetool.com/).

Capabilities an organisation requires to run a TRE are documented and deconstructed to show the elements (Roles, processes, applications and data) needed to realise those capabilities.

## Versions

Version | Release Date | Release Notes
--------|---------------|--------------
[Version 2.0](./Report_SATRE_2.0/index.html)| 2026-06-01| See [Version 2.0 Release Notes](#version-20-release-notes) below.
[Version 1.1](./Report_SATRE_1.1/index.html)| 2025-7-01| * Output Management added as capability as per specification.<br>* Specification Statements added as requirements and linked to capabilities.<br>* Added URL to specification statements in "documentation" where possible<br>* Supporting Capabilities pillar aligned to specification.<br>* Views created for all supporting capabilities.<br>* All requirements added to views.
[Version 1.0](./Report_SATRE_1.1/index.html) | 2023-10-05 | 

## Version 2.0 Release Notes

Version 2.0 is a major update to the SATRE architecture introducing a new Federation Management pillar and significant restructuring of existing capabilities.

### New: Federation Management Pillar (5.0)

A complete new capability pillar has been added to address how multiple TREs work together in a federated model:

- **5.0 Federation Management** - Governance, coordination and operation of a federation of TREs
- **5.1 Federation Governance** - Oversight, policy and decision-making across federation members
- **5.2 Federation Researcher Accreditation** - Consistent identification and accreditation of researchers across member TREs
- **5.3 Federation Study Management** - Research studies and work packages spanning multiple TREs
- **5.4 Federation Information Security** - Safeguarding research and shared resources across member TREs
- **5.5 Federation Infrastructure Management** - Shared infrastructure supporting research across member TREs
- **5.6 Federation Data Management** - Data assets shared across member TREs
- **5.7 Federation Financial Management** - Financial resources for operating the federation

23 new specification requirements have been added for the Federation pillar (5.x series).

### New/changed Capabilities

- **2.6 Cyber Resilience** - Anticipating, withstanding, recovering from and adapting to adverse cyber events
- **1.7 Public Involvement and Engagement** - Involving patients, participants and the public in research oversight (moved from Supporting pillar 4.8)

### Capability Renaming and Renumbering

Several capabilities have been renumbered and renamed for clarity and alignment with the specification:

- "1.0 Information Governance" → "1.1 Information Governance"
- "1.5 Member Accreditation" → "1.5 Researcher Accreditation"
- "2.5 Encryption" → "2.8 Encryption"
- "2.5 Vulnerability Management" → "2.7 Vulnerability Management"
- "2.5 Physical Security" → "2.9 Physical Security"
- "4.8 Public Involvement and Engagement" → moved to "1.7 Public Involvement and Engagement"
- "4.9 Legal Services" → "4.8 Legal Services"

### Removed Capabilities

- **Network Management** - Removed as a standalone capability (covered within other capabilities)

### New Views

- **5.0 Federation Management** - New view for the federation pillar
- **1.7 Public Involvement and Engagement** - New view for public engagement capability
- **2.6 Cyber Resilience** - New view for cyber resilience capability

### Removed Views

Views for "3.8 Data Archiving", "3.5 Security Levels and Tiering", "3.6 Research Metadata", "3.7 Metadata Search and Discovery" and "Network Management" have been removed (content consolidated into other views or capabilities).

### Requirements Reorganisation

- Requirements have been reorganised into the correct pillars and organised as per the specification
- New specification requirements added for Data Management (3.x series) covering data ingress, egress, deletion, archiving, output checking and disclosure control
- All existing requirements updated with improved documentation links to the specification

### New Elements

- New business actors: Public Member, Public Engagement Specialist
- New business objects: Federation Project Register, Federation Agreement Data, Federation Identities
- New processes: Statistical Disclosure Control, Output Checking, Threat Modelling Process, Public Involvement and Engagement Process, Federation Member Onboarding
- Documentation added to all capabilities that previously lacked descriptions
- Extensive updates to all existing views to reflect the restructured architecture

## SATRE Architecture Repository

This repo manages the architecture files for SATRE. [Archi](https://www.archimatetool.com/) files within the [model](https://github.com/sa-tre/satre-archimate/tree/master/model) directory can be cloned into the [Archi](https://www.archimatetool.com/) tool and edited locally.

Collaboration and synchronisation of files can be done via the [coArchi tool](https://github.com/archimatetool/archi-modelrepository-plugin/wiki).

Current version of the SATRE architecture is stored in the "master" branch. 