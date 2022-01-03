# The Impact of Covid on the US Economy

The objective of this project is to analyze and demonstrate the impact of COVID on the economy and food insecurity issue in the US.

## Project Background

COVID took us by surprise in 2020. While people were still trying to figure out what it was and how it was going to impact our life, it quickly turned into a global pandemic. On March 13, President Donald Trump declared the novel coronavirus a national emergency. On the same day, schools in Illinois were closed to in-person instruction. On March 20, JB Pritzker, Governor of the State of Illinois issued the ‘stay at home’ order for Illinois residents. It felt like the whole world was put on pause. It was not until December of 2020 when Pfizer and Moderna vaccines received the Emergency Use Authorization (EUA) from the U.S Food and Drug Administration (FDA) that people started to see some light at the end of the tunnel. Before COVID, there were already many people in the U.S. who lived in food-insecure households. After COVID hit the US like a cyclone, there were even more people who lost their jobs overnight, putting more families at risk for affording enough food. Long lines at food banks across the US were seen in the news everyday. The actual impact to the US economy and poor families at the macro level can be revealed from analyzing The US GDP data and snap program data.

## Technical Solution
I used data science tools in Python including Pandas, Numpy, and Matplotlib. Coding and analysis were performed using Jupyter Notebook. Three sets of openly available data were used for the analysis:  
GDP Data - quarterly US GDP data published by FRED Economic Research (https://fred.stlouisfed.org/series/GDP)  
Supplemental Nutrition Assistance Program (SNAP) Data - monthly national level annual summary data published by the U.S. Department of Agriculture Food and Nutrition Service (https://fns-prod.azureedge.net/pd/supplemental-nutrition-assistance-program-snap)  
US Census Data - US population data published by the United States Census Bureau (https://www.census.gov/data)  

There are two major steps performed on this project: 

## Step 1 - Data Preparation

Data was downloaded in the Excel format then loaded in DataFrames of Pandas. Using dataframes, I filtered for 2020 data then combined data from the three datasets into one. After that, I added a few analysis columns (such as calendar month, ratio, and percentage change) for further analysis and visualization. 

## Step 2 - Data Analysis
The following analyses were performed using the consolidated dataframe and final results were presented in a visual format:
1. Quarterly GDP (in Billions) and Percentage Change From the Prior Quarter in 2020
This analysis shows that the US GDP dropped by 9.3% from Q1 to Q2, then increased by 8.5% from Q2 to Q3. Q4 GDP reached a level close to Q1 GDP.

2. Number of People Enrolled in the SNAP Program and Percentage Change From the Prior Month
This analysis shows that the number of people enrolled in the SNAP program increased by 10.22% in April and kept increasing in both May and June. The headcount started decreasing in June but at a very slow pace.

3. Percentage of Benefit of Snap Program Over US GDP
This analysis shows that, in Q1 before COVID, only 0.06% - 0.07% of the US GDP was used for the SNAP program. That percent doubled to 0.12% in Q2. In Q3, the percentage dropped by only 0.01% to 0.11% and stayed flat until the end of 2020.

Additionally, the following statistical summaries are provided at the end to provide further support on the analysis results.
Amount of SNAP benefits per month
Amount of US GDP per month
Count of people enrolled in SNAP per month
US population in 2020
Percent of SNAP benefit over GDP per month
Percent of people enrolled in SNAP over US population
SNAP benefits percent of change from the prior month
SNAP enrollment percent of change from the prior month


Example: https://github.com/AlyonaTiki/Food-Insecurity-/blob/main/main-project.py


# The Impact of Covid on the US Economy and Food Insecurity

## Project Background

The objective of this project is to analyze and demonstrate the impact of COVID on the economy and food insecurity issue in the US.  

COVID took us by surprise in 2020.  While people were still trying to figure out what it was and how it was going to impact our life, it quickly turned into a global pandemic.  On March 13, President Donald Trump declared the novel coronavirus a national emergency. On the same day, schools in Illinois were closed to in-person instruction. On March 20, JB Pritzker, Governor of the State of Illinois issued the ‘stay at home’ order for Illinois residents. It felt like the whole world was put on pause. It was not until December of 2020 when Pfizer and Moderna vaccines received the Emergency Use Authorization (EUA) from the U.S Food and Drug Administration (FDA) that people started to see some light at the end of the tunnel. Before COVID, there were already many people in the U.S. who lived in food-insecure households. After COVID hit the US like a cyclone, there were even more people who lost their jobs overnight, putting more families at risk for affording enough food.  Long lines at food banks across the US were seen in the news everyday.  The actual impact to the US economy and poor families at the macro level can be revealed from analyzing The US GDP data and snap program data.

## Data Sources:

Quarterly US GDP Data - 
Monthly Supplemental Nutrition Assistance Program (SNAP) Data - 
US Census Data - 


## Data Analysis: 

Quarterly GDP (in Billions) and Percentage Change From the Prior Quarter in 2020 
This analysis shows that the US GDP dropped by 9.3% from Q1 to Q2, then increased by 8.5% from Q2 to Q3.  Q4 GDP reached a level close to Q1 GDP


Number of People Enrolled in the SNAP Program and Percentage Change From the Prior Month
This analysis shows that the number of people enrolled in the SNAP program increased by 10.22% in April and kept increasing in both May and June. The headcount started decreasing in June but at a very slow pace.


 Percentage of Benefit of Snap Program Over US GDP 
This analysis shows that, in Q1 before COVID, only 0.06% - 0.07% of the US GDP was used for the SNAP program.  That percent doubled to 0.12% in Q2. In Q3, the percentage dropped by only 0.01% to 0.11% and stayed flat until the end of 2020.


## Summary Statistics
Total by Month
Percent of SNAP Benefit over GDP
Percent of People Enrolled in SNAP over US Population
Percent of Change from the Prior Month
