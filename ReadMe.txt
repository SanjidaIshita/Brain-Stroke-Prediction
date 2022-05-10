#Brain Stroke Prediction

#Introduction: A stroke occurs when a blood vessel in the brain ruptures and bleeds, or when there’s a blockage in the blood supply
to the brain. The rupture or blockage prevents blood and oxygen from reaching the brain’s tissues. Without oxygen, brain cells and 
tissue become damaged and begin to die within minutes.

The dataset contains 250 real world observations and 11 different attributes

#Attribute:

1.Gender: 'Male' or 'Female'
2.Age: age of patient
3.Hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension.
4.Heart Disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
5.Marital Status: 'No' or 'Yes'
6.Work Type: 'Private' or 'Self-employed' or 'Govt_job' or 'Never_worked' or 'children'
7.Residence Type: 'Rural' or 'Urban'
8.Avg Glucose Level: average glucose level in blood
9.BMI: body mass index
10.Smoking Status: 'never smoked' or 'formerly smoked' or 'Unknown' or 'smokes'
11.Stroke: 1 if the patient had a stroke or 0 if not

#Model: Here I used 2 types model-

1.SVM(Support Vector Machine) Classifier.
2.Decision Tree Classifier

#Main Functionalities:

1. Import sklearn libraries
2. Openning the dataset
3. Handling missing value
4. Exchanging class to numerical values
5. Histogram features
6. Data Processing: 
    a.Balance target(Stroke) class
    b.Handling Imbalanced Class
    c.Data Splitting
    d.Data Normalization
7. Model Trainning and Evaluation
    a.Performance Matric
    b.SVM(Support Vector Machine) Classifier
    c.Decision Tree
8. Performance comparison between 2 models(SVM and DT)





