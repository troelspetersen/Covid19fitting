# Covid19fitting
Python (Jupyter) Notebooks fitting the Covid19 developments in Denmark

The code uses both publicly available data (from Epidemologisk Rapport by Statens Serum Institute (SSI)) for general developments in Denmark, but also non-public data (from WGS of positive samples) for determining the development of B.1.1.7 in Denmark.

The data is used to extract parameters for possible scaling and corrections, after which it is fitted (ChiSquare or Likelihood) with simple models using the Minuit minimisation package (from CERN).

The code should be possible to run directly in a Jupyter Notebook environment with the required packages (iMinuit among them) and correct link to the data files.

The code was developed by Troels C. Petersen (Niels Bohr Institute) with contributions from students assisting the project (Albert, Julie, Peter, Kimi, and Magnus).
