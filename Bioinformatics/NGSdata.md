**Public domain next-generation sequencing data**  
As known, next-generation sequencing is very powerful technology and try to answer biological questions from whole genome, transcriptome, and so on. Although the sequencing cost is cheaper than a decade ago, it is not affordable for a small scale laboratory. In addition, sequencing library should be published for scientific proof. Therefore, it is very important to have a collection of sequencing reads.  

The following is a list of archive databases.  
1. NCBI Sequence Read Archive
1. European Nucleotide Archive
1. DDBJ Sequence Read Archive (DRA)
1. DBCLS SRA: Survey of Read Archives


The file format for archiving sequencing read is so-called sra and file extension is .sra. You can download NCBI SRA Toolkit to extract reads from sra file into fastq format.  

hint:  
If you want to extract paired-end read from sra by fastq-dump, you have a option of "--split-3" to output forward reads and reverse reads.  
`fastq-dump --split-3 path_to_file.sra`
