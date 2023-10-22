## Applied Machine Learning Assessment

The repository contains code used to analyse sequencing data (gene expression matrices) and cell body segmentation data. Data mining approaches were employed to determine the features of the datasets. Following this, two machine learning approaches were applied.

## Part 1

A range of data-mining approaches were applied on three types of 'faulty' datasets. Datasets were visualised and examined for unstable entries or missing values. Imputation methods (static as well as model-based methods) were applied and compared. The associated R Markdown document with relevant code can be found in the AML_part1.Rmd file.

## Part 2

Two machine learning methods were applied on a chosen dataset using all features. The first method was clustering; two approaches, hierarchical clustering and k-means clustering, were applied on all features as well as a selection of features, and the subsequent partitions were compared. The second method was an ensemble of support vector machines that was applied on the full dataset as well as a subsample. A voting approach was applied to yield predictions for the ensemble SVM method. The associated R Markdown document with relevant code can be found in the AML_part2.Rmd file.
