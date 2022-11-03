# Machine Learning Algorithm with Python (Classification) 
In this notebook we try to practice all the classification algorithms that we have learned in this course.

We load a dataset using Pandas library, and apply the following algorithms, and find the best one for this specific dataset by accuracy evaluation methods.

## About Dataset
This dataset is about past loans. The **Loan_train.csv** data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

| Field          | Description                                                                           |
| -------------- | ------------------------------------------------------------------------------------- |
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |


![ffb3a7e3-c603-40f9-9758-8dd132662a08](https://user-images.githubusercontent.com/110522512/199631622-3580ca48-4bd9-496f-a566-a04360105960.png)

After importing and cleaning the data, we'll use the training set to build an accurate model. Then use the test set to report the accuracy of the model
You should use the following algorithm:

*   K Nearest Neighbor(KNN)
*   Decision Tree
*   Support Vector Machine
*   Logistic Regression

#### Notice:

*   Can go above and change the pre-processing, feature selection, feature-extraction, and so on, to make a better model.
*   Should use either scikit-learn, Scipy or Numpy libraries for developing the classification algorithms.
*   Should include the code of the algorithm in the following cells.


The results is reported as the accuracy of each classifier, using the following metrics:

* Jaccard index

* F1-score

* LogLoass

