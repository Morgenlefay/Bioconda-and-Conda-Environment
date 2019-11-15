## Quality control
```bash
conda create -n QC
conda activate QC
conda install -c bioconda fastqc
conda install -c bioconda rseqc
conda install -c bioconda trim-galore
conda install -c bioconda multiqc 
conda deactivate
```
## RNA-seq
```bash
conda create -n RNAseq
conda activate RNAseq
conda install -c bioconda hisat2
conda install -c bioconda bowtie2
conda install -c bioconda samtools
conda install -c bioconda bedtools 
conda install -c bioconda subread 
conda install -c bioconda htseq
conda install -c bioconda stringtie
conda install -c bioconda gffcompare
conda install -c bioconda rsem
conda install -c bioconda cufflinks
conda install -c bioconda tophat
mamba install -c compbiocore gsnap 
conda deactivate
```
## ChIP-seq
```bash
conda create -n ChIPseq
conda activate ChIPseq
mamba install -c bioconda deeptools
mamba install -c bioconda r-ngsplot
mamba install -c bioconda macs2
mamba install -c bioconda homer
mamba install -c bioconda hisat2
mamba install -c bioconda bowtie2 
mamba install -c bioconda samtools
mamba install -c bioconda bedtools
mamba install -c bioconda picard 
mamba install -c bioconda sambamba
mamba install -c bioconda manorm
mamba install -c bioconda sicer
conda deactivate
conda remove -n ChIPseq --all
```
