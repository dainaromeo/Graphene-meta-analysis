# Graphene-meta-analysis
This repository contains the code and data used in the paper "A meta-analysis of graphene-related materials' toxicity on lung cells in vitro" by D. Romeo, C. Louka, B. Gudino, J. Wigstrom, and P. Wick

DATA:
Graphene_for_BMD_UPDATE.csv contains the toxicity data about graphene-related materials collected from the literature considering the publication time frame 2015-2021.
Graphene_BMD_UPDATED_no_outliers.csv contains the data set of BMDL values obtained from the Graphene_for_BMD_UPDATE.csv data set using PROAST software.

CODE:
Viability_Prediction_UPDATED.ipynb contains the code relative to the prediction of the viability dependent variable from the Graphene_for_BMD_UPDATE.csv data set.
BMDL_Prediction_UPDATE_DR.ipynb contains the code relative to the prediction of the BMDL dependent variable from the Graphene_BMD_UPDATED_no_outliers.csv data set.
Graohene BMDL classification.ipynb contains the code relative to the classification of the BMDL dependent variable from the Graphene_BMD_UPDATED_no_outliers.csv data set.
