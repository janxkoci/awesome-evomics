# awesome-evomics
curated list of awesome resources for evolutionary and population genomics [work in progress]

## data sets

### human

- [InternationalGenome.org](https://www.internationalgenome.org/) - data portal for the 1000 Genomes and other projects
  - [data collections](https://www.internationalgenome.org/data-portal/data-collection)
  - [map of populations](https://www.internationalgenome.org/data-portal/population)
- [Genome Projects at Max Planck Institute for Evolutionary Antropology](https://www.eva.mpg.de/genetics/genome-projects/) - sequencing data for the Neanderthals and Denisovans
  - http://cdna.eva.mpg.de/neandertal/ - direct downloads
- [Simons Genome Diversity Project (SGDP)](https://reichdata.hms.harvard.edu/pub/datasets/sgdp/) - WGS data from 142 populations around the world
- [The Allen Ancient DNA Resource (AADR)](https://doi.org/10.7910/DVN/FFIDCW) - ancient and modern human samples sequenced using the 1240K SNP panel

### zoology

- [Ultraconserved elements (UCEs)](https://www.ultraconserved.org/) - resources for ultraconserved elements (UCEs), a useful set of genome-wide markers, especially for non-model taxa without reference genomes. The combination of conserved sequences with variable flanking regions offers markers to study evolution at different levels, from populations to phylogenomics at higher taxonomic ranks.
- [The Vertebrate Genomes Project](https://vertebrategenomesproject.org/) - aims to sequence genomes for all known vertebrate species.

### parasites

- [VEuPath database](https://veupathdb.org/veupathdb/app) of eukaryotic pathogen, vector and host informatics
- [TriTryp database](https://tritrypdb.org/tritrypdb/app) of trypanosomatid parasites

## learning
Helpful tutorials, blogs, and books on topics in evomics, bioinformatics, and data science.

### genomics

- [Speciation genomics](https://speciationgenomics.github.io) - tutorials covering around 70% of my PhD, too bad I found the page after my defense
- [Evomics.org](https://evomics.org) - portal with materials from years of summer schools on evolutionary genomics
- [The G-cat](https://theg-cat.com) - genetic theory in nice digestible articles
- [Introduction to the Command Line for Genomics](https://datacarpentry.github.io/shell-genomics/) (a course by Data Carpentry)
- [Population genetics and genomics in R](https://grunwaldlab.github.io/Population_Genetics_in_R/)

### data skills

- [Bioinformatics Data Skills](https://vincebuffalo.com/book/) (book by Vince Buffalo)
- [Data Science at the Command Line](https://jeroenjanssens.com/dsatcl/) (free book by Jeroen Janssens)
- [Ad Hoc Data Analysis From The Unix Command Line](https://en.wikibooks.org/wiki/Ad_Hoc_Data_Analysis_From_The_Unix_Command_Line) (free book at Wikibooks)

## software tools

### software repositories

- [Bioconda](https://bioconda.github.io/) - channel of bioinformatic software, for the [conda](https://docs.anaconda.com/miniconda/) / [mamba](https://mamba.readthedocs.io/en/latest/index.html) package managers
- [Conda-forge](https://conda-forge.org/) - channel of scientific software, for the conda / mamba package managers
- [Homebrew Bio](https://github.com/brewsci/homebrew-bio) - repository of bioinformatic software for the [Homebrew / Linuxbrew](https://brew.sh/) package managers
- [Bioconductor](https://www.bioconductor.org/) - bioinformatic packages and versioned data in R

### population & evolutionary genomics

- https://methodspopgen.com/ - overview of software tools for population and evolutionary genomics, described in a [review paper](https://onlinelibrary.wiley.com/doi/10.1111/mec.15989)
- [PLINK2](https://www.cog-genomics.org/plink2/) - toolkit for population genomics and GWAS
- [EIGENSOFT](https://github.com/DReichLab/EIG) - tools for analysis of populations, including population stratification and SmartPCA
- [ADMIXTOOLS2](https://uqrmaie1.github.io/admixtools/index.html) - R package with reimplementation of the original ADMIXTOOLS, with higher performance and easy scripting interface, plus a GUI webapp
- [ADMIXTOOLS](https://github.com/DReichLab/AdmixTools) - the original ADMIXTOOLS package

### simulations

- [msprime](https://tskit.dev/software/msprime.html) - coalescent simulator
- [SLiM](https://messerlab.org/slim/) - forward-time simulator for spatial models of evolution
- [slendr](https://www.slendr.net/) - R interface to msprime and SLiM simulators, with support for spatial and non-spatial models
- [stdpopsim](https://github.com/popsim-consortium/stdpopsim) - library of standard population genetic simulation models

### bioinformatic formats

- [HTSlib](https://www.htslib.org/) - Umbrella project for Samtools and related packages
  - [Samtools](https://www.htslib.org/doc/samtools.html) for SAM/BAM alignments
  - [Bcftools](https://www.htslib.org/doc/bcftools.html) for variant data in VCF/BCF formats
  - [Bgzip](https://www.htslib.org/doc/bgzip.html) - Block gzip allows fast random access to compressed files
  - [Tabix](https://www.htslib.org/doc/tabix.html) - indexing of files compressed with Bgzip.
- [SeqKit](https://bioinf.shenwei.me/seqkit/) - for efficient manipulation of FASTA/FASTQ formats
- [SeqTK](https://github.com/lh3/seqtk) - for efficient manipulation of FASTA/FASTQ formats
- [bioawk](https://github.com/lh3/bioawk) - extension of the AWK language with support for common bioinformatic formats and compressed data
- [Seqmagick](https://seqmagick.readthedocs.io/) - a kickass little utility built in the spirit of imagemagick to expose the file format conversion in Biopython in a convenient way. Instead of having a big mess of scripts, there is one that takes arguments.

### tabular data
There is plenty of tabular data in bioinformatics, from the well-known formats to all kinds of metadata. Many tools were developed to process generic tabular data.

- [structured text tools](https://github.com/dbohdan/structured-text-tools) - overview of tools for processing structured text
- [Miller](https://miller.readthedocs.io/) - Miller is like awk, sed, cut, join, and sort for data formats such as CSV, TSV, JSON, JSON Lines, and positionally-indexed
- [csvtk](https://bioinf.shenwei.me/csvtk/) - fast CSV/TSV toolkit in Go, with many features and simple plot functions
- [xsv](https://github.com/BurntSushi/xsv) - fast CSV/TSV toolkit in Rust
- [visidata](https://www.visidata.org/) - terminal spreadsheet app