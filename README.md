# Gmat64
a piece of cake to build different kinds of kinship matrix

This program is written by C. Intel mkl need to be installed in advance.

The program start from PLINK binary file, and five command-line arguments are needed to build different additive and non-additive kinship matrix.
NOTE: missing genotype should be imputed!!!

--bfile  prefix for PLINK binary file
--inv 0 or 1 whether to output the inverse matrix of kinship
--normMat  0 or 1 whether to output the normlized marker matrix
--Gmat kinship type. addGmat, additive kinship matrix; domGmat_AS or domGmat_GS, dominant kinship, domGmat_GS should be used for genomic 
selection; epiGmatAA, AxA epistatic kinship; epiGmatAD_AS or epiGmatAD_GS, AxD epistatic kinship;
epiGmatDD_AS or epiGmatDD_GS, DxD epistatic kinship

