# Moksha Shrivastava

Clinical Research student developing practical projects in **Clinical Data Management (CDM) & Clinical-tech** to demonstrate industry-relevant skills.

## Focus Areas
- Clinical Data Management
- CDISC (CDASH & SDTM)
- Clinical data validation
- Python automation
- Documentation (CRF, eCRF)
- Clinical & Statistical programming

## Featured Projects
### Clinical Trial Validator — Edit Check Framework (VAERS)
Applied a clinical data management edit-check framework to 40,806 records from the 2025 VAERS (Vaccine Adverse Event Reporting System) dataset to assess completeness, validity, and data integrity.
- Designed **12 edit checks** across 5 quality dimensions (completeness, range, date logic, controlled terminology, referential integrity), aligned to **GCDMP** and **ICH E6(R2)** principles
- Generated **9,638 queries with 23.62% query rate** — plausible given VAERS's known data-completeness issues as a passive, voluntary reporting system; largest single issue was missing vaccination date (6,692 records, EC007) — highlighting one field-level gap rather than broad dataset quality failure
- Deliverables: edit check specification, query report (CSV), summary report (Excel)
- Repo Link: https://github.com/Moksha-Shrivastava/ClinicalTrialValidator

### Protocol-to-CRF Study Startup
Simulated a pre-EDC study startup package by converting a publicly available clinical trial protocol into CDM documentation.
- Source protocol: **PROBES trial (NCT05586724)**, a double-blind RCT on menopausal hormone therapy safety
- Built Schedule of Assessments, 11 CRFs with inline CDASH-annotated fields, CRF metadata specification, and a Requirements Traceability Matrix linking every protocol requirement to its CRF/field
- Disclaimer: Simulated exercise based on a publicly available protocol; _no patient data used_
- Repo Link: https://github.com/Moksha-Shrivastava/Protocol-to-CRF-Study-Startup

### SDTM Mapping — NHANES to CDISC Domains
Transformed NHANES 2017–2018 public health survey data into CDASH-aligned, SDTM-compliant domains.
- Mapped data into **DM (Demographics)**, **VS (Vital Signs)**, and **LB (Laboratory)** domains per CDISC SDTM standards
- Known limitation: NHANES combines race/ethnicity in a single variable (RIDRETH3) — not separately mapped to SDTM's ETHNIC variable and NHANES is a survey data, not trial data — no visit structure or protocol-defined assessment windows
- Repo link: https://github.com/Moksha-Shrivastava/SDTM_Mapping

## Currently Learning
- SAS
- SDTM implementation
- REDCap workflows
- Clinical database design

## Connect
- LinkedIn: https://www.linkedin.com/in/moksha-s-9b893b323
