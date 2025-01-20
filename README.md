Project Title: "Cerebral-Stroke-Prediction" for predicting whether a patient will suffer from a stroke, in order to provide timely interventions.


Input Features:

id: A unique identifier for each patient in the dataset.

gender: The gender of the patient, which can be "Male" or "Female".

age: The age of the patient, represented in years.

hypertension: Information about the patient's hypertension status, with a value of 0 if absent and 1 if present.

heart_disease: Information about the patient's heart disease status, with a value of 0 if absent and 1 if present.

ever_married: Information about the patient's marital status, which can be "No" (Not married) or "Yes" (Married).

work_type: The patient's type of work, which can be "Private", "Self-employed", "Govt_job", "children", or "Never_worked".

Residence_type: The patient's type of residence, which can be "Urban" or "Rural".

avg_glucose_level: The patient's average blood glucose level.

bmi: The patient's body mass index (BMI), calculated from height and weight.

smoking_status: Information about the patient's smoking status, which can be "never smoked", "smokes", or "formerly smoked".

stroke: The target variable, with a value of 0 if the patient does not suffer from a stroke and 1 if the patient has had a stroke.



Project Introduction: My project is titled "Cerebral-Stroke-Prediction", with the goal of predicting whether a patient will suffer from a stroke so that timely interventions can be provided. The input data is sourced from Kaggle, and this dataset is severely imbalanced, so we need to apply techniques like UnderSampling to balance the data.

The most effective model for this case is SVM (Support Vector Machine), and using UnderSampling yielded the best results.

I have written the code with clear explanations in Vietnamese to assist Vietnamese users.

After completing the project, I deployed it on Streamlit for experimentation and achieved good results. You can check it out here: https://dp-machine-predict.streamlit.app/.

This is the project I have worked on and completed. If you find it useful, I would appreciate your support.

Thank you!
