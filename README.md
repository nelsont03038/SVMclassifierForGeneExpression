# SVMclassifierForGeneExpression
This is a Jupyter notebook showing how to build a support vector machines classifier on gene expression data from an RNA-seq experiment.  I use 
the Python programming language and the numpy, pands and scikit-learn packages.  I use publicly available data from an experiment where they 
did RNA-seq to measure miRNA levels in 29 tumor/normal pairs.  I build a support vector machines classifier that can accurately predict if an 
unseen sample is a tumor or normal sample.  I apply "bagging" (boostrap aggregating) to the model to avoid overfitting and to improve bias and variance.

Dependencies - You will need Python and the latest version of numpy, pandas and scikit-learn.

The data are from:

Witten  D,  Tibshirani  R,  Gu  S,  et  al.  (2010).  Ultra-high  throughput  sequencing-based  small
RNA discovery an discrete statistical biomarker analysis in a collection of cervical tumors and
matched controls.  BMC Biology, 8(58).
