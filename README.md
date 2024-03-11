# Credit-card-debt-prediction

### Description

Credit card debt prediction is important for managing risk, aiding financial planning, retaining customers, complying with regulations, and making informed investment decisions.

With several explanatory variables describing (almost) every aspect of social, economic, and cultural features of different individuals (masked as Index), this competition challenges you to predict their credit card balance (Balance, Y).

### Evaluation

#### Goal

our job is to predict the credit card balance for each individual for the test dataset (50 individuals). For each index in the test set, we must predict the value of the "Balance" variable.

Metric:

Submissions are evaluated on R-squared (Coefficient of Determination) between the predicted value and the observed credit card balance.

### Dataset Description

#### Files

Train_Features.csv - features of the training set

Test_Features.csv - features of the test set

Train_Output.csv - output of the training set

Sample_Submission.csv - a sample submission file in the correct format

#### Columns

'Index' - Unique identifier of individuals

Income - Income of the individual in $1,000's

'Limit' - Credit card limit of the individual

'Rating' - Credit rating

'Cards' - Number of credit cards

'Age' - Age in years

'Education' - Number of years of education

'Own' - A factor with levels of Yes and No

'Student' - A factor with levels No and Yes indicating whether the individual was a student

'Married' - A factor with levels No and Yes indicating whether the individual was married

'Region' - A factor with different levels of the individual's location

'Balance' - The response variable indicating credit card balance
