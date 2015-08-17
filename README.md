#CpG_MPs v1.1.0
>CpG_MPs v1.1.0 is developed by Perl script wchich could be run in Linux or Window system. Users need to install Perl in the Window system before running the program.

___
####What is CpG_MPs
CpG_MPs, is proposed for identification and analysis of CpG methylation patterns of genomic regions from high-throughput bisulfite sequencing data. It may identify the unmethylated and methylated regions for a single sample, the conserved and differential methylation regions with different methylation patterns for paired or multiple samples. 
It includes four main modules as follows:

1. Normalization of the sequencing reads of cytosines following guanines;
2. Identification of the unmethylated (methylated) regions using hotspot extension algorithm;
3. Identification of conservatively and differentially methylated regionsby combining the combinatorial algorithm for determination of potentially functional regions with the algorithm of analysis of variance (ANOVA) for assess the statistical significance of differentially methylated regions;
4. Extraction of sequence features and visualization of these potentially functional regions.

___
####Command Line

* **Data Normalization**

USAGE: Normalization [OPTION] {--m_u <c1,c2>|--r_t <c1,c2>} [-i <file|folder>] [-o <folder>]

* **Identification of Methylation Patterns of regions**

USAGE: CpG_MPs [options] [-i <folder>] [-o <folder>]

* **Identification of Differentially and Conserved Methylated Regions**

USAGE: CpG_MPs_Dif_Con [options] [--patterns <folder_string>] [--methy <folder_string>] [-o <folder>]

* **Calculation the sequence features of the regions of DNA methylation patterns**

USAGE: Seq_Feature [--ref <folder>] [-i <folder>] [-o <folder>]

>More details please read the User Guide of CpG_MPs v1.1.0.
