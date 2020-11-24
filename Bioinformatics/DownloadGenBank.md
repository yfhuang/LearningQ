Simple way to obtain genbank file (.gb) from NCBI GenBank
How to obtain full genome record (.gb) from NCBI GenBank

According to "Entrez Programming Utilities Help," jump to the section of "Downloading Full Records" and you will find the way to download full genome record from NCBI GenBank.

For example, if you want to download the genome with accession number NC_027449 in GenBank format, the url will be in the following format.


https://eutils.ncbi.nlm.nih.gov/entrez/eutils/efetch.fcgi?db=nuccore&id=NC_027449&rettype=gb&retmode=text

db: Entrez database
id: List of UIDs (gene id or accession number)
rettype: Retrieval type (gb, fasta)
retmode: Retrieval mode (text)


Caution: Don't retrieve records in a short time. It is a good choice to use "sleep."
