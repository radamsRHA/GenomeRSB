# RSB (_Oebalus pugnax_) Genome Assembly & Annotation
This repository contains the genome assembly, annotation files, and supporting reports for RSB. The project includes both
contig-level and scaffold-level assemblies as well as full structural and functional annotation.

## Directory Overview

### Assembly
Contains genome assemblies and QC reports.
 - RSB_genome.fa.bz2 — genome assembly
 - HC_report/ — Hi‑C scaffolding results and heatmaps 
     
### Annotation
Contains annotation datasets and reports.
 - RSB_Annotation_Report/
 - RSB_Annotation_Results/
    - 00.Genome/ scaffold level genome assembly
    - 01.repeat_annotation/  RepeatMasker output, divergence statistics, and annotation notes
    - 02.ncRNA_annotation/ non coding RNAs prediction miRNA.gff3, rRNA.gff3, tRNA.gff3 and snRNA.gff3
    - 03.structure_annotation/ RSB.gff3 — Structural gene models RSB.cds — Coding sequences RSB.pep —Predicted protein sequences
    - 04.function_annotaion/ function_merge.xls — Integrated functional annotation table KEGG, NR, SwissProt and InterProScan results GO statistics and summary files

## Notes
This repository includes all major components of the RSB genome project, including assembly, annotation, and
supporting documentation
