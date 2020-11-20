**Pipeline of genome mapping by bowtie2**

1. Build index for reference genome  
`bowtie2-build reference_genome.fasta reference_genome`  
reference genome in FastA format: reference_genome.fasta  
reference genome index file prefix: reference_genome  

2. Map reads against with reference genome and generate sorted BAM file by coordinates  
`bowtie2 -x reference_genome -1 PE.R1.fastq -2 PE.R2.fastq [-u SE.fastq] [-I -X ] [--no-mixed --no-discordant] [-p threads#] | samtools view -bS - | samtools sort -o mapping_result.bam -`  

3. Build BAM file index  
`samtools index mapping_result.bam`  

4. Use IGV to browse the mapping result  
reference_genome.fasta  
mapping_result.bam  
mapping_result.bam.bai  
