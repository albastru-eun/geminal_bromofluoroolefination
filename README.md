# Reaction Profile Forecasting by Artificial Data Generation
This project is based on the paper: "Reaction Profile Forecasting by Artificial Data Generation for Wittig-type Geminal Bromofluoroolefination"
(for the experimental data: "Stereoselective synthesis of geminal bromofluoroalkenes by kinetically controlled selective conversion of oxaphosphetane intermediates" doi/10.1126/sciadv.adq5316)

Machine learning models of kernel ridge with radial basis function (KR rbf), support vector machine with rbf (SVM rbf), k-nearest neighbor (kNN), random forest (RF), extreme gradient boosting (XGB), and feed-forward network (FNN).
The augmented datasets were prepared by fitting data into sigmoidal curves using the Origin software, and virtual points at median time between two observations were produced.
The synthesized datasets were prepared by variational autoencoder (VAE) and conditional tabular augmentation (CTGAN) before the learning.

## Data Explanation
\models #models <br/>
\other_data #Sterimol, fitting curves <br/>
\result #several selected results (for all graphical results, see the Supporting Information) <br/>
\split #datasets <br/>
