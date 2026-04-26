# Awesome Compliance [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome resources for Governance, Risk Management, and Compliance (GRC) professionals.

This list is intended for **compliance officers, risk managers, auditors, and cybersecurity professionals** or for **people with a compliance need** who need trusted resources for **ISO 27001, SOC 2, SOX, ESG compliance, and more**.

## Contents

- [Frameworks & Standards](#frameworks--standards)
  - [Security & Privacy](#security--privacy)
  - [ESG & Sustainability](#esg--sustainability)
  - [Financial & Corporate](#financial--corporate)
  - [Quality & Assurance](#quality--assurance)
  - [Risk Management](#risk-management)
- [Legislative & Regulatory](#legislative--regulatory)
  - [Privacy Legislation](#privacy-legislation)
  - [EU Cybersecurity & AI Regulations](#eu-cybersecurity--ai-regulations)
- [Tools & Platforms](#tools--platforms)
  - [Open Source Platforms](#open-source-platforms)
  - [Commercial Platforms](#commercial-platforms)
  - [Compliance Specifications & Resources](#compliance-specifications--resources)


## Frameworks & Standards

### Security & Privacy

- [SOC Reports (SOC 1/2/3)](https://www.aicpa.org/soc) - AICPA Service Organization Control reports. SOC 1 for financial reporting controls, SOC 2 for security/availability/confidentiality/processing integrity/privacy controls, SOC 3 for public distribution.
- [ISO/IEC 27001](https://www.iso.org/isoiec-27001-information-security.html) - International standard for establishing an Information Security Management System (ISMS). Requires annual certification audits.
- [ISO/IEC 27002](https://www.iso.org/standard/75652.html) - Implementation guidance for ISO 27001 controls.
- [ISO/IEC 27017](https://www.iso.org/standard/43757.html) - Cloud security controls based on ISO 27002.
- [ISO/IEC 27018](https://www.iso.org/standard/76559.html) - Code of practice for protecting personally identifiable information in public cloud.
- [ISO/IEC 27701](https://www.iso.org/standard/71670.html) - Privacy Information Management System (PIMS) extension to ISO 27001.
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework) - Voluntary risk-based model for managing cybersecurity risk (Identify, Protect, Detect, Respond, Recover).
- [NIST Risk Management Framework](https://csrc.nist.gov/projects/risk-management) - Framework for integrating security and risk management into system development lifecycle.
- [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) - Security and privacy controls for federal information systems and organizations. Widely adopted beyond government.
- [NIST SP 800-171](https://csrc.nist.gov/publications/detail/sp/800-171/rev-2/final) - Protecting Controlled Unclassified Information in nonfederal systems.
- [NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework) - AI Risk Management Framework for trustworthy AI development and deployment.
- [NIST SP 800-82](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-82r3.pdf) - Guide to Industrial Control Systems (ICS) Security for operational technology environments.
- [NIST SP 800-160](https://csrc.nist.gov/publications/detail/sp/800-160/final) - Systems Security Engineering for developing trustworthy secure systems.
- [NIST SP 800-161](https://csrc.nist.gov/publications/detail/sp/800-161/rev-1/final) - Cybersecurity Supply Chain Risk Management Practices for Systems and Organizations.
- [NIST SP 800-172](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-172.pdf) - Enhanced Security Requirements for Protecting Controlled Unclassified Information.
- [NIST SP 800-218](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-218.pdf) - Secure Software Development Framework (SSDF) for integrating security into SDLC.
- [NIST SP 800-63B](https://pages.nist.gov/800-63-3/sp800-63b.html) - Digital Identity Guidelines for authentication and lifecycle management.
- [NIST SP 800-66](https://csrc.nist.gov/pubs/sp/800/66/r2/final) - Implementing the Health Insurance Portability and Accountability Act (HIPAA) Security Rule.
- [NIST Privacy Framework](https://www.nist.gov/privacy-framework) - Tool for improving privacy risk management.
- [PCI DSS](https://www.pcisecuritystandards.org/) - Payment Card Industry Data Security Standard. Required for handling credit card data. Version 4.0 emphasizes continuous compliance.
- [HIPAA](https://www.hhs.gov/hipaa/index.html) - US Health Insurance Portability and Accountability Act. Mandates safeguards for protected health information.
- [HITRUST CSF](https://hitrustalliance.net/hitrust-csf/) - Common certifiable framework combining HIPAA, NIST, ISO, and other requirements for healthcare.
- [HICP](https://www.phe.gov/Preparedness/planning/405d/Pages/hic-practices.aspx) - Health Industry Cybersecurity Practices for healthcare organizations (small, medium, and large practice guidance).
- [FedRAMP](https://www.fedramp.gov/) - Federal Risk and Authorization Management Program. Required for cloud services used by US federal agencies based on NIST 800-53.
- [CMMC](https://www.acq.osd.mil/cmmc/) - Cybersecurity Maturity Model Certification for US DoD contractors. Version 2.0 streamlines requirements.
- [FISMA](https://www.cisa.gov/federal-information-security-modernization-act) - Federal Information Security Modernization Act for US federal agency information security.
- [StateRAMP](https://www.stateramp.org/) - Standardized approach to cloud security for US state and local governments.
- [FERPA](https://www2.ed.gov/policy/gen/guid/fpco/ferpa/index.html) - Family Educational Rights and Privacy Act protecting student education records.
- [Microsoft SSPA](https://www.microsoft.com/en-us/securityengineering/sdl/) - Microsoft Security Software Privacy Assurance framework.
- [CIS Controls](https://www.cisecurity.org/controls) - Center for Internet Security 18 Critical Security Controls (formerly 20).
- [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks) - Configuration security benchmarks for systems and applications.
- [CSA Cloud Controls Matrix](https://cloudsecurityalliance.org/research/cloud-controls-matrix) - Cloud Security Alliance control framework for cloud computing.
- [MITRE ATT&CK](https://attack.mitre.org/) - Knowledge base of adversary tactics and techniques based on real-world observations.
- [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/) - Application Security Verification Standard.
- [CPS234](https://www.apra.gov.au/information-security) - Australian Prudential Regulation Authority information security requirements.
- [CISA](https://www.cisa.gov/) - Cybersecurity Information Sharing Act and CISA agency resources.
- [NERC CIP](https://www.nerc.com/pa/Stand/Pages/CIPStandards.aspx) - North American Electric Reliability Corporation Critical Infrastructure Protection standards.
- [CJIS](https://www.fbi.gov/services/cjis/cjis-security-policy-resource-center) - Criminal Justice Information Services Security Policy.
- [Secure Control Framework](https://securecontrolsframework.com/scf-download/) - Comprehensive control framework with mappings across multiple standards and regulations.
- [NIST National Online Informative References Program (OLIR)](https://csrc.nist.gov/projects/olir) - Machine-readable mappings between NIST frameworks and other standards.
- [Adobe Common Controls Framework](https://www.adobe.com/trust/compliance/adobe-ccf.html) - Adobe's unified control framework for compliance.
- [Equifax Security Controls Framework](https://controlsframework.equifax.com/home) - Equifax's control framework with mappings to major standards.
- [CIS Controls Navigator](https://www.cisecurity.org/controls/cis-controls-navigator) - Tool for navigating and implementing CIS Controls.
- [MITRE NIST 800-53 to ATT&CK Mappings](https://mitre-engenuity.org/cybersecurity/center-for-threat-informed-defense/our-work/nist-800-53-control-mappings/) - Maps NIST security controls to adversary techniques.
- [NIST AI RMF Crosswalks](https://airc.nist.gov/AI_RMF_Knowledge_Base/Crosswalks) - Mappings between AI RMF and other frameworks, standards, and regulations.
- [CSF Tools](https://csf.tools/) - Tools and resources for implementing the NIST Cybersecurity Framework.

### ESG & Sustainability

- [B Corp Certification](https://www.bcorporation.net/) - Certification for companies meeting high standards of social and environmental performance.
- [CDP](https://www.cdp.net/) - Carbon Disclosure Project for environmental impact reporting.
- [GRI Standards](https://www.globalreporting.org/) - Global Reporting Initiative for sustainability reporting.
- [ISO 14001](https://www.iso.org/iso-14001-environmental-management.html) - Environmental Management Systems.
- [ISO 45001](https://www.iso.org/iso-45001-occupational-health-and-safety.html) - Occupational Health and Safety Management Systems.
- [ISO 50001](https://www.iso.org/iso-50001-energy-management.html) - Energy Management Systems.
- [SASB Standards](https://www.sasb.org/) - Sustainability Accounting Standards Board standards for ESG disclosure.
- [TCFD](https://www.fsb-tcfd.org/) - Task Force on Climate-related Financial Disclosures recommendations.
- [UN SDGs](https://sdgs.un.org/) - United Nations Sustainable Development Goals.

### Financial & Corporate

- [SOX](https://www.congress.gov/bill/107th-congress/house-bill/3763) - Sarbanes-Oxley Act for financial reporting and corporate governance.
- [SOX ITGC](https://www.aicpa.org/) - IT General Controls for Sarbanes-Oxley compliance.
- [Basel Framework](https://www.bis.org/basel_framework/) - International banking regulations on capital adequacy, stress testing, and market liquidity.
- [FCRA](https://www.ftc.gov/legal-library/browse/statutes/fair-credit-reporting-act) - Fair Credit Reporting Act regulating credit information collection and use.
- [IFRS](https://www.ifrs.org/) - International Financial Reporting Standards for accounting and financial reporting.
- [GLBA](https://www.ftc.gov/business-guidance/privacy-security/gramm-leach-bliley-act) - Gramm-Leach-Bliley Act requiring financial institutions to protect customer information.
- [NYDFS](https://www.dfs.ny.gov/industry_guidance/cyber_regulations) - New York Department of Financial Services Cybersecurity Regulation (23 NYCRR 500).
- [SWIFT CSF](https://www.swift.com/myswift/customer-security-programme-csp/security-controls) - SWIFT Customer Security Controls Framework for financial messaging and payment systems.
- [FFIEC](https://www.ffiec.gov/pdf/cybersecurity/FFIEC_CAT_App_B_Map_to_NIST_CSF_June_2015_PDF4.pdf) - Federal Financial Institutions Examination Council cybersecurity assessment tool.
- [FINRA](http://www.finra.org/industry/cybersecurity) - Financial Industry Regulatory Authority cybersecurity requirements for broker-dealers.
- [SAMA CSF](https://www.sama.gov.sa/en-US/Laws/FinanceRules/SAMA%20Cyber%20Security%20Framework%20v1.0%20final_updated.pdf) - Saudi Arabian Monetary Authority Cyber Security Framework for financial sector.
- [EBA ICT Guidelines](https://www.eba.europa.eu/regulation-and-policy/internal-governance/guidelines-on-ict-and-security-risk-management) - European Banking Authority ICT and security risk management guidelines.
- [OFDSS](https://www.ofdss.org/) - Office of Federal Student Aid Security Standards.

### Quality & Assurance

- [ISO 9001](https://www.iso.org/iso-9001-quality-management.html) - Quality Management Systems standard.
- [AS9100](https://www.sae.org/standards/content/as9100d/) - Quality management for aerospace industry.
- [ISO 13485](https://www.iso.org/standard/59752.html) - Quality management for medical devices.
- [ISO 22000](https://www.iso.org/iso-22000-food-safety-management.html) - Food Safety Management Systems.
- [ISO/TS 16949](https://www.iso.org/standard/52844.html) - Quality management for automotive industry (superseded by IATF 16949).
- [ISO 22301](https://www.iso.org/standard/75106.html) - Security and resilience business continuity management systems requirements.
- [cGMP](https://www.fda.gov/drugs/pharmaceutical-quality-resources/current-good-manufacturing-practice-cgmp-regulations) - Current Good Manufacturing Practice for pharmaceuticals.
- [FDA 21 CFR Part 11](https://www.gpo.gov/fdsys/pkg/CFR-2012-title21-vol1/pdf/CFR-2012-title21-vol1-part11.pdf) - Electronic records and electronic signatures in FDA-regulated industries.
- [IEC TR 60601-4-5](https://webstore.iec.ch/publication/64703) - Medical electrical equipment cybersecurity requirements.
- [IEC 62443-4-2](https://webstore.iec.ch/publication/34421) - Security for industrial automation and control systems technical requirements.
- [ISO/SAE 21434](https://www.iso.org/standard/70918.html) - Road vehicles cybersecurity engineering standard.
- [UN R155](https://unece.org/transport/documents/2021/03/standards/un-regulation-no-155-cyber-security-and-cyber-security) - UN Regulation cybersecurity and cyber security management system for vehicles.
- [TISAX](https://portal.enx.com/en-us/TISAX/downloads/) - Trusted Information Security Assessment Exchange for automotive industry information security assessment.
- [ITIL](https://www.axelos.com/certifications/itil-service-management) - Information Technology Infrastructure Library for IT service management.
- [COBIT](https://www.isaca.org/resources/cobit) - Control Objectives for Information and Related Technologies governance framework.
- [ISO 42001](https://www.iso.org/standard/81230.html) - AI Management System standard.

### Risk Management

- [COSO ERM](https://www.coso.org/Pages/erm.aspx) - Committee of Sponsoring Organizations Enterprise Risk Management framework.
- [FAIR](https://www.fairinstitute.org/) - Factor Analysis of Information Risk, quantitative risk analysis framework.
- [ISO 27005](https://www.iso.org/standard/75281.html) - Information security risk management.
- [ISO 31000](https://www.iso.org/iso-31000-risk-management.html) - Risk management guidelines and principles.
- [NIST SP 800-37](https://csrc.nist.gov/publications/detail/sp/800-37/rev-2/final) - Risk Management Framework for Information Systems.
- [NIST SP 800-39](https://csrc.nist.gov/publications/detail/sp/800-39/final) - Managing Information Security Risk: Organization, Mission, and Information System View.
- [OCTAVE](https://www.cmu.edu/sei/our-work/projects/display.cfm?customel_datapageid_4050=21281) - Operationally Critical Threat, Asset, and Vulnerability Evaluation by Carnegie Mellon.
- [Rapid Risk Assessment](https://infosec.mozilla.org/guidelines/risk/rapid_risk_assessment) - Mozilla's lightweight risk assessment methodology.
- [TARA](https://www.mitre.org/publications/technical-papers/threat-assessment-and-remediation-analysis-tara) - Threat Assessment and Remediation Analysis by MITRE.

## Legislative & Regulatory

### Privacy Legislation

- [IAPP US Federal Privacy Legislation Tracker](https://iapp.org/resources/article/us-federal-privacy-legislation-tracker/) - Comprehensive tracking of 50+ federal privacy bills in the 118th Congress (2023-2024).
- [IAPP US State Privacy Legislation Tracker](https://iapp.org/resources/article/us-state-privacy-legislation-tracker/) - Comprehensive tracking of state privacy legislation across all US states.
- [CCPA/CPRA](https://oag.ca.gov/privacy/ccpa) - California Consumer Privacy Act and California Privacy Rights Act. Comprehensive consumer privacy rights including data deletion, opt-out, and transparency requirements.
- [Virginia CDPA](https://law.lis.virginia.gov/vacodefull/title59.1/chapter53/) - Virginia Consumer Data Protection Act establishing consumer privacy rights and business obligations.
- [Colorado CPA](https://leg.colorado.gov/bills/sb21-190) - Colorado Privacy Act providing consumer data privacy rights similar to CCPA.
- [GDPR](https://gdpr.eu/) - EU General Data Protection Regulation governing personal data protection. Self-attestation via Data Protection Officer with demonstrated compliance.
  - [GDPR-info.eu](https://gdpr-info.eu/) - Complete GDPR text with recitals and commentary.
  - [GDPR Expert](https://www.gdpr-expert.com/) - GDPR compliance resources.
  - [GDPRhub](https://gdprhub.eu/) - Free and open database of GDPR case law.

### EU Cybersecurity & AI Regulations

- [NIS2 Directive](https://digital-strategy.ec.europa.eu/en/policies/nis2-directive) - EU Network and Information Security Directive establishing cybersecurity requirements for critical infrastructure and digital services.
- [EU DORA](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32022R2554&from=EN) - Digital Operational Resilience Act for financial sector ICT risk management in the EU.
- [ePrivacy Directive](http://ec.europa.eu/newsroom/dae/document.cfm?doc_id=41241) - EU directive on privacy and electronic communications (under revision).
- [ENISA Guidelines](https://resilience.enisa.europa.eu/article-13/guideline-for-minimum-security-measures/Article_13a_ENISA_Technical_Guideline_On_Security_Measures_v2_0.pdf) - European Union Agency for Network and Information Security technical guidelines and security measures.
- [EU AI Act](https://artificialintelligenceact.eu/) - Comprehensive AI regulation with risk-based approach, prohibitions on high-risk uses, and transparency requirements. First comprehensive AI law globally.
- [Systima Comply](https://github.com/systima-ai/comply) - Open-source EU AI Act compliance scanner for CI/CD pipelines. AST-based detection of 37+ AI/ML frameworks with call-chain tracing and obligation checking against Articles 5-50. Ships as CLI, GitHub Action, and TypeScript API. Apache 2.0 licensed.
- [AIR Blackbox](https://github.com/airblackbox/gateway) - Open-source EU AI Act compliance scanner and runtime trust layer for Python AI agents. 39 checks across Articles 9-15 with HMAC-SHA256 tamper-evident audit chains, PII detection, and prompt injection blocking. Trust layers for LangChain, CrewAI, AutoGen, OpenAI, Google ADK, and Claude Agent SDK. Ships as CLI, MCP server, and GitHub Action. Apache 2.0 licensed. ([Website](https://airblackbox.ai) | [PyPI](https://pypi.org/project/air-blackbox/))
- [NeuralFlow](https://github.com/omergili/neuralflow) - Open-source EU AI Act Article 50 transparency toolkit. Adds machine-readable (JSON-LD, meta tags) and human-visible AI disclosure to websites with a single script tag. Ships as npm package (`@neuralflow/ai-act`), CLI, and WordPress plugin. 5.1 KB, zero dependencies. MIT licensed. ([npm](https://www.npmjs.com/package/@neuralflow/ai-act) | [Website](https://neuralflow.mylurch.com))

## Tools & Platforms

### Open Source Platforms

- [Openlane](https://www.theopenlane.io/) - Comprehensive compliance automation platform for SOC 2, ISO 27001, and custom frameworks (Apache-2.0). Transforms compliance from static annual process to continuous collaborative workflow with risk register, policy management, evidence lifecycle, and control validation. ([GitHub](https://github.com/theopenlane) | [Docs](https://docs.theopenlane.io/))
- [SOC 2 Reliability Guild](https://s2guild.org/) - A community creating standardized evaluation criteria to help GRC and TPRM practitioners assess how much weight to give a SOC 2 report when making vendor trust decisions. ([GitHub](https://github.com/SOC-2-Quality-Guild/s2guild.org))
- [Comply](https://github.com/strongdm/comply) - SOC 2 compliance automation framework by StrongDM (Apache-2.0). Provides markdown-based policy templates and document pipeline for auditor-ready policies.
- [Compliance Masonry](https://github.com/opencontrol/compliance-masonry) - CLI tool to build compliance documentation using OpenControl YAML schema. Supports FedRAMP, NIST, and other frameworks.
- [Asqav](https://github.com/jagmarques/asqav-sdk) - Open-source SDK for AI agent governance with tamper-evident audit trails, tool scanning, and enforcement policies (MIT). Designed for teams running AI agents in production who need compliance-ready logging and control.
- [Auditree Framework](https://github.com/ComplianceAsCode/auditree-framework) - IBM's framework for automated evidence collection and verification (Apache-2.0). Treats compliance checks as code with version-controlled evidence locker.
- [Trestle](https://github.com/IBM/compliance-trestle) - IBM's compliance-as-code toolset using NIST's OSCAL format. Manages compliance catalogs and automates documentation generation.
- [InSpec](https://www.inspec.io/) - Chef's compliance and security testing framework. Write automated compliance tests in Ruby DSL with pre-built profiles for CIS, DISA STIGs.
- [OpenSCAP](https://www.open-scap.org/) - Security Content Automation Protocol toolset for automated system scanning against SCAP benchmarks (Red Hat sponsored).
- [Lynis](https://cisofy.com/lynis/) - Security auditing tool for Unix/Linux systems. Performs host configuration scans and generates hardening reports.
- [Cloud Custodian](https://cloudcustodian.io/) - CNCF Sandbox rules engine for cloud compliance. Write policies in YAML to enforce and remediate violations in AWS, Azure, GCP.
- [Prowler](https://github.com/prowler-cloud/prowler) - AWS security and compliance scanner. Checks against AWS CIS Benchmark, GDPR, HIPAA, PCI DSS, SOC 2.
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite) - Multi-cloud security auditing tool by NCC Group. Detects misconfigurations in AWS, Azure, GCP.
- [Steampipe](https://steampipe.io/) - Query cloud and SaaS APIs as SQL tables. Includes compliance mod packs for CIS AWS Foundations, HIPAA, PCI.
- [PacBot](https://github.com/tmobile/pacbot) - T-Mobile's cloud compliance platform. Continuously monitors AWS for violations with auto-remediation capabilities.
- [OSQuery](https://osquery.io/) - Endpoint monitoring using SQL queries (Linux Foundation). Query running processes, configurations, and compliance-related data across fleet.
- [Wazuh](https://wazuh.com/) - Open source security platform with SIEM and HIDS capabilities. Provides compliance rule sets for PCI DSS, GDPR, HIPAA with reporting.
- [CISO Assistant](https://github.com/intuitem/ciso-assistant-community) - Open-source GRC app supporting 40+ frameworks. Manages risks, controls, audits with one-click audit reports.
- [Comp AI](https://github.com/trycompai/comp) - Open source compliance platform (AGPL-3.0) for SOC 2, ISO 27001, HIPAA, GDPR.
- [Eramba](https://www.eramba.org/) - Enterprise GRC platform with free Community Edition. Modules for compliance, risk management, incidents, vendor assessments.
- [Trivy](https://github.com/aquasecurity/trivy) - Comprehensive security scanner for containers and IaC. Detects vulnerabilities, misconfigurations, secrets.
- [kube-bench](https://github.com/aquasecurity/kube-bench) - Checks Kubernetes clusters against CIS Kubernetes Benchmark.
- [Kyverno](https://kyverno.io/) - Kubernetes-native policy management. Enforce, validate, and mutate configurations.
- [OPA Gatekeeper](https://open-policy-agent.github.io/gatekeeper/) - Policy controller for Kubernetes using Open Policy Agent.
- [Havengrc](https://havengrc.com/) - Open-source GRC platform for compliance management.
- [GGRC Core](https://github.com/google/ggrc-core) - Google's governance, risk, and compliance platform (archived but historically significant).
- [Govready](https://github.com/GovReady/govready-q) - Open-source GRC platform for automated compliance assessments.
- [Probo](https://github.com/ProboCI/probo) - Open source compliance automation focused on continuous integration workflows.
- [Venturalitica SDK](https://github.com/Venturalitica/venturalitica-sdk) - Open-source Python SDK (Apache-2.0) for EU AI Act and ISO 42001 compliance evidence generation from ML training pipelines. Produces OSCAL Assessment Results, CycloneDX ML BOM, bias audits, and Annex IV technical documentation as a byproduct of model training.

### Commercial Platforms

- [Drata](https://drata.com/) - Cloud platform for continuous compliance monitoring and automation. Connects to tech stack for evidence collection. Supports SOC 2, ISO 27001, PCI DSS.
- [Vanta](https://www.vanta.com/) - Compliance automation platform for SOC 2, ISO 27001. Continuous monitoring with AI-powered questionnaire responses.
- [Secureframe](https://secureframe.com/) - End-to-end compliance platform for SOC 2, ISO 27001, HIPAA. Includes policy templates, evidence collection, training, auditor coordination.
- [Tugboat Logic](https://www.onegrc.com/) - Security assurance platform now part of OneTrust. Automated evidence collection and audit project management.
- [Tenable](https://www.tenable.com/) - Cloud-based and On-prem vulnerability and exposure management.
- [Hyperproof](https://hyperproof.io/) - Compliance operations platform for ongoing risk and compliance management. Workflow automation and continuous control monitoring.
- [Sprinto](https://sprinto.com/) - Automated compliance platform for SOC 2, ISO 27001, GDPR, HIPAA.
- [Oneleet](https://oneleet.com/) - Continuous compliance monitoring and automation platform.
- [Scrut](https://scrut.io/) - Automated compliance platform with integrations for real-time monitoring.
- [Thoropass](https://thoropass.com/) - Information security and compliance software.
- [AuditBoard](https://www.auditboard.com/) - Leading platform for audit and compliance management. One-stop solution for managing audits, controls, risks, and reporting.
- [Archer](https://www.archerirm.com/) - RSA's GRC platform widely used in enterprises.
- [LogicGate](https://www.logicgate.com/) - Risk Cloud platform tailored for IT Risk, Compliance, Third-Party Risk.
- [MetricStream](https://www.metricstream.com/) - Enterprise GRC platform for integrated risk management.
- [Onspring](https://onspring.com/) - No-code GRC platform for risk, compliance, and audit management.
- [OneTrust](https://www.onetrust.com/) - Privacy, security, and data governance platform. Extensive GRC suite including Vendorpedia.
- [ServiceNow GRC](https://www.servicenow.com/products/governance-risk-compliance.html) - Integrated risk and compliance management on ServiceNow platform.
- [TrustCloud](https://trustcloud.ai/) - GRC platform with free trust center offering. Compliance tracking with integrations. (Freemium)
- [Benchmark ESG](https://www.benchmarkesg.com/) - ESG data management and reporting platform.
- [Diligent ESG](https://www.diligent.com/solutions/esg) - ESG governance and reporting solution.
- [Locus Technologies](https://www.locustec.com/) - Environmental, health, safety, and sustainability management software.
- [Novata](https://www.novata.com/) - ESG data management for private markets.
- [Novisto](https://www.novisto.com/) - ESG reporting automation platform.
- [Proof](https://www.proof.com/) - ESG performance management platform.
- [Sametrica](https://www.sametrica.com/) - ESG impact measurement software.
- [Workiva](https://www.workiva.com/) - Cloud platform for ESG, financial, and compliance reporting.

### Compliance Specifications & Resources

- [AWS Artifact](https://aws.amazon.com/artifact/) - Access AWS compliance reports (SOC, ISO, PCI, etc.).
- [Azure Compliance](https://learn.microsoft.com/en-us/azure/compliance/) - Microsoft Azure compliance documentation and reports.
- [GCP Compliance](https://cloud.google.com/security/compliance) - Google Cloud compliance resources and certifications.
- [OpenRegistry](https://openregistry.sophymarine.com) - Real-time MCP-server access to 27 national company registries for KYC / UBO / cross-border due-diligence. Includes UK Companies House, France RNE, Germany Handelsregister, Italy InfoCamere via BRIS, Spain BORME, Korea OpenDART, and 21 others.
- [Unified Compliance Framework](https://www.unifiedcompliance.com/) - Common Controls Hub with 1000+ mapped authorities (Commercial).
- [NIST OSCAL](https://pages.nist.gov/OSCAL/) - Open Security Controls Assessment Language for machine-readable compliance.
- [OpenControl](http://open-control.org/) - YAML-based compliance documentation framework.
- [ComplianceForge](https://www.complianceforge.com/) - Commercial policy libraries and toolkits for multiple frameworks.
- [Regulations.gov](https://www.regulations.gov/) - US federal regulations repository.

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
