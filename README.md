# Open Access Database of Optimization Models and Related Learning Methods

This repository contains **Deliverable D1.2** of the TÜBİTAK 2219 research project
**“New Optimization Procedures in Machine Learning Algorithms.”**

**Researcher:** Elif Kozan  
**Host institution:** Lancaster University  
**Project period:** August 2025–July 2026  
**Repository:** https://github.com/elifkozanstat/2219-ml-optimization-literature-database  
**Release:** Version 1.0, September 2026

## Contents

- `data/D1_2_literature_database.csv` — canonical machine-readable database.
- `data/D1_2_literature_database.xlsx` — formatted workbook containing the database and supporting documentation.
- `docs/DATA_DICTIONARY.md` — definitions of database fields.
- `docs/SEARCH_STRATEGY.md` — scope, source preference, inclusion logic, and evidence-handling rules.
- `docs/DELIVERABLE_NOTE.md` — concise description of the deliverable.
- `metadata.json` — release metadata.
- `CITATION.cff` — citation metadata.

## Scope

The database contains **57 literature records** covering:

1. numerical and gradient-based machine-learning optimization;
2. robust and adaptive objective/loss design;
3. heuristic and metaheuristic optimization in engineering;
4. classical road-network shortest-path methods;
5. learned road-network distance indexes and embeddings; and
6. coordinate-/trajectory-based distance and travel-time estimation.

The database was prepared as a **structured state-of-the-art evidence base**.
It is not presented as a PRISMA systematic review or meta-analysis.

## Evidence handling

The fields `Evidence_Checked` and `Evidence_Review_Status` document the level of
source verification for each record. A record is not described as full-text
reviewed when only an abstract, bibliographic record, or official publication
page was checked.

Preprints are retained only when directly relevant or uniquely current and are
explicitly identified in `Publication_Status`.

## Relationship to WP1 outputs

- **D1.1** uses this database as the evidence base for the state-of-the-art synthesis.
- **D1.2** is this open and auditable literature database.
- **D1.3** provides a separate project-specific score-ranking framework.
- **D1.4** synthesizes methodological deficiencies identified from the evidence base.

The literature extraction is kept separate from the completed D1.3 evaluative scoring so that
D1.2 remains an auditable evidence database rather than a ranking table.

## Funding acknowledgement

This output was developed with support from the **Scientific and Technological
Research Council of Türkiye (TÜBİTAK)** under the **2219 International
Postdoctoral Research Fellowship Programme**.

## Citation

Citation metadata are provided in `CITATION.cff`.

## Version

Version 1.0 — September 2026.
