<img width="770" height="403" alt="ev-2-edit min_-770x403" src="https://github.com/user-attachments/assets/24040f6a-930d-4e9e-aa1f-5fa262a5f724" />

# Electric Vehicle (EV) Data Analysis - MIS 311

## 1. Project Overview
   
The dataset analysed in this project contains electric vehicle (EV) registration records collected across multiple cities and postal codes. The data provides detailed information about registered clean energy vehicles, including unique identification numbers, geographical locations, vehicle manufacturers, and specific models. This dataset is highly appropriate for analysing consumer purchasing behaviour, manufacturer market share, and overall electric vehicle adoption trends over time.
Before the cleaning process, the dataset consisted of various registration records across 6 columns:
-	Vehicle Identification Number
-	City
-	Postal Code
-	Model Year
-	Make
-	Model
  
The dataset includes both categorical variables (such as City, Make, and Model) and numerical/temporal variables (such as Model Year), enabling frequency distribution analysis, descriptive statistics, and business-oriented data visualisation.


## 2. Data Cleaning & Preparation
   
To improve data quality and ensure reliable analysis results, several preprocessing and cleaning procedures were conducted using Microsoft Excel.

Handling Missing Values A review of the dataset identified missing values across five variables:

-	Vehicle Identification Number **(4 missing values)**
-	City **(2 missing values)**
-	Model Year **(2 missing values)**
-	Make **(2 missing values)**
-	Model **(1 missing value)**

All rows containing these missing values were systematically removed to eliminate potential bias.

**Handling Duplicates**: In addition to missing values, the dataset was checked for redundant entries. The "Remove Duplicates" function in Excel identified and deleted **3 duplicate rows**.

After completing the data cleaning procedures, the final refined dataset consists of exactly **188 valid rows**, ensuring absolute accuracy for the subsequent analysis.


## 3. Descriptive Statistics & Key Insights
   
<img width="278" height="543" alt="Table 1" src="https://github.com/user-attachments/assets/456c2efc-18b7-4aa4-b77c-fab7f81440da" />

**Table 1: Descriptive Statistics Summary**

Since the dataset consists entirely of categorical and qualitative variables (such as Manufacturer, Model, and City), traditional descriptive statistics like Mean, Median, or Standard Deviation are not applicable. Instead, the analysis focuses on frequency distribution (Count and Percentage) to discover key insights.


<img width="624" height="310" alt="Figure 1" src="https://github.com/user-attachments/assets/f0386d6e-31e3-4dbc-8aa2-1c3876e8dc1c" />

**Figure 1: Most common manufacturers**


**Insight 1: Manufacturer Market Dominance**

-	**Finding:** Tesla dominates the dataset, accounting for the highest number of registered vehicles with 74 out of 188 observations. It significantly outperforms competitors such as Nissan (38 vehicles) and Kia (19 vehicles).
  
-	**Implication:** This commanding market presence reflects higher consumer demand, brand trust, and the increasing popularity of Tesla's technology. For automotive stakeholders and policymakers, this indicates that future infrastructure development (such as EV charging stations) and aftermarket services should heavily consider Tesla compatibility to serve the largest customer segment, while still accommodating the secondary market share held by Nissan and Kia.



<img width="624" height="269" alt="Figure 2" src="https://github.com/user-attachments/assets/3ebec192-8050-4ec8-b111-fda691114b23" />

**Figure 2: Model year distribution**

<img width="664" height="498" alt="Figure 3" src="https://github.com/user-attachments/assets/4d0a8de8-66d9-4508-8e5b-9bee05a50d49" />


**Figure 3: Cities with the Highest Number of Electric Vehicles**


**Insight 2: Urban Concentration & Adoption Trends**

-	**Finding**: Distribution by year of manufacture reveals a sharp upward trend in EV registrations from 2018 to 2020, peaking significantly in 2020. Geographically, these registrations are heavily concentrated in major urban centers, with Seattle, Mukilteo, and Bothell recording the highest numbers.
  
-	**Implication**: The rapid adoption of electric vehicles is primarily driven by urban populations, likely due to more developed charging infrastructure, higher environmental awareness, and better access to newer models. The preference for recent model years highlights a strong consumer appetite for updated automotive technologies. To sustain this growth, businesses and local governments should focus on maintaining robust infrastructure in these saturated urban hubs while expanding incentives to neighboring areas.


## 4. Tools Used
- Microsoft Excel
- Pivot Tables
- Charts and Visualisations

## 5. Author
   
Nguyen Vo Huynh Huong

