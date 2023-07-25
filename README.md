# cpn60-Classifier

The “universal target” region of the gene encoding the 60 kDa chaperonin protein (cpn60, also known as groEL or hsp60) is a proven sequence barcode for bacteria and a useful target for marker gene amplicon based studies of complex microbial communities. To date, identification of cpn60 sequence variants from microbiome studies has been accomplished by alignment of queries to a reference database. Naïve Bayesian classifiers including the RDP classifier offer an alternative identification method that provides variable rank classification and shorter analysis times. 

This repository contains training sets that can be used with the Ribosomal Database Project classifier (Wang et al., 2007) or the QIIME2 q2-feature-classifier plugin (https://github.com/qiime2/q2-feature-classifier) to taxonomically assign chaperonin 60 (cpn60) sequences. 

# Citation

Ren, Q. and Hill, J.E. 2023. Rapid and accurate taxonomic classification of cpn60 amplicon sequence variants. ISME Communications 3:77 https://doi.org/10.1038/s43705-023-00283-z

# Releases
The classifier used in initial performance testing is **v10.1**, which contains a non-redundant set of 11,001 cpn60 barcode sequences retrieved from https://www.cpndb.ca and used to train the RDP Classifier.

The latest release is **v11.1**, which includes 16,413 cpn60 reference sequences that have undergone additional curation. In this latest release, we provide a trained RDP Classifier and a QIIME2 artifact for use with the q2-feature-classifier plugin (Bokulich NA, Kaehler BD, Rideout JR, et al. Optimizing taxonomic classification of marker-gene amplicon sequences with QIIME 2’s q2-feature-classifier plugin. Microbiome. 2018;6:90). Input taxonomy tables and sequence files are also provided for those who want to do the training themselves.
