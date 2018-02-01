# Utilities for MSA

These are utility scripts useful for multiple sequence alignment research.

 - num_seq: count sequences in a FASTA file.
 - seq_len: calculate average length of sequences in a FASTA file.
 - percent_id: calculate percent identity of sequences in a FASTA alignment file.
 - shuffle_fasta: randomly reorder sequences in a FASTA file.
 - unshuffle_fasta: reorder sequences in a FASTA file according to a reference order.
 - ungap_fasta: remove all gaps from a FASTA alignment file.
 - subtree: prune a guide tree or phylogenetic tree down to the minimum tree containing a given set of leaves (sequences specified by a FASTA file).

## Dependencies 
These scripts rely on [BioPython](http://biopython.org/). The subtree script additionally requires [ete3](https://pypi.python.org/pypi/ete3).
