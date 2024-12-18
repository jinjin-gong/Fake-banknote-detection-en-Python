1. Context
   Client: National Organization for Counterfeit Money Control (ONCFM).
   Objective: Develop an algorithm to automatically detect counterfeit euro banknotes based on their dimensions and specific features.

2. Approach
   Data: Dimensions and characteristics of banknotes (real/fake included).

3. Methodology: 
   Exploratory analysis to understand patterns.
   Data cleaning and preprocessing (missing value imputation using linear regression).
   Represent relationships between variables by creating a correlation circle.
   Select prediction methods (logistic regression, K-means clustering).
   Compare the performance of two prediction methods using a confusion matrix and evaluation metrics (precision, recall, F1-score).

4. Results
   Selected Model: Logistic regression (Accuracy: 95%, AUC: 0.98).
   Impact: Fast and reliable detection of counterfeit banknotes, reducing human errors.

5. Deliverables
   Python Code: Data preprocessing, model training, and deployment.
   Test Algorithm: Allows real-time verification of new banknotes' authenticity.

6. Tools Used
   Python (Pandas, Scikit-learn), Microsoft Power BI for visualizations (Matplotlib/Seaborn).
   Visualization tools: Graphs to explore variable relationships (correlation circle, confusion matrix, elbow method).
