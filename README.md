# APOBEC3-deaminase-editing-in-mpox-virus
DOI: 10.1126/science.adg8116

Original file with APOBEC3 sites is located in supplementary materials hmpxv-apobec3-dd7a582/data/B.1/B.1_2022-08-22.og.aln.pruned.tree.amino_acid.reconstruction.csv

APOBEC3_sites.ipynb contains transformation of original dataframe with APOBEC3 sites, programs for searching amino acids in these positions and potential target sites for APOBEC in MPOX genome. Received tables are saved in data/article_pos_aa_edited.csv and data/APOBEC_targets_aa.csv

We built the barplot data/APOBEC_targets_plus_observed.png using R (R_barplot.Rmd).

Than we calculated the Grantham score for hypothetical amino acid changes (grantham_score.R) and built the plot with amino acids hypothetical changes.