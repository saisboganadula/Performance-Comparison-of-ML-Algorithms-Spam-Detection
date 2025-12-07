# Performance-Comparison-of-ML-Algorithms-Spam-Detection

README
This document provides detailed instructions for running the machine learning experiment coded in ML_assgn_2_final.ipynb, aimed at comparing classifier performances on the Spambase dataset.

Developed BY
Sai Sukheshwar Boganadula

Code Description:

This Jupyter Notebook encompasses a sequence of operations designed to evaluate the efficiency and effectiveness of three machine learning classifiers: Random Forest, KNN (K-Nearest Neighbors), and Naive Bayes. The code is structured to perform the following tasks:

Load the Spambase dataset from its source.
Initialize the three classifiers for comparison.
Apply 10-fold stratified cross-validation to ensure an unbiased assessment of each model.
Evaluate and compare the classifiers based on three key metrics: accuracy, F1 score, and training time. Results are neatly organized into Pandas dataframes for ease of analysis.
Execute the Friedman and Nemenyi statistical tests to identify significant performance differences among the classifiers, offering a rigorous statistical basis for comparison.
Running the Code
To execute this analysis, please follow the steps outlined below:

Ensure you have Python 3 installed along with the necessary libraries: NumPy, Pandas, SciPy, and Scikit-learn. These can be installed via pip if not already available in your Python environment.


Copy code:
pip install numpy pandas scipy scikit-learn


Download the Spambase dataset and ensure that the spambase.data file is placed in the same directory as the ML_assgn_2_final.ipynb notebook to facilitate seamless data loading. You can download the dataset from UCI Machine Learning Repository.

Open and run the ML_assgn_2_final.ipynb notebook using a Jupyter environment (JupyterLab, Jupyter Notebook, or similar interfaces). This can typically be done by navigating to the notebook's directory in a terminal and executing.


Upon completion, the notebook will display comprehensive results, including accuracy, F1 scores, and training times for each classifier, alongside the outcomes of the Friedman test and the Nemenyi post-hoc analysis. These results are presented in a clear, concise manner, allowing for straightforward interpretation of the classifiers' comparative performances.

No additional configuration is required beyond setting up the specified Python environment and ensuring the dataset is correctly positioned. Should issues arise during execution, please do not hesitate to submit an issue for further assistance.
