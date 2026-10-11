# Reconstructing Scientific Peer-Review Trajectories

## A Version-Aware Corpus Construction Framework for Large Language Models

This repository provides the Python implementation of a methodological
framework for constructing a traceable, version-aware scientific
peer-review corpus from F1000Research.

The framework preserves relationships between manuscript versions,
reviewer reports, and author responses, supporting the reconstruction
of longitudinal scientific evaluation histories.

## Research Scope

The framework introduces two complementary representations:
- \*\*CanonicalPairs:\*\* Version-specific associations between manuscripts
&#x20; and reviewer reports.
- \*\*Knowledge Units:\*\* Structured representations that consolidate
&#x20; the documented peer-review history of individual publications.

## Corpus Construction Results

| Indicator | Result |
|---|---:|
| Articles assessed | 500 |
| Knowledge Units | 396 |
| Manuscript versions | 639 |
| Reviewer reports | 1,131 |
| CanonicalPairs | 1,131 |
| Author responses | 459 |
| Structural validation checks | 52 passed; 0 failed |

These results correspond to the corpus construction reported in the associated research manuscript.

## Implementation

The corpus construction pipeline was implemented in Python using
Google Colab.

The original implementation is preserved in: `F1000\_500.ipynb`

The notebook includes procedures for data acquisition, processing, knowledge representation, and structural validation.

## Reproducibility

The notebook corresponds to the implementation preserved for the reported research.
The original notebook has not been modified for public dissemination.

*\*SHA-256:\*\*
`410F624F4397CA69237E6901D191B24308A1D8C7D23F4174DBC771FF87E84D31`

The checksum identifies the preserved notebook and enables integrity verification.
Re-execution may produce different results if records or API responses from the external data source have changed.
The notebook was developed using Google Colab and requires access to Google Drive for file storage.

## Validation

The reported corpus passed 52 automated structural validation checks.
These checks assess structural consistency and do not establish semantic fidelity.

## Research Status
- Corpus construction: Completed
- Structural validation: Completed
- Semantic audit: Planned
- LLM training and evaluation: Not performed in this study

## Citation

If you use this software in academic research, please cite the
archived version of the original research implementation:

Velasco, J. L. (2026). *F1000Research corpus construction framework:
Original research implementation* (Version v1.0.0)
[Computer software]. Zenodo.
https://doi.org/10.5281/zenodo.23299613

The repository includes a CITATION.cff file containing
machine-readable citation metadata.

The DOI identifies the specific software version used in the
research, rather than the repository's subsequent updates.

## License

The original software developed for this project is distributed
under the Apache License, Version 2.0.

See the LICENSE file for the full license terms.

Copyright 2026 Jefferson Lewis Velasco.

The NOTICE file provides additional authorship and academic
attribution information.

The Apache 2.0 license permits use, modification, and redistribution
of the software, subject to its terms, including preservation of
applicable copyright and attribution notices.

Academic citation is requested as a matter of scholarly practice
but is not an additional legal requirement of the Apache 2.0 license.

**Third-party materials:** The software license does not automatically
extend to source publications, manuscript versions, reviewer reports,
author responses, or other third-party materials retrieved from
F1000Research. These materials remain subject to their respective
copyright and licensing conditions.

### Release Provenance

Version v1.0.0 represents the original research implementation
archived on Zenodo (DOI: 10.5281/zenodo.23299613).

The LICENSE, CITATION.cff, and NOTICE files were added to the
main branch after the original release to improve software
documentation, attribution, and licensing information.

These additions do not modify the original notebook or the
archived research implementation.

The original notebook is identified by the following SHA-256 checksum:
410F624F4397CA69237E6901D191B24308A1D8C7D23F4174DBC771FF87E84D31
