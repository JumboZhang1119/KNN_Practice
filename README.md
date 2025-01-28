# Summary of K-Nearest Neighbors (KNN) Processing Steps
1. **Import Necessary Functions and Download the Specified Kaggle Dataset**
   
   > Begin by importing the required functions and downloading the designated Kaggle dataset.
2. **Remove Data with a Mix of English and Numerals (Having Minimal Impact on Classification Features)**  

   > Exclude data instances that combine English and numerals, as these have minimal influence on classification features.
3. **Calculate the Feature Correlation Matrix Using the Feature Correlation Matrix**

    > Utilize the feature correlation matrix to assess the relationships between each feature and theclassification labels.
4. **Select the Most Relevant Features from the Training and Testing Sets**
   
    > Identify the most highly correlated features with the training and testing datasets.
5. **Evaluate Accuracy Using a KNN Model**

    > Assess accuracy by feeding these features into a KNN model for testing.
6. **Enhance Precision with Normalization and Weight**

    > Improve precision by introducing normalization and weighting techniques.
