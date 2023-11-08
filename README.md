# Machine_Learning

## Table of Contents:
[Jupyter Notebook](https://github.com/julyndav/Machine_Learning/blob/main/ML_Megaline%20Analysis.ipynb)

## Required Project Libraries:
| Library |Purpose |
| --- | --- |
| Pandas | Main library for working with data |
| Numpy | Used for numerical operations on large quantities of data |
| Seaborn | Python visualization library based on matplotlib |
| Matplotlib | Python visualization library |
| **The following SKlearn Libraries:** |
| sklearn | Open source machine learning library that supports supervised and unsupervised learning  |
| sklearn.tree | Decision tree classifications |
| sklearn.metrics | Used in determining model accuracy |
| sklearn.model_selection | Used in splitting dataframe into 'train','test','validation' sets |
| sklearn.ensemble | Random forest classifier model |
| sklearn.linear_model | Logistic Regression model|
<br>
</br>

## Project Overview:
The following project will analyize subsciber behavior to help in determining what type of model has better accuracy finding the more popular phone plan: Ultra or Smart.

We have access to behavior data about subscribers who have already switched to the new plans. This will be used to develop a model that will pick the right plan. In this project, the threshold for accuracy is 0.75 and will be checked by using the test dataset.

## Data description
<li>
сalls — number of calls<li>
minutes — total call duration in minutes<li>
messages — number of text messages<li>
mb_used — Internet traffic used in MB<li>
is_ultra — plan for the current month (Ultra - 1, Smart - 0)

## Analysis Steps:
| Step |Description |
| --- | --- |
| 1 | Create project description |
| 2 | Import libraries |
| 3 | Upload and analyize data |
| 4 | Data cleaning and preparation |
| 5 | Mold the data to Tidy data *(Tidy data is data that is easy to manipulate, model and visualize)* |
| 6 | Exploratory Data Analysis *(EDA)* |
| 7 | Split the source data into a training set, a validation set, and a test set |
| 8 | Investigate the quality of different models by changing hyperparameters |
| 9 | Check the quality of the model using the test set |
| 10 | Sanity check the model |
| 11 | Formulate Conclusions |

<br></br>

## Brief Analysis Overview:

After inital steps were taken and data cleaning/data manipulation done, brief exploratory analsyis was performed to get a better sense of how customers use their phones and which plans were involved. This was done with using historgrams to visualize the data to show how many calls users typically make, how many minutes they use on their plan, number of messages sent, data used and which plan has the most users. 
<br></br>
![EDA](https://github.com/julyndav/Machine_Learning/blob/main/readmepic/eda%20hist.png)
<br></br>

## Machine Learning:
The data was then split into a Training, Validation and Test sets. The Training set will consist of 60% of the dataset with the Test and Validation taking 20% each. Next we used the following learning alogrithms to help with the anlaysis:<br>
In this section we are going to figure out the best hyperparameters for each of the 3 learning algorithms:
<li>
Decision Tree<li>
Random Forest<li>
Logistic Regression</li>
<br>
The findings from the learning models were grouped to give a compact view of the results. Threshold for the project was 75%.

![Models](https://github.com/julyndav/Machine_Learning/blob/main/readmepic/models.png)

<br></br>
## Brief Project Conclusions:
#### <i> Full project conclusion given at the end of the project notebook </i>
##### Quality and Sanity Checks
To end out the analysis, we compared the quality of the models against the test set. We used both the training and validation sets. The test set accuracy was right at our threshold of 75% followed by the training set at 74.2% and the validation set at almost 73%.

Final step was to sanity check our model. To begin a baseline accuracy was found and the other learning models were compared to that. Against the baseline, our best learning model the Random Forest, was 10.11 percentage points more.
