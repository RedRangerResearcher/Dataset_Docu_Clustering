# Dataset_Docu_Clustering
# Data Supplement: Multi-View Representation-Based Clustering of Judicial Documents

## Overview
This repository contains supplementary data for the manuscript **"Multi-View Representation-Based Clustering of Judicial Documents"** submitted to *Artificial Intelligence and Law*. It includes anonymized metadata for 170 Indian court cases analyzed in the study.

## Contents

### 1. Data Files
- **`anonymized_metadata.csv`**: Core dataset containing:
  - `case_id`: Anonymous identifier for each case (CASE_0001 to CASE_0170)
  - `neutral_citation`: Official legal citation for locating cases
  - `manupatra_id`: Database-specific identifier for Manupatra subscribers
  - `date`: Decision date (DD.MM.YYYY format)
  - `court`: Court name (Supreme Court/High Court)
  - `subjects`: Legal subjects/topics (semicolon-separated)
  - `acts_mentioned`: Relevant legislation cited
  - Additional legal metadata fields

- **`search_protocol.md`**: Detailed documentation of the exact search parameters and methodology used to construct this dataset on the Manupatra platform.

### 3. How to Use This Data

#### For Verification (with Manupatra access):
1. Use the `manupatra_id` field to locate exact cases in Manupatra
2. Follow the protocol in `search_protocol.md` to reconstruct the search

#### For Analysis (without database access):
1. Use `neutral_citation` fields to locate cases in public databases
2. The metadata enables replication of analytical findings reported in the paper

#### Column Definitions (for `anonymized_metadata.csv`):
| Column | Description | Example |
|--------|-------------|---------|
| `case_id` | Anonymous case identifier | CASE_0001 |
| `neutral_citation` | Official legal citation | 1998 INSC 6 |
| `manupatra_id` | Manupatra database identifier | MANU/SC/0016/1998 |
| `date` | Decision date | 07.01.1998 |
| `court` | Court name | Supreme Court of India |
| `subjects` | Legal subjects | Labour and Industrial; Service |
| `acts_mentioned` | Legislation cited | Employees' Provident Funds Act, 1952 |
| `disposition` | Case outcome | Appeal Dismissed |

### 4. Methodology
The dataset was constructed through systematic search on the Manupatra legal database. See `search_protocol.md` for complete methodological details including:
- Search query terms
- Date range filters
- Court selections
- Download and processing steps

### 5. Limitations and Notes
- **Does not contain full-text judgments** due to copyright restrictions
- Personal identifiers have been removed for ethical compliance
- Database access required to view full case texts
- Metadata accuracy verified through random sampling

### 6. Citation
If using this dataset, please cite:
> Multi-View Representation-Based Clustering of Judicial Documents. *Artificial Intelligence and Law* (under review). Data supplement available at: [Repository URL/DOI]

### 7. Contact
For questions about this dataset during peer review, please contact the journal editor. For post-publication inquiries, contact the corresponding author.

---

*This dataset has been prepared in accordance with Springer Nature's data sharing policy and research ethics guidelines for legal scholarship.*
