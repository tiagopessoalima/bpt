# bpt
Blood Prediction Tool (BPT)

Introduction: Blood transfusion is a common practice in cardiac surgery, despite its well-known negative effects, such as increased risk of infection, transfusion-related acute lung injury, and transfusion-related immunomodulation. To mitigate the risks associated with blood transfusions, identifying patients who are at higher risk of needing this procedure is crucial. Furthermore, the limited availability of blood products emphasizes the need for strategic preventive measures. The Transfusion Risk and Clinical Knowledge (TRACK) and Transfusion Risk Understanding Scoring Tool (TRUST) are currently widely used risk scores to predict the need for blood transfusions. However, these scoring systems have yielded unsatisfactory results when validated for the Brazilian population. Methods: In this retrospective study, Machine Learning (ML) algorithms were compared to predict the need for blood transfusions in a cohort of 495 cardiac surgery patients treated at a Brazilian reference service between 2019 and 2021. Demographic data, comorbidities, preoperative laboratory tests, surgical characteristics, and transfusion outcomes were collected from electronic medical records, and only the most relevant variables for predicting blood transfusion were included through feature selection. Bayesian optimization was employed to tune hyperparameters, and the ML algorithms evaluated in the study were Support Vector Machines (SVM), Random Forest (RF), Logistic Regression (LR), and Multi-Layer Perceptron (MLP). The models' robustness was ensured through k-fold cross-validation. The performance of the models was evaluated using various metrics, including the Area Under the Receiver Operating Characteristic Curve (AUC), and compared to the commonly used TRACK and TRUST scoring systems. Results: The study found that the LR model had the highest performance, achieving an AUC of 0.7350 (CI: 0.7203 to 0.7497). Importantly, all ML algorithms performed significantly better than the commonly used TRACK and TRUST scoring systems in clinical practice. Specifically, the TRACK system had an AUC of 0.6757 (CI: 0.6609 to 0.6906), while the TRUST system had an AUC of 0.6622 (CI: 0.6473 to 0.6906). These results suggest that ML algorithms may offer a more accurate prediction of the need for blood transfusions than the traditional scoring systems. Conclusion: The findings of this study suggest that ML algorithms could enhance the accuracy of predicting blood transfusion requirements in cardiac surgery patients. Feature selection and hyperparameter optimization techniques were utilized to fine-tune the ML algorithms, resulting in improved precision. In contrast, the TRACK and TRUST scores rely on a limited number of variables and may not be as effective in predicting transfusions in different populations. Further research could focus on optimizing and refining ML algorithms to improve their accuracy and make them more suitable for clinical use.