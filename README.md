\# Reconstructing Scientific Peer-Review Trajectories



\## A Version-Aware Corpus Construction Framework for Large Language Models



This repository provides the Python implementation of a methodological

framework for constructing a traceable, version-aware scientific

peer-review corpus from F1000Research.



The framework preserves relationships between manuscript versions,

reviewer reports, and author responses, supporting the reconstruction

of longitudinal scientific evaluation histories.



\## Research Scope



The framework introduces two complementary representations:



\- \*\*CanonicalPairs:\*\* Version-specific associations between manuscripts

&#x20; and reviewer reports.

\- \*\*Knowledge Units:\*\* Structured representations that consolidate

&#x20; the documented peer-review history of individual publications.



\## Corpus Construction Results



| Indicator | Result |

|---|---:|

| Articles assessed | 500 |

| Knowledge Units | 396 |

| Manuscript versions | 639 |

| Reviewer reports | 1,131 |

| CanonicalPairs | 1,131 |

| Author responses | 459 |

| Structural validation checks | 52 passed; 0 failed |



These results correspond to the corpus construction reported in the

associated research manuscript.



\## Implementation



The corpus construction pipeline was implemented in Python using

Google Colab.



The original implementation is preserved in:



`F1000\_500.ipynb`



The notebook includes procedures for data acquisition, processing,

knowledge representation, and structural validation.



\## Reproducibility



The notebook corresponds to the implementation preserved for the

reported research.



The original notebook has not been modified for public dissemination.



\*\*SHA-256:\*\*



`410F624F4397CA69237E6901D191B24308A1D8C7D23F4174DBC771FF87E84D31`



The checksum identifies the preserved notebook and enables integrity

verification.



Re-execution may produce different results if records or API responses

from the external data source have changed.



The notebook was developed using Google Colab and requires access to

Google Drive for file storage.



\## Validation



The reported corpus passed 52 automated structural validation checks.



These checks assess structural consistency and do not establish

semantic fidelity.



A human semantic audit is planned.



\## Research Status



\- Corpus construction: Completed

\- Structural validation: Completed

\- Semantic audit: Planned

\- LLM training and evaluation: Not performed in this study



\## Citation



Citation information will be provided following publication of the

associated research article and archival software release.



\## License



Licensing information is pending.



The licensing of the implementation is distinct from the licensing

and reuse conditions of the source publications and peer-review records.


