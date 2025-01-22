# awesome-evomics
awesome list of evolutionary genomics resources

## data sets

### human

- https://www.internationalgenome.org/ - data portal for the 1000 Genomes and other projects
  - [data collections](https://www.internationalgenome.org/data-portal/data-collection)
  - [map of populations](https://www.internationalgenome.org/data-portal/population)
- https://www.eva.mpg.de/genetics/genome-projects/ - sequencing data for the Neanderthals and Denisovans
  - http://cdna.eva.mpg.de/neandertal/ - direct downloads
- [Simons Genome Diversity Project (SGDP)](https://reichdata.hms.harvard.edu/pub/datasets/sgdp/)

### zoology

- https://www.ultraconserved.org/ - resources for ultraconserved elements (UCEs), a useful set of genome-wide markers, especially for non-model taxa without reference genomes. The combination of conserved sequences with variable flanking regions offers markers to study evolution at different levels, from populations to phylogenomics at higher taxonomic ranks.

### parasites

- https://veupathdb.org/veupathdb/app - VEuPath database of eukaryotic pathogen, vector and host informatics
- https://tritrypdb.org/tritrypdb/app - TriTryp database of trypanosomatid parasites

## learning
### genomics

- https://speciationgenomics.github.io - tutorials covering around 70% of my PhD, too bad I found the page after my defense
- https://evomics.org - portal with materials from years of summer schools on evolutionary genomics
- https://theg-cat.com - genetic theory in nice digestible articles

### data management

- https://vincebuffalo.com/book/ - Bioinformatics Data Skills (by Vince Buffalo)
- https://jeroenjanssens.com/dsatcl/ - Data Science at the Command Line (by Jeroen Janssens)

## software tools
### population & evolutionary genomics

- https://methodspopgen.com/ - overview of software tools for population and evolutionary genomics, described in a [review paper](https://onlinelibrary.wiley.com/doi/10.1111/mec.15989)
- https://www.cog-genomics.org/plink2/ - PLINK toolkit for population genomics and GWAS (2nd generation)

### bioinformatics

- https://www.htslib.org/ - HTSlib + Samtools (for SAM / BAM alignments)
- https://samtools.github.io/bcftools/ - Bcftools (for variant data in VCF format)
- https://bioinf.shenwei.me/seqkit/ - SeqKit (for efficient manipulation of FASTA/FASTQ formats)
- https://github.com/lh3/seqtk - SeqTK (for efficient manipulation of FASTA/FASTQ formats)
- https://github.com/lh3/bioawk - extension of the AWK language with support for common bioinformatic formats and compressed data

### tabular data
There is plenty of tabular data in bioinformatics, from the well-known formats to all kinds of metadata. Many tools were developed to process general tabular data.

- https://github.com/dbohdan/structured-text-tools - overview of tools for processing structured text
- https://miller.readthedocs.io/ - Miller is like awk, sed, cut, join, and sort for data formats such as CSV, TSV, JSON, JSON Lines, and positionally-indexed
- https://bioinf.shenwei.me/csvtk/ - fast CSV/TSV toolkit in Go, with many features and simple plot functions
- https://github.com/BurntSushi/xsv - XSV is a fast CSV/TSV toolkit in Rust
- https://www.visidata.org/ - terminal spreadsheet app