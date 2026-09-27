# Awesome-Electronic-Lab-Notebook

# Top Electronic Lab Notebook (ELN) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Research Data Management, Experiment Documentation, Sample Tracking & FAIR Data Compliance*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Electronic Lab Notebooks (ELNs)** . These tools help researchers, lab managers, and scientific organizations digitally document experiments, manage samples, track protocols, and ensure research data is Findable, Accessible, Interoperable, and Reusable (FAIR).

**Examples** include Benchling, LabArchives, eLabJournal, Dotmatics Signals Notebook, SciNote, RSpace, Labguru, STARLIMS ELN, IDBS E-WorkBook, CDD Vault, eLabNext, Scispot, and OpenClinica Participate (the category leaders).

**Open-source emphasis**: The ELN space has a **mature open-source ecosystem**—unlike many enterprise software categories. Open-source ELNs are actively developed, widely adopted in academia, and often exceed commercial tools in flexibility and data ownership. This section is heavily expanded with every major active project, from general-purpose platforms to chemistry-specific and FAIR-focused solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Benchling](https://www.benchling.com/)**  
  R&D cloud platform combining ELN, LIMS, and molecular biology tools. Widely used in biotech for DNA design, CRISPR planning, and regulatory-compliant experiment tracking.

- **[LabArchives](https://www.labarchives.com/)**  
  Cloud-based ELN designed for academic and industry research. Provides notebook entry creation, data storage, collaboration, and compliance with 21 CFR Part 11.

- **[eLabJournal](https://www.elabjournal.com/)**  
  Integrated ELN and LIMS platform by Bio-ITech. Provides experiment documentation, sample tracking, protocol management, and inventory in a single system.

- **[Dotmatics Signals Notebook](https://www.dotmatics.com/)**  
  ELN within the Dotmatics R&D platform. Provides chemistry-aware experiment documentation, structure drawing, and integration with Dotmatics' broader scientific data management suite.

- **[SciNote](https://www.scinote.net/)**  
  Open-source ELN with a cloud-hosted premium offering. Provides experiment protocols, inventory management, team collaboration, and regulatory compliance features.

- **[RSpace](https://www.researchspace.com/)**  
  Research platform with ELN and sample management at its core. Went fully open-source in 2024 (AGPL v3) while maintaining enterprise services for deployment, support, and migration .

- **[Labguru](https://www.labguru.com/)**  
  Integrated ELN and LIMS platform. Provides experiment documentation, sample tracking, protocol management, and research data management.

- **[STARLIMS ELN](https://www.starlims.com/)**  
  ELN module within STARLIMS' laboratory information management platform. Focused on regulated environments including pharmaceutical QC and clinical labs.

- **[IDBS E-WorkBook](https://www.idbs.com/)**  
  Enterprise ELN for R&D organizations. Provides experiment capture, data analysis, and integration with IDBS' broader data management platform.

- **[CDD Vault](https://www.collaborativedrug.com/)**  
  Collaborative drug discovery platform with ELN capabilities. Provides chemical registration, assay data management, and experiment documentation for drug discovery teams.

- **[eLabNext](https://www.elabnext.com/)**  
  Digital lab platform combining ELN, LIMS, and inventory management. Provides experiment documentation, sample tracking, and workflow automation.

- **[Scispot](https://www.scispot.com/)**  
  Digital lab platform with ELN, LIMS, and automation capabilities. Designed for biotech and life sciences labs seeking integrated data management.

## Open-Source GitHub Projects

- **[eLabFTW](https://github.com/elabftw/elabftw)**  
  The most popular open-source electronic lab notebook for research labs. PHP-based, actively developed with a broad user base. Features structured experiment documentation (extra fields, resources, steps), embedding graphics, file attachments, relations/linked entries, tags, categories, full searchability, fine-grained permission control, teams and user groups, signing and timestamping of experiments, export/import, LIMS/inventory management with booking, QR codes for samples, and a comprehensive REST API . ~1,358 stars. **Open source**.

- **[Chemotion ELN](https://github.com/ComPlat/chemotion_ELN)**  
  Electronic Lab Notebook specifically designed for chemistry research. Provides structure drawing, reaction planning, and chemistry-aware data management .

- **[RSpace](https://github.com/rspace-os/rspace-web)**  
  Open-source research platform with ELN and sample management at its core. Released under AGPL v3 in June 2024. Features vertical interoperability with research tools (Galaxy, iRODS, Dataverse), API/SDK access, and FAIR data workflow support. Enterprise services available for deployment, migration, and support . **AGPL v3**.

- **[OpenBIS](https://github.com/openbis/openbis)**  
  Flexible ELN-LIMS and FAIR data management platform developed at ETH Zürich. Designed for academic labs requiring structured experiment tracking and FAIR-compliant research data management. Docker deployment supported, REST APIs with Java and Python clients . **Apache 2.0**.

- **[open_enventory](https://github.com/rudolphi/open_enventory)**  
  PHP/MySQL-based chemical inventory and Electronic Lab Notebook for chemistry labs. Free and open-source .

- **[Tulpa](https://github.com/tulpahq/tulpa)**  
  Open, extensible ELN & LIMS positioned as an open-source alternative to Benchling, LabStep, and Dotmatics. TypeScript-based .

- **[LabKey Server](https://github.com/LabKey/labkey)**  
  Web application for building and managing online databases and surveys. Strong for lab data management, sample tracking, analysis, and clinical data. Python, SQL, and JavaScript APIs. Docker deployment with docker-compose examples. Free and open-source .

- **[FAIRDOM-SEEK](https://github.com/FAIRDOM/seek)**  
  Web-based open-source platform for organizing and managing research (meta)data. Manages datasets, models, protocols, samples, and publications with full research lifecycle capture. ISAtools-based structure (Investigation-Study-Assay framework). DOI assignment, version tracking, and flexible sharing controls. **Open source** .

- **[MLZ ELN](https://github.com/MLZ-ELN)**  
  Electronic Lab Notebook based on TUM Workbench, developed for the Heinz Maier-Leibnitz Zentrum. Integrates with instrument control systems (NICOS), user office software (GhoST), and supports parallel editing capabilities. Under active development .

- **[Jekyll Lab Notebook](https://github.com/tlnagy/jekyll-lab-notebook)**  
  Full-featured electronic lab notebook theme with plugins for Jekyll. Static site generation approach for lab documentation. ~62 stars .

- **[LabInform](https://github.com/tillbiskup/labinform)**  
  Python components of a laboratory information system providing ELN functionality .

### Additional Strong Open-Source Options

- **Chemistry-Specific ELNs**: **Chemotion ELN** (structure-aware, chemistry-focused), **open_enventory** (chemical inventory + ELN) .
- **FAIR Data Platforms**: **OpenBIS** (ETH Zürich, FAIR-compliant), **FAIRDOM-SEEK** (ISA framework, DOI support) .
- **General-Purpose ELNs**: **eLabFTW** (most popular, actively developed), **RSpace** (open-sourced 2024, enterprise services) .
- **LIMS Integration**: **OpenBIS**, **LabKey** for combined ELN-LIMS workflows .

**Frameworks for building custom systems**: Combine **eLabFTW** for core ELN functionality, **OpenBIS** or **FAIRDOM-SEEK** for FAIR data management, **Chemotion ELN** for chemistry-specific needs, and **PostgreSQL** for persistence. Add **Docker** for deployment and **Galaxy/iRODS** integrations for computational workflows .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ELNs handle sensitive research data; ensure compliance with institutional data policies, funder mandates, and relevant regulations (21 CFR Part 11 for regulated environments).
- Self-hosted open-source solutions require proper security hardening, regular updates, and backup strategies. Open-source ELNs are mature but require institutional IT support for production deployments.

---

**Made for researchers, lab managers, data stewards, and scientific IT teams.**  
Let's make research data management more open, FAIR, and reproducible.
