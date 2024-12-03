# AmPro
Amplicon data processing pipeline for environmental microbiology bioinformatics

This pipeline takes FASTQ sequences, processes them with filtering, editing, chimera removal etc before running them through phyloseq to identify each amplicon sequence variant (ASV). The relative abundance of each ASV identification can then be calculated and finally graphed with ggplot2.

# Dependencies
AmPro uses DADA2, phyloseq, and ggplot2 so make sure you have them installed before starting!
