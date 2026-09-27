# Data Dictionary

| Field | Meaning |
|---|---|
| `ID` | Unique sequential record identifier. Stable within this release. |
| `Research_Stream` | Literature stream used in the state-of-the-art mapping. Examples: gradient-based optimization, robust/adaptive objective design, learned road-network distance estimation. |
| `Year` | Publication year. Preprint year is used for preprints. |
| `Authors` | Author list as captured from the primary record. Semicolon-separated in the CSV. |
| `Title` | Publication title.  |
| `Publication_Status` | Publication type/status. Peer-reviewed article/conference paper, review, preprint, etc. |
| `Venue` | Journal, conference, proceedings, or repository.  |
| `DOI_or_ID` | DOI, arXiv ID, or other persistent identifier when available. May be blank if not verified. |
| `Source_URL` | Primary or authoritative source used for checking the record. Plain-text URL for auditability. |
| `Problem_Application` | Problem domain or engineering application.  |
| `Method_or_Model` | Main method, model, or algorithm family.  |
| `Optimization_or_Learning_Component` | Optimization/learning mechanism most relevant to the review.  |
| `Objective_Loss` | Loss/objective function or objective family. Uses 'Multiple' where a review spans many objectives. |
| `Adaptivity` | How the method adapts to data, gradients, model geometry, or structure.  |
| `Robustness_Focus` | Whether/how robustness, heavy tails, noise, contamination, or stability are addressed.  |
| `Evaluation_or_Scale` | Datasets, scale, evaluation setting, or metrics noted during extraction.  |
| `Code_Artifact_Status` | Availability of code, artifacts, or open-access implementation when verified. Not assumed when not checked. |
| `Evidence_Checked` | What source evidence was actually checked for the record. Used to avoid implying a full-text read when only metadata/abstract was checked. |
| `2219_Relevance` | Relevance classification used internally for WP1 synthesis. High, Medium, Medium-High, Low-Medium as applicable. |
| `D1_1_Use` | How the record contributes to the D1.1 state-of-the-art report.  |
| `Evidence_Review_Status` | Standardized review depth derived from Evidence_Checked. Full text/detailed source; abstract/metadata; benchmark + metadata; source record checked. |
| `Notes` | Additional qualification or caveat.  |
