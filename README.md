
# UK Road Accidents Data Analysis

![cover](https://user-images.githubusercontent.com/105977171/185628259-4c608cb0-af1f-4504-8e7c-4ba35c757ef2.jpg)


## Overview :

Road accidents have become very common nowadays.
 With ever increasing number of vehicles on the roads the, the incidences of road accidents seem to be increasing day by day. But is it really true ? Have the modern safety standards along with new laws resulted in a decrease in the road accidents ? Where do most accidents occur ? What fraction of accidents are severe ? In this Exploratory Data Analysis project, we try to answer such questions by analysing the dataset to arrive at various conclusions. The dataset we are working on was gathered by the UK government from the traffic data between 2005 and 2016, recording over 1.5 million accidents in the process, making this one of the most comprehensive traffic data sets.
 
The dataset is obtained from kaggle from the following [link](https://www.kaggle.com/datasets/devansodariya/road-accident-united-kingdom-uk-dataset) 

![df](https://user-images.githubusercontent.com/105977171/185671537-f72dd8f9-050b-451d-971a-770a3b139156.png)





Given below we see some sample of the key takeaways form the Analysis. <br>
To view the entire project notebook containing all the codes and analysis, click in the link below :


## [Data Analysis : UK road Accidents Notebook](https://github.com/prateem-biswas/UK_Road_Accidents--Exploratory_Data_Analysis/blob/main/Data_Analysis_UK_accidents.ipynb)



## Summary :

### Accident Distribution :

![Acc_distribution](https://user-images.githubusercontent.com/105977171/185759319-4e4942b4-0a8f-4405-a6df-70345734384b.png)

By plotting the latitude and longitudes of the accident locations, we get the the distribution of road accidents throughout UK ! 
Most accidents are clustered around the large, populated cities, as is expected ! A large population of people live in and
 around the cities and commute to work daily . This definitely increases the likelihood of an accident to occur in these areas.
Also, a majority of  the accidents seem to have occured in the sounthern part of the island !

### Accident trends yearwise :

![yearlylineplot](https://user-images.githubusercontent.com/105977171/185759818-134219af-174e-4061-b63e-22067c5b98ce.png)  

The number of traffic accidents in UK shows a decreasing trend over the years. Right from 2005 when the data collection started
the number of accidents have been gradually decreasing uptil 2013, with 2012 being the major exception. This is a good sign as the number of
casualties also follows the same pattern, meaning the lowering of the accident rates results in a better road safety !

### Accident Distribution thoughout the days and weeks :

![dayandweek](https://user-images.githubusercontent.com/105977171/185760997-2b1d5ba0-33c9-462f-af75-8b0553dc599a.png)

The number of accidents are very little between midnight and early morning, with least being at 4 am. A large number of accidents occur between 7 am and 2 pm while, peaking at around 8 am . Another peak occurs between 3 and 7 pm and accounts for the highest cases of accidents, with the time between 4pm and 5pm accounting for the most number of accidents throughout the day. This correlates with the rush hour timings (6-10 am, 3-7 pm), with most people commuting and returning from work.

The total cases of accidients seems to be distributed equally among the weekdays, with the weekends having comparitively lower cases. Sunday has the least number of accidents while Friday has maximum cases.

![sun_fri_dist](https://user-images.githubusercontent.com/105977171/185761438-638e62dc-9ef0-4040-9dfa-08f612f37de8.png)

The above graphs represents the difference between two types of distributions found in weekends and weekdays respectively ...
On weekends, the distribution resembles a normal distribution with the peak around 3pm. Incase of weekdays however it seems to resemble the overlap of 2 normal distribution curves, each contributed to the rush hour in traffic during workdays.

### [Read the complete Analysis ](https://github.com/prateem-biswas/UK_Road_Accidents--Exploratory_Data_Analysis/blob/main/Data_Analysis_UK_accidents.ipynb)
