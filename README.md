# BitsMagnet
CodeFundo++(Team: Bits Magnet)

Problem statement:

       Floods are the most common natural disasters, and cause significant damage to life, agriculture and economy. Flood water levels at downstream areas are strongly affected by upstream conditions.
       A recent report shows, India accounts for 1/5th of global deaths from floods,  As many as 107,487 people died due to heavy rains and floods across India over 64 years between 1953 and 2017.It is predicted that, India could see a six-fold increase in population exposed to the risk of severe floods by 2040 to 25 million people.
       Accurate prediction of flood water level is extremely importance as an early warning system to the public to inform them about the possible incoming flood disaster, which will help in taking precautionary measures.

Solution for prediction of extension of damage of infrastructure:

       In particular, if there is rapid pre disaster forecasting of expected damage by the administrative division for the regions that will be affected, this can be of great help to policymakers in setting up and implementing disaster prevention measures. Moreover, it will be possible to establish a voluntary disaster management system in which citizens themselves can prepare for disasters and expected damage by receiving forecasts about them.
       The method that we are using in predicting and preparing for natural disaster damage in advance mostly performed regression analysis using weather factors such as precipitation, rainfall intensity, maximum wind speed that cause natural disasters and damage through floods, rainstorms, and hurricanes. This results in establishing the relationship between weather factors and damage extent through regression analysis, and they used the constructed regression models to attempt to predict the extent of damage through weather factors alone.                
       However, it becomes difficult for most of these models to predict the actual extent of damage adequately. In order to overcome the shortcomings of such studies, we have taken into account socioeconomic factors such as per capita income, population density, and imperviousness of an area in addition to weather factors that directly give rise to natural disasters.
       
 Alerting remote areas of flood beforehand without intensive and bulky weather models:
 
      Similarly for remote areas , when it rains for a long time, the ground will become saturated and the soil will not be able to store water leading to surface runoff. Similarly if there is a sudden bust of heavy rainfall, it may lead to flash floods due to increased discharge. Thus the flooding of a river can be predicted by predicting the river’s discharge.
      Existing models of stream discharge are very complex and involves many variables like climate, soil storage potential, vegetation, soil type, evaporation rates, etc. These models require a lot of data and not very portable.
      River discharge of small rivers can be predicted using the previous data of precipitation and discharge using a simple regression model. The precipitation and water discharge data at a particular area has to be collected for a reasonable amount of days. The river’s discharge on a particular day also depends on the precipitation and water discharge of the previous days (weeks & months), hence they are also considered as features in different combinations.  The rivers with similar geography can be grouped and trained together by normalizing the features. For the rivers whose previous data is unavailable, the trained models of other rivers having similar geography is used to predict the river discharge.




