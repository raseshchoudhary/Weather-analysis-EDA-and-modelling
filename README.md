# Weather-analysis-EDA-and-modelling

![alt text](https://www.cmcc.it/wp-content/uploads/2021/01/max-larochelle-uu-unsplash.jpg)


Are you tired of listening to weather news over and over again, well I may be able to present you weather new in a slightly amusing way through these valuable insights and visualizations. Weather has always been the area of focus and is often been a subject of prediction and forecasting by subject matter experts and scientists. 

I too have given it a shot using some prediction models that we shall look further. Without a further ado, lets quickly take a brief look about what information is available in the dataset along with some valuable insights.

# About the dataset

![alt text](https://cdn3.iconfinder.com/data/icons/project-management-105/103/23-1024.png)

The dataset  contains information about weather conditions at a particular location over a period of time. Lets look at the variables one by one along with their meannings.

1.Year: The year in which the weather conditions were recorded.
2.Month: The month in which the weather conditions were recorded.
3.Summary: A brief summary of the weather conditions (e.g., "Partly Cloudy," "Rain," "Foggy," etc.).
4.Precip Type: The type of precipitation recorded (if any). This could be rain, snow, sleet, or other forms of precipitation.
5.Temperature (C): The temperature in Celsius at the time of the recording.
6.Apparent Temperature (C): The perceived temperature in Celsius at the time of the recording, which takes into account factors such as wind chill and humidity.
7.Humidity: The relative humidity at the time of the recording.
8.Wind Speed (km/h): The wind speed in kilometers per hour at the time of the recording.
9.Wind Bearing (degrees): The direction from which the wind is blowing, given in degrees (0 to 360).
10.Visibility (km): The visibility in kilometers at the time of the recording.
12.Pressure (millibars): The atmospheric pressure in millibars at the time of the recording.

# Importance of this project.

![alt text](https://2.bp.blogspot.com/-xaXhkB32HUU/TzCPBkVhLaI/AAAAAAAAFvg/Hc0s6Yu8GFI/s1600/Important.jpg)

> The dataset can be used for multiple endavours such as.

1.Weather forecasting
2.Climate analysis
3.Weather-related research
4.Energy planning
5.Aviation industry

# Who is the user?

![alt text](https://www.pngitem.com/pimgs/m/22-220721_circled-user-male-type-user-colorful-icon-png.png)

There can be diverse users of this dataset as our lives are closely associated with the weather around us. It can impact business from various domains and people from various walks of life. The user can be a member of the logistic department as weather can impact transportation. The user can be the aviation industry as they use weather data to schedule their flights accordingly. Last but not the least, the user can be weather experts who wants to study weather for forecasting.

# Limitations of the study.

![alt text](https://1.bp.blogspot.com/-GsUAWIw-Yqc/X1FY1BUPJDI/AAAAAAABmS8/FaFue3pjn98Zao8b8VmGA10e8NOT4jmswCLcBGAsYHQ/s1600/clue-less.jpg)

Weather is highly capricious and unpredictable. Despite of various studies and analysis, the preduction can go horribly wrong and the exact opposite may happen. Thus this project must not be taken as an absolute standard for weather parameter and should only be considered in lines with the data in this particular dataset. With that being said lets look at some insights.

# Some of the insights

![alt text](https://th.bing.com/th/id/OIP.fn9f7Pks09J4MCKkMllQGwHaG3?pid=ImgDet&rs=1)

1.The maximum degree of humidity was experienced in the year 2006 followed by 2010. Also its a safe assumption that be it any year we can be damn sure that the humidity will be more than 0.6 %.

2.Every single year experienced wind speed upto 35 km (except in 2010). But a wind speed beyond 35 km varied from year to year. 2007 and 2008 experienced the highest wind speed. In 2007 there is an outlier in which a wind speed of whopping 65km/hr was recorded.

3.Rain is experienced when the temperature be above 0 degree with the maximum rain being expericed when the temperature is between 5-20 degrees, also there is a certain temperature near 0 degrees where both snow and rain can be experienced.

4.Rain can occur even when the humidity is low like 0.2 in this case, but for the snow to occur, the humidity is supposed to touch a certain number like in the graph above we can deduce that atleast a humidity of 0.7 is required for the snow to occur.

5.2010 experienced the maximum temperature because of which the scope of snow occurence was rather bleak and the weather was more welcoming for rain.

6.Wind speed upto 18km is conducive for both rain and snow. But beyond that the snow frequency beings to fall, however rain is still experienced in the full swing upto 38 km of wind speed.

7.A visibility from 12-14 km is hardly experienced irrespective of whether it is rainy or snowy. Also there are more instances of snow occurence below a visibility of 8 KM than above it.

8.Among all the 4 years and 12 months, the highest temperature ever recorded was the July Month(7) of 2007 and the lowest temperature ever was recorded in the January Month of 2006.

9.The weather was majorly cloudy in 2006. That might be the reason why the year 2006 experienced way more rainfall than snow.

# Modelling part

I made a decision tree classifier model the classify the model as snow or rain based in certain input variables. Along with the model I have made the confusion matrix to gauga the training and testing accurcay.