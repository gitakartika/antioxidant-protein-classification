# antioxidant-protein-classification

This project goal is to classify either the protein sequences have antioxidant property or not. To achieve this goal, we perform:

1. Feature extraction: To obtain protein feature based on their sequences
2. Feature selection: To select only impactful feature, there are two ways to get these features: 
  a) Eliminate high correlated features
  b) Perform RFECV
3. Analyze optimal SVM parameter to determined which parameter we used on hyperparameter tuning
4. Hyperparameter Tuning using SVM
5. Evaluate model using data testing
6. Analyze whether the model is overfit or not.
