# nf-core/smrnaseq: Changelog

## v1.0.0 - 2019-09-19
* Add figures to output documentation
* Add samtools stats for genome alignments
* Add seqkit and remove razers
* Add mirtop and razers tools
* Adapt code and docs to [nf-core](http://nf-co.re/) template
* Update tools and Dockerfile/Singularity to match current template

#### Dependency Updates
* openjdk 8.0.144 -> 11.0.1
* fastqc 0.11.7 -> 0.11.8
* trim-galore 0.5.0 -> 0.6.2
* bioconductor-edger 3.20.7 -> 3.26.0
* bioconductor-limma 3.34.9 -> 3.40.0
* conda-forge::r-data.table 1.11.4 -> 1.12.2
* conda-forge::r-gplots 3.0.1 -> 3.0.1.1
* conda-forge::r-r.methodss3 1.7.1 -> 1.7.1
* htseq 0.9.1 -> 0.11.2
* r-markdown 0.9
* Added mirtop 0.4.18a
* Removed razers3 3.5.3
* Added seqkit 0.10.1-1
* Added seqcluster 1.2.5
* conda-forge::r-base=3.5.1 -> 3.6.1
* conda-forge::r-statmod=1.4.30 -> 1.4.32
* conda-forge::r-markdown=0.9 -> 1.0
* trim-galore=0.6.2 -> 0.6.3
* mirtop=0.4.18a -> 0.4.22
* bioconductor-edger=3.26.0 -> 3.26.5
* bioconductor-limma=3.40.0 -> 3.40.2

## [1.0](https://github.com/nf-core/smrnaseq/releases/tag/1.0) - 2019-01-10
* Add "protocol" with pre-defined settings
* Add miRTrace in the pipeline.
* Software updates: multiqc 1.6 to 1.7.

## [1.0](https://github.com/nf-core/smrnaseq/releases/tag/1.0) - 2018-08-06
* Switch from SciLifeLab/NGI-smRNAseq to nf-core/smrnaseq.
* Use Bowtie 1 instead of Bowtie 2 for the alignment to host reference genome.
* Add option for sequencing centre in BAM file.
* Software updates: trim-galore 0.4.5 to 0.5.0; samtools 1.8 to 1.9; multiqc 1.5 to 1.6.
