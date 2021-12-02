# AI/ML Project - Breast Cancer Diagnosis

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/144494628-74d4abb9-9f26-4c12-b499-f6fa79a56864.jpg" style="width: 1000px;"/></p>

### Description:

Breast cancer is the most common cancer amongst women in the world. It accounts for 25% of all cancer cases, and affected over 2.1 Million people in 2015 alone. It starts when cells in the breast begin to grow out of control. These cells usually form tumors that can be seen via X-ray or felt as lumps in the breast area.

The key challenges against it’s detection is how to classify tumors into malignant (cancerous) or benign(non cancerous). We ask you to complete the analysis of classifying these tumors using machine learning (with SVMs) and the Breast Cancer Wisconsin (Diagnostic) Dataset.


### Acknowledgements:
This dataset is taken from Kaggle, \
https://www.kaggle.com/c/breast-cancer-classification/data

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to predict wheather the cancer type is Malignant or Benign.
- Also fine-tune the hyperparameters & compare the evaluation metrics of vaious classification algorithms.

### <center> Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Feature Selection/Extraction
6. Predictive Modelling
7. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. Target Variable Distribution**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/144494695-5838f2d6-6a38-4dee-b063-d7d37c85660b.png" /></p>

**2. Categorical Feature-set Distribution**

**3. Numerical Feature-set Distribution**

![image](https://user-images.githubusercontent.com/54996245/144494831-8603b613-0759-4219-8232-eca3871a8ae5.png)
![image](https://user-images.githubusercontent.com/54996245/144494850-bc135961-47aa-42db-b37e-d2a64f9e0a1c.png)

**4. Relationship between the Feature-set**

![download-min](https://user-images.githubusercontent.com/54996245/144495668-0ac921f1-e3ce-48e1-856e-1784f75c93b9.png)

**5. Data Retention after preforming preprocessing step**

![image](https://user-images.githubusercontent.com/54996245/144495133-4b9c5617-3964-4168-966c-ad506fb51503.png)

**6. Correlation plot for features**

![image](https://user-images.githubusercontent.com/54996245/144495160-a18c999e-b49c-4647-b1c5-520f9f2cab3d.png)

**7. VIF & RFE Scores & PCA Decomposition**
  
![image](https://user-images.githubusercontent.com/54996245/144495198-230994ed-c7c8-4843-9c7a-f77f2e7f374c.png)
![image](https://user-images.githubusercontent.com/54996245/144495218-e3cb9c5b-1fed-44f9-a847-ce0417fb05da.png)
![image](https://user-images.githubusercontent.com/54996245/144495291-7eb061b9-e3a7-42e5-873f-cb942a36bdd9.png)

**8. ROC Plots**

![image](https://user-images.githubusercontent.com/54996245/144495351-4808e0b7-9032-4506-bb3b-8e2af5e8d780.png)

**9. Tree Plot & Feature Importance in Random Forest
  
![image](https://user-images.githubusercontent.com/54996245/144495785-b44538a9-0573-4489-a55b-6b72faac4dcd.png)
![image](https://user-images.githubusercontent.com/54996245/144495805-2ff4bc20-6b68-46b9-905c-d0c507010c6b.png)


**10. ML Algorithm's Scores for the Dataset**
  
![image](https://user-images.githubusercontent.com/54996245/144495382-21862d14-a6cb-4b90-a32f-2a0d29b78c1c.png)
![image](https://user-images.githubusercontent.com/54996245/144495393-16c7bee4-7cc3-4b8b-a48f-9ee25a9635c2.png)

  
### Here are some of the key outcomes of the project:
- The Dataset was small totally around 569 samples & after preprocessing 8.3% of the datasamples were dropped. 
- The samples were highly imbalanced, hence SMOTE Technique was applied on the data to  balance the classes, adding 21.3% more samples to the dataset.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the featureset.
- Feature Selection/Eliminination was carried out and appropriate features were shortlisted.
- Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.
- The Support Vector algorithm perform the best on the current dataset, considering Recall as the key-metric, as is relatively ok to falsely classify any patient as False Positive, but can be quiet dangerous if classified as False Negative.
- Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive.

