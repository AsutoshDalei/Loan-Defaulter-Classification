
****Loan-Defaulter-Classification****

**Project Members:**

•	Shruti Gajipara 121233882 shruti01@umd.edu

•	Aayush Verma 121331076 aver23@umd.edu

•	Premal Shah 121293596  shah1305@umd.edu

•	Asutosh Dalei 120997754 asutoshd@umd.edu

**Introduction**

In consumer finance, lending money is a delicate balance between opportunity and risk. Loan providing companies often face challenges in lending to individuals with insufficient or non-existent credit history, thus facing the challenge of identifying potential customers who can responsibly manage their loans. This project aims to tackle that challenge by analysing historical data to identify patterns that can help predict which applicants are likely to default on their loans.
The lack of credit history information can lead to adverse outcomes, where some consumers exploit the situation and become defaulters. In this context, our project addresses two critical risks associated with loan approval decisions:
•	Opportunity Loss: Failing to approve loans for applicants who are capable of repaying them results in missed business opportunities.
•	Financial Loss: Approving loans for applicants likely to default can lead to significant financial losses for the company.

**Methodology**

This project uses a **Meta-Modeling approach** to predict loan defaults by combining two machine learning models: **CatBoost**, which handles imbalanced data and general patterns, and **One-Class SVM**, which detects anomalies in high-risk applicants. 
A **Random Forest meta-classifier** integrates their predictions for better accuracy. Advanced feature engineering ensures clean, meaningful data, improving performance and interpretability. CatBoost focuses on overall trends, while One-Class SVM highlights defaulters. Together, this system helps loan providers reduce risks, avoid missed opportunities, and make smarter decisions.
**Key Insights:**

1.	Top Features:
Higher income-to-loan ratios and longer credit history reduce default risk.
Prior defaults strongly predict future defaults.

2.	Anomalies:
One-Class SVM identified high-risk cases with unusual patterns like high loans or short credit history.

3.	Class Imbalance:
Balanced using oversampling and weighted loss to improve fairness.

4.	Model Performance:
he Meta-Classifier (CatBoost + SVM) achieved an AUC-ROC of 0.92, balancing precision and recall.

5.	Business Impact:
Reduces missed opportunities by approving reliable applicants.
Flags risky defaulters to cut financial losses.

**Conclusions:**

1.	Effective Solution: Machine learning accurately predicts loan defaults using a combined model approach.
2.	Scalable & Actionable: The framework is adaptable for fraud detection or healthcare risks.
3.	Fair & Ethical: Ensures unbiased predictions for better decision-making.

