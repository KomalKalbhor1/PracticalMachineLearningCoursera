# PracticalMachineLearningCoursera
Course10 from Data Scientist toolbox

**Background**
Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively.
These type of devices are part of the quantified self movement – a group of enthusiasts who take measurements about themselves regularly to
improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify
how much of a particular activity they do, but they rarely quantify how well they do it. 
In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. 
They were asked to perform barbell lifts correctly and incorrectly in 5 different ways.
More information is available from the website here: http://groupware.les.inf.puc-rio.br/har (see the section on the Weight Lifting
Exercise Dataset).


**Data**
The training data for this project are available here: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv
The test data are available here: https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv
The data for this project come from this source: http://groupware.les.inf.puc-rio.br/har. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment.        

**Goal**     
The goal of your project is to predict the manner in which they did the exercise. This is the “classe” variable in the training set. You may use any of the other variables to predict with. You should create a report describing how you built your model, how you used cross validation, what you think the expected out of sample error is, and why you made the choices you did. You will also use your prediction model to predict 20 different test cases. 

**
Model is built using classification algorithm from caret package.
Predictor variables to predict with are found out using Near-Zero variance using caret package. 
Cross validation is performed and training data is split into sub training and sub test set.
The expected out of sample error is 1-accuracy of classification model.
The prediction model was used tompredict 20 different test cases.

