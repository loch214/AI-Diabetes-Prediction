# AI for Early Diabetes Prediction (IT2011 Project)

This repository contains the work for our 2nd Year, 1st Semester AI & Machine Learning module group project at SLIIT. The project focuses on building a machine learning model to predict the onset of diabetes based on key health indicators.

---

## My Individual Contribution

My primary responsibilities in this project were:

1.  **Initial Data Cleaning:** As part of the group's preprocessing pipeline, I handled implausible age values and corrected data types in the raw dataset.
2.  **Random Forest Modeling:** I was responsible for training, tuning, and evaluating a Random Forest Classifier.

---

## Files in this Repository

*   `diabetes_prediction_dataset.csv`: The original, raw dataset used for this project.

*   `pipeline.ipynb`: The complete, collaborative group notebook that performs all preprocessing steps, from initial cleaning to data balancing and feature selection.

*   `IT24100314_Random_Forest.ipynb`: My individual notebook. It loads the final preprocessed data from the pipeline and details the implementation, tuning (with GridSearchCV), and final evaluation of the Random Forest model.

*   `IT_24100314_Implausible_Data_Cleaning.ipynb.ipynb`: My initial individual notebook demonstrating the data cleaning task for the 'age' column.

---

## Final Model Performance

My final tuned Random Forest model achieved the following results on the unseen test set:

*   **Accuracy:** 90.00%
*   **AUC Score:** 0.9765
*   **Recall (for Diabetes class):** 91.35%
*   **F1-Score (for Diabetes class):** 0.6082
