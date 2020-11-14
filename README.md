# Tornado-visualization
## Prediction of the financial loss impact of Tornadoes
##### Data Visualization Team Project

### Abstract
The effects of global warming have resulted in drastic changes to  the climate of Earth and every year the number of natural  calamities such as tornadoes, drought, floods has been constantly increasing The extreme weather conditions always result in huge financial  and human losses Natural disasters have resulted in $145 billion in losses for the past decade alone

### 1. Problem

In the present world, the effects of global warming have resulted in drastic changes to the climate of Earth and every year the number of natural calamities such as tornadoes, drought, floods has been constantly increasing. Although we have many existing systems to predict such calamities, these extreme weather conditions always result in huge financial and human losses [4]. For instance, the recent natural disaster, storm Stella which affected the east coast and Midwest regions of USA brought a major drag to US GDP growth. These natural disasters have resulted in $145 billion in losses for the past decade alone. Tornadoes have been ranked as the third largest disaster in causing largest financial losses behind floods and hurricanes during the past 25 years [1]. Hence in this project, we would be analyzing the financial impact of tornadoes.

With the advent of visual analytics tools and with proper data sets obtained from the government website, the effectiveness of tornado warnings has significantly improved [2]. We are focusing on how Geographic Information Systems (GIS) could be effectively used to study the behavior of tornadoes and the resultant financial losses in any given state. We would be able to identify patterns and relationships by analyzing some of the key parameters of the state geography and tornado characteristics using ArcGIS tool [3], in particular how the magnitude, hail inches and wind speed of tornadoes have a direct impact on the financial loss of a state. We aim to understand the geography covered by the tornadoes, the infrastructure and agricultural damages caused by it [5] and to make intelligent predictions on financial losses and magnitude of tornadoes.


### 2. Objectives
	1. Identify the relationship between the width of the tornadoes based on the distance traveled and the magnitude of the tornadoes.
	2. Explore the pattern between the geographic location covered by the tornadoes based on their type such terrain, oceanic regions etc., and how do it affect the magnitude of the tornadoes.
	3. Predict the pattern between the wind speed at a geographic location and the financial losses incurred by it over a period of time.
	4. Identify the geographic locations which has experienced maximum tornadoes over a certain period of time frame.
	5. Based on the above identifications, categorize the geographic locations that has suffered maximum losses over the same period of time considered based on the magnitude of tornadoes.

![GitHub Logo](/images/Page-2-Image-1.jpg)
Figure 1. Magnetization as a function of applied field.



III   methodology AND DATASETS
The dataset that we would be considering for our project proposal is from Kaggle website. Here the real tornado activity data is captured between 1950 to 2015 and contains 60,115 records. This data set is created by the National Weather Service and it helps us to understand the various characteristics of the storm, tornadoes such as the various indicators which are responsible for damage and cause financial loss to the geographical location, weather conditions, wind speed and also about the width of each tornado. The data is available in CSV format. The link to the dataset https://www.kaggle.com/jtennis/spctornado.
The dataset contains the following attributes

The dataset “Storm Prediction Center” is obtained from Kaggle website and contains 60,115 recor
Date and Time 
State and State Number
Magnitude 
Injuries
Fatalities
Financial loss and Crop loss
Latitude and Longitude
Length and Width 


Cleansing the data 
We used Excel spreadsheets for the purpose of data cleansing. The inbuilt functionality of excel was used to modify the column attributes and remove the unnecessary column attributes. Following modifications were made in the dataset in the excel sheets.
The codes in the loss column were replaced with the actual loss values as per the information which was given in the metadata information
The codes which were given for the time zone in the dataset was replaced with the actual timezone values as per the information in the metadata

To avoid any kind of ambiguity and confusion we removed some of thecolumn attributes which were not being used for any kind of visualization or analysis purpose.Some of these column attributes are FC,State Number, State FIPS code.

Visualization of the data set 
We utilized this  preprocessed  data to generate data that can be used for further processing which helped us to analyze the data set by using Tableau, ESRI ArcMaps and Power BI and study the relationships between geography of the state, width of the tornados, magnitude, the fatalities, injuries, crop loss versus year . We then validated  the effectiveness of our findings by comparing the predictions with the recent tornados and financial losses that we obtained from the wiki


















Analysis from the visualization

We analyzed the magnitude of the tornadoes on a yearly basis based on the Fujita scale of magnitude and found out that most of the tornadoes which were destructive had a magnitude between 5 and 6.
The fatalities caused due to the tornadoes on a yearly basis was also determined using the resulting graphs from the visualizations from Tableau and PowerBI
The injuries according to the year was also represented in the graphs.
The crop loss according to the year and  by state was represented in the line chart.

Perform data cleansing on the data set, analyzing the attributes and remove fields whi	
	
IV   RESULTS
According to the analysis conducted from the visualizations from the charts we obtained from tableau and powerBI, we see that 2011 was the year when USA  experienced the deadliest tornadoes.
We also see that records for highest number of fatalities, injuries and crop loss was in the same year.
From the line chart we observe that Alabama and neighboring states were adversely affected by the tornado.
From the visualizations of PowerBI we observe some relationship between the attributes of the tornadoes
As the length of the tornado increases, magnitude also increases and they are directly related
As the width of the tornado increases, magnitude decreases and hence they are inversely related.

Anticipated Outputs:
A webpage which contains the video of analysis and predictions of financial impact and magnitude of tornadoes as they pass over each state, the relationships and graphs based on our analysis output displayed using D3.js, Google charts, and Tableau.
Anticipated Limitations:
The loss information in the data set for the older years around 1950 might not be very accurate and also it would be difficult to consider the data for all the given years within the given time frame, hence we would be considering only those years which had witnessed major tornadoes and impact considerable number of states.
ARCMAP

 
 
V   summary
             Vi   CONCLUSION

            Vii   FUTURE WORK

We intend to work on this prediction model using classification algorithms in Weka and using python which can predict patterns for future and to build a real time system which fetches data dynamically on a daily basis from National Weather Service and Storm Prediction center and generates the results.

References


Boruff, B, Easoz, JA, Jones, SD, Landry, HR, Mitchem, JD & Cutter, SL 2003, 'Tornado hazards in the United States' Climate research, vol 24, no. 2, pp. 103-117. DOI: 10.3354/cr024103
T. Gula, C. Grosu, D. Nanuti, M. Mocanu and S. N. Ciolofan, "ArcGIS Based Visualization Tool for Assessment of Earthquakes Impact," 2015 Ninth International Conference on Complex, Intelligent, and Software Intensive Systems, Blumenau, 2015, pp. 308-313
Cannon, Amber. "Deriving Population Exposure Fatality Rate Estimates for Tornado Outbreaks Using Geographic Information Systems (GIS)" Paper presented at the annual meeting of the Oklahoma Research Day, Cameron University, Lawton, OK, Nov 04, 2011
Donner, W. R., “The political ecology of a disaster: An analysis of factors influencing U.S. tornado fatalities and injuries, 1998-2000,” 2007 Demography, 2007, 44(3), 669-685
Brenner SA, Noji EK, “Tornado injuries related to housing in the Plainfield Tornado,” Int J Epidemiol 24:144–149




