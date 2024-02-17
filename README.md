# SpaceX_Capstone_Project_IBM
### Introduction
In this capstone project, the objective is to make predictions on the successful landing of the Falcon 9 first stage. SpaceX offers rocket launches on their website, priced at 62 million dollars, significantly lower than other providers whose costs can reach 165 million dollars per launch, mainly due to the reusability of the first stage. By accurately determining the landing outcome, we can estimate the cost of a launch, which can be valuable information for competing companies interested in bidding against SpaceX for a rocket launch.
### Business Problem
This cost reduction is mainly attributed to SpaceX's ability to reuse the first stage of the rocket. Consequently, accurately predicting the probability of a successful first stage landing enables the determination of launch costs. Leveraging the insights and models derived from utilizing Data Science techniques, what are certain factors that may affect the landing outcome?
### Methodology Approach 
* Data collected from Space X API 
* Additional information collected through Web scraping [Link here](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches_(2010%E2%80%932019)). 
* Data Wrangling and processing
* Exploratory analysis using SQL magic and Python visualization tools.
* Data analytics using Folium Interactive maps and Plotly Dashboards
* Predictive analysis using Machine Learning Classification algorithms.
### Dependencies 
* Data collection Libraries
    * Requests
    * Beasutiful Soup
* Data Wrangling and processing Libraries
    * Pandas
    * Numpy
* Visualization Libraries
    * Matplotlib
    * Seaborn
    * Folium
    * Plotly
    * Dash
* Machine Learning Libraries
    * Scikit Learn
### Conclusion
The exploratory data analysis has shown us that successful landing outcomes are somewhat correlated with flight number. It was also apparent that successful landing outcomes have had a significant increase since the year 2013. All launch sites are located near the coast line. This makes it easier to test rocket landings in the water. The machine learning were able to predict the landing success of rockets and the best model was decision tree algorithm.
