# mybayesclsproject
Gaussian Classifier with PCA and Bayesian Decision Theory
This repository implements a classification pipeline using Principal Component Analysis (PCA) for dimensionality reduction, Gaussian Density Estimation for modeling distributions, and Bayesian Decision Theory for optimal classification. The pipeline is applied to a dataset of numerical features.
Key Features
1.	Data Preprocessing:
  o	Normalization of features to ensure uniform scaling.
  o	Data reshaping for compatibility with matrix operations.
2.	Dimensionality Reduction with PCA:
  o	Computation of principal components for feature reduction.
  o	Projection of data onto the top components for visualization and classification.
3.	Gaussian Density Estimation:
  o	Estimation of class-specific means and covariance matrices.
  o	Visualization of Gaussian distributions in reduced-dimensional space.
4.	Bayesian Classification:
  o	Implementation of Bayesian Decision Theory to classify data points.
  o	Visualization of decision boundaries for binary classification.
5.	Evaluation Metrics:
  o	Calculation of training and testing accuracies.
  o	Visualization of projected data and decision regions.
Technologies Used
•	Python: Core programming language.
•	NumPy: For numerical computations.
•	SciPy: For matrix operations and Gaussian distributions.
•	Matplotlib: For data visualization.
Project Structure
•	Data Preprocessing: 
  o	Normalization and reshaping of training and testing datasets.
•	Principal Component Analysis: 
  o	Eigen decomposition of the covariance matrix.
  o	Dimensionality reduction for visualization.
•	Gaussian Parameters Estimation: 
  o	Calculation of mean and covariance for each class.
  o	Visualization of class distributions.
•	Bayesian Classifier: 
  o	Implementation of posterior probability computation.
  o	Decision-making based on maximum a posteriori (MAP) estimation.
Results
•	Training Accuracy: 99.75%
•	Testing Accuracy: 99.90%
•	Visualizations include: 
  o	Projected data points onto principal components.
  o	Gaussian distributions for each class.
  o	Bayesian decision boundaries.
Getting Started
Prerequisites
•	Python 3.8+
•	Required libraries: 
•	pip install numpy scipy matplotlib
Running the Code
1.	Clone the repository: 
2.	git clone https://github.com/your-username/gaussian-classifier.git
3.	cd gaussian-classifier
4.	Run the notebook in Jupyter: 
5.	jupyter notebook
6.	Ensure train_data.mat and test_data.mat are in the same directory.
Input Data Format
•	train_data.mat: Contains: 
  o	x: Training data features.
  o	y: Training data labels.
•	test_data.mat: Contains: 
  o	x: Testing data features.
  o	y: Testing data labels.
Acknowledgments
•	Inspired by Bayesian decision theory for classification.
•	Acknowledgment to NumPy and SciPy for enabling efficient numerical computations.
