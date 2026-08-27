Dataset for German Credit available at:
https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

PyMC for testing
https://www.pymc.io/welcome.html

JAX_NUTS.ipynb:

	- Source code of the "hand made" NUTS algorithm 

JAX_NUTS_Gauss10D.ipynb:

	- Define L(\theta) as a Gaussian distribution
	- Sample with hand made algorithm the defined distribution
	- KS-test and QQ-plots


Gaussian_250D.ipynb:

	- Analysis for a 250D gaussian syntetic dataset
	- Contains comparison NUTS vs HMC, replicating the results of the paper

GermanCreditData.ipynb:

	- Analysis for the German Credit Dataset with a simple prior
	- Contains explanation for our procedure and comparison NUTS vs HMC, replicating the results of the paper

GermanCredit_HLR.ipynb

	- Analysis for the German Credit Dataset with a more complex hierarchical prior
	- Contains explanation for our procedure and comparison NUTS vs HMC, replicating the results of the paper
	
Plotter.ipynb

	- Notebook to plot the results of the analysis on German Credit Dataset.
