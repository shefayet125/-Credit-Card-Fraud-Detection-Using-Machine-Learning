# -Credit-Card-Fraud-Detection-Using-Machine-Learning
Credit card fraud is a major issue in the financial industry, leading to significant economic losses and security concerns. This project develops machine learning models to detect fraudulent transactions with high accuracy while handling highly imbalanced data.

**Objectives:**
- Build a robust fraud detection model.
- Handle class imbalance effectively.
- Compare multiple machine learning algorithms
- Provide interpretable insights into fraud patterns.

**Modeling Approach:**
1. Isolation Forest
- Detects anomalies by isolating observations
- Works well for high-dimensional data
2. Local Outlier Factor (LOF)
- Identifies anomalies based on local density deviation
- Effective for detecting local clusters of fraud
3. PCA-Based Detection
- Reduces dimensionality
- Detects anomalies through reconstruction error
- Captures underlying structure of normal transactions

**Model Evaluation:**
- Evaluation was performed using:
- Classification Report
- Accuracy comparison
- Number of detected fraud transactions

**Results :)**
- Isolation Forest detected 5385 errors,
- Local Outlier Factor detecting 6139 errors,
- PCA detecting 492 errors.
- PCA is 100% accurate to detect fraud transaction.Isolation forest and Local Outlier Factor are both 98% accuracy.














