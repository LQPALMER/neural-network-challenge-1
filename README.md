# neural-network-challenge-1

I work at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. My team has asked me to create a model to predict student loan repayment.

The business team has given me a CSV file that contains information about previous student loan recipients. With my knowledge of machine learning and neural networks, I decided to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking.

 I completed this task using  the following steps, which are divided into four parts:

1. Prepare the data for use on a neural network model:
a. Two datasets were created: a target (y) dataset, which includes the "credit_ranking" column, and a features (X) dataset, which includes the other columns.
b.The features and target sets have been split into training and testing datasets. 
c. Scikit-learn's StandardScaler was used to scale the features data.


2. Compile and evaluate a model using a neural network:
a. A deep neural network was created with appropriate parameters. (10 points)
b. The model was compiled and fit using the accuracy loss function, the adam optimizer, the accuracy evaluation metric, and a small number of epochs, such as 50 or 100. (10 points)
c. The model was evaluated using the test data to determine its loss and accuracy. (5 points)
d. The model was saved and exported to a keras file named student_loans.keras

3. Predict loan repayment success by using your neural network model:
a. The saved model was reloaded.
b. The reloaded model was used to make binary predictions on the testing data. (10 points)
c. A classification report is generated for the predictions and the testing data.

4. Discuss creating a recommendation system for student loans:
For Question 1: Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.

My response describes the data that should be collected to build a recommendation system for student loan options, and why I think that data should be collected. 
The type of data described is appropriate for a recommendation system for student loan options. 


For Question 2: Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.

In my response I chose and justifed my choice of filtering method. 
The choice of filtering method was appropriate for the data selected in the previous question. 

For Question 3: Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.


My response lists two real-world challenges with building a recommendation system for student loans. Those challenges are Data Privacy and Security, and Bias and Fairness. I also explain why these challenges would be of concern for a student loan recommendation system. 

Results:
My model performed decently, at 0.745% Model Accuracy, and  0.594% Model Loss.
