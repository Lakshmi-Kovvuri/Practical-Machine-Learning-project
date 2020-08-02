# Practical-Machine-Learning-project
Coursera project in Practical machine learning
Over view:
Using devices such as Fitbit, Nike FuelBand and so on, is now easily possible to collect data about physical activity. These type of devices are part of the quantified self movement. A group of enthusiasts who take measurements about themselves regularly to improve their health and to find patterns in their behaviour.
The goal of this project is to use data from accelerometers on the belt, forearm, arm and dumbell of 6 participants. And also to predict the manner in which they did the exercise.
The 5 possible methods include:
A: Exactly according to the specification
B: Throwing the elbows to the front
C: Lifting the dumbell only halfway
D: Lowering the dumbell only halfway
E: Throwing the hips to the front
The dataset used in this project is a courtesy of Ugulino, W.;Cardador, D.; Vega, K.; Velloso, E.; Milidiu, R.; Fuks, H. Wearable Computing: Accelerometers, Data Classification of Body Postures and Movements.

Data obtained from the following links

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv


In this project, we sliced the data by 70:30 as a train data set and test data set

Prediction model building
Here, we used two models to predict the outcome variable.
1. Decision tree model
2. Random Forest model
In order to limit the effects of overfitting and improve the efficiency of the models, we will use Cross Validation.
Also we use Confusion Matrix for each analysis to better visualize the accuracy of the models.

Accuracy rate for the Random forest model is very high and the out of sample error is equals to zero
Applying Random forest model to the test data to answer the 20 question in course project prediction quiz.
