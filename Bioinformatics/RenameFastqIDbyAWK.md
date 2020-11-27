**Simple way to rename FastQ ID by AWK**  
There is a simple way to rename FastQ ID by AWK defined as follow.  

`awk '{if(NR%4==1) $0=sprintf("%s/1",$0); print;}' input.fastq`

The NR is the value of line number.  

If NR%4 is equal to 1, it means that $0 is the FastQ ID. Therefore, you can modify the ID by sprintf as you desired. Otherwise, you can just print remaining parts.  
