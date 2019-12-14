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
The following are the variables concerning the match:

* Match_ID                             
* Date                        
* HomeTeam                             
* AwayTeam                             
* Home ex-Rank                          
* Home Team Goals                      
* Away ex-Rank                         
* Away Team Goals                       
* Referee                             
* Home Team Shots                       
* Away Team Shots                      
* Home Team Shots on Target             
* Away Team Shots on Target            
* Home Fouls Committed                 
* Away Fouls Committed                  
* Home Corners                          
* Away Corners                         
* Home Yellow Cards                     
* Away Yellow Cards                     
* Home Red Cards                        
* Away Red Cards                                           
* Match Result_A                        
* Match Result_D                       
* Match Result_H                        


And these other variables are produced by different betting websites: Odds, set before the match.

* B365 Home                          
* B365 Draw                          
* B365 Away                           
* Bet&Win Home                        
* Bet&Win Draw                        
* Bet&Win Away                        
* Interwetten Home                    
* Interwetten Draw                   
* Interwetten Away                   
* William Hill Home                   
* William Hill Draw                   
* William Hill Away                  
* VC Bet Home                         
* VC Bet Draw                         
* VC Bet Away 

## Methodology
* Upload, clean and add the necessary variables to complete the Dataset
* Create scatter plots to show the repartition between the realized prediction vs non realized prediction
* Create the classification models (Logistic regression, then decision trees) for each match result, using one time the match statistics, the other time using the odds
* Evaluate the accuracy of the models and create confusion matrixes to have a visual representation of the project
* Finally, drawing some conclusions that we can be retrieved from these classfications and methodologies

## Execution
In order to execute the project, you should download the principal Notebooke [Notebook_Rolex.ipynb](https://github.com/abdul232/DMML_Team_Rolex/blob/master/code/Notebook_Rolex.ipynb), withe the [Dataset](https://raw.githubusercontent.com/abdul232/DMML_Team_Rolex/master/data/England_2008_2018_Premiere_League_Final.csv).
And run it using Jupyter Notebook app Anaconda, or online by using [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb#recent=true) or [Azure Notebooks](https://notebooks.azure.com)
