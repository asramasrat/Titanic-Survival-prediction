# Titanic-Survival-prediction
Predicting survival rate of passengers on titanic 

The sinking of the RMS Titanic caused the death of thousands of  passengers  and  crew  is  one  of  the  deadliest  maritime disasters in history. One of the reasons that the shipwreck led to such loss  of life was  that there  were not  enough lifeboats for  the  passengers  and  crew.  
The  interesting  observation which comes out  from the  sinking is that some  people were more likely to survive than others, like women, children were the one who got the priority to rescue.Also people from First class were given more priority followed by second class and then the third class.The objective is to first explore  hidden  or  previously  unknown  information  by applying exploratory  data analytics  on available  dataset and then apply our machine learning model which uses KNN algorithm to complete the analysis of what sorts of people were likely to survive. 

Our hypothesis is that while saving passengers females were given priority over males. Another hypothesis is that while saving passengers Minors were given preference over adults.
Also Another hypothesis is that First class passenger were given preference while rescuing over second and third class passengers, and second class passengers where given preference over third class passengers

# Data Description:
We have a data set with the following columns :
1.	pclass: Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
2. survived: Survival (0 = No; 1 = Yes)
3. name: Name
4. sex: Sex
5. age: Age
6. sibsp: Number of siblings/spouses aboard
7. parch: Number of parents/children aboard
8. fare: Passenger fare (British pound)
9. embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

#   Pipeline
1.	Understand different features in the training dataset
2.	Clean the features
3.	Remove outliers
4.	Visualizing the features
5.	Find relation between different features and survival
6.	Find the best features using SelectKBest (to get an optimal fit between bias and variance)
7.	Train and fit the model
8.	Predict the scores using KNearestNeighbors
9.	Check Accuracy
10.	Predict Survival values for test.csv
