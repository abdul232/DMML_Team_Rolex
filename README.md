# DMML_Team_Rolex

Project repo of Data Mining and Machine Learning

Master: Information Systems - HEC Lausanne - 2019

## The Team
* Abdul Rahman Aloraib Alsalim
* Alexandre Lang
* Alix Muller
* Joël Kuflom

## The Project
This project will help you understand this world, and also provide you a betting strategy that you will be able to apply on your own.
The goal of this project is to establish a betting strategy for **England Premiere League** match results.

## The Dataset
To build our dataset, we will gather the results of the England Premiere League since 2008 to 2018. It was taken from the following [website](http://www.football-data.co.uk/englandm.php).

Ranking dataset was created manually by using several websites as [Google](https://www.google.com) & [Wikipedia](https://www.wikipedia.org)

## The Variables
All the variables are linked to the matche: 
* Match's ID
* Match's date time
* Home team
* Away team
* Final number of goals
* Match result (Home Team win, Away Team win or Draw Match)
* Team's ranking of the previous Football season (static rank at the end of the past season)
* Referee for the match
* Number of shots
* Number of fouls

And the other variables are not directly linked to the match statistics.
These other variables are the
* Odds set before the match by different betting websites. These odds are set on the final result of a match (Home Team win, Away Team win, Draw Match).

## Methodology
* Upload, clean and add the necessary variables to complete the Dataset
* Create scatter plots to show the repartition between the realized prediction vs non realized prediction
* Create the classification models (Logistic regression, then decision trees) for each match result, using one time the match statistics, the other time using the odds
* Evaluate the accuracy of the models and create confusion matrixes to have a visual representation of the project
* Finally, drawing some conclusions that we can be retrieved from these classfications and methodologies

## Execution
In order to execute the project, you should download the principal Notebooke [Notebook_Rolex.ipynb](https://github.com/abdul232/DMML_Team_Rolex/blob/master/code/Notebook_Rolex.ipynb), withe the [Dataset](https://raw.githubusercontent.com/abdul232/DMML_Team_Rolex/master/data/England_2008_2018_Premiere_League_Final.csv).
And run it using Jupyter Notebook app Anaconda, or online by using [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true) or [Azure Notebooks](https://notebooks.azure.com)
