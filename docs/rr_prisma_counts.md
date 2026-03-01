# PRISMA-like counts (title/abstract/full-text assumed consistent)

Search sources (raw exports):

- Scopus: 752
- ACM DL: 398
- DBLP: 44
- Total (raw, merged): 1194

After deduplication (DOI if present; otherwise normalized title + year): **1139**

Screening outcomes (assumption: abstract and full text are consistent with titles):

- Include: 83
- Maybe: 28
- Exclude: 1018
- Marked as background due to schema discovery / summarization: 10

Notes:
- Because the present iteration assumes abstracts and full texts match the titles, we set `screen_abstract = screen_title` and `screen_fulltext = screen_title`.
- Records marked as background reflect schema discovery / summarization and are treated as context only (not part of the evidence set).
