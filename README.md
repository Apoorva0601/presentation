Slide 1: Title / Introduction

This project focuses on Early Prediction of Neonatal Hypoxic-Ischemic Encephalopathy (HIE), a type of brain injury caused by insufficient oxygen supply during or just after birth. HIE is a major cause of death and long-term disability in newborn babies worldwide. Identifying this condition early is very important for saving lives and reducing complications.

The brain damage caused by HIE happens because oxygen is crucial for brain cells to function properly. When the oxygen supply is reduced, brain cells start to die, leading to severe outcomes. However, diagnosing HIE soon after birth is difficult because the early symptoms can be vague or similar to other conditions.

Studies show that treatment within the first six hours after birth can significantly improve outcomes for affected babies. So, early detection is critical to allow doctors to intervene quickly and prevent further brain damage. This project aims to build a tool that helps with early diagnosis.

To achieve this, we developed a machine learning model combined with a simple, interactive program doctors can use easily. This tool can support faster, more accurate diagnosis of HIE in newborns, especially where advanced medical devices may not be available.

Slide 2: Problem Statement

Currently, diagnosing HIE relies on tests like MRI scans or EEG, which show brain activity and injury signs. However, these tools are expensive, require specialist staff, and are not available in all hospitals, especially in resource-limited settings. This limits timely diagnosis and treatment.

Additionally, the early signs of HIE are often unclear or subtle, making it difficult for doctors to identify the problem quickly based on physical symptoms alone. Because of this, many babies are diagnosed late, reducing the chances of successful treatment.

Hospitals lack a simple, real-time tool that can help doctors predict which newborns are at risk of HIE using commonly available clinical information. A practical and easy-to-use solution is needed to support faster decisions.

Therefore, our project addresses the need for a simple, accessible, and reliable tool that can be used in real hospital settings to detect HIE early and enable prompt neonatal care.

Slide 3: Objectives

The primary goal of this project is to build a predictive model that can accurately identify newborns at risk of HIE as early as possible. This model uses clinical and neonatal data collected soon after birth, helping doctors make quicker decisions.

We chose the Random Forest algorithm because it performs well with medical datasets, handling complex relationships between features and giving high accuracy. Random Forest is robust and less likely to overfit the data, making it a reliable choice.

In addition to the model, we developed a Graphical User Interface (GUI) that allows hospital staff to enter baby’s information and get a clear, color-coded risk prediction. This makes the tool easy to use without technical expertise.

Our overall objective is to improve neonatal care by enabling faster detection and intervention, thus reducing brain injury caused by delayed treatment of HIE in newborns.

Slide 4: Literature Review

We reviewed past research on early detection of HIE using different machine learning models and clinical approaches. Many studies highlight the potential of machine learning to analyze clinical data and predict neonatal outcomes more accurately than traditional methods.

Most existing models, however, depend heavily on advanced diagnostic tests like MRI and EEG, limiting their practical use in many hospitals that lack these facilities. This motivated us to find alternative approaches using simpler, readily available data.

Some recent studies have shown promising results using clinical indicators such as Apgar score and seizure history to predict HIE. We built on this idea by combining several clinical features into our model.

Our literature review helped us understand which features are most predictive of HIE and how to design a model that balances accuracy with practicality for real hospital settings.

Slide 5: Dataset

Our dataset was collected from Father Muller Hospital and contains clinical data on newborns and their mothers. The data includes maternal health history, birth details, and neonatal information like Apgar scores, feeding difficulties, seizure events, and EEG results when available.

Key features such as the Apgar score are important because they provide quick assessments of the newborn’s health immediately after birth. Other features like seizures are critical warning signs for brain injury.

The dataset was anonymized to protect patient privacy and cleaned to remove errors or inconsistencies. We also balanced the data so the model could learn equally from both HIE-positive and HIE-negative cases.

A clean, balanced, and comprehensive dataset is essential to train a machine learning model that performs well and generalizes to new cases.

Slide 6: Methodology

Our methodology included several steps: data collection, preprocessing, model training, and GUI development. First, we collected and cleaned the hospital data, handling missing values and preparing it for analysis.

We selected the Random Forest algorithm for the predictive model due to its ability to handle mixed data types and its strong accuracy in medical data classification problems. This model learns patterns from the training data to predict HIE risk.

The dataset was split into training (80%) and testing (20%) subsets. The model was trained on the larger portion and then tested on unseen data to evaluate its accuracy and robustness.

We then developed a GUI using Python’s Tkinter library. The GUI allows hospital staff to input patient data manually and get color-coded risk predictions instantly, helping doctors make quick decisions without needing advanced computing knowledge.

Slide 7: Results

The Random Forest model achieved an accuracy of approximately 90% on the training data and 88% on the test data, showing good performance in predicting HIE. The model’s ROC-AUC score of 0.83 confirms its strong ability to distinguish between babies with and without HIE.

The GUI displays results using clear color codes: green for low risk, yellow for moderate risk, and red for high risk. This visual aid helps doctors quickly understand the risk level without complex interpretation.

Such a system can significantly reduce the time required to identify high-risk newborns, allowing earlier intervention and improving health outcomes.

Overall, these results demonstrate the model’s potential to assist clinical decision-making and enhance neonatal care quality.

Slide 8: Challenges

One of the main challenges was the small dataset size, which was collected from a single hospital. This limits how well the model may perform when used in other hospitals or regions without further testing and adaptation.

The dataset had some missing values and an imbalance between the number of babies with and without HIE, which can affect the model’s accuracy and reliability.

Another challenge is that the GUI currently requires manual data entry, which introduces the risk of human errors. Automating data input could improve accuracy and usability in the future.

Finally, more diverse and larger datasets are needed to improve the model’s generalizability and ensure it works well across different populations and clinical settings.

Slide 9: Conclusion

In conclusion, this project successfully developed a Random Forest-based model that predicts neonatal HIE early with high accuracy. The model uses clinical data easily available at birth, making it practical for real-world hospital use.

The GUI provides an easy way for medical staff to input data and receive quick, clear predictions, helping speed up diagnosis and treatment decisions.

This tool has the potential to improve neonatal care, especially in hospitals with limited access to advanced diagnostic tools like MRI and EEG.

Future work will focus on expanding the dataset, improving data input methods, and validating the model in multiple hospitals to make it more robust and widely usable.

Final: Thank You

Thank you very much for your attention. I hope this presentation has helped you understand how machine learning and simple technology can improve early detection of HIE in newborns.

I am happy to answer any questions you have about the project or explain any part in more detail.

Please feel free to ask!
