# Principal-Component-Analysis
Milestone Assignment 2: Principal Component Analysis (PCA)

This project implements PCA to reduce the dimensionality of the Breast Cancer dataset and optionally applies Logistic Regression for prediction.

## Steps Implemented
1. **Data Loading**: Loaded the breast cancer dataset using `sklearn.datasets`.
2. **Data Standardization**: Standardized the data to ensure all features have equal importance.
3. **PCA**: Reduced the data to 2 principal components for dimensionality reduction.
4. **Visualization**: Visualized the PCA results.
5. **Logistic Regression** (Bonus): Used the PCA-transformed data to predict cancer types and evaluated model accuracy.

## How to Run
1. Install the required libraries:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
2. Run the 'Principal_Component_Analysis.ipynb' file to execute the code.

                                                      
## Files Included
- 'Principal_Component_Analysis.zip': Consists of the README and Python script. Download and unzip to access all files.
- 'Principal_Component_Analysis.ipynb': Contains the code for the assignment.
- 'README.md': Explains the project structure and instructions.

## Results
- Explained Variance Ratio: The two principal components explain approximately 44.27% and 18.97%  of the variance in the dataset.
- Logistic Regression Accuracy: Achieved an accuracy of 99.12%.
