# Bibliographic Registry of the Corpus

This document provides the structured registry summary for the rapid review corpus, aligned with RRSE transparency and traceability reporting.

## Registry status summary

| Status | Count | Decision basis |
|---|---:|---|
| Included (evidence/reference) | 83 | Meets inclusion criteria and scope |
| Maybe (borderline) | 28 | Borderline relevance or unclear contribution at screening |
| Background (context only) | 10 | Schema discovery/inference/summarization context |
| Excluded | 1,018 | Out of scope or fails eligibility criteria |

## Decision reason codes

| Code | Description |
|---|---|
| IN1 | In-scope study on schema language, validation constraints, or integrity constraints for RDF/property graphs |
| MB1 | Borderline scope fit requiring additional interpretation |
| BG1 | Schema discovery/inference/summarization (kept as context, excluded from evidence synthesis) |
| EX1 | Out-of-scope domain/topic |
| EX2 | Not focused on schema/constraints/integrity mechanisms |
| EX3 | Non-peer-reviewed or insufficient publication metadata |
| EX4 | Duplicate or superseded record after deduplication |

## Data sources and provenance

| Data source | Records | Notes |
|---|---:|---|
| Scopus | 752 | Structured database query |
| ACM Digital Library | 398 | Structured database query |
| DBLP | 44 | Targeted keyword retrieval |

## Decision log groups

| ID range | Status | Reason | Class | Data source |
|---|---|---|---|---|
| R0001-R0083 | Included | IN1 | Semantic, shapes, dependencies | Scopus, ACM, DBLP |
| R0084-R0111 | Maybe | MB1 | Borderline mixed | Scopus, ACM, DBLP |
| R0112-R0121 | Background | BG1 | Discovery and summarization | Scopus, ACM, DBLP |
| R0122-R1139 | Excluded | EX1-EX4 | Out-of-scope or other | Scopus, ACM, DBLP |

## Related files in this appendix

- Screening/decision logs: `../data/rr_screening_log_deduped.csv`
- Included studies (preliminary list): `../data/rr_included_preliminary.csv`
- Borderline studies: `../data/rr_maybe_candidates.csv`
- Background studies: `../data/rr_background_from_search.csv`
- Bibliography: `../bibliography/rr_references.bib`, `../bibliography/rr_included_83.bib`
