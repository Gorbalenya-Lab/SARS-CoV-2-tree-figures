1. betacorona-5d-C4L1-2013-b1000-TEST-1 folder contains IQ-Tree run logs and the
resulted tree files for the species of SARS-related betacoronavirus
(cluster C4L1 in DEmARC classification):

* betacorona-5d-C4L1-2013.fasta - source alignment, it's exported from the
genome-wide alignment of coronaviridae. The following selected columns of
5 domains were taken and merged into one aminoacid MSA:

    Domain list = nsp5A-3CLpro:2..226,nsp13-HEL1core:1..327,nsp12-RdRp:190..677,nsp12-NiRAN:125..396,nsp13-ZBD:12..89

* betacorona-5d-C4L1-2013.fasta.treefile - IQ-tree output, see *.log
for the options used;

* betacorona-5d-C4L1-2013.r.nwk - rooted by "midpoint root" algortihm;

* betacorona-5d-C4L1-2013.nwk - support values are scaled from [0;100] to [0;1];

* betacorona-5d-C4L1-2013.f.nwk - EPI_ISL_402131.1 is renamed to SARSr-CoV_RaTG13;

* iq-tree-sars-test.selected.nwk - 17 genomes are selected (plot-2B-selection.txt);

* iq-tree-sars-test.selected.collapsed.1e-3.nwk, plot-2B-iq-tree.nwk -
with Forester tool (aka Archaeopteryx) branches with branch lengths larger than
0.001 were collapsed, it turned some internal nodes to multifurcations,
this is the final tree file.

2. The Figure 2B PNG,TIFF,PDF files were made with R "ape" library,
several branches in the tree were rotated for better placement in the figure.

