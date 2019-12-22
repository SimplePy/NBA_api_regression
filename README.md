# Linear Regression Using Python's NBA API (Beginner Project)

## Introduction

The use of statistics has fundamentally changed the NBA over the last decade. Teams are using dozens of advanced metrics to gauge how well their players are performing as well as how college prospects will perform in the future. Statistics have also contributed towards a shift in coaching philosophy. For example, the midrange jumper has disappeared in favor of the three-point shot which scores more points per attempt. It can be really fun to explore some of these Basketball statistics but challenging for a beginner Python programmer to approach.

For this project, we will use NBA season statistics to build a basic linear regression model. Our x-variable will be the number of field goal attempts (FGA) taken and the y-variable will be the average number of points per game (PPG) scored by each player. Instead of having a row for each game player, we will take season averages. This way, each row represents a single player's season average. We'll keep things simple in this project by focusing on how to make an API call with nba_api and how to use ScitKit-Learn to create a linear regression. Our end product will be a visualization and model that will help us understand the relationship between attempting a shot and scoring a point. Luckily for us, this is a fairly linear relationship. In the future, we can expand upon the model by including more variables, optimizing the model's parameters, or choosing a more interesting y-variable. 


#### Prerequisites:
*This is a beginner project that is easy enough for any new Python user*
<br>
* You must be comfortable downloading some packages

    
#### Packages:
* Pandas
* Numpy
* Sklearn
* requests
* nba_api ([found here](https://pypi.org/project/nba-api/)) 
* matplotlib


## Detailed Tutorial:

Follow along by filling out the empty project template according the the completed Jupyter Notebook project.

[Read the Step-by-step Tutorial Here](nba_point_regression.ipynb)

[Code Template](projectTemplate.py)



