We will conduct a comprehensive analysis of the dataset, focusing on identifying key features that influence outcomes. To achieve this, we will employ Logistic Regression and TabNet models to discern feature importance.

For basic visualization see `Basic_about_dataset.ipynb`.

# Dataset Explanation
- id: Unique identifier for each patient.
- age: Age of the patient.
- ER: Estrogen Receptor status, which is a marker used in breast cancer diagnosis. A value of 1 might indicate positive status, and 0 negative.
- PR: Progesterone Receptor status, similar to ER, where 1 could indicate positive status and 0 negative.
- HER2: Human Epidermal growth factor Receptor 2 status, another marker used in breast cancer diagnosis. 1 might indicate HER2 positive status, and 0 HER2 negative.
- KI67: A protein marker used to determine the growth fraction of a given cell population. The higher the number, the more the cells are growing and dividing.
- Met: Indicates the presence of metastases, where 1 might mean metastases are present, and 0 absent.
- Death: Indicates if the patient has died (1) or is still alive (0).
- AgeGrd: Age group classification of the patient, with numerical values representing different groups.

This dataset could be used for several purposes, including:

- Medical Research: Analyzing factors that contribute to breast cancer outcomes.
- Predictive Modeling: Developing models to predict patient outcomes based on their clinical data.
- Healthcare Policy Making: Informing decisions on treatment guidelines and resource allocation.
- Educational Use: As a case study in bioinformatics, statistics, or health sciences courses.
