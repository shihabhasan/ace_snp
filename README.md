# ACE SNP Calling


## Dataset
```
human amplicon by nextseq
```

## Reference 
```
human genome
```

## Tools to use

### Alignment

```
bwa or bwa-mem
```

### SNP Calling
```
samtools & BCFtools
```
http://samtools.sourceforge.net/mpileup.shtml
https://www.nature.com/articles/srep17875

Among many read aligners, BWA-MEM, Bowtie2, and Novoalign (http://novocraft.com/) are popular, and among many variant callers, 
the Genome Analysis Tool Kit HaplotypeCaller (GATK-HC), Samtools mpileup, Freebayes, and Torrent Variant Caller (TVC) are widely used in genomic variant analyses. 
For SNP variant calls, BWA-MEM-Samtools pipeline showed the best performance.

```
gatk HaplotypeCaller
```
https://software.broadinstitute.org/gatk/documentation/tooldocs/current/org_broadinstitute_gatk_tools_walkers_haplotypecaller_HaplotypeCaller.php
