# Baltimore-NewportNews-Incarceration-Rates-Python

According this recently published [article](https://www.prisonpolicy.org/blog/2020/07/27/disparities/), recent protests and radical changes in the American policing system have brought national attention to the systematic racism within our criminal justice system. Although this is an issue rooted in many sectors beyond policing, the systematic racism in policing is evident ranging from sentencing and correctional discipline to pretrial processing and incarceration. Furthermore, the mass incarceration sweeping the nation is affecting many lives, particularly the lives of vulnerable communities such as people of color and other marginalized demographics in various socioeconomic classes. To better understand issues around public health issues regarding race and criminal justice reform, we will be specifically focusing on the relationship between incarceration rates and race (black and white) in Baltimore, Maryland vs. Newport News, VA. The main data source used to compare these cities was [Opportunity Atlas](https://www.opportunityatlas.org/), an open data source that uses anonymous data following 20 million Americans from childhood to their mid-30s.

### Where are the areas of interest?  
![Baltimore, Maryland](https://github.com/EuniceNamkoong/Baltimore-NewportNews-Incarceration-Rates-Python/blob/main/Bmore%20Map.png)

Here we can see the outline of Baltimore, Maryland where population data was taken from.  

![Newport News, Virginia](https://github.com/EuniceNamkoong/Baltimore-NewportNews-Incarceration-Rates-Python/blob/main/NN%20Map.png)

Here we can see the outline of Newport News, Virginia where population data was taken from.  

## Python Analysis 
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oofP8cEalM8yoDQWwv-kSRMRomYyHqKD?usp=sharing) Python was used to filter, merge, and create data visualizations using pandas, numpy, and plotly. 

### What is the incarceration rate among Black vs. White populations in Baltimorean neighborhoods? 
![Baltimore1](https://github.com/EuniceNamkoong/Baltimore-NewportNews-Incarceration-Rates-Python/blob/main/BAR_bmore_black.png)


![Baltimore2](https://github.com/EuniceNamkoong/Baltimore-NewportNews-Incarceration-Rates-Python/blob/main/BAR_bmore_white.png)

In the bar charts above, incarceration rates within the neighborhoods in Baltimore are compared by race. Overall, the incarceration rates within the Black neighborhoods are higher than the incarcerations rates of the white neighborhoods. These are similar findings to the excel bar charts comparing Baltimore. 

### What is the incarceration rate among Black vs. White populations in Newport News neighborhoods? 

![Newport News1](https://github.com/EuniceNamkoong/Baltimore-NewportNews-Incarceration-Rates-Python/blob/main/BAR_newport_black.png)

![Newport News2](https://github.com/EuniceNamkoong/Baltimore-NewportNews-Incarceration-Rates-Python/blob/main/BAR_newport_white.png)

Similarily, this microview of the neighborhoods in Newport News compared by race. This shows that the Black population has higher incarceration rates than white neighborhoods in Newport News. Comapred to the excel analysis, there are no new findings. Both show similar results.  

Between both cities, the black population incarcerations were higher. However, between Baltimore and Newport News, the mean incarceration rate was 0.042916.

## Python vs. Excel Analysis Comparison 
In the python analysis, we focused on data visualization using bar graphs. Our data showed us that incarceration rates are disproportionately distributed across neighborhoods in both cities. The results show that the incarceration rates are slightly higher for black demographics than white demographics. Compared to the excel analysis, there weren't stark differences or new findings. However, the method in which these data results were visualized differed. For excel, the [bar charts](https://github.com/EuniceNamkoong/Baltimore-NewportNews-IncarcerationRate-Data) that were used included a macroview comparison of overall average incarceration rate comparison of Baltimore vs. Newport News of all races. Additionally, the average incarceration rates among black vs. white populations were then split by city. 

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1oofP8cEalM8yoDQWwv-kSRMRomYyHqKD?usp=sharing) However, in the python analysis, we were able to get more detailed information about the race distribution among the neighborhoods within each city and their correlating incarceration rates. 

### How can these findings be used? 
When it comes to racial disparities in criminal justice reform and policy change, there needs to be reform efforts in identifying structural disadvantages and implicit biases. The python analysis was more helpful in that it provided more insight to where priorities should be. 
1) Individual neighborhoods with higher incarcerations can be studied for the reasonings behind higher incarceration rates. 
2) Neighborhood clusters with higher incarcerations and correlating police districts can be identified and thus held accountable. Further actions such as racial implicit bias trainings in the police departments and community assessment can be conducted. 

Additional data that would serve to be useful include socioeconomic distribution and the political landscape, such as redlining. These factors could also be factors that contribute to social contexts of the neighborhooods with higher incarcerations, which would provide more insight on why there are great inequities. 





