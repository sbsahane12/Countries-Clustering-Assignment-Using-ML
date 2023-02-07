# [Project  5: Countries  Clustering  Assignment Using ML(https://github.com/sbsahane12/Countries-Clustering-Assignment-Using-ML.git) 
## Problem Statement
HELP International is an international humanitarian NGO that is committed to fighting poverty and  providing the people of backward countries with basic amenities and relief during the time of  disasters and natural calamities
After the recent funding programmes, they have been able to raise around $ 10 million. Now the  CEO of the NGO needs to decide how to use this money strategically and effectively.
The significant issues that come while making this decision are mostly related to choosing the
countries that are in the direst need of aid.
As a Data Scientist, we need to find the countries in direst need and help CEO of HELP  International in using the fund money to reach right countries
## Problem Approach
As we have the Data of countries like child mortality rate, GDP Per Capita, Income etc. , we can
use Clustering to segregate the countries into different groups
Steps :
Data Inspection – Missing Values if any, EDA
Outlier Analysis
Data Pre-processing
Finding Optimal number of Clusters
Modelling
KMeans Clustering
Hierarchical Clustering – Single and Complete Linkages
Listing down top 5 countries in need
## Install
This project requires Python 3.6 and the following libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
## Result
- From the list of poor countries we obtained, sorted the list on income, gdpp, child_mortality rate.
- Top 5 countries which are in direst need :
- Congo, Dem Rep
- Liberia
- Burundi
- Niger
- Central African Republic

## Models trained on: 
#### Built the model using “Euclidean distance” as metric and linkage type as “Single”
- Plotted the Dendrogram for single linkage, we won’t be able to observe good clusters in single linkage
- Built the model using Complete Linkage, we could clearly observe 3 clusters formed. Used Cut_tree with n_clusters = 3 to get the labels of the clusters forme
