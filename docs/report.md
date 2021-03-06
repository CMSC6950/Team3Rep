# Team Orange

Team Members:

Hanieh Marvikhorasani

Mahesh Kumar Reddy Pochamreddy

Jonathan Conway

---

# Introduction

The growing degree days (GDD) is a temperature index tool used in agriculture to predict the best planting season for a plant. GDD enhances predicting the best planting time of a crop to its maturity, in terms of high heat accumulated in the ground in regions conducive. GDD is used to predict and compare the growing rate of a plant from germination to yielding and predict future planting. Generally, GDD is calculated by adding the maximum (Tmax) and minimum (Tmin) temperature together dividing by two (2) and then subtracting the base temperature (Tbase).

When determining the GDD of a plant, each plant has a conducive temperature for development and so it has a base temperature (Tbase). The base temperature is the lowest temperature a plant can survive in. (Tbase) will be considered 0 degrees celcius for the calculation of GDD in this report.

The reference temperature for a given plant is the temperature below which its development slows or stops. For example, peas are planted during the cold season, where it has a reference temperature of 40 degrees fahrenheit while sweet corn and soybeans are planted during the hot season, where they have a reference temperature of 50 degrees fahrenheit.
---

# Methodology
## Data Collection

Required  data  for  different  cities  have  been  obtained  from  the  given  website:
https://climate.weather.gc.ca.  Also needed columns including year, Min Temp,
Max  Temp  and  etc  have  been  extracted  for  the  selected  cities  and  this  data
have  been  used  to  create  the  plots  for  defined  tasks.   

The main data selected was the monthly data for 2016 from stations located in Montreal, Victoria, and Ottawa. This data was used to complete the required Minimum Core Tasks.

For the regression analysis performed for the Secondary Tasks, data from 1950 to 2010 was selected from a weather station in Montreal.

Data was also selected from unique stations on the island on the Newfoundland based on the 6 different geographic regions. This data spans 10 years and covers the years 1995-2004. This data was used to compile the necessary files for the Final Task analysis which will be elaborated further in this presentation.  

---

## Scientific Results for Minimum Core Tasks

1. For our Core Tasks, we chose data from Montreal, Ottawa, and Victoria for the year 2016

.center[<img src="http://www.cs.mun.ca/~charlesc/cmsc6950/Canada_final.jpg">]

---

2. Showing annual cycle of min/max daily temperatures for selected Canadian cities. We did this analysis on Montreal, Victoria, and Ottawa for 2016.

.center[<img src="http://www.cs.mun.ca/~charlesc/cmsc6950/MinMaxPlot.png">]

---

3. Showing accumulated GDD vs time for some selected cities

---

## Scientific Results for Secondary Tasks

1. Create a plot showing GDD

---

2. Standalone Bokeh Plots

[Click Here for Bokeh Plots](http://www.cs.mun.ca/~charlesc/cmsc6950/bokehplot.html)

---

3. Liner Regression

.center[<img src="http://www.cs.mun.ca/~charlesc/cmsc6950/LinReg.png">]

---

# The Final Tasks

The island of Newfoundland was divided into 6 geographic regions; North, South, East, West, Central, and The Avalon

.center[<img src="http://www.cs.mun.ca/~charlesc/cmsc6950/Island_of_Newfoundland_Regions_final.jpg">]

---

A station from each region was selected: Plum Point (North), Swift Current (South), Charleston (East), Corner Brook (West), Gander (Central), St. John's (The Avalon)

.center[<img src="http://www.cs.mun.ca/~charlesc/cmsc6950/Island_of_Newfoundland_final.jpg">]

---

The 10 Year Average Annual GDD was calculated and compared to the minimum GDD for 3 types of wheat. From the analysis, based solely on GDD, parts of Newfoundland could sustain wheat production.

.center[<img src="http://www.cs.mun.ca/~charlesc/cmsc6950/nlwheatplot.png">]

Minimum GDD for wheat production was found [here](http://store.msuextension.org/publications/agandnaturalresources/mt200103ag.pdf)

---

Using the 10 Year Average Annual GDD calculation again, the results were compared to the minimum GDD for 6 types of seeds. From the analysis, based solely on GDD, parts of Newfoundland could sustain wheat production.

.center[<img src="http://www.cs.mun.ca/~charlesc/cmsc6950/nlseedplot.png">]

Minimum GDD for seed production was found [here](http://store.msuextension.org/publications/agandnaturalresources/mt200103ag.pdf)
