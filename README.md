# AntiTbPdb: A Knowledgebase of Anti-Tubercular Peptides

Welcome to the official repository for AntiTbPdb, a comprehensive and manually curated knowledgebase of experimentally validated anti-tubercular and anti-mycobacterial peptides. This resource is designed to support researchers in peptide therapeutics, tuberculosis biology, and computational drug discovery.

Database URL: http://webs.iiitd.edu.in/raghava/antitbpdb/

ZENODO : https://doi.org/10.5281/zenodo.20067092

## Citation

Usmani, S. S., Kumar, R., Kumar, V., Singh, S., & Raghava, G. P. S. (2018).
AntiTbPdb: a knowledgebase of anti-tubercular peptides.
Database. https://doi.org/10.1093/database/bay025


## About the Database

AntiTbPdb is a unique repository fully dedicated to anti-tubercular and anti-mycobacterial peptides, addressing the lack of a centralized resource in this space. It consolidates experimentally validated data scattered across research articles and patents into a single, searchable platform enabling systematic exploration of peptide sequences, structures, modifications, and biological activities.

The database integrates information from:

* Literature (PubMed — 10,652 research articles screened)
* Patents (USPTO — 35 patents screened)
* Public repositories (PDB, PubChem)


## Key Features

Curated Dataset

* 1010 total entries
* 542 unique anti-tubercular/anti-mycobacterial peptides

Diverse Peptide Coverage

* 668 linear peptides
* 279 cyclic peptides
* 771 entries with L-amino acids, 124 with D-amino acids, 44 with mixed chirality

Rich Annotations
Each entry includes:

* Sequence, length, chirality
* Nature and source of origin
* Mycobacterium species and strain
* Inhibition concentration and cytotoxicity data
* Cell line and animal model information
* Immune response data (where available)
* Mechanism of action and molecular target

Modification Data

* N-terminal and C-terminal modifications
* Chemical modifications (e.g., disulfide linkage, N-methylation, non-natural amino acids)

Structural Data

* Experimental structures from PDB and PubChem
* Predicted tertiary structures via PEPstrMOD and I-TASSER
* Secondary structure composition analysis


## Overview

AntiTbPdb provides experimentally validated data along with:

* Anti-mycobacterial activity profiles
* Species and strain specificity
* Physicochemical and structural properties
* Chemical modifications
* Moonlighting activity (peptides active against multiple Mycobacterium species)
* Cross-references (PDB, PubChem)


### Structure Prediction

Structures were obtained or predicted using:

* PDB (experimental structures)
* PubChem (experimental structures)
* PEPstrMOD (peptides up to 25 amino acids, including modified residues)
* I-TASSER (remaining peptides)


### Data Retrieval Tools

* **Search** — Simple and advanced search with Boolean expressions (AND, OR, NOT) across all fields
* **Browse** — By peptide type, source, chirality, length, modification, Mycobacterium species, and moonlighting activity
* **Composition** — Amino acid composition/frequency, physicochemical property analysis, and secondary structure composition
* **Sequence Alignment** — BLAST, Smith-Waterman algorithm, sub-search and super-search for peptide mapping


### Limitations

* Structural prediction limitations for:
    * Peptides with complex chemical modifications beyond PEPstrMOD scope
    * Peptides lacking published sequence information (stored without sequence; updated when available)
* Force-field limitations in structure prediction tools


## Applications

* Anti-tubercular peptide design
* Machine learning model training for MDR-TB / XDR-TB therapeutics
* Structure-function relationship analysis
* Synergistic therapy research (peptides combined with conventional antibiotics)
* Drug discovery against drug-resistant Mycobacterium strains


## Contact & Authors

Prof. Gajendra P. S. Raghava
raghava@iiitd.ac.in
http://webs.iiitd.edu.in/raghava/

Developed at:
* Bioinformatics Centre, CSIR-Institute of Microbial Technology, Chandigarh, India
* Centre for Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), India


## License

This database is distributed under the
Creative Commons Attribution License (CC BY 4.0)


We acknowledge all researchers whose published work contributed to this dataset.
