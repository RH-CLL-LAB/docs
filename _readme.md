# DALYCARE Documentation Overview

## Diagnose_table_definitions.docx
**Date:** 2025-11-21  
**Size:** 114 KB  
**Description:** Detailed mapping of SNOMED morphology codes to ICD10 codes, rules for determining first diagnosis date across SDS, RKKP, SP, and Patobank, and conflict handling between sources.

## !_data_that_requires_written_work_permission_!.docx
**Date:** 2025-11-21  
**Size:** 19 KB  
**Description:** Lists datasets requiring explicit written permission to use, including daratumumab cohort, RH cohort, lenalidomide maintenance cohort, and ABCD cohort. Includes contact information.  

## DALYCARE DATABASE DOCUMENTATION.docx
**Date:** 2025-11-21  
**Size:** 199 KB  
**Description:** Full technical documentation of the DALYCARE PostgreSQL server environment, dataflow, pseudonymization, import workflows, QC processes, core database structure, best practices, and SOP for pseudonymization and import.

## dalycare package - all functions.pdf
**Date:** 2025-11-21  
**Size:** 480 KB  
**Description:** R package reference manual for the `dalycare` package. Includes all cleaner, loader, definer, and analysis helper functions such as diagnosis filtering, AKI detection, infections, comorbidity scoring, and ERIC export.

## DALYCARE_NAMING_CONVENTIONS.pdf
**Date:** 2025-11-21  
**Size:** 194 KB  
**Description:** Naming conventions for variables, tables, and cleaned datasets across IMPORT and CORE schemas. Defines prefixes (ICD10_, ATC_, SNOMED_, NPU_), date/time rules, and treatment line suffixes.

## DALYCARE_tables_views_by_function.docx
**Date:** 2025-11-21  
**Size:** 26 KB  
**Description:** Describes all tables and views divided by category (diagnoses, treatments, labs, administrative registers) and the logic behind each category. Complements database_schema_column_datatype.

## SDS_DATADICTIONARY_and_agreement_DK.pdf
**Size:** 603 KB  
**Date:** 2025-11-21  
**Description:** SDS data dictionary and agreement document describing structure, variables, formats, and permissions for SDS datasets used in DALY-CARE.

## Diagnose_table_definitions.docx
**Size:** 114 KB  
**Date:** 2025-11-21  
**Description:** Detailed logic for determining first diagnosis date across RKKP, SDS, SP, and Patobank. Includes large SNOMED→ICD10 conversion table. fileciteturn1file1

## Figure_S1 - t_dalycare_diagnoses.pdf
**Size:** 36 KB  
**Date:** 2025-11-21  
**Description:** Diagram of diagnosis ingestion workflow: RKKP, SDS, SP, Patobank → cleaned codes → DALY‑CARE ICD10 set → final t_dalycare_diagnoses. fileciteturn1file2

## Figure_S2 - patient.pdf
**Size:** 27 KB  
**Date:** 2025-11-21  
**Description:** Diagram showing logic for determining date_death, status, date_last_FU, and date_death_fu using RKKP, SDS, SP and t_doedsarsag_2. fileciteturn1file3

## Github upload quickguide.pdf
**Size:** 140 KB  
**Date:** 2025-11-21  
**Description:** Visual step‑by‑step guide for GitHub login, 2FA, creating repositories, and uploading files. fileciteturn1file4

## Guideline for Submitting and Working with data on the NGC cloud_2023-07-26.pdf
**Size:** 832 KB  
**Date:** 2025-11-21  
**Description:** Official guideline for working with NGC data: user accounts, project workflows, RStudio use, sFTP upload/download, data export rules, and database connection examples. fileciteturn1file5

## Quick guide_WIP220124.docx
**Size:** 20 KB  
**Date:** 2025-11-21  
**Description:** Condensed naming‑convention cheat‑sheet for the NGC system: dataset naming format, variable naming rules (patientid, date_*, ICD10_*, SNOMED_*). fileciteturn1file6

