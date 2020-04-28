1. betacorona-5d-b1000-WAG-2 folder contains IQ-Tree run logs and the resulted tree files
for genus Betacoronaviruses:

* betacorona-5d-2013.fasta - source alignment, it's exported from the genome-wide alignment
of coronaviridae. The following selected columns of 5 domains were taken and merged into
one aminoacid MSA:

    Domain list = nsp5A-3CLpro:2..226,nsp13-HEL1core:1..327,nsp12-RdRp:190..677,nsp12-NiRAN:125..396,nsp13-ZBD:12..89

* betacorona-5d-2013.fasta.treefile - IQ-tree output, see *.log for the options used;

* betacorona-5d-2013.r.nwk - rooted by "midpoint root" algortihm;

* betacorona-5d-2013.r.fixed.NL63.supp.nwk - fixed support value for NL63 node (outgroup node);

* betacorona-5d-2013.r.fixed.NL63.supp1.nwk, plot-2C-iq-tree.nwk - support values are scaled
from [0;100] to [0;1], it's the final tree file.

2. The Figure 2C PNG,TIFF,PDF files were made with R "ape" library,
several branches in the tree were rotated for better placement in the figure.

