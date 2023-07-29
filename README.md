# Project-3-AIRBNB-Market-Analysis-For-New-York-City-

## Overview 
New York, the largest city in the United States, has an estimated population of 19.84 million. The dataset used for this project includes AIRBnB accomodation for both local residents as well as tourists who visit the city annually. Being a major tourist attraction, New York receives visitors from various countries like Spain, France, Russia, and more. It is a popular vacation destination for families, and many people also work in the city. However, finding an affordable and suitable living space can be a challenge. With the help of the available dataset from year 2019 and 2023, we aim to analize the current AirBnB Rental Market via data app visualization to offer a cost-effective living option to our clients.

##Website Development  
The steps involved in making the website are as follows:
* Extraction of Data from the following link: http://insideairbnb.com/
* EDA Conducted on the data via Google Collaboratory Notebook
* Data deployed on MongoDB Local Server
* Mongo DB linked to the Flask App, to fetch the data 
* The dataset is jasonified and sent to the html pages for visual calculation and display via HighCharts.js library.

![image](/Images/All_Tech.png)
## Technologies Used 
* Google Collaboratory Notebook
* Python
* Flask
* MONGODB
* HTML
* CSS
* Javascript
* Highcharts.js Library


## Description 
Flask code for the app can be located [here](https://github.com/RimpleDabas/Interactive-Visualizations_Canadian_Rental_market/blob/main/app/app.py).

The dashboard for our app has click buttons for four tabs and html script can be located [here](https://github.com/RimpleDabas/Interactive-Visualizations_Canadian_Rental_market/blob/main/app/templates/index.html). 

 The first one is yearly trend by years. It is built using [charts](!https://www.chartjs.org/) javascript library and code for the same is [here](https://github.com/RimpleDabas/Interactive-Visualizations_Canadian_Rental_market/blob/main/app/static/js/app.js).



* The first page was created to showcase the conduction of task distribution.
![image](/Images/ImageNo1.png)


* The second page shows comparative analysis via three types of graphs as follows:
1. Graph1: Comparison of the types of room distribution in year 2019 and 2023.

![Image](/Images/Image2.png)

2. Graph2: Comparison of total number of accomodation available in the 5 burroughs of New York City for AirBnB for year 2019 and 2023.

![Image](/Images/Image3.png)

3. Graph3: Pie-graph to show the top 10 neighbourhoods available for year 2019 and 2023.
![Image](/Images/Image4.png)
  
4. Graph4: Pie-graph to show the bottom 10 neighbourhoods available for year 2019 and 2023.
![Image](/Images/Image5.png)



* The third graph shows the comparison of mean price distribution over the 5 burroughs in the new york city for year 2019 and 2023. 
![Image](/Images/Image6.png)

*The fourth graph is bulit using word_cloud alternative with highcharts.js to show all the names of the included neighbourhoods.
![Image](/Images/image7.png)

## Refrences
 - https://www.chartjs.org/docs/latest/
 - https://plotly.com/javascript/
 - Leaflet
 - Youtube videos




