# Advertising-Dataset---Exploratory-data-analysis-and-Machine-Learning-Classification

In this project, I worked on an advertising data set, indicating whether or not a particular internet user clicked on an Advertisement. I performed Exploratory Data Analysis and developed several Machine Learning Classification models that predicts whether or not a user will click on an ad based off the features of that user.

This data set contains the following features:

- 'Daily Time Spent on Site': consumer time on site in minutes
- 'Age': cutomer age in years
- 'Area Income': Avg. Income of geographical area of consumer
- 'Daily Internet Usage': Avg. minutes a day consumer is on the internet
- 'Ad Topic Line': Headline of the advertisement
- 'City': City of consumer
- 'Male': Whether or not consumer was male
- 'Country': Country of consumer
- 'Timestamp': Time at which consumer clicked on Ad or closed window
- 'Clicked on Ad': 0 or 1 indicated clicking on Ad

## Conclusion

### **Model Comparison**

| **Parameter** | **Logistic Regression** | **KNN** | **Decision Tree** | **Random Forest** | **SVM** |
| --- | --- | --- | --- | --- | --- |
| **Accuracy** | 0.91 | 0.94 | 0.95 | 0.95 | 0.97 |
| **Precision** | 0.94 | 0.99 | 0.96 | 0.96 | 0.99 | 
| **Recall** | 0.87 | 0.90 | 0.94 | 0.94 | 0.95 | 
| **F1-Score** | 0.91 | 0.94 | 0.95 | 0.95 | 0.97 |

- The confusion matrix provides more insight into the accuracy of a predictive model and which classes are being predicted correctly, which incorrectly, and what type of errors are being made.
- For the Advertisements Dataset, 5 different machine learning models were developed to predict if a person would click on the advertisements or not provided we have information about the dependent variables.
- From the summary provided, it is evident that the SVM model works slightly better than all other models.
- While SVM turned out to be the best model, it looks like Logistic regression is the worst model out of all for this particular dataset. Overall, SVM has a high Classification Accuracy.
- In all the classification models, the test and train dataset was split randomly. However, the models can be further improved by using Cross-Validation method for splitting the data into test and train. The way the data is resampled has the potential to affect the overall quality of the model.
- The input parameters can be further tuned to improvise the quality of the model. No attempt was made to tune the parameters except the SVM model, as the accuracy was already high. There is always a slight risk of overfitting the model if the parameters are tuned extensively.

-- **Deepansh Arora**
