# Stochastic optimization and machine learning

This repository contains a Jupyter notebook and a project report showing an implementation of two optimization algorithms to learn a linear SVM from scratch : Stochastic Dual Coordinate Ascent (SDCA) and Primal Estimated sub-GrAdient SOlver for SVM (PEGaSoS). This was done as part of a school project at ENSAE in 2017.

The report contains :

* A brief overview of the theoretical framework behind both algorithms and their variants (mainly ASDCA and mini-batch PEGaSoS)
* A benchmark of their performances on different datasets : simulated data and regular data (including one high dimensional dataset). The corresponding code can be found in the Jupyter Notebook

Main references :

* Shalev-Shwartz S., Singer Y., Srebro N. and Cotter A. “PEGASOS : Primal Estimates sub-GrAdient SOlver
for SVM.” Proceedings of the 24th international conference on Machine learning (2007)

*Shalev-Shwartz S. and Zhang T. “Stochastic Dual Coordinate Ascent Methods for Regularized Loss Minimization.”
Journal of Machine Learning Research 14 (2013).

Additional references can be found in the report
