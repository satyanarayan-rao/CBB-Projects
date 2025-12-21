# Understanding biological functions from a list of genes

Many curiosities or analysis boils down to a potential list of candidates. For
example, in cases of genome sequence or genome-wide assays, a set of analysis
leads to a list of genes to investigate. A natural next step is to first look
at in what set of biological functions they are involved. To do this, all we
need to do is to feed that list to existing R or Python packages and get a
visualization.

In this tiny project, we are going to simply do that. We will get a list of
genes after searching for a sequence of interest in promoter region of all the
genes and then look at their biological functions.

You will need the following datasets to do the project.

- [Human genome](https://hgdownload.soe.ucsc.edu/goldenPath/hg38/bigZips/), search for `hg38.fa.gz` and download

- Dreg from [EMBOSS](https://anaconda.org/bioconda/emboss)
 
