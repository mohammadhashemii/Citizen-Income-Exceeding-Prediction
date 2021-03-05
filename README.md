# Citizen Income Exceeding Prediction using SVM/KNN
This project was the second assignment of the Computational Intelligence course at Shahid Beheshti University. The aim of the project was to take advatage of the SVM(using [scikit-learn](https://scikit-learn.org/stable/)) and KNN(from scratch and without other external libraries) in order to predict the income of the citizens whether they exceed from some constant number or not.


# Dataset

![](https://github.com/mohammadhashemii/Citizen-Income-Exceeding-Prediction/blob/master/data-description.png)

The dataset has been obtained from [KEEL](https://sci2s.ugr.es/keel/dataset.php?cod=192#sub1). The Adult data set was extracted in 1994 from census data of the United States. It contains continuous and nominal attributes, describing some social information (age, race, sex, marital status, ...) about the citizens registered.training neural networks in PyTorch)


# Preprocessing   
The dataset itself needs lots of data-cleaning! There are many missing values for features which should be filled by existing techniques like **Imputation** or **Removing**.

Also the **one-hot encoding** technique has been used for categorical features. **Binning** method also was used for some features like Age.

At last, standardization and normalization was used for better convergence of the model.  

# Model

**SVM** with differenet kernels like **RBF** and **Polynomial** has been tried and the results are plotted in the notebook. Also there is an efficient implementation of **KNN** in the notebook. Other explanation of the this procedure is documented in the `citizenIncomeExceedingPrediction.ipynb`.



