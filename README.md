ANS-Thermal-Architecture-ML
Benchmarking ML and Seismic-Derived Heat Flow Models for the Arabian-Nubian Shield
Description
This repository contains the computational framework and data products associated with the study of the lithospheric thermal state of the Arabian-Nubian Shield (ANS). By integrating satellite gravity (EIGEN-6C4) and seismic tomography (SL2013sv), we employ a Random Forest Regression approach to predict surface heat flow and map the thermal lithosphere-asthenosphere boundary (LAB).
Repository Contents
/Data: Contains the processed geothermal data products (Grid files in .csv or .nc format). Note: Raw datasets are cited from the Global Heat Flow Database.
/Scripts: Python notebooks (.ipynb) detailing the Random Forest model training, hyperparameter tuning, and cross-validation scripts.
/Results: High-resolution Geothermal Gradient and Heat Flow maps of the ANS produced by the model.
Requirements
Python 3.x
Scikit-learn, Pandas, NumPy, Matplotlib/Cartopy.
Citation
If you use this code or the data products, please cite:
Haggag et al., (2026). Benchmarking Machine Learning and Seismic-Derived Heat Flow Models... [Scientific Reports Journal].
