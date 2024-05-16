# Modified-SCOP-Database-TSV-format-
This repository provides a modified version of the Structural Classification of Proteins (SCOP) database in tab-separated value (TSV) format.  The original SCOP database is a freely available resource for classifying protein structural domains (https://scop.berkeley.edu/).


This repository provides a modified version of the Structural Classification of Proteins (SCOP) database, based on SCOPe release 2.08 (September 2021).

**Key modifications:**

* Data organization: The data is split into two files for better usability:
    - **Based_on_PDB_id.tsv**: This file sorts the data by PDB ID, making it convenient to look up classifications based on protein identifiers.
    - **Original_cla_file.tsv**: This file retains the original SCOP classification hierarchy sorted by SCOP ID.
* Data formatting: The data format (TSV) is user-friendly and easily parsed by various data analysis tools.

**Usage:**

The specific usage of your modified database will depend on your research needs. However, the provided organization by PDB ID and SCOP ID allows for efficient retrieval of classifications based on either identifier type.

**Citation:**

* Fox, NK, Brenner, SE & Chandonia, JM (2014). SCOPe: Structural Classification of Proteins—extended. Nucleic Acids Research, 42(Database issue): D304-D309. doi: 10.1093/nar/gkt1240.

**Copyright Notice:**

* Based on SCOPe (copyright 1994-2023 The SCOP and SCOPe authors).

**Contact:**

* [https://github.com/Bibhuprasadbehera] or [bibhu.behera@niser.ac.in] (for questions about this modified database)
