# YCBS-255: Statistical Machine Learning
<img width="701" alt="Capture d’écran, le 2023-06-04 à 08 08 42" src="https://github.com/MNLepage08/MNLepage08/assets/113123425/5edce3ef-fefe-42ab-a978-d2e0f628e1ef">

## :rocket: Assignments
1. [Matematical Algoritm, Descriptive & Inferential Statistics, and Linear Regression Model :](https://github.com/MNLepage08/YCBS-255/blob/main/Assignment01_(MNL).ipynb)<p>
   - Write 2 mathematical algorithm: Greatest common divisor / Prime numbers.<p>
   - Create an exponential population distribution. Generate 100 different samples from the population. Estimate the population mean using the lay of large numbers and the central limit theorem. Use appropriate visualization to describe the estimation. Draw an inference from the estimated population parameters and test the hypotheses.<p>
   - Create simulated data and fit a simple linear regression model. Fit a linear least-squares model to predict y. Use an appropriate visualization to see the sample versus the population. Explain how results change by generating data with less noise.<p>

2. [Data Exploration (distribution, correlation), Models (LR, LDA, QDA), Evaluation (confusion matrix, accuracy, AUC, F-measure), Cross-Validation, PCA:](https://github.com/MNLepage08/YCBS-255/blob/main/Assignment02_(MNL).ipynb)<p>
   - Collect the dataset from credit CSV file. Use appropriate descriptive statistical methods to describe the variables and possible associations between them. Create LR, LDA and QDA models and find the probability of a balance < 1500. Evaluate the models using the confusion matrix, precision and AUC.<p>
   - Collect all data from the ziptrain/ziptest CSV file. Select digits 2 and 7 only. Use the first 2 PCAs to separate the 2 digits. Model with logistic regression to separate the numbers. Evaluate the model with the confusion matrix, accuracy and F-Measure. With all numbers, use the LDA model with 5-fold cross-validation and select the best number of principal components.<p>
      
3. [Model (Lasso Regression, Polynomial Regression, Step Function, SVM, Random Forest), Cross-Validation for tuning parameter to chose variable selection. K-means clustering:](https://github.com/MNLepage08/YCBS-255/blob/main/Assignment03_(MNL)_v2.ipynb)<p>
   - Create simulated data and generate the y variable with multiple linear regression. Use 5-fold cross-validation with a reasonable proportion of training/testing for a lasso regression model with different predetermined tuning parameters. Evaluation with MSE and select the best tuning parameter.<p>
   - Build a non-linear model to predict salary using age. Collect the dataset from wage CSV file. Compute the summary statistic to clean dataset. Build polynomial regression and step function. Use 5-fold cross-validation to select the optimal degree of the polynomial and the optimal number of cuts for the step function. View the cross-validated MSE vs. the parameters and chose the best one based on the graph.<p>
   - Build a SVC/Random Forest model for Indian patients with liver disorders to the disease. Collect a dataset of Indian liver disorder patient records. Compute the summary statistic, clean up missing values by replacing them with the mean, and look the correlation between features. Split the data with train/test and use 5-fold cross-validation to select the best hyperparameter for the SVM (AUC: 76%) and Random Forest (AUC: 75%) model.<p>
   - Build a K-means clustering: Generate 2-dimentional dataset with 500 observations from 3 Gaussian clusters. Visualize the data with scatterplot. Shuffle the data and use 2, 3, 4 - means cluster. Visualize the result.<p>


## :mortar_board: Courses

| # | Sessions | Concepts |
| ------------- | ------------- | ------------- |
| 1 | Probability and Statistics | Basics of probability & statistics, visualization |
| 2 | Introduction to Statistical Learning and Regression Analysis | Statistical Learning (Supervised & Unsupervised, Estimation), simple & multiple linear regression |
| 3 | Introduction to Classification | General framework, hard vs soft classifiers, logistic regression, discriminant analysis, naive bayes |
| 4 | Model Evaluation and Resampling |  Regression & classification models, cross-validation and resampling |
| 5 | Model Selection, Regularization, and Dimensionality Reduction | Pros & cons & possible improvements at linear models, variable selection, shrinkage mothods, dimension reduction vs variable selection, Principal component analysis |
| 6 | Beyond Linearity | Polynomial regression, step functions, regression with basis functions, regression splines, generalized additive models |
| 7 | Decision Trees | Regression trees (construction recipe and loss function), classification tree (choice of the cost function) |
| 8 | Tree-Based Methods | Ensemble mothods for trees (bagging, random forests, boosting) |
| 9 | Support Vector Machines | Linear classifiers, linear separability, support vector machines (maximum margin principle, soft margin, more extreme cases, kernel method) |
| 10 | Introduction to Unsupervised Learning | Cluster analysis (k-means & hierarchical clustering)|      
           
      
## :books: Bibliography
      
| <img width="238" alt="An Introduction to Statistical Learning" src="https://github.com/MNLepage08/MNLepage08/assets/113123425/9482d6bc-9a9b-490f-b216-aa1bd9f43ca0">  | <img width="280" alt="Python Data Science" src="https://github.com/MNLepage08/MNLepage08/assets/113123425/6a2cc3e1-b3e5-4903-8b1d-5c67763f4656"> | 
| :-------------: | :-------------: | 
| [An Introduction to Statistical Learning](https://hastie.su.domains/ISLR2/ISLRv2_website.pdf) | [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) | 
      
