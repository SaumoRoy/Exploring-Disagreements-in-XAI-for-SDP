# Exploring Disagreements in XAI Techniques for Software Defect Prediction: An In-Depth Evaluation
Software defects can cause significant problems in software development, leading to reduced software quality and increased maintenance costs. Numerous models have been introduced to predict defects; however, ensuring consistency in explaining the results of these defect prediction models remains challenging. Differences in explainer views often arise due to the varying expected properties of the models, which refer to the specific characteristics and behaviors anticipated from the model's predictions. Understanding when and if the explanations produced by various post-hoc explanation methods conflict is essential, as well as how such conflicts are resolved in practice. This understanding is crucial for improving the reliability and trustworthiness of defect prediction models, ultimately aiding developers in making informed decisions.

This research examines the disagreement problem in explainable machine learning, particularly in the context of software defect prediction. Machine learning (ML) models have been proposed to achieve accurate and reliable predictions, but feature engineering techniques, specifically feature selection strategies, are crucial for preparing input data. However, the feature selection process can only impact explainability if it is transparent and well-documented. Recently, there has been growing interest in explainable ML techniques to address these issues.
This study, which is centered on the crucial role of feature selection techniques in improving the accuracy and understandability of defect prediction models, employs explainable ML methods. The study aims to find out how well different feature selection methods, like the Chi-square Test and the Correlation Matrix with Heatmap, work at making defect prediction models work better. Experiments were conducted on 33 datasets, and the results were analyzed to evaluate the models' performance before and after applying feature selection techniques. Furthermore, a study involving 15 software developers was conducted to explore how feature selection impacts explainability by focusing on a small set of features when explaining prediction outcomes.

Our findings indicate that implementing a specific set of features can enhance both the accuracy and explainability of the model. This study highlights the significant role of feature selection in improving software defect prediction and identifies a notable research gap in this area. The need for further investigation into the interplay between feature selection and explainability in ML models is emphasized, setting the stage for future research and potential advancements in the field.

## Materials included in the Replication Package
  ### Survey Questionaires:replication_package/Survey Questionaires
* Survey.pdf is the survey form for the control group
### Survey Responses:replication_package/Survey Responses
* Survey Responses.csv contains the responses given by the control group
### Survey Result:replication_package/Survey Result
* Summary_Survey Responses.pdf contains the summarized responses  
### Data Preprocessing:XAI-in-Software-Defect-Predication-In-depth-evaluation/Jira _32 dataset/
* Supporting Documents.pdf contains data preprocessing and other experimental result
