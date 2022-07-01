# Crop-Recommendation System
This repository contains a Machine Learning project, implemented in python, named 'Crop Recommendation System using Optimized Extreme Learning Machine'.
# Dataset 
A dataset named ‘Crop Recommendation Dataset’ was opted to make appropriate recommendations with the backing of Machine Learning techniques. The indicated dataset is available in a website named ‘Kaggle’.
The Crop Recommendation Dataset consists of 2200 rows and 8 columns. These 8 columns correspond to 8 different 
attributes or features of the dataset. The attributes and their meaning are as follows:- <br/>
● N - Proportion of Nitrogen in soil content <br/>
● P - Proportion of Phosphorus in soil content <br/>
● K - Proportion of Potassium in soil content <br/>
● Temperature - Temperature in degree Celsius unit <br/>
● Humidity - Percentage of relative humidity <br/>
● ph - pH level of soil <br/>
● Rainfall - Amount of rainfall received in mm <br/>
● Label - Names of crops <br/>
 Here, we choose 7 attributes, namely N, P, K, Temperature, Humidity, ph and Rainfall collectively as the input and the label as the output. This label contains 22 unique values which specify the name of different crops. 
# Exploratory Data Analysis 
The basic statistical measures are calculated from the dataset 
to get an overall notion of the dataset. The number of 
instances corresponding to each unique crop is 100. From 
the heat map drawn, we could observe that there 
exists no null value in the dataset. The distance plot drawn from the attributes Temperature and 
ph conveys that both these attributes 
are normally distributed. A bar plot is drawn for 
comparing the N-P-K values which converts the data 
capable of easier analysis through observation alone. Thus after subjecting the original data for some 
statistical and visual analysis, we were able to obtain a clear 
image about the dataset and gather a comprehensible idea 
about the structure of the dataset. Therefore we could reach 
the conclusion that the 'crop recommendation dataset' is a 
befitting choice for building a crop recommendation system.
# Comparitive Study
After the exploratory data analysis of the Crop 
Recommendation Dataset, it is submitted to the comparative 
study of classical supervised learning algorithms. These 
commonly used algorithms of machine learning are chosen 
one by one and they are trained using the available 
predefined models and their accuracies corresponding to its 
default parameters are noted down. Then each of these 
algorithms is provided with normalized data which is 
developed using different Normalization techniques. 
Afterwards, the data is submitted to hyperparameter tuning 
which enables us to choose the best parameters to yield an 
optimized accuracy for the model. GridSearchCV is the 
function we use for hyperparameter tuning. All the 
supervised algorithms we have chosen for analysis and 
normalization techniques are available in the scikit-learn 
library in Python. <br/>
The algorithms used for the comparative study are K Nearest Neighbor Algorithm, Decision Tree, Random Forest, Naive Bayes Algorithm, Logistic Regression, Multi-Layer Perceptron and Support Vector Machine.<br/>
We succeeded in optimizing the accuracies of these 
algorithms which they had from training the model using 
default parameters. Now, we move on to another advanced 
neural network algorithm to build the proposed model. 
Extreme Learning Machine algorithm is used in our project 
to build the crop recommendation system with an optimized 
accuracy and enhanced performance. 
# Implementation 
Extreme Learning Machine or ELM is an advanced Neural 
Network algorithm for a single hidden layer feed-forward 
network. This is a three-step 
learning model algorithm. Random parameters are assigned 
for hidden nodes. Then, a matrix is calculated using the 
hidden layer output. The output weight is computed with the 
assistance of the Moore-Penrose generalized inverse of this 
matrix. All these steps are carried out using basic 
mathematics computation. Thus it needs much less training 
time and effort. <br/>
 In our system, we create an Extreme Learning 
Machine model according to five different activation 
functions. These activation functions are hyperbolic tangent 
function, sine square function, triangular basis function, 
hard limit transfer function and radial basis function. 
Including these five activation functions, an Extreme 
Learning Machine classifier is defined. While defining this 
classifier the number of hidden neurons is given as 500. 
This number was chosen after examining the accuracy of the 
model while considering the number of hidden neurons 
within an interval of 50 to 650. After tuning, the model with 
hyperbolic tangent function as activation function gained the 
maximum accuracy and efficient performance. Thus, our 
proposed model developed a system with ease of 
implementation and minimum human 
intervention.
# Conclusion
The Crop Recommendation System nurtured through the 
optimized Extreme Learning Machine model has several 
advantages over the conventional classification algorithms. 
When compared with the existing Crop Recommendation 
Systems, our model acknowledges to result in the maximum 
accurate model. In our project, a comparative study of the 
existing classification algorithms was carried out. But, the Extreme Learning Machine 
model managed to generate the maximum prediction 
accuracy of 99.77% by using the hyperbolic tangent 
function as the activation function. This was the highest 
accuracy value when compared with all the other existing 
conventional algorithms.
