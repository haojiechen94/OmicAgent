# OmicAgent
OmicAgent is a toolkit for searching, downloading, and analyzing publicly available biomedical data. It supports keyword-based dataset discovery across public databases and integrates data retrieval with downstream analysis to simplify data reuse in biomedical research.




GEO

Use $organize-geo-sra-metadata to organize "geo_metadata.json".
Process GEO independently. Work offline using only the supplied JSON.
Generate the detailed sample metadata table and all supporting outputs
defined in the skill. Save results to "./geo_organized".
Preserve the input file and do not download sequencing or image data.

SRA

Use $organize-geo-sra-metadata to organize "sra_metadata.json".
Process SRA independently. Decode JSON-encoded record strings when needed.
Work offline using only the supplied JSON.
Generate the detailed sample metadata table and all supporting outputs
defined in the skill. Save results to "./sra_organized".
Preserve the input file and do not download sequencing data.
