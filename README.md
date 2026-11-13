# Documentation Decay in Software Engineering: A Systematic Literature Review

Replication package for the systematic literature review by Bernard Barnieh and Alexander Wolf (COIS-5210H Advanced Topics in Software Engineering, Trent University, Fall 2026; instructor: Dr. Taher Ghaleb).

The review covers 74 peer-reviewed primary studies on documentation decay published between 2016 and 2026: 57 from database searches, 12 from one round of backward snowballing and 5 from one round of forward snowballing.

## Contents

1-search
- Search strings for IEEE Xplore, Scopus, and Web of Science.
- records_by_source.csv: records imported from each database (1,280 before deduplication).
- The strings for ACM Digital Library and ScienceDirect (initial round, 5 November 2026) and the shortened Springer Link string are described in Section 3.2 of the report.

2-screening
- Blind Screening Guide used for the calibration round.
- Calibration Results 2026-11-08.xlsx: results of the calibration round in which both researchers screened the same 50 records blind (Cohen's kappa 0.88). The individual calibration sheets are kept by the researchers and are not included.
- Forward Snowballing Results (Alexander).txt: the 12 candidates accepted on title and abstract in forward snowballing and the screening counts.

3-extraction
- Data Extraction Sheet - Docs Left Astray (Final).xlsx: extraction for every study assessed in full text, quality scores (QA1 to QA5), the verification sample, and the backward and forward snowballing decisions. The column "Ref. no. in report" matches the reference numbers in the report.
- Extraction Check - Instructions.docx: instructions used for the manual verification of 12 extractions. The check was done on a working copy of the extraction sheet, which is included here as the Final version.
- included_studies.csv: the 74 included studies with reference number, first author, year, venue, and DOI.

4-analysis
- PRISMA 2020 flow diagram.
- VOSviewer 1.6.21 map, network, scores, and thesaurus files, cluster terms, and the network, overlay, and density maps.
- Charts used in the report.
- DOIs of the 74 included studies (the URL for the one study without a DOI).

## Notes

- Full texts of the primary studies are not included because they are copyrighted by their publishers. All studies can be retrieved through the DOIs (or URL) listed in included_studies.csv.
- The VOSviewer corpus file (titles and abstracts) is not included for the same reason; it can be rebuilt from the DOIs.
- Generative AI (Claude, Anthropic) assisted with screening, extraction, and drafting under the researchers' supervision, as disclosed in Section 9 of the report.
