# Online Appendix: Schema Languages and Integrity Constraints for Graph Databases

This repository is the online appendix for the rapid review manuscript:
**"Schema Languages and Integrity Constraints for Graph Databases: A Rapid Review."**

It follows transparent reporting principles used in **Rapid Reviews in Software Engineering (RRSE)**, with explicit artifacts for:

- screening and selection traceability,
- data extraction reproducibility,
- bibliographic provenance.

## Repository structure

```text
rapid_review_online_appendix/
├── README.md
├── bibliography/
│   ├── rr_included_83.bib
│   ├── rr_references.bib
│   └── rr_references_corrected_full.bib
├── data/
│   ├── rr_background_from_search.csv
│   ├── rr_data_extraction_filled.csv
│   ├── rr_data_extraction_template.csv
│   ├── rr_included_preliminary.csv
│   ├── rr_maybe_candidates.csv
│   └── rr_screening_log_deduped.csv
├── ontology/
│   ├── rr_ontology.ttl
│   └── visualization/
│       └── rr_ontology.pdf
└── docs/
    ├── rr_background_corpus.md
    ├── rr_bibliographic_registry.md
    ├── rr_methods_notes.md
    └── rr_prisma_counts.md
```

## Artifact map (RR workflow)

1. Search and screening trace:
   - `data/rr_screening_log_deduped.csv`
   - `data/rr_included_preliminary.csv`
   - `data/rr_maybe_candidates.csv`
   - `data/rr_background_from_search.csv`
2. Extraction protocol and coding:
   - `data/rr_data_extraction_template.csv`
   - `data/rr_data_extraction_filled.csv`
3. Study metadata and references:
   - `bibliography/rr_included_83.bib`
   - `bibliography/rr_references.bib`
   - `bibliography/rr_references_corrected_full.bib`
4. Method/reporting notes:
   - `docs/rr_methods_notes.md`
   - `docs/rr_prisma_counts.md`
   - `docs/rr_background_corpus.md`
   - `docs/rr_bibliographic_registry.md`
5. Ontology artifacts:
   - `ontology/rr_ontology.ttl`
   - `ontology/visualization/rr_ontology.pdf`

## Notes

- This appendix package is assembled from the working project files; original source files remain in their original locations.
- `rr_references.bib` and `rr_references_corrected_full.bib` are currently identical.
- Ontology artifacts include a machine-readable Turtle file and a PDF visualization.
