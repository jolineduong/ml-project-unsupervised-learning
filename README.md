# ml-project-unsupervised-learning

## Project Outcomes
For this project, I created unsupervised learning models that explained variance and customer behaviour from a wholesale dataset.

The modules used in this project include: pandas, numpy, matplotlib.pyplot, seaborn, scipy, and sklearn. 

I performed EDA, data pre-processing, and unsupervsed learning techniques to display data visualizations with the goal of communicating the insights gained from this analysis. 

KMeans clustering, hierarchical clustering, and principle component analysis are the unsupervised learning models implemented in this project. 

### Process
1.	Explore dataset to get a clear understanding of the relationships between variables and how they affect the outcome variable. 
2.	Start data pre-processing. Clean the data by checking for null/missing values, duplicates, and outliers.
3.	Start feature analysis – look at feature correlations, decide whether or not the data needs to be scaled or normalized.
4.	Begin creating unsupervised learning models
5.	Interpret model outputs

### Findings
I found that grocery and detergent_paper have a high positive correlation (85%), indicating that customers tend to purchase items from these categories at the same time. When we group these features up based on attribute similarities, there are 3 main groups. The lack of clear clusters suggests that customers have similar shopping habits. Some outliers were kept. Variability is important in this dataset and the outliers contribute to that. Not all customers shop the same way and these customers should be accounted for in our data.
