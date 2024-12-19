# Adverse-effects-of-Drugs
GlobalXYZ, a pharmaceutical company, provided a dataset from a randomized controlled drug trial to assess adverse drug reactions. The dataset contains demographic information, medical data (e.g., white blood cell counts), and observations on adverse effects, with a focus on predicting whether an individual experienced any adverse reactions. Various machine learning models—KNN, Decision Tree, Random Forest, XGBoost, and a Voting Classifier—were applied to identify patterns and predict outcomes.
![AdobeStock_627493260](https://github.com/user-attachments/assets/36c9e14f-4ccd-4ca1-9bf2-ecc46f7e8ebe)

### Results
KNN: Achieved moderate performance with a test accuracy of 72.44%, but it was less effective than other models.
Decision Tree: Showed good accuracy (81.83%) but had slight overfitting, with high training accuracy (90.33%).
Random Forest: Delivered the best individual performance, with a test accuracy of 84.46% and a balanced precision-recall score, making it reliable for predictions.
XGBoost: Matched Random Forest in test accuracy (84.40%) and provided higher precision (88.96%), though with slightly lower recall.
Voting Classifier: Combined the strengths of all models, achieving robust test accuracy (84.33%) and a good balance between precision (85.12%) and recall (83.01%).
Overall, Random Forest and the Voting Classifier emerged as the top-performing models for predicting adverse effects.
