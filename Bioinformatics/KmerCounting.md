**K-mer counting tool for large K**
In next-generation sequencing, k-mer counting is a essential tool to glance through the complexity of genome and the quality of sequencing library. Recently, most k-mer statistics tools only count k-mer sub-sequence with small k up to 31. Jellyfish, tallymer in genometools and meryl in wgs-assembler are most used. With the growth of sequencing technology, sequencers can output reads with more than hundred bps in length. However, demand on a k-mer counting tool with large k value is still urgently. So far, we can find out two k-mer counting tools with large k value up to 63: BFCounter and Turtle.  

**References**
1. Jellyfish  
Guillaume Marcais and Carl Kingsford, A fast, lock-free approach for efficient parallel counting of occurrences of k-mers. Bioinformatics (2011) 27(6): 764-770  
[[url](http://www.cbcb.umd.edu/software/jellyfish/)]
1. Tallymer in genometools  
S. Kurtz, A. Narechania, J.C. Stein and D. Ware, A new method to compute K-mer frequencies and its application to annotate large repetitive plant genomes. BMC Genomics, 9:517 (2009)  
[[url](http://www.zbh.uni-hamburg.de/?id=211)]
1. Meryl in wgs-assembler  
[[url](http://kmer.sourceforge.net/)]
1. BFCounter  
Melsted, P. and Pritchard, J.K.: Efficient counting of k-mers in DNA sequences using a bloom filter. BMC Bioinformatics 12:333 (2011) [[url](http://pritch.bsd.uchicago.edu/bfcounter.html)]  
1. Turtle  
Roy, Rajat S. and Bhattacharya, Debashish and Schliep , Alexander. Turtle: Identifying frequent k-mers with cache-efficient algorithms. arXiv:1305.1861 (2013) [[url](http://bioinformatics.rutgers.edu/Software/Turtle/)]  
