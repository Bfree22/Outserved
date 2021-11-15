# Outserved Duration Analysis


![outserved](https://github.com/Bfree22/Outserved-Reports/blob/master/Images/Outserved%20White%20.jpg)


A web and mobile application for IOS and Android. This repo contains a report of the in-store analytics based on time inside a business geo-fence. To accurately show the user distribution, we used Pandas and Plotly to chart the duration inside in seconds. The following steps are how we collected the data from a third party back-end host [Back4App](https://www.back4app.com). 




1. Clean the data by checking to see if there are any null values. 
![nullvalues](https://github.com/Bfree22/Outserved-Reports/blob/master/Images/table.isnull().png)


2. Count the values from the duration column in the user_data table.
![user_data](https://github.com/Bfree22/Outserved-Reports/blob/master/Images/value_counts.png)


3. Sort the values in ascending order to visualize trends in user in-store activity.
![sort_values](https://github.com/Bfree22/Outserved-Reports/blob/master/Images/sort_values.png)





### Libraries

Imported the following libraries to clean and visualize the data:

* Import pandas
  ```
  import pandas as pd
  ```
  * Import numpy
  ``` 
  import numpy as np
  ```
  * import matplotlib.pyplot
  ```
  import matplotlib.pyplot as plt
  ```
  
  
  
  ### Result
  
The results of duration analysis shows that the average time in seconds a user is inside a geo-fence is 5-6 seconds, showing that most geofence logs are user drive-bys. The graph shows that there were active user logs of over 200 logs for users that were inside the geofence between 5 and 60 seconds. See below the .gifs of the selected graphs for the report.

![results](https://github.com/Bfree22/Outserved-Reports/blob/master/Images/results_.gif)
  
  
  
  
