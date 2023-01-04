# Preston Curve
Following the 'Wealth and Health of Countries (2015) Using Choropleth Maps' project, this is a follow-up project to plot the same data through a different visualization. A problem with the wealth choropleth map and health choropleth map was the difficulty for readers to shift their attention between the two maps to observe a relationship between the two variables. Hence, in this project, I used a preston curve (bubble chart) to plot life expectancy and GDP per capita on the y and x axis, respectively. This plot will aim to better represent the relationship between these two variables and emphasize which countries are on the higher or lower scale on wealth and health in 2015. 

For easy access to choropleth_maps.html, click on this link: https://kellyngsf.github.io/choropleth_maps/choropleth_maps.html.

![](https://github.com/kellyngsf/preston_curve/blob/main/images/preston_curve.png)

# Conclusions
- The plot shows a positive correlation between GDP per capita and life expectancy. This is the same as what we have observed previously using choropleth maps. 
- This trend stops at around the United States, after which there is a slight negative correlation between GDP per capita and life expectancy. It's important to note that there are a few countries around that region, which causes the standard error to increase as well (shown through the large grey uncertainty interval).
- Most countries with around \$1,000 GDP per capita and lower are from Africa, while most countries with around \$100,000 GDP per capita are European countries. The life expectancies for African countries are also lower than European countries. This also reflects what we have discovered in the choropleth maps visualization. 

# Advantages and Disadvantages
- Easier to observe a relationship between life expectancy and GDP per capita. 
- Line also shows the relationship between the two variables clearly. 
- Different colors for different continents shows which are the wealthier and healthier continents (generally) clearly. 
- However, countries with smaller populations have a really small circle on the plot, which prevents viewers from knowing which country they are. This may be solved with an interactive aspect to the plot. 
