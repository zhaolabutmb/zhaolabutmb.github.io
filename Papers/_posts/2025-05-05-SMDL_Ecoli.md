---
layout: paper
title: "Combining Structural Modeling and Deep Learning to Calculate the E. coli Protein Interactome and Functional Networks"
image: 
authors: Haiqing Zhao, Caroline Velez, Anekit Navarene, Aakash Saha,Jonathan Feldman, Jeffrey Skolnick, Diana Murray, Barry Honig
year: 2025
ref: Haiqing Zhao, Caroline Velez, Anekit Navarene, Aakash Saha, Jonathan Feldman, Jeffrey Skolnick, Diana Murray, Barry Honig, 2025, bioRxiv
journal: bioRxiv
pdf: https://www.biorxiv.org/content/10.1101/2025.05.07.652715v1.full.pdf
doi: doi.org/XXXX
github: 
---

# Abstract
We report on the integration of three methods that are computationally efficient enough to predict,
on a proteome-wide scale, whether two proteins are likely to form a binary complex. The methods
include PrePPI, which uses three-dimensional structure information as a basis for predictions,
Topsy-Turvy which analyzes sequences using a protein language model, and ZEPPI which uses
evolutionary information to evaluate protein-protein interfaces. We demonstrate how these
methods can be integrated and validate the performance of the integrated method and its
separate components at predicting E. coli protein-protein interactions through testing on the HINT
high-quality literature-curated database of binary interactions. The integrated method identifies
more high-confidence (FPR ≤ 0.001) interactions (~20K) than any of the component methods.
The AF3Complex algorithm was used to predict the structures of 400 protein-protein interactions,
and 78% of the integrated method predictions resulted in models deemed accurate by the
AF3Complex evaluation score. Notably, essentially all AF3Complex models have at least partially
overlapping interfaces with PrePPI models of the complexes. Finally, we clustered the highconfidence E. coli interactome and obtained 385 subnetworks which have high functional
coherence defined by enrichment of Gene Ontology Biological Process terms, thus, illustrating
that our methods which contain no explicit functional information provide biologically meaningful
protein interactions. Biological insights derived from the subnetworks, including the annotation of
proteins of unknown function, are discussed in detail. Overall, independent validations support
the accuracy of the comprehensive E. coli interactome we have presented.
