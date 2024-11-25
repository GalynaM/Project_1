## How Brazil was affected by Hosting the 2016 Summer Olympics

### Assumption
We assume that Athletes of hosting country will have more familiarity with home field, receive great support from home crowd, have easier qualification criteria, thus more participation is expected.
Considering all these factors we are expecting increase in number of Medals Brazil won in Rio 2016 comparing to the number of medals Brazil usually wins.

### Data Source
Historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016 was used.
This dataset was scraped from www.sports-reference.com in May 2018.
https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results?select=noc_regions.csv.
World Bank's data API was used to get GDP data.
https://pypi.org/project/wbgapi/

![image](https://github.com/user-attachments/assets/0cc130f0-0b0f-45e1-9ad3-d48e5ed71b69)

![image](https://github.com/user-attachments/assets/2e2c6a4d-66e8-4936-bcd7-2357bbd45dbf)

#### Total number of Medals is higher than in any other previous games: 19 medals total.
- The average for years with highest Medal Count (1996-2012) is 14.3;
- The average for all other years (<1996) is 2.75 total medals.
- Total number of Gold Medals is higher than in any other previous games: 7 gold medals.
- The next highest number is 5 Gold Medals in 2004;
- For all other games the average number is 1.7 gold medals.

##### The obtained during analysis data shows that in the hosting year 2016 Brazil won its highest number of medals comparing to previous years. This is true for total number of medals as well as for number of gold medals.

#### GDP per capita data was obtained for Olympics years to investigate if there is a correlation between Medal Count and GDP per capita.
![image](https://github.com/user-attachments/assets/aa65869c-1047-4e25-a3f5-831165d1d367)
![image](https://github.com/user-attachments/assets/962eb203-dc60-4d02-afdc-e97656aace2a)
- Scatter Chart for Total Medals vs GDP per capita for Olympics years was plotted. Weights are the Medal Counts.
- Linear Regression Model was calculated and plotted for those values.
- Found R-value = 0.85 shows that there is a strong correlation between GDP per capita and Medals Count.
- However, the hosting year does not have the highest GDP (8710.097), but the Medal number is the highest (19).
- We found strong correlation between Number of Medals and GDP per capita with R-value = 0.85.
- However, GDP itself can not explain the raise in Number of Medals in 2016.
- So we can conclude that our assumption was correct and it's hosting of the Olympics that caused Brazil to win more medals this year.
