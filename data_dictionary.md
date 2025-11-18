#  Data Dictionary: AR Vocabulary Learning Dataset

This dataset includes students' **demographic information**, **interactions**, and **learning outcomes** in an Augmented Reality (AR)-based vocabulary learning application.

---

##  1. Variable Definitions

| Variable Name | Type | Description | Possible Values / Range |
| :--- | :--- | :--- | :--- |
| **User_ID** | Categorical | Unique identifier for each user. | User_1, User_2, … |
| **Age** | Numeric | User's age. | 10–18 (example range) |
| **Grade_Level** | Categorical | User's education level. | Primary, Secondary |
| **Activity_Type** | Categorical | The AR activity performed by the user. | Gamified Quiz, Real-World Task, Word Matching |
| **Duration** | Numeric (float) | Activity duration (normalized or in minutes). | 0–1 |
| **Pre_Test_Score** | Numeric (float) | Pre-activity test results (normalized). | 0–1 |
| **Engagement_Score** | Numeric (float) | Student's interaction/participation level. | 0–1 |
| **AR_Feature_Used** | Categorical | The AR feature used. | Interactive AR, Animations |
| **Feedback_Score** | Numeric (float) | Score given by the student in feedback (satisfaction). | 0–1 |
| **Accuracy** | Numeric (float) | Accuracy rate in the activity. | 0–1 |
| **Completion_Rate** | Numeric (float) | Activity completion percentage. | 0–1 |
| **Post_Test_Category** | Categorical | Post-activity achievement level (**target variable**). | High, Medium, Low |

---

##  2. Variable Groups

### Demographics
* **User_ID**
* **Age**
* **Grade_Level**

### Activity Interaction Metrics
* **Activity_Type**
* **Duration**
* **AR_Feature_Used**
* **Engagement_Score**
* **Feedback_Score**

### Performance Metrics
* **Pre_Test_Score**
* **Accuracy**
* **Completion_Rate**
* **Post_Test_Category**

---

##  3. Notes

* **Performance** and **behavior** variables have been **normalized**.
* **Post_Test_Category** can be used as the **target label** for machine learning models.
* The dataset is suitable for both **causal analysis** and **classification** projects.
