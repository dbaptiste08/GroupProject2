# GroupProject2

# Team Name:
47114 Group 3


# Team Members:
1. Danielle Baptiste: [@dbaptiste08](https://github.com/dbaptiste08)
2. Connor Miller: [@ConnorMiller64](https://github.com/ConnorMiller64)
3. Jack Miller: [@Jackhmiller31](https://github.com/jackhmiller31)
4. Hayden Martin: [@haydentMartin](https://github.com/haydentMartin)
5. Timofei Begun: [@Conscientisehandball](https://github.com/conscientisehandball)
6. Andrew Sharpe: [@andrewsharpeuga](https://github.com/andrewasharpeuga)

# Description of Dataset:
This data is a combination of two data sets. The first documents the public school district dropout rates for the state of Iowa (catalog.data.gov State of Iowa - 2014-2015 Public School District Dropout Rates Public school district drop out rates for SY 2015 by race and gender). In this data set it has the type number for district number, name for district name, county, overall enrollment rate, dropout rate, and different dropout counts for different races. We combined this data set with another data set that reports median household income for Iowa by county (usa.com Iowa Median Household Income County Rank Based on ACS 2010-2014 data Iowa Median Household Income County Rank). We chose this to help dive deeper on the problem of high high-school dropout rates and to see if there was a correlation between median income and dropout rates. 



# Question 1: 
Is lower median household income correlated with higher dropout rate? Which county had the worst total enrollment vs dropout rate?

<img width="1225" alt="Screenshot 2024-04-24 at 11 02 39 AM" src="https://github.com/dbaptiste08/GroupProject2/assets/149968815/638cbcff-06f1-46ec-a7ca-b8e216dc2280">

Graph Description: This is a tree map showcasing the highest dropout rate compared to the county and the median income.


<img width="628" alt="Screenshot 2024-04-24 at 10 37 41 AM" src="https://github.com/dbaptiste08/GroupProject2/assets/149968815/c91b35e9-14d1-4a97-a60c-b659ff29e0af">

Graph Description: This is a scatter plot comparing average overall dropout rate and median household income to showcase trends.


Importance & Findings Interpretation: 
This question provides valuable insights into dropout rates in public schools in Iowa. The question uses median household income to predict dropout rate. The aim of the question is to see whether or not less financially fortunate students are suffering from higher dropout rates. If that was the case, an action plan could be implemented to help the students who may be dropping out due to financial strain. Our data shows the highest dropout rate was Polk County with a median income of $59,844. Not the lowest, but we still need to take into account the population.Then we created a second graph, and our data shows a slight negative correlation between dropout rate and median household income. This means that as median household income goes up, the dropout rate goes down. Therefore, the correct answer to our question is yes; Lower median household income is correlated with a higher dropout rate. The question also asks what county had the worst total enrollment vs dropout rate. This question allows us to specifically visualize counties suffering from high dropout rates. The two questions combine to provide us with information about who is dropping out (more students from lower income households), where they are dropping out (what county) and a possible reason why they are dropping out (financial strain). Wielding this information gives the user an opportunity to effectively lower dropout rates by focusing on students and counties who need the help most. 





# Question 2:
Which district had the highest dropout rate? What is the highest race per district that has dropped out?

<img width="1225" alt="Screenshot 2024-04-24 at 10 41 31 AM" src="https://github.com/dbaptiste08/GroupProject2/assets/149968815/cbfd9c03-8f37-4979-b245-a41c84149d38">

Graph Description: This graph showcases the highest dropout rate across the distrcits. 


<img width="1226" alt="Screenshot 2024-04-24 at 10 30 33 AM" src="https://github.com/dbaptiste08/GroupProject2/assets/149968815/ce429f3f-8f9d-46cd-9c75-f8eabbc15608">

Graph Description: This graph showcases the racial background of the drop outs in Iowa's districts.


Importance & Findings Interpretation:
This question focuses on deriving information from the specific districts and the racial makeup of those districts. Firstly, visualizing districts with the highest dropout rate allows us to see what district is struggling the most. A treemap is the perfect visualization tool for this question since the viewer can simply compare districts by size and color differences. The treemap makes it easy to see which district has the highest dropout rate and makes it hard to see the districts who have lower dropout rates, thus the treemap enlarges districts that need to be focused on and hides districts who are doing well. In a further effort to discover correlation and help to explain why students are dropping out, the second question adds the dimension of race. This may be important and necessary to ensure that discrimination is not occurring. For example, if a particular racial group is seeing disproportionately higher dropout rates than other races, this group could be facing some sort of discrimination that needs to be addressed. This visualization, however, is important because it could highlight the discrimination of a racial group if it were occuring. 



# Manipulations Applied to Dataset for Analysis:
The data set consists of data on high school Iowa dropouts and median household income by counties in Iowa. The only manipulation done to this dataset was adding all the separate races, African American, Native American, etc., into one pivot to display the results in a clear, visually appealing manner. We also had to add a calculated field of drop out rate by making a function by dividing overall dropouts over overall enrollment.



# Tableau Packaged Workbook:
The packaged workbook containing the visualizations shown above is attached to this repository.
