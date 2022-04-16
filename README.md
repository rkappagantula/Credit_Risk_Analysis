# Credit_Risk_Analysis


The objective of this project was to use machine learning models to analyze credit risk to provide a quicker and more reliable loan experience. Using these models, will help accurately identify good candidates for loans which could help a financial institution decrease their default rate on their loans. I was able to build and evaluate several machine learning algorithms to predict credit risk. 

## Resources
- Dataset: 
  - LoanStats_2019Q1.csv

- Software used:
  - Python
  - Jupyter Notebook
  - NumPy, scikit-learn, and imbalanced-learn libraries
  - Logistic Regression and Random Forest models
  - Ensemble and resampling techinques

## Results


**- Naive Random Oversampling:**

![image](https://user-images.githubusercontent.com/96051648/163658808-4efb0fe1-2d1f-4716-810c-e5e2fe808ecb.png)

**- SMOTE Oversampling:**

![image](https://user-images.githubusercontent.com/96051648/163658822-65c55fd5-704f-420d-be62-2dbf7d893ecf.png)


**- Undersampling:**

![image](https://user-images.githubusercontent.com/96051648/163658863-73860b61-dfa2-453a-9573-afb7ec97c0b6.png)


**- Over and UnderSampling:**

![image](https://user-images.githubusercontent.com/96051648/163658880-c263a63d-f2bf-49b1-a07b-e93f40cb05d4.png)


**- Balanced Random Forest Classifier:**

![image](https://user-images.githubusercontent.com/96051648/163658898-9a478888-beba-4250-942d-8dd187c7a554.png)


**- Easy Ensemble AdaBoost Classifier:**

![image](https://user-images.githubusercontent.com/96051648/163658909-474ceefc-67bb-4b8b-a3a8-f8df0b37db43.png)


## Summary

In financial industry, sensitivity is more valuable than precision for analyzing risk and default rates on loan candidates, because banks want to be able to mark all of the high-risk individuals as high-risk for them not to default. It doesn't matter if it is not as precise as long as the posible defaults are marked as that. The highest one was the Easy Ensemble AdaBoost Classifier with 7% precision which is still considered pretty low for finding these high risk individuals not to give loans to. This means that out of all the customers marked as high-risk 7% were actually high-risk. 

The model with the highest sensitivity was the easy ensemble adaboost classifier (91% for high-risk and 94% for low-risk individuals), meaning that 91% of the time all the high-risk individuals are marked as high-risk individuals. 

The accuracy score stands for how correct was the model, meaning out of all the predictions how many of them were true to the classification. As we were able to see, the model with the highest accuracy score by far was the Easy Ensemble AdaBoost Classifier. and is recommended because of its high accuracy, highest precision, and highest sensitivity. 

