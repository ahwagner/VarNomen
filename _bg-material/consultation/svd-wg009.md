---
layout: default-md
title: SVD-WG009
category: SVD-WG
---

## Community Consultation

### Proposal SVD-WG009 (conversion)

*	Status: <font color="red">open</font>
	:	proposal SVD-WG009 opened for **Community Consultation** on August 1 (2020) and will be closed October 31 (2020). 

* * *

The proposal suggests simplification of the HGVS nomenclature by discontinuing the use of the variant type “con” to describe conversions (see [<i>Converion</i>](/recommendations/DNA/variant/conversion/)).

According to the HGVS definition: conversion = a sequence change where, compared to a reference sequence, a range of nucleotides are replaced by a sequence from elsewhere in the genome.

*	the HGVS recommendations do not need the "con" format since such variants can be described using the existing "delins" format (simply replace "con" by "delins" in the description).
*	the format is rarely used so the change should not cause many problems
*	stopping its use will help simplify the HGVS recommendations

* * *

#### Examples

*	NC\_000022.10:g.42522624\_42522669delins42536337\_42536382
	:	previously NC\_000022.10:g.42522624\_42522669con42536337\_42536382, a conversion in exon 9 of the CYP2D6 gene on cromosome 22 (NC\_000022.10) replacing exon 9 nucleotides g.42522624 to g.42522669 with nucleotides g.42536337 to g.42536382 of the 3’ flanking CYP2D7P1 gene

*	NC\_000012.12:g.6128479\_6128749delins[NC\_000022.11:17178616\_17178886]
	:	previously NC\_000012.12:g.6128479\_6128749con[NC\_000022.11:17178616\_17178886], a gene conversion in the VWF gene converting the chromosome 12 sequence (NC\_000012.12) from position g.6128479 to g.6128749 with the sequence from chromosome 22 (NC\_000022.11) from position g.17178616 to g.17178886. 