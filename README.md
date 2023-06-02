# YCBS-255: Statistical Machine Learning


## Assignments
1. [Matematical algoritm, descriptive and inferential statistics, and linear regression model :](https://github.com/MNLepage08/YCBS-255/blob/main/Assignment01_(MNL).ipynb)
   - Write 2 mathematical algorithm.
   - Create an exponential population distribution. Generate 100 different samples from the population. Estimate the population mean using the lay of large numbers and the central limit theorem. Use appropriate visualization to describe the estimation. Draw an inference from the estimated population parameters and test the hypotheses.
   - Create simulated data and fit a simple linear regression model. Fit a linear least-squares model to predict y. Use an appropriate visualization to see the sample versus the population. Explain how results change by generating data with less noise.
2. [Data Exploration (distribution, correlation), Models (LR, LDA, QDA), Evaluation (confusion matrix, accuracy, AUC, F-measure), Cross-Validation, PCA:](https://github.com/MNLepage08/YCBS-255/blob/main/Assignment02_(MNL).ipynb)
   - Collect the dataset from credit CSV file. Use appropriate descriptive statistical methods to describe the variables and possible associations between them. Create LR, LDA and QDA models and find the probability of a balance < 1500. Evaluate the models using the confusion matrix, precision and AUC.
   - Collect all data from the ziptrain/ziptest CSV file. Select digits 2 and 7 only. Use the first 2 PCAs to separate the 2 digits. Model with logistic regression to separate the numbers. Evaluate the model with the confusion matrix, accuracy and F-Measure. With all numbers, use the LDA model with 5-fold cross-validation and select the best number of principal components.
3. [Model (Lasso Regression, Polynomial Regression, Step Function, SVM, Random Forest), Cross-Validation for tuning parameter to chose variable selection. K-means clustering](https://github.com/MNLepage08/YCBS-255/blob/main/Assignment03_(MNL)_v2.ipynb)
   - Create simulated data and generate the y variable with multiple linear regression. Use 5-fold cross-validation with a reasonable proportion of training/testing for a lasso regression model with different predetermined tuning parameters. Evaluation with MSE and select the best tuning parameter.
   - Build a non-linear model to predict salary using age. Collect the dataset from wage CSV file. Compute the summary statistic to clean dataset. Build polynomial regression and step function. Use 5-fold cross-validation to select the optimal degree of the polynomial and the optimal number of cuts for the step function. View the cross-validated MSE vs. the parameters and chose the best one based on the graph.
   - Build a SVC/Random Forest model for Indian patients with liver disorders to the disease. Collect a dataset of Indian liver disorder patient records. Compute the summary statistic, clean up missing values by replacing them with the mean, and look the correlation between features. Split the data with train/test and use 5-fold cross-validation to select the best hyperparameter for the SVM (AUC: 76%) and Random Forest (AUC: 75%) model.
   - Build a K-means clustering: Generate 2-dimentional dataset with 500 observations from 3 Gaussian clusters. Visualize the data with scatterplot. Shuffle the data and use 2, 3, 4 - means cluster. Visualize the result.



## Courses

1. Probability and Statistics:
   - Basics of probability & statistics, visualization
2. Introduction to Statistical Learning and Regression Analysis:
   - Statistical Learning (Supervised & Unsupervised, Estimation), simple & multiple linear regression 
3. Introduction to Classification: 
   - General framework, hard vs soft classifiers, logistic regression, discriminant analysis, naive bayes
4. Model Evaluation and Resampling:
   - Regression & classification models, cross-validation and resampling
5. Model Selection, Regularization, and Dimensionality Reduction:
   - Pros & cons & possible improvements at linear models, variable selection, shrinkage mothods, dimension reduction vs variable selection, Principal component analysis
6. Beyond Linearity:
   - Polynomial regression, step functions, regression with basis functions, regression splines, generalized additive models <br />
7. Decision Trees:
   - Regression trees (construction recipe and loss function), classification tree (choice of the cost function) 
8. Tree-Based Methods:
   - Ensemble mothods for trees (bagging, random forests, boosting) <br />
9. Support Vector Machines:
   - Linear classifiers, linear separability, support vector machines (maximum margin principle, soft margin, more extreme cases, kernel method) <br />
10. Introduction to Unsupervised Learning:
    - Cluster analysis (k-means & hierarchical clustering) <br />

## Bibliography
* [An Introduction to Statistical Learning](https://hastie.su.domains/ISLR2/ISLRv2_website.pdf)
* [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
