# Precog Recruitment Task

Name - Srija Mukhopadhyay

Branch - CLD Dual Degree

Email - srija.mukhopadhyay@research.iiit.ac.in 

# Analysis Points 

## Point 1

Finding the trends in the criminal activities performed by men and women over the years and across different states

### Process of Work 

- The first step was ensuring that the data we are dealing with was clean and making the required changes to the dataset in order to ensure the most optimal working for the purpose of this project 

- Following that, the cases file was broken down into smaller chunks to make the working easier for later purposes 

- After that, the cases by men and women were calculated and stored - this was done year wise as well as state wise 

- The percentages were also found to get a better insight into the data and the trends that are being followed 

### Observations and Insights (and Prospects)

- As it might be visible from the graph how the crimes performed by men have gone up slightly over the years while the number of crimes performed by women have gone down over the yeras 

- It might be interesting to co-relate this data point with the kind of crime being committed and how their numbers vary across the gender as well as state categories 

- At the same time, the state data was not plotted because of the high amount of data that was obtained, however, more manipulation might be able to give insights such as which state has more women performing criminal activities and which states have more men performing criminal activities as well as their trends over the years 

## Point 2

Finding the trends in the criminal activities performed against men and women over the years and across different states 

### Process of Work 

- The first step was ensuring that the data we are dealing with was clean and making the required changes to the dataset in order to ensure the most optimal working for the purpose of this project 

- Following that, the cases file was broken down into smaller chunks to make the working easier for later purposes 

- After that, the cases against men and women were calculated and stored - this was done year wise as well as state wise 

- The percentages were also found to get a better insight into the data and the trends that are being followed

- In addition to that, I tried to study the trends in cases performed against the genders by the other gender categories and tried to find valuable insight or input from those points as well

### Observations and Insights (and Prospects)

- As we can observe there crimes against men decreased and then increased while the opposite happned in the case of crimes against women 

- What's more interesting to noteice is the fact that there has been a significant decrease in the crimes committed by men against men, a sort of decrease in the number of crimes committed by women against women as well.

- The state data also provides valuable insight as well as might give insight into how the gender and state data co-relate 

## Point 3

Finding the time taken for the jurisdiction of cases across different states and years 

### Process of Work 

- The first step was ensuring that the data we are dealing with was clean and making the required changes to the dataset in order to ensure the most optimal working for the purpose of this project 

- This data was also broken down into smaller chunks that needed to be worked with in order to make the task easier 

- In this case, I tried to find the avarage number of days taken in each state for the jurisdiction of cases 


### Observations and Insights (and Prospects)

- Rajasthan and Chandigarh really need to speed up their process while most other states are doing mostly fine in this regard

# Classification Problem 

## Problem

Predicting the gender of the judge based on factors such as tenure, position as well as the court and state they work in

### Process of Work
- The start involved cleaning the data set to obtain a close to idea framework. Cleaning the dataset was not easy, especially owing to the 'judge_position' attribute which had a lot of fuzzy data. I did try my best to clean it, but there are more improvements that can be made for the same. 

- Following the Cleaning process, the features were obtained and the data set was broken down into the traning and testing chunks to run the different kinds of models. 

### Insights Gained 
- To an extent, owing to the not amazing accuracy obtained from the models, we can conclude that we would either need more feature points or data points or more informative data points for a better analysis and classification algorithm

- In addition to that, looking at the feature points which have been considered valueable - they happen to include the position of the judge as well as the court number (which denotes the type of court) and also the district code

- We can see how most models give a similar sort of accuracy in the ballpark of 70 to 75 with the K Nearest Neighbour model and the Random Forest one being the most effective ones 

- This was an insight gained while cleaning the corpus which is also something that might be needed to be kept in mind for making more improvements to the project - which is the fact that the judge position data needs a lot more cleaning for more effective working because of the presence of a lot of redundancies as well as inconsistencies which is bound to bring down the performance of the model

# Additional Notes 

- All the code is presented in the form of ipynb notebooks and their working is pretty self explanatory.

- The provided dataset was used for the working of the entire Project and it was mostly coded in Kaggle.