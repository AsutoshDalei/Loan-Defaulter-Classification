
Loan-Defaulter-Classification

Project Members:

•	Shruti Gajipara 121233882 shruti01@umd.edu

•	Aayush Verma 121331076 aver23@umd.edu

•	Premal Shah 121293596  shah1305@umd.edu

•	Asutosh Dalei 120997754 asutoshd@umd.edu

Introduction

In consumer finance, lending money is a delicate balance between opportunity and risk. Loan providing companies often face challenges in lending to individuals with insufficient or non-existent credit history, thus facing the challenge of identifying potential customers who can responsibly manage their loans. This project aims to tackle that challenge by analysing historical data to identify patterns that can help predict which applicants are likely to default on their loans.
The lack of credit history information can lead to adverse outcomes, where some consumers exploit the situation and become defaulters. In this context, our project addresses two critical risks associated with loan approval decisions:
•	Opportunity Loss: Failing to approve loans for applicants who are capable of repaying them results in missed business opportunities.
•	Financial Loss: Approving loans for applicants likely to default can lead to significant financial losses for the company.

Methodology

•	To mitigate these risks, this project leverages a unique Meta-Modeling approach that combines the strengths of two powerful machine learning algorithms: CatBoost, a gradient boosting model known for its superior handling of categorical data and imbalanced datasets, and One-Class SVM, a robust anomaly detection algorithm designed to focus on the minority class of loan defaulters.
What sets this project apart is its innovative use of a meta-classifier, which dynamically integrates predictions from these two distinct models to optimize classification accuracy. By utilizing historical application data, the project incorporates advanced feature engineering techniques to extract meaningful patterns, correct data inconsistencies, and handle missing values intelligently.
This dual-model framework not only improves predictive performance but also enhances interpretability by aligning each component with specific business challenges. CatBoost excels at identifying general patterns across all applicants, while the One-Class SVM provides deep insights into anomalies within the minority defaulter class. Together, these models, guided by a Random Forest meta-classifier, create a seamless decision-making system that empowers loan providers to maximize profits and minimize risk.
By addressing both opportunity loss and financial loss, this project exemplifies how cutting-edge machine learning techniques can be tailored to solve high-stakes problems in consumer finance with precision and reliability.

Key Insights:

1.	Top Features:
o	Higher income-to-loan ratios and longer credit history reduce default risk.
o	Prior defaults strongly predict future defaults.

2.	Anomalies:
o	One-Class SVM identified high-risk cases with unusual patterns like high loans or short credit history.

3.	Class Imbalance:
o	Balanced using oversampling and weighted loss to improve fairness.

4.	Model Performance:
o	The Meta-Classifier (CatBoost + SVM) achieved an AUC-ROC of 0.92, balancing precision and recall.

5.	Business Impact:
o	Reduces missed opportunities by approving reliable applicants.
o	Flags risky defaulters to cut financial losses.

Conclusions:
1.	Effective Solution: Machine learning accurately predicts loan defaults using a combined model approach.
2.	Scalable & Actionable: The framework is adaptable for fraud detection or healthcare risks.
3.	Fair & Ethical: Ensures unbiased predictions for better decision-making.

