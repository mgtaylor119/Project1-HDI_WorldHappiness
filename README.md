### Happiness and Development: The Unlikely Power Couple
Our project focuses on the industry of Health and Well-being using data gathered from the World Happiness Report and the Human Development Index.  The World Happiness Index is an annual report that ranks and analyzes the happiness and well-being of countries based on various factors such as income, social support, life expectancy, freedom, generosity, and corruption. The Human Development Index is an annual report that uses things like standard of living (income), health(life expectancy), and education (years of schooling) to determine these scores. Our analysis uses world data and Geoapify to combine data from both indices to uncover possible relationships and trends, allowing us to view well-being from both subjective and objective dimensions.

**Part 1: Happiness Index and Geoapify**<br>
* Geomapping that shows Happiness Values around the world<br>
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/Screenshot%202023-07-30%20184212.png?raw=true)

**Part 2: Happiness Rank vs. Human Development Index (HDI) Correlation**<br>
* Scatter plot showing a positive correlation between happiness and human development.
*As the Happiness Index increases, so does the HDI showing that they are both accurately measured.*<br>
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/assets/135649789/1f60c5d8-ccca-41c8-a248-eeeef3a66832)

* Happiness and Human Development Top 4<br>
 ![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/HDI_Happiness_Top_5%20.png)

* Happiness and Human Development Bottom 4<br>
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/HDI_Happiness_Bottom5.png)

**Part 3: Human Development Time Series Analysis**<br>
* **Human Development Change Over Time (10 Years)**<br>
  *The time series for the Top 5 countries shows a steading incline with a dip in 2020. The theory is that the onset of the Covid-19 Pandemic caused that dip.*<br>
  *The time series for the Bottom 5 countries does not show a steady trejectory, however, they too have a dip in 2020.*<br>
   
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/hdi_top_5_linegraph.png?raw=true)
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/hdi_bottom_5_linegraph.png?raw=true)

**Part 4: Individual Components of HDI vs. Happiness Linear Regression Models**<br>

* **Life Expectancy vs. Happiness Index Correlation**<br>
  *The linear regression line indicates a positive correlation between Life Expectancy and Happiness. The positive slope of 5.57 suggests that that, on average, for each one-unit increase in the Happiness Index, there is an expected increase of 5.57 years in Life Expectancy at Birth. In contrast, as the Happiness Index decreases (indicating lower happiness levels), the average life expectancy tends to decrease. The relationship between Life Expectancy and Happiness is statistically significant as indicated by the r-value of 0.7658840088647312, showing a relatively strong correlation between the two variables.*<br>

![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/Rachaels_Branch/images/Life_Expectancy_Happiness_Linear_Regression.png?raw=true)

* **Education vs. Happiness Index Correlation**<br>
  *The linear regression line indicates a moderate, positive correlation between Education and Happiness. The positive slope of 2.11 suggests that as the Happiness Index increases (higher happiness levels), there is a moderate tendency for the average years of schooling to increase. In general, countries with higher Happiness Index scores tend to have higher average years of schooling, and countries with lower Happiness Index scores tend to have lower average years of schooling. The relationship between Education and Happiness is statistically significant as indicated by the r-value of 0.6985499956715034, showing a moderate correlation between the two variables.*<br>
  
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/Rachaels_Branch/images/Education_Happiness_Linear_Regression.png?raw=true)

* **Income vs. Happiness Index Correlation**<br>
  *The positive slope of the regression line (14451.34) indicates a direct relationship between Income and Happiness. For each one-unit increase in the Happiness Index, the Income Per Capita is expected to increase by 14,451.34 (approximately $14,451.34). Conversely, has the Happiness Index decreases, the Gross National Income Per Capita tends to decrease. The relationship between Income and Happiness is statistically significant as indicated by the r-value of 0.7745149054243162, showing a relatively strong correlation between the two variables.*<br>
  
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/Rachaels_Branch/images/Income_Happiness_Linear_Regression.png?raw=true)

**Analysis Summary**<br>
  *While the World Happiness Index and the Human Development Index both aim to measure well-being and progress, they approach the concept from different angles. Our research found positive correlations between the two data sets, where factors like better health, education, and income opportunities can contribute to increased well-being; however, they are not directly interchangeable, as a country with high human development may or may not necessarily have the highest levels of happiness and vice versa as shown in our various DataFrames.*<br>
  
**Limitations**<br>
  *We initially wanted to examine the impact that Covid-19 had on the data; however, because government data is always two years behind, it limited our ability to analyze and compare numbers before, during, and after the pandemic. Additionally, the accuracy and reliability of these reports are contingent on the availability and quality of data from different countries. Some nations lack comprehensive data, leading to gaps and discrepancies in the rankings.*<br>
  
**Possible Next Steps**<br>
  *Next steps might include a subgroup analysis to explore how the relationship between the indices varies across different regions, income levels, or other relevant demographic factors.* 
