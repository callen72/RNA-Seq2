# RNA-Seq2
Created n new directory WTAvE
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE>mkdir 0_raw_data
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE>cd 0_raw_data/
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/0_raw_data>mv ../*.fastq .
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/0_raw_data>ls
WTair1_S1_R1_001.fastq  WTair3_S3_R1_001.fastq  WTeth2_S7_R1_001.fastq
WTair2_S2_R1_001.fastq  WTeth1_S4_R1_001.fastq  WTeth3_S8_R1_001.fastq

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/0_raw_data>wget ftp://ftp.ncbi.nlm.nih.gov/genomes/all/GCF_000009725.1_ASM972v1/GCF_000009725.1_ASM972v1_genomic.fna.gz

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/0_raw_data>wget ftp://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/000/009/725/GCF_000009725.1_ASM972v1/GCF_000009725.1_ASM972v1_genomic.gff.gz

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/0_raw_data>ls
GCF_000009725.1_ASM972v1_genomic.fna.gz    WTair3_S3_R1_001.fastq
GCF_000009725.1_ASM972v1_genomic.fna.gz.1  WTeth1_S4_R1_001.fastq
GCF_000009725.1_ASM972v1_genomic.gff.gz    WTeth2_S7_R1_001.fastq
WTair1_S1_R1_001.fastq                     WTeth3_S8_R1_001.fastq
WTair2_S2_R1_001.fastq

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/0_raw_data>gunzip *.gz

/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE>mkdir alignment_STAR
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE>cd alignment_STAR/
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/alignment_STAR>ls
/lustre/projects/RNA_Seq_Data/SynRNA_Seq_Data/WTAvE/alignment_STAR>mkdir genomeDir

l
