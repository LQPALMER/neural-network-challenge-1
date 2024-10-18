# Neural Network Challenge

I work at a company that specializes in student loan refinancing. If the company can predict whether a borrower will repay their loan, it can provide a more accurate interest rate for the borrower. My team has asked me to create a model to predict student loan repayment.

The business team has given me a CSV file that contains information about previous student loan recipients. With my knowledge of machine learning and neural networks, I decided to use the features in the provided dataset to create a model that will predict the likelihood that an applicant will repay their student loans. The CSV file contains information about these students, such as their credit ranking.

I completed this task using the following steps, which are divided into four parts:

## Prepare the data for use on a neural network model:
1. Two datasets were created:
    - A target (y) dataset, which includes the "credit_ranking" column
    - A features (X) dataset, which includes the other columns
2. The features and target sets have been split into training and testing datasets.
3. Scikit-learn's StandardScaler was used to scale the features data.

## Compile and evaluate a model using a neural network:
1. A deep neural network was created with appropriate parameters.
2. The model was compiled and fit using the accuracy loss function, the adam optimizer, the accuracy evaluation metric, and a small number of epochs, such as 50 or 100.
3. The model was evaluated using the test data to determine its loss and accuracy.
4. The model was saved and exported to a keras file named `student_loans.keras`.

## Predict loan repayment success by using your neural network model:
1. The saved model was reloaded.
2. The reloaded model was used to make binary predictions on the testing data.
3. A classification report is generated for the predictions and the testing data.

## Discuss creating a recommendation system for student loans:
1. **For Question 1**: Describe the data that you would need to collect to build a recommendation system to recommend student loan options for students. Explain why this data would be relevant and appropriate.
    - My response describes the data that should be collected to build a recommendation system for student loan options, and why I think that data should be collected. The type of data described is appropriate for a recommendation system for student loan options.
2. **For Question 2**: Based on the data you chose to use in this recommendation system, would your model be using collaborative filtering, content-based filtering, or context-based filtering? Justify why the data you selected would be suitable for your choice of filtering method.
    - In my response I chose and justified my choice of filtering method. The choice of filtering method was appropriate for the data selected in the previous question.
3. **For Question 3**: Describe two real-world challenges that you would take into consideration while building a recommendation system for student loans. Explain why these challenges would be of concern for a student loan recommendation system.
    - My response lists two real-world challenges with building a recommendation system for student loans. Those challenges are Data Privacy and Security, and Bias and Fairness. I also explain why these challenges would be of concern for a student loan recommendation system.

## Results:
My model performed decently, at 0.745% Model Accuracy, and 0.594% Model Loss.
