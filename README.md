# Machine_Learning

### Table of Contents:
[Jupyter Notebook](https://github.com/julyndav/Machine_Learning/blob/main/ML_Megaline%20Analysis.ipynb)

## Megaline Subscriber Analysis
The following project will analyize subsciber behavior to help in determining what type of model has better accuracy finding the more popular phone plan: Ultra or Smart.

We have access to behavior data about subscribers who have already switched to the new plans. This will be used to develop a model that will pick the right plan. In this project, the threshold for accuracy is 0.75 and will be checked by using the test dataset.

### Data description
<li>
сalls — number of calls<li>
minutes — total call duration in minutes<li>
messages — number of text messages<li>
mb_used — Internet traffic used in MB<li>
is_ultra — plan for the current month (Ultra - 1, Smart - 0)

### Preparing the Data
<li>
Download the data<li>
Inspect and clean the data<li>
Explore the data<li>
Mold the data to Tidy data (Tidy data is data that is easy to manipulate, model and visualize)

### Project Steps taken:
<li>
Open and look through the data file then upload dataset<li>
Split the source data into a training set, a validation set, and a test set.<li>
Investigate the quality of different models by changing hyperparameters. Briefly describe the findings of the study.<li>
Check the quality of the model using the test set.<li>
Sanity check the model.

After inital steps were taken and data cleaning performed, brief exploratory analsyis was performed to get a better sense of how customers use their phones and which plans were involved.
This was done with using historgrams to visualize the data to show how many calls users typically make, how many minutes they use on their plan, number of messages sent, data used and which plan has the most users. 

The data was then split into a Training, Validation and Test sets. The Training set will consist of 60% of the dataset with the Test and Validation taking 20% each. Next we used the following learning alogrithms to help with the anlaysis:<br>
In this section we are going to figure out the best hyperparameters for each of the 3 learning algorithms:
<li>
Decision Tree<li>
Random Forest<li>
Logistic Regression

Once the algorithms returned their findings, the project was finished with a report on findings and conclusions to further prove which phone plan would be the most profitable. 


