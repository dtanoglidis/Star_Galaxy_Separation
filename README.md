# Star-Galaxy-QSO Separation

## Repository for a short project on Star Galaxy separation using SDSS data.

This repository contains the notebook and data of a short project that I did on star-galaxy-quasar separation (classifictation)
using data from the 15th data release (DR 15) of the Sloan Digital Sky Survey (SDSS).


I used the fluxes (brightnesses) in bands $u,g,r,i,z$ and the derived astronomical colors to classify objects into three categories:

- Galaxy
- Star
- Quasar (QSO)

The total annotated sample contained 100000 instances, split into 80-20 \% training/testing sets.

For the classification problem we tried a number of well-performing supervised learning algorithm, namely:

- Support Vector Machines (SVM)
- Random Forest 
- Gradient Boosterd Random Forest
- A fully connected artificial Neural Net (ANN)

The Best results were obtained with the Random Forest algorithm, where we achieved $90.6 \%$ accuracy (when three categories where considered) and $95.5\%$ accuracy when two categories (Star/Galaxy) were considered.
