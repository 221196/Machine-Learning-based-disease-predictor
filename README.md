# Machine-Learning-based-disease-predictor
# Problem Statement
Health information needs are also changing the information seeking behavior and can be observed around the globe. Challenges faced by many people are looking online for health information regarding diseases, diagnoses and different treatments. If a recommendation system can be made for doctors and medicine while using review mining will save a lot of time. In this type of system, the user face problem in understanding the heterogeneous medical vocabulary as the users are laymen. User is confused because a large amount of medical information on different mediums are available.The idea behind recommender system is to adapt to cope with the special requirements of the health domain related with users.
# Training.csv
This is the main dataset which has been used in this project. This dataset consist of mainly two columns "Disease" and "Symptoms" but this dataset is preprocessed so it helps in easily clasifying the data. This dataset is used to train our model.
# Testing.csv
This is the dataset which has been used to test our model so that we can know the accuracy of our model. this dataset is predefined with output.
# PythonCodeOfAlgorithm.py
This is the file which consist of dataset and there are various differnt algorithms used for training of our model which are as follows:

Decision Tree
Random Forest
Naive Bayes 
These four algorithms is used to train our model and all gives an accuracy of over 90
# Working with GUI

Step 1:
Enter the name in the provided space infront of the label as "Name of the Patient". It is the mandatory field which user have to enter in order to get result.

Step 2:
Select 5 Symptoms from the dropdown menu which are labelled as Symptom 1, Symptom 2, Symptom 3, Symptom 4, Symptom 5 respectively. If user is not aware of 5 symptoms then it is mandatory for him to enter atleast 2 starting systems, otherwise the result will not come and a message box will pop up for the same

Step 3:
As per user interest,he/she can predict the disease using different algorithms such as Decision tree algorithm, Random forest algorithm, Naive bayes algorithm and K-Nearest neighbour. According to algorithm click on buttons:
Press Prediction 1 for Decision tree algorithm
Press Prediction 2 for Random forest algorithm
Press Prediction 3 for Naive bayes algorithm

(User can predict the disease using more than one algorithm at a time)

Step 4:
Disease Recommendation will be available infront of the labels of algorithm of user's choice.

Step 5:
Click on "Reset" button to predict the disease for any other patient or Press "Exit System" button to come out of the GUI.


![output2](https://user-images.githubusercontent.com/68703153/128571149-d674f782-0119-4e1a-9b30-6000ff0cf008.PNG)


