# Udacity-Arvato

## Project Motivation

Bertelsmann is a media, services and education company that operates in about 50 countries around the world. It includes the broadcaster RTL Group, the trade book publisher Penguin Random House, the magazine publisher Gruner + Jahr, the music company BMG, the service provider Arvato, the Bertelsmann Printing Group, the Bertelsmann Education Group and Bertelsmann Investments, an international network of funds.

**Website:** https://www.bertelsmann.com/divisions/arvato/#st-1

In this project, we applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns.
The data used in this project has been provided by Udacity's partners at Bertelsmann Arvato Analytics, and represents a real-life data science task.

For this reason, the data used for this project was not uploaded to this repository.

## Requirements
The project needs the following libraries in the Anaconda distribution to run:

- Pandas 1.0.3
- Matplotlib 2.2.2
- Seaborn 0.10.1
- Scikit Learn: 0.22.1

## Files in the repository

```Identify_Customer_Segments_Toscano_Paulo```: Jupyter notebook containing the analysis of the project
<br/>
```picture1.png```: Bar chart with the cluster comparison (General Population x Customer Population)


## Results
![Image](https://github.com/Ptoscanode/Udacity-Arvato/blob/main/picture1.png)

#### Overrepresented component - People from Cluster number 9

A huge chunk of customers belong to Cluster number 9 whereas it doesn't have the same proportion in the general population. 

People who have the following characteristics are part of this cluster, which it is not a relevant part of the general population.

- belong to small families
- live in a residence in a residencial area
- don't have to share the area they live with other people
- have healthy issues
- length of residence less than 1 year
- have a tradional mind
- live in mainly 1-2 family homes in the PLZ8 region


#### Underrepresented component - People from Cluster number 3

Cluster number 3 is the most popular cluster in the general population and it is not even close to the top when it comes to the customer population.

People who have the following characteristics are part of this cluster, which represent a big part of the population.
- older
- born in the war years
- live in a very good neighbourhood
- healthy
- with a big family
- a rational mind
- live in a small community
- are sensual minded
- live in a place with less than 34 households per km^2 


#### Popular segment
As we mentioned before, cluster 3 is the most popular cluster in the general population and its customers have already been described. 


#### Unpopular segment

Customers who are part of Cluster number 20 are a not a numerous segment in neither the general population nor among customers.  

The following variables have the highest positive weight values and help explain the positive variation of this Principal Componenent. People who have the following characteristics are part of this cluster:

- wealthy
- part of a family whose members hold professional academic titles
- Crazy-Shopper
- live with his family in a residence.

To finish, based on the variables that have highest negative weight values, we can assume that, a typical person from this cluster also has the following characteristics:

- lives in city center
- in Eastern Germany
- less than 10 Km to nearest urban center
- is single
- lives in place whose unemployment rates is low

This specific cluster is not a relevant fraction of the customers and should be left aside. At least for now.

## Acknowledgements

https://scikit-learn.org/stable/
<br/>
https://pandas.pydata.org
<br/>
https://matplotlib.org
<br/>
https://seaborn.pydata.org
<br/>
https://github.com/othneildrew/Best-README-Template/blob/master/README.md
<br/>
https://www.kaggle.com/kashnitsky/topic-7-unsupervised-learning-pca-and-clustering
