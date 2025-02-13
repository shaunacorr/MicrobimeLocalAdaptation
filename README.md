# MicrobimeLocalAdaptation
 Local Adaptation in Seaweed Microbiomes
R scripts, Qiime2 workflows and data for performing bioinformatics analyses in Corr et al. Local adaptation in seaweed Microbiome. Files are spilt into 3 different folders, dependent on the three different experiments conducted.

Reciprocal Two-Species Transplant Experiment – Sequencing:
All 16S rRNA gene sequencing fastq files used for this section are available on the NCBI database with BioProject ID PRJNA1223129, and SRA accession XXXXXXX to XXXXXXXX. “Qiime Commands” in the “Qiime2 Analysis” folder was used to process these files following the DADA2 pipeline, assign ASV taxonomy, calculate UniFrac distances and complete a differential abundance analysis. Relevant output files are also available within the folder.
“R Studio Analysis” contains the script and input files needed to conduct alpha and beta diversity analysis and product Figure 1, 2, 3, S2, S3 and Table S1.

Reciprocal Two-Species Transplant Experiment – Growth Curve: 
Contains the script and input files to analyse growth curve data obtained from OD readings to produce Figure 4. Input files are as follows: “ALL_DD_Plates” = Dulse bacterial isolates grown in Dulse seaweed environment, “ALL_DF_Plates” = Dulse bacterial isolates grown in Fucus seaweed environment, “ALL_FD_Plates” = Fucus bacterial isolates grown in Dulse seaweed environment, and “ALL_FF_Plates” = Fucus bacterial isolates grown in Fucus seaweed environment.

Six-species Rhodophyta ASV Diversity Experiment:
All 16S rRNA gene sequencing fastq files used for this section are available on the NCBI database with BioProject ID PRJNA1223129, and SRA accession XXXXXXX to XXXXXXXX. “Qiime Commands” in the “Qiime2 Analysis” folder was used to process these files following the DADA2 pipeline, assign ASV taxonomy, and calculate UniFrac distances. Relevant output files are also available within this folder.
“R Studio Analysis” contains the script and input files needed to conduct alpha diversity analysis and product Figure 5, S4 and S5.
