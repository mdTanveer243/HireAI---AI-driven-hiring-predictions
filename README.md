# HireAI – AI-driven hiring predictions

## Project Overview
HireAI is a machine-learning-based project designed to predict the employability status of job seekers based on various attributes like education, experience, skills, and other professional factors. This project utilizes machine learning classification models to analyze employability trends and provide insights for job seekers and recruiters.

## Dataset Description
- **Source:** Kaggle ([70K+ Job Applicants Data](https://www.kaggle.com/datasets/ayushtankha/70k-job-applicants-data-human-resource))
- **Size:** 73,462 rows × 15 columns
- **Key Features:**
  - `Age`: Age of the applicant (binary: >35 years old or <35 years old)
  - `EdLevel`: Education level (Undergraduate, Master, PhD)
  - `Employment`: Employment status (Yes/No)
  - `YearsCode`: Number of years the applicant has coded
  - `ComputerSkills`: Number of technical skills
  - `Employed`: Target variable (Yes/No)

## Machine Learning Models Used
- **Logistic Regression**
- **Decision Tree Classification**
- **Support Vector Machine (SVM)**
- **Naive Bayes**
- **Random Forest Classification**
- **Kernel SVM**
- **K-Nearest Neighbors (KNN)**


## Model Performance
| Model                | Accuracy (%) | F1 Score |
|----------------------|--------------|----------|
| Logistic Regression  | 78.70        | 0.7708   |
| Decision Tree        | 70.70        | 0.6855   |
| Kernel SVM           | **79.03**    |**0.8131**|

## Future Scope
- Develop a **web-based UI** for users to interact with the model.
- Expand the model to **predict job fit based on industry trends**.
- Integrate a **recommendation system** for career improvement.

## Conclusion
HireAI aims to help job seekers and recruiters by providing accurate employability predictions. This project demonstrates how machine learning can be applied in human resources for data-driven hiring decisions.

---
👨‍💻 **Developed by:** MD Tanveer | **Institution:** IIT Patna

