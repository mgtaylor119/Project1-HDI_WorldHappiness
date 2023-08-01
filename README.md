### Happiness and Development: The Unlikely Power Couple
The aim of our project is to provide valuable insights into the overall well-being and quality of life in different countries. 

Our analysis combines data from The World Happiness Report and The Human Development Index (HDI) to uncover possible relationships and trends.

**Part 1: Components of Happiness Index and Regional Geomapping**<br>
* Happiness 
* Happiness Around the World<br>
![image] insert Geomapping API

**Part 2: Components of HDI vs. Happiness Linear Regression Models**<br>

* **Life Expectancy vs. Happiness Index Correlation**<br>
  *The linear regression line indicates a positive correlation between Life Expectancy and Happiness. The positive slope of 5.57 suggests that that, on average, for each one-unit increase in the Happiness Index, there is an expected increase of 5.57 years in Life Expectancy at Birth. In contrast, as the Happiness Index decreases (indicating lower happiness levels), the average life expectancy tends to decrease. The relationship between Life Expectancy and Happiness is statistically significant as indicated by the r-value of 0.7658840088647312, showing a relatively strong correlation between the two variables.*<br>

![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/Rachaels_Branch/images/Life_Expectancy_Happiness_Linear_Regression.png?raw=true)

* **Education vs. Happiness Index Correlation**<br>
  *The linear regression line indicates a moderate, positive correlation between Education and Happiness. The positive slope of 2.11 suggests that as the Happiness Index increases (higher happiness levels), there is a moderate tendency for the average years of schooling to increase. In general, countries with higher Happiness Index scores tend to have higher average years of schooling, and countries with lower Happiness Index scores tend to have lower average years of schooling. The relationship between Education and Happiness is statistically significant as indicated by the r-value of 0.6985499956715034, showing a moderate correlation between the two variables.*<br>
  
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/Rachaels_Branch/images/Education_Happiness_Linear_Regression.png?raw=true)

* **Income vs. Happiness Index Correlation**<br>
  *The positive slope of the regression line (14451.34) indicates a direct relationship between Income and Happiness. For each one-unit increase in the Happiness Index, the Income Per Capita is expected to increase by 14,451.34 (approximately $14,451.34). Conversely, has the Happiness Index decreases, the Gross National Income Per Capita tends to decrease. The relationship between Income and Happiness is statistically significant as indicated by the r-value of 0.7745149054243162, showing a relatively strong correlation between the two variables.*<br>
  
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/Rachaels_Branch/images/Income_Happiness_Linear_Regression.png?raw=true)

**Part 3: Human Development Time Series Analysis**<br>
* 2021 Human Development Top 5<br>
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/hdi_top_5.png?raw=true)

* 2021 Human Development Bottom 5<br>
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/hdi_bottom_5.png?raw=true)

* **Human Development Change Over Time (10 Years)<br>
  *The time series for the Top 5 countries shows a steading incline, but does show a dip in 2020. The theory is that the onset of the Covid Pandemic cause that dip.*<br>

   *The time series for the Bottom 5 countries does not show a steady trejectory, however they too have a dip in 2020.*<br>
   
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/hdi_top_5_linegraph.png?raw=true)
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/hdi_bottom_5_linegraph.png?raw=true)

**Part 4: Happiness Rank vs. Human Development Index (HDI) Correlation**<br>
* Scatter plot showing that there is a positive correlation between happiness and human development <br>
![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/assets/135649789/1f60c5d8-ccca-41c8-a248-eeeef3a66832)

* Happiness and Human Development Top 5<br>
 ![image](https://github.com/mgtaylor119/Project1-HDI_WorldHappiness/blob/main/images/Education_Happiness_Linear_Regression.png)

* Happiness and Human Development Bottom 5<br>
![image] insert bottom 5 dataframe
