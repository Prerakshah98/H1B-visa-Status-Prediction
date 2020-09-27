# H1B-visa-Status-Prediction
**DATASET**- https://www.kaggle.com/nsharan/h-1b-visa <br />
In recent times, H1B visas have become the most demanded visa. It is a visa that is filed for highly skilled foreign nationals every year. The allocation of these visas is said to be a lottery method which does not rely on any criteria. There is a sense of uncertainty, employers find talents that fit their requirement, but they are unable to provide a sense of security. The H1B visa application process depends on factors like salary, work location, full-time employment etc. In this project, we are given a data based on the visa applications filed from 2011 to 2016. I processed the data and used Sklearn train test split method to randomly split into training set and test set, so that we can run model on the training set and measure the performance on the test set. The baseline models were Naïve Bayes, Random Forest, and XGBoost. Our aim is to outperform their results and train the data on new deep learning models like Neural Networks and Convolutional Neural Networks.
The goal of the project is to classify the H1B status based on the data provided by Office of Foreign Labor Certification (OFLC) [**DATASET**](https://www.kaggle.com/nsharan/h-1b-visa). We used Employer name, Prevailing wage, SOC (Standard Occupational Classification) name, Job title, Full time position, year and worksite as the inputs and predicted the case status as the output. We predicted the Case status as 1 and 0. 1 represents the certified while 0 represents the denied status. We added multiple features like Occupation, and State extracted from the columns to improve our efficiency of our model and to derive meaningful insights. Additionally, we selected the important features from running on the classification models and ran on the deep learning models.
3
