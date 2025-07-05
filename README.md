README for Securing Machine Learning Models - privacy project
Overview - This project focuses on privacy-preserving methods for machine learning models, specifically applied to sensitive health data. Various anonymization and differential privacy techniques are implemented to ensure data privacy while maintaining utility. Contents

Introduction - Overview of the project and the importance of privacy-preserving techniques in handling sensitive health data.

Problem Statement - Addressing the risks of exposing or misusing personal health data when training machine learning models.

Results - Evaluation of privacy-preserving techniques applied to a neural network model predicting systolic and diastolic blood pressure. Techniques include k-Anonymity, l-Diversity, m-Invariance, t-Closeness, and Differential Privacy.

Conclusion - Summary of findings and effectiveness of different privacy-preserving methods. Key Sections

Introduction - Focuses on the application of privacy-preserving techniques to datasets for machine learning models handling sensitive health data. Methods include k-Anonymity, l-Diversity, m-Invariance, and t-Closeness to anonymize data, ensuring privacy and data utility.

Problem - Primary issue: risk of exposing sensitive health data during neural network training. Approach: implementing and evaluating the effectiveness of anonymization techniques and differential privacy to protect data privacy.

Results - Standard Neural Network Training a neural network model to predict systolic and diastolic blood pressure using cleaned datasets.

Application of Privacy Techniques -

k-Anonymity: Generalizes quasi-identifiers to ensure each record is indistinguishable from at least k-1 others. l-Diversity: Ensures each group of records sharing the same quasi-identifiers has diverse values for the sensitive attribute. m-Invariance: Maintains the sensitive attribute invariant across groups sharing the same quasi-identifiers. t-Closeness: Ensures the distribution of the sensitive attribute in each group is close to its distribution in the overall dataset. Comparison of predictions from neural network models trained on secured vs. non-secured datasets.

Application of Differential Privacy Technique - Applying differential privacy to predictions with varying levels of noise (epsilon values). Evaluation of the trade-off between privacy and accuracy. Reconstruction Attack Testing the effectiveness of privacy techniques against reconstruction attacks, aiming to infer original data from model predictions. Inversion Attack Evaluating privacy techniques against inversion attacks, attempting to infer sensitive features from model predictions.

Conclusion - t-Closeness is identified as the most effective technique in balancing privacy and data utility. Differential privacy shows varying levels of effectiveness based on the epsilon value, highlighting the need for careful calibration.
