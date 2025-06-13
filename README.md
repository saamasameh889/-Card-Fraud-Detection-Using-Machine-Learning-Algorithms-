# Card Fraud Detection Using Machine Learning Algorithms

Credit Card Fraud Detection on IEEE-CIS Dataset: A Comparative and Explainable Machine Learning Approach

# Abstract

This project performs a comparative analysis of several machine learning models applied to the IEEE-CIS Fraud Detection dataset. We explore the efficacy of Logistic Regression, Random Forest, SVM, Decision Tree, Naive Bayes, MLP, and XGBoost in identifying fraudulent transactions in a highly imbalanced dataset. We also incorporate interpretability techniques like SHAP, LIME, PDP, ICE, and PFI to explain and justify model decisions. Our results highlight the effectiveness of ensemble models and the importance of explainable AI in fraud detection.

# Introduction 
This project addresses the real-world problem of credit card fraud detection using machine learning and explainable AI. It focuses on answering two research questions:

RQ1: How do traditional ML models perform on a highly imbalanced dataset compared to previous research?

RQ2: Which model balances accuracy and interpretability effectively?

# Dataset
We use the IEEE-CIS dataset from Kaggle, containing over 590,000 transaction records, with anonymized features and a binary target indicating fraudulent or legitimate transactions.

# Related Work
Previous research has shown high accuracy with models like Random Forest and XGBoost, but most studies neglect interpretability. Our project bridges this gap by integrating XAI tools.

# Preprocessing
Missing Value Handling: Dropped or imputed.

Feature Scaling: Standard Scaler / MinMax.

Categorical Encoding: Label/One-Hot.

Train-Test Split: 80-20 split with stratification.

Imbalance Handling: SMOTE, class weighting.

# Models Implemented

Logistic Regression

Random Forest

Decision Tree

Naive Bayes

# Install dependencies:
pip install -r requirements.txt

Usage
Run the colab files

# Results and Findings
Best Performance: XGBoost and Random Forest achieved the highest AUC and F1 scores.

Interpretability: Decision Trees and Logistic Regression were easier to explain but less accurate.

Class Imbalance: SMOTE improved model sensitivity significantly.

# Explainability & Interpretability
SHAP: Revealed top influencing features like TransactionAmt and ProductCD.

LIME: Explained individual high-risk transactions.

PDP & ICE: Showed marginal and individual feature effects.

PFI: Validated feature importance rankings.

Visual outputs are saved in the outputs/ folder.

# Conclusion
This study confirms that ensemble models like XGBoost outperform others in fraud detection tasks but at the cost of interpretability. Explainable AI tools are essential for real-world deployment, enhancing model transparency and trust.

# References
1-Credit card fraud detection using state-of-the-art machine learning and deep learning algorithms. IEEE Access, 10, 3166891.https://doi.org/10.1109/ACCESS.2022.3166891

2- Review of machine learning approach on credit card fraud detection." Human-Centric Intelligent Systems 2.1 (2022

3- Credit Card Fraud Detection using Machine Learning Algorithms. Procedia Computer Science, 165, 631–641. https://doi.org/10.1016/j.procs.2020.01.057

4- Credit card fraud detection using machine learning techniques: A comparative analysis," 2017 International Conference on Computing Networking and Informatics (ICCNI), Lagos, Nigeria, 2017, pp. 1-9, doi: 10.1109/ICCNI.2017.8123782.

5-Performance Evaluation of Machine Learning Algorithms for Credit Card Fraud Detection. 2019 9th International Conference on Cloud Computing, Data Science & Engineering (Confluence).doi:10.1109/confluence.2019.8776925 

6-Real-time Credit Card Fraud Detection Using Machine Learning. 2019 9th International Conference on Cloud Computing, Data Science & Engineering (Confluence). doi:10.1109/confluence.2019.8776942

7-Credit Card Fraud Detection - Machine Learning methods. 2019 18th International Symposium INFOTEH-JAHORINA (INFOTEH). doi:10.1109/infoteh.2019.8717766.

8-An advanced machine learning algorithm for fraud financial transaction detection. Journal for Innovative Development in Pharmaceutical and Technical Science, 4(9), September. ISSN(O): 2581-6934. https://jidps.com/wp-content/uploads/An-advanced-machine-learning-algorithm-for-fraud-financial-transaction-detection.pdf.

9-Credit Card Fraud Detection Using Machine Learning. 2020 4th International Conference on Intelligent Computing and Control Systems (ICICCS). doi:10.1109/iciccs48265.2020.9121

10- A Comparative Study of Machine Learning Techniques for Credit Card Fraud Detection Based on [11]Time Variance. 2018 IEEE Symposium Series on Computational Intelligence (SSCI). doi:10.1109/ssci.2018.8628930

11- Financial statement fraud detection: An analysis of statistical and machine learning algorithms. Auditing: A Journal of Practice & Theory

12- Machine learning for credit card fraud detection systems." International Journal of Applied Engineering Research 

