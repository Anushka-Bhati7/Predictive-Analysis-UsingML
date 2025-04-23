# Predictive-Analysis-UsingML
COMPANY- CODTECH SOLUTION

NAME- ANUSHKA BHATI

INTERN ID- CT04DA489

DOMAIN- DATA ANALYTICS

DURATION- 4 WEEKS

MENTOR- NEELA SANTOSH
# Predictive Analysis Using Machine Learning
#  Objective
The objective of this project is to build and evaluate a machine learning classification model that can predict whether a YouTube video will go viral or not based on key features such as video title length, views, likes, category, and upload day. This task simulates a real-world scenario of using predictive analytics in the field of digital media and marketing, helping content creators and strategists make informed decisions about content optimization.

This project was developed as part of a machine learning internship under CodTech, fulfilling the requirement to create a working ML model along with proper feature selection, training, and evaluation techniques.

# Dataset Description
A structured dataset representing simulated YouTube video metadata was used, containing both numerical and categorical variables. Each row represents a single video upload, and each column describes a feature of that video.

# Features include:

* Video_ID: Unique identifier (not used in training)
  
* Title_Length: Number of characters in the video title

* Views, Likes, Comments: Engagement metrics gathered over a fixed period

* Duration: Total duration of the video in minutes

* Category: Categorical variable representing genre/type of video (e.g., Education, Tech, Entertainment) 

* Upload_Day: The day of the week the video was uploaded

* Is_Viral: Target variable — binary classification (1 = Viral, 0 = Not Viral)

# Tools and Libraries Used
* Language: Python 

* Libraries:
    * pandas, matplotlib, seaborn for data handling and visualization
      
    * scikit-learn for model training and evaluation
      
    * LabelEncoder and StandardScaler for preprocessing
  
   * RandomForestClassifier for classification modeling
# Machine Learning Workflow
1. Data Preprocessing
     * Label encoding was used to convert the categorical Category column into numerical values.
   
     * Irrelevant columns like Video_ID were dropped.
       
     * Feature scaling was applied using StandardScaler to normalize numerical features.
2. Splitting the Dataset
   
     * The dataset was split into training (80%) and testing (20%) sets to evaluate model performance effectively.
3. Model Selection and Training
     * A RandomForestClassifier was chosen due to its strong performance in classification tasks and ability to handle both numerical          and categorical data.
       
4. Model Evaluation
     * Predictions were compared against the test set.
       
     * The following evaluation metrics were used:
       
         * Accuracy
       
         * Classification Report (Precision, Recall, F1-score)
       
         * Confusion Matrix
       
         * ROC Curve and AUC Score

# Visualizations & Metrics
  * Confusion Matrix: Provided a breakdown of correct and incorrect classifications.
    
  * ROC Curve: Evaluated the trade-off between true positive rate and false positive rate.
    
  * AUC Score: Quantified model's performance (closer to 1 = better).
    
  * Achieved Model Accuracy: ~75% on test data.
    
# Outcome and Learning
This project demonstrates how supervised learning can be applied to predict real-world outcomes in the digital content space. By analyzing basic video metadata and engagement metrics, we were able to build a fairly accurate classification model that predicts the potential virality of a YouTube video. 

Key learnings:

* Importance of data preprocessing and feature selection
  
* Strengths of ensemble methods like Random Forest
  
* How to interpret evaluation metrics to improve models
  
* Visual storytelling through graphs like ROC curves and confusion matrices
  
# Deliverable
The final deliverable is a Jupyter Notebook that clearly presents:

* Data processing and cleaning
  
* Feature engineering
  
* Model training
  
* Evaluation using metrics and visualizations
  
* This fulfills the requirements for the CodTech Internship Completion Certificate under the "Predictive Analysis Using Machine Learning" task.

